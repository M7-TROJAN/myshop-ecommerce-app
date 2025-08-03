# myshop-ecommerce-app

A clean, simple, and functional e-commerce web application built using ASP.NET Core MVC (.NET 8). This project demonstrates real-world concepts like multi-role authentication, Stripe integration, and a layered architecture suitable for both learning and production use.

## 🛍️ Project Overview

it's a two-role e-commerce system:

- **Users** can browse products, search, view product details, add items to a shopping cart, and complete purchases via Stripe.
- **Admins** have access to a dashboard where they can manage products and view sales activities.

---

## ✨ Features

- 🛒 Product listing with search & detail views
- 🧑‍🤝‍🧑 Role-based authentication (User / Admin)
- 🧾 Shopping cart with quantity tracking
- 💳 Stripe payment integration
- ✉️ Email notifications (via utility service)
- 📁 Modular structure with layered architecture
- 🧠 Clean and maintainable code

---

## 🛠 Technologies Used

- **.NET 8 (ASP.NET Core MVC)**
- **Entity Framework Core**
- **SQL Server**
- **Razor Views + Bootstrap**
- **Stripe API**
- **Microsoft Identity (for auth)**
- **Dependency Injection + Repository Pattern**

---

## 📂 Project Structure

```text
myshop.Web.sln
│
├── myshop.Web           → MVC Web UI, Razor Pages, Controllers
├── myshop.Entities      → Models, Repositories, ViewModels
├── myshop.DataAccess    → DbContext, EF Migrations, Data Layer
└── myshop.Utilities     → Stripe, Email, Shared constants
````

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/M7-TROJAN/myshop-ecommerce-app.git
   ```

2. **Configure the database connection**

   * Edit `appsettings.json` and update the connection string.

3. **Apply Migrations**

   ```bash
   dotnet ef database update
   ```

4. **Run the project**

   ```bash
   dotnet run --project myshop.Web
   ```

---

## 🧪 Sample Accounts

> ⚠️ If seeded with test data:

* **Admin**: `admin@myshop.com` / `Admin123!`
* **User**: `user@myshop.com` / `User123!`

---

## 🧱 Future Improvements

* Product reviews & ratings
* Admin product analytics dashboard
* Image upload with cloud storage
* Order history & invoice download
* Multi-language support (AR/EN)

---

## 👨‍💻 Developer

**Mahmoud Mohamed**
.NET Developer
[LinkedIn](https://www.linkedin.com/in/mahmoud-mohamed-abd/)

---

## License

This project is licensed under the MIT License.
