# ElixirHand E-Commerce Website

[![GitHub](https://img.shields.io/badge/GitHub-Zohaibcode740-181717?logo=github)](https://github.com/Zohaibcode740)

ElixirHand E-Commerce is an open-source e-commerce project built with **ASP.NET Core Web API (.NET 6)** and **Angular 15**. The project includes a RESTful API, PostgreSQL database, Redis-based shopping cart, authentication, order management, and Stripe payment integration.

## 👨‍💻 Author

**Zohaibcode740**

- GitHub: https://github.com/Zohaibcode740
- Project Repository: https://github.com/Zohaibcode740/ecomerce

---

## 🚀 Project Overview

ElixirHand E-Commerce is a full-stack online shopping application.

The backend is built with **ASP.NET Core Web API and .NET 6**, while the frontend is developed with **Angular 15**, TypeScript, Bootstrap, and SASS.

The application uses **Entity Framework Core** to communicate with PostgreSQL and uses **Redis** for shopping-cart storage.

### Main Features

- RESTful ASP.NET Core Web API
- Angular 15 client application
- User registration and authentication
- ASP.NET Core Identity
- Product browsing
- Searching, sorting, filtering and paging
- Shopping cart
- Redis-based cart storage
- Order management
- Stripe payment integration
- PostgreSQL database
- Docker and Docker Compose support
- Entity Framework Core
- AutoMapper
- Dependency Injection
- Angular Reactive Forms
- Lazy Loading
- SSL support

---

## 🏗️ Project Structure

```text
e-comerce/
├── .config/
├── API/
├── Core/
├── FrontendApp/
├── Infrastructure/
├── .editorconfig
├── .gitignore
├── docker-compose.yml
├── ElixirHand.Com.sln
└── README.md
```

### Main Projects

| Project | Description |
|---|---|
| `API/` | ASP.NET Core Web API, endpoints and application configuration |
| `Core/` | Core/domain models and business logic |
| `Infrastructure/` | Database, repositories and infrastructure services |
| `FrontendApp/` | Angular client application |
| `.config/` | Project configuration |
| `docker-compose.yml` | PostgreSQL, Redis and other Docker services |

---

# 🛠️ Technologies

## Backend

- C#
- .NET 6
- ASP.NET Core Web API
- Entity Framework Core
- ASP.NET Core Identity
- Dependency Injection
- AutoMapper
- RESTful Web APIs
- PostgreSQL
- Redis
- Docker

## Frontend

- Angular 15
- Angular CLI 15.2.6
- TypeScript
- JavaScript
- HTML5
- SASS
- Bootstrap
- Angular Reactive Forms
- Angular Lazy Loading

## Development Environment

- Node.js 18.20.2
- NPM 10.5.0
- Angular CLI 15.2.6
- .NET 6 SDK
- Docker / Docker Compose

---

# 🗄️ Database

The project uses **PostgreSQL** as the primary relational database.

Redis is used to store shopping-cart data.

### Database Technologies

- PostgreSQL
- Redis
- Entity Framework Core

---

# 🐳 Docker

The project includes a `docker-compose.yml` file in the root directory.

After cloning the repository, navigate to the project root and run:

```bash
docker-compose up -d
```

This starts the required Docker services such as PostgreSQL and Redis.

Make sure **Docker Desktop** is installed and running.

### Useful Docker Commands

Start services:

```bash
docker-compose up -d
```

Stop services:

```bash
docker-compose down
```

View running containers:

```bash
docker ps
```

---

# 💳 Stripe Payments

Stripe is used for testing payment functionality.

To test payments, you need your own Stripe test keys.

Add your Stripe configuration to the API application's configuration file:

```text
API/appsettings.json
```

Do **not** commit real Stripe secret keys to GitHub.

Use Stripe's official documentation for test keys and payment integration:

https://docs.stripe.com/

---

# ▶️ How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/Zohaibcode740/e-comerce.git
cd e-comerce
```

Repository:

https://github.com/Zohaibcode740/e-comerce

---

## 2. Start Docker Services

From the project root:

```bash
docker-compose up -d
```

Make sure PostgreSQL and Redis containers are running:

```bash
docker ps
```

---

## 3. Run the Backend API

Navigate to the API directory:

```bash
cd API
```

Run the application:

```bash
dotnet run
```

Make sure the **.NET 6 SDK/runtime** is installed.

---

## 4. Run the Angular Frontend

Open another terminal and navigate to the Angular client:

```bash
cd FrontendApp/ClientApp
```

Install dependencies:

```bash
npm install
```

Start Angular:

```bash
ng serve
```

Then open the local URL shown by Angular in your browser.

---

# 📦 Required Versions

| Tool | Version |
|---|---|
| .NET | 6 |
| Node.js | 18.20.2 |
| NPM | 10.5.0 |
| Angular CLI | 15.2.6 |
| Angular | 15 |
| PostgreSQL | Docker/local installation |
| Redis | Docker/local installation |

---

# 🔐 Configuration

Before running the application, make sure the required configuration values are available in the API configuration.

Typical configuration includes:

- PostgreSQL connection string
- Redis connection
- JWT/Identity configuration
- Stripe test keys
- Other application settings

**Never upload production passwords, API keys, connection strings containing secrets, or Stripe secret keys to GitHub.**

Use environment variables or a local configuration file that is excluded from Git when appropriate.

---

# ✨ Features

### Authentication

- User registration
- User login
- ASP.NET Core Identity
- Secure authentication

### Product Management

- Product listing
- Product details
- Searching
- Sorting
- Filtering
- Paging

### Shopping Cart

- Add products to cart
- Update cart quantities
- Remove products
- Redis-based cart storage

### Orders

- Create orders from shopping cart
- Order management
- Order processing

### Payments

- Stripe payment integration
- Stripe test payments
- 3D Secure support

---

# 🔗 Useful Links

- GitHub Profile: https://github.com/Zohaibcode740
- ElixirHand E-Commerce Repository: https://github.com/Zohaibcode740/e-comerce
- .NET: https://dotnet.microsoft.com/
- ASP.NET Core: https://learn.microsoft.com/aspnet/core/
- Angular: https://angular.dev/
- Angular CLI: https://angular.dev/tools/cli
- Bootstrap: https://getbootstrap.com/
- SASS: https://sass-lang.com/
- TypeScript: https://www.typescriptlang.org/
- Node.js: https://nodejs.org/
- PostgreSQL: https://www.postgresql.org/
- Redis: https://redis.io/
- Docker: https://www.docker.com/
- Entity Framework Core: https://learn.microsoft.com/ef/core/
- Stripe: https://stripe.com/
- Stripe Documentation: https://docs.stripe.com/

---

# 📄 License

This project is an ongoing open-source e-commerce project.

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**GitHub:** https://github.com/Zohaibcode740/e-comerce
