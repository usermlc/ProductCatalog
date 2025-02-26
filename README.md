# ProductCatalog

**ProductCatalog** is a product catalog management system built using the **Ports and Adapters (Hexagonal) Architecture**. It allows fetching products from an external API, storing them in memory, and performing basic operations like adding, viewing, searching, and deleting products.

---

## Technologies

- **C# 12** — Core programming language.
- **.NET 8** — Framework for building the application.
- **Dependency Injection** — For managing dependencies.
- **HttpClient** — For interacting with external APIs.
- **In-Memory Storage** — Temporary storage for products.

---

## Features

- Fetch products from an external API.
- Add, view, search, and delete products.
- Store products in memory.
- Each product includes an ID, name, price, and photo URL.

---

## Project Structure

```
ProductCatalog/
├── Domain/               # Domain logic and entities
├── Application/          # Business logic and services
├── Infrastructure/       # Adapters (implementations of ports)
├── Presentation/         # Console application
└── ProductCatalog.sln
```

---

## Setup

1. Ensure .NET 8 is installed:
   - Download from the [official website](https://dotnet.microsoft.com/download).
   - Verify installation:
     ```bash
     dotnet --version
     ```

2. Build and run the project:
   ```bash
   dotnet build
   dotnet run --project Presentation
   ```

---

## Usage

- The application automatically fetches products from the API and stores them in memory.
- You can view, search, and delete products.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
