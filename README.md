# API de Tarefas Desafio da DIO

API REST desenvolvida com .NET e Entity Framework para gerenciamento de tarefas.

---

## Tecnologias utilizadas

* .NET
* Entity Framework Core
* SQL Server
* Swagger

---

## Como executar

### 1. Clonar o repositório

```bash
git clone https://github.com/h0wld1ee/trilha-net-api-desafio.git
cd trilha-net-api-desafio
```

### 2. Configurar o banco

No arquivo `appsettings.json`:

```json
"ConnectionStrings": {
  "ConexaoPadrao": "ADICIONE_SUA_CONNECTION_STRING_AQUI"
}
```

---

### 3. Aplicar migrations

```bash
dotnet ef database update
```

---

### 4. Executar

```bash
dotnet run
```

## Endpoints

* `GET /ObterTodos`
* `GET /ObterPorId/{id}`
* `POST /Criar`
* `PUT /Atualizar/{id}`
* `DELETE /Deletar/{id}`

---

## Observações

* Necessário ter instalado SQL Server
* Migrations já estão incluídas
*  Configure sua connection string

---

## Autor

Projeto desenvolvido para prática de backend com .NET.

