# FastAPI CRUD en AWS EC2 🚀

Este proyecto es una **API REST con FastAPI** desplegada en una instancia de **AWS EC2**, que implementa operaciones CRUD (Crear, Leer) para **Usuarios** y **Libros**.

---

## 📌 Características
- **FastAPI** como framework principal.
- **SQLite** como base de datos local.
- **SQLModel + SQLAlchemy** para ORM.
- Endpoints documentados automáticamente en `/docs` (Swagger).
- CRUD básico:
  - `/users` → Crear y listar usuarios.
  - `/books` → Crear y listar libros.

---

## ⚙️ Instalación en local

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/CtrlAltBryan/fastapi-ec2.git
   cd fastapi-ec2
