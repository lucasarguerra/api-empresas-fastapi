# 🏢 API de Empresas - FastAPI + PostgreSQL

API desenvolvida em **FastAPI** para **gerenciamento de empresas**, permitindo cadastrar, listar, filtrar e buscar informações com validação de duplicidade (CNPJ e e-mail).  
O projeto utiliza **SQLAlchemy** para ORM e **PostgreSQL** como banco de dados.

---

## 🚀 Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Pydantic](https://docs.pydantic.dev/)
- [PostgreSQL](https://www.postgresql.org/)

---

## 📦 Funcionalidades da API

✅ Cadastrar uma nova empresa  
✅ Listar todas as empresas  
✅ Filtrar empresas por **cidade**, **ramo de atuação** e **nome**  
✅ Verificar duplicidade de **CNPJ** e **e-mail**  
✅ Retornar mensagens de erro apropriadas  

---

## 🛠️ Como Rodar o Projeto Localmente

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/lucasarguerra/api-empresas-fastapi.git
cd api-empresas-fastapi
