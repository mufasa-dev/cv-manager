# CV Manager API

This is a resume management API developed in **Go**, using **PostgreSQL** as the database and **GraphQL** for queries and mutations.

![Skills](https://skills.syvixor.com/api/icons?i=go,chi,postgresql,graphql,swagger,github,vscode,postman)

## 🚀 Technologies Used
- **Go** (Golang) - Main programming language
- **PostgreSQL** - Relational database
- **GraphQL** - Flexible API for queries and mutations
- **GORM** - ORM for interacting with PostgreSQL
- **Chi** - Lightweight HTTP router for route management

## 📌 Installation & Setup

#### 1. Clone the repository

```bash
git clone https://github.com/yourusername/cv-manager.git
cd cv-manager
````

#### 2. Database Configuration

Make sure PostgreSQL is installed.

Create a database named `cv_manager`.

Set your database credentials in the `.env` file.

#### 3. Install dependencies

```bash
go mod tidy
```

#### 4. Start the server

```bash
go run main.go
```

