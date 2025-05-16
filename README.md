# 🌐 GitHub Actions - .NET WebApp

Este projeto foi desenvolvido como parte da atividade prática do **Módulo 4 - Modern Development** do programa da **WomakersCode**. O objetivo é praticar a criação de uma aplicação web em .NET com suporte a **GitHub Codespaces** e automação de build com **GitHub Actions**. 🚀

---

## 📦 Sobre o Projeto

Esta aplicação é uma **WebApp ASP.NET Core** criada com o comando `dotnet new webapp`. A estrutura foi gerada e configurada diretamente no ambiente do **GitHub Codespaces**, e conta com um pipeline CI automatizado usando **GitHub Actions**.

---

## ⚙️ Tecnologias Utilizadas

- [.NET 8](https://dotnet.microsoft.com/)
- ASP.NET Core
- GitHub Codespaces
- GitHub Actions
- Visual Studio Gitignore

---

## 🚀 Como Executar no Codespaces

1. Acesse o repositório
2. Clique no botão verde **`Code`**
3. Vá até a aba **`Codespaces`**
4. Clique em **`Create codespace on main`**
5. No terminal, execute:

```bash
dotnet new webapp -n github4women
dotnet restore **/*.csproj
dotnet build **/*.csproj --no-restore
dotnet run --project **/*.csproj
