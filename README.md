# Instruções de Configuração para Alunos do Curso de Dotnet 👩‍💻👨‍💻

Bem-vindo ao curso de Dotnet! Aqui estão as instruções para configurar seu ambiente de desenvolvimento. Certifique-se de seguir cada passo cuidadosamente.

## 1. Visual Studio Community 2022 ou VSCode

- **Visual Studio Community 2022:**
  - Baixe e instale o [Visual Studio Community 2022](https://visualstudio.microsoft.com/pt-br/downloads/).
  
- **VSCode:**
  - Baixe e instale o [Visual Studio Code](https://code.visualstudio.com/).

## 2. Dotnet 8

- Baixe e instale o SDK .NET 8: [Download .NET 8](https://dotnet.microsoft.com/download/dotnet/8.0).

## 3. WSL2 Ubuntu

- Siga as instruções para instalar o WSL 2 com Ubuntu: [WSL 2 Installation Guide](https://docs.microsoft.com/pt-br/windows/wsl/install).

## 4. Docker

- Baixe e instale o [Docker](https://github.com/codeedu/wsl2-docker-quickstart/blob/main/README.md).

## 5. Postman ou Similar

- Baixe e instale o [Postman](https://www.postman.com/downloads/) ou uma ferramenta similar de sua preferência.

## 6. SQL Server 2019 (Docker)

- Execute o seguinte comando no terminal para baixar e iniciar o contêiner do SQL Server 2019:

  ```bash
  docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=SuaSenhaSuperSegura!' -p 1433:1433 --name sql_server_container -d mcr.microsoft.com/mssql/server:2019-latest
  ```

## 7. SQL Server Management Studio ou Outro Cliente SQL de Preferência

- Baixe e instale o [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms).

## 8. Git

- Baixe e instale o [Git](https://git-scm.com/downloads).

## 9. Conta no GitHub

- Crie uma conta no [GitHub](https://github.com/).
- Configure suas credenciais no Git usando:

  ```bash
  git config --global user.name "SeuNome"
  git config --global user.email "seu@email.com"
  ```

Agora você está pronto para mergulhar no mundo do Dotnet! 🚀 Lembre-se de consultar essas instruções sempre que precisar configurar um novo ambiente. Boa programação!
