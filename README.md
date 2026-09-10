<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,50:CE93D8,100:B39DDB&height=180&section=header&text=E-Commerce%20Web%20App&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=ASP.NET%20Core%20%2B%20SQL%20Server&descAlignY=58&descSize=15)

</div>

## Overview

A full stack e-commerce platform built with ASP.NET Core and SQL Server, covering the core flow a real store needs: secure accounts, an interactive cart, and integrated payment processing.

## Key Features

### Secure authentication
User accounts are protected with ASP.NET Core's built in identity and authentication framework.

### Interactive shopping cart
Users can add, update and remove items with the cart state persisted per session or account.

### Integrated payment processing
Checkout is wired directly into a payment provider, so orders can move from cart to completed purchase within the app.

### Relational data model
Products, orders and users are modeled in SQL Server with proper relationships, keeping the store's data consistent as it grows.


## Tech Stack

<div align="center">
<img src="https://raw.githubusercontent.com/Rawishs-2882/ASPNET-Ecommerce-WebApp/main/assets/tech-orbit.svg" alt="tech stack orbit" width="380" />
</div>

ASP.NET Core and C# for the backend, SQL Server for data storage, and Entity Framework Core for data access and migrations.

## How It Works

The ASP.NET Core app follows an MVC style structure, with controllers handling product browsing, cart operations and checkout. SQL Server stores product, user and order data, accessed through Entity Framework Core, while checkout hands off to the integrated payment provider.

## Setup and Run

1. Update the connection string in `appsettings.json` to point at your SQL Server instance.
2. Run `dotnet ef database update` to apply migrations and create the schema.
3. Run `dotnet run` to start the application locally.
4. Configure your payment provider's API keys in the app configuration before testing checkout.

## Roadmap

- Add an admin dashboard for inventory management
- Add order history and tracking for customers
- Add unit tests around the checkout flow

## Status

> **Status:** This repository was scaffolded from the project description on the author's resume. Source code is being migrated and added here in stages. Reach out using the contact links below if you would like early access to the implementation.

## Let's Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rawish0922@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rawishsarfraz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rawishs-2882)
[![Phone](https://img.shields.io/badge/Call-+92--332--8747138-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+923328747138)

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:B39DDB,50:CE93D8,100:F8BBD0&height=80&section=footer)

</div>
