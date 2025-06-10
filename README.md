## 📌 Funcionalidades

- ✅ Cadastro e controle de veículos
- ✅ Controle de entrada e saída com cálculo de tempo e valor
- ✅ Tabelas de preços e tarifas configuráveis
- ✅ Emissão de recibos
- ✅ Relatórios gerenciais (faturamento, movimentação, etc.)
- ✅ Gestão de usuários e permissões
- ✅ Dashboard administrativo com KPIs

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** C#
- **Framework:** ASP.NET Core 8.0 (ou versão correspondente)
- **Frontend:** Razor Pages ou MVC (ou Blazor, se for o caso)
- **Banco de Dados:** SQL Server / PostgreSQL / SQLite *(especifique o utilizado)*
- **ORM:** Entity Framework Core
- **Autenticação:** Identity / JWT / OAuth *(especifique o método usado)*
- **Outros:** AutoMapper, Swagger, Serilog, etc.

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seuusuario/sistema-estacionamento-erp.git
   cd sistema-estacionamento-erp
````

2. **Configure o banco de dados:**

   * Atualize a `connectionString` no `appsettings.json`.
   * Rode as migrações:

     ```bash
     dotnet ef database update
     ```

3. **Execute o projeto:**

   ```bash
   dotnet run
   ```

4. **Acesse no navegador:**

   ```
   https://localhost:5001
   ```

## 🔐 Acesso Padrão

| Usuário                               | Senha    | Perfil        |
| ------------------------------------- | -------- | ------------- |
| [admin@erp.com](mailto:admin@erp.com) | admin123 | Administrador |

> **Obs:** Altere a senha padrão após o primeiro login.

## 📂 Estrutura do Projeto

```
/Controllers
/Models
/Views
/Data
/Services
/Migrations
/Configurations
```

## 🧪 Testes

Execute os testes com:

```bash
dotnet test
```

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

### 📧 Contato

Desenvolvido por **destiny7 - Vinicius**
Email: \[[seu.email@example.com](mailto:seu.email@example.com)]
LinkedIn: [linkedin.com/in/seunome](https://linkedin.com/in/seunome)


