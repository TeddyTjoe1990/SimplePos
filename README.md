
# 🍣 SimplePOS – Sushi Heero

**SimplePOS – Sushi Heeron** is a lightweight Point of Sale (POS) application built using **.NET Blazor Server**. It’s designed for small food businesses like sushi stalls or casual dining restaurants, providing a simple interface to manage menu items, process orders, and calculate totals.

---

## 📌 Project Goals

- Help small food vendors like *Sushi Heero* manage sales efficiently
- Support basic POS functions: menu management, order handling, and billing
- Use modern web technology (Blazor) with clean architecture
- Include user authentication for staff
- Deploy to the cloud using Azure App Service

---

## 🚀 Key Features

- ✅ View sushi menu items
- ✅ Add food items to the cart with quantity
- ✅ Display total price for the order
- ✅ User login and registration (ASP.NET Core Identity)
- ✅ Create, Read, Update, Delete (CRUD) menu items
- ✅ In-memory order handling (no database yet)
- ✅ Accessible and responsive design

---

## 🧰 Technologies

- .NET 8 Blazor Server
- ASP.NET Core Identity
- Azure DevOps (Boards, Repos, Pipelines)
- Azure App Service (Cloud Deployment)
- HTML/CSS for UI components

---

## 📂 Folder Structure

```
SimplePOS-SushiHeero/
├── Pages/
│   ├── Menu.razor
│   ├── Cart.razor
│   ├── Orders.razor
│   └── Account/
│       ├── Login.razor
│       └── Register.razor
│
├── Models/
│   ├── MenuItem.cs
│   └── Order.cs
│
├── Services/
│   └── OrderService.cs
│
├── Shared/
│   └── NavMenu.razor
│
└── wwwroot/
    └── css/
        └── site.css
```

---

## 🏁 How to Run the App Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/TeddyTjoe1990/SimplePos.git
   cd SimplePOS
   ```

2. **Run the application**
   ```bash
   dotnet run
   ```

3. Open your browser and go to:
   ```
   https://localhost:5001
   ```

---

## 🔐 Authentication

- Login/Register system using ASP.NET Core Identity
- Some pages are protected (e.g., Cart, Orders)
- Roles and access levels may be added in future versions

---

## 🌐 Deployment

To deploy to Azure App Service:
```bash
az login
az webapp up --name sushi-heero-pos --resource-group SimplePOS-RG --runtime "DOTNET|8.0"
```

---

## 📋 DevOps Practices

- Project tracked in Azure DevOps Board with:
  - Epics, Features, Tasks
  - Status workflow: `New → Active → Resolved → Closed`
- Source control via Azure DevOps Repo
- Continuous Deployment setup (optional)

---

## 🧪 Testing Plan

- Functional testing of:
  - Menu display and interaction
  - Cart operations and total price calculation
  - Authentication flows
- Accessibility and responsiveness check

---

## 📘 Documentation

- 🛠️ Developer notes are available via inline code comments
- 📖 A basic user guide is available in `/docs/UserGuide.md`

---

## 👥 Contributors

- [Jannuar Teddy Herjanto] – Project Lead & App Developer

---

## 📃 License

This project is licensed under the MIT License.

---

Thank you for supporting small food businesses with smart digital tools! 🍣
