# E-Commerce Product Management System

A console-based C# product-management application for an Algorithm and Programming course. It uses an in-memory array to demonstrate CRUD operations, searching, category filtering, and defensive console-input validation in a small e-commerce workflow.

## Features

- List all products
- Add a product
- Edit an existing product
- Delete a product
- Search by product name
- Filter by category
- Validate empty names, numeric input, negative stock, and negative prices
- Store up to 50 products in an array

## Tech stack

- C#
- .NET 9.0
- Console UI
- Array-based in-memory data handling

## Repository structure

```text
├── Program.cs                 # Menu, product model, CRUD, search, and validation
├── tubesalproarray.csproj     # .NET project configuration
├── tubesalproarray.sln        # Visual Studio solution
└── README.md
```

## Run locally

Install the .NET 9.0 SDK, then run from the repository root:

```bash
dotnet run --project tubesalproarray.csproj
```

The interactive menu supports options 1–7: show, add, edit, delete, search, filter, and exit.

## Design notes

The project intentionally keeps data in a fixed-size array so the core exercise remains focused on fundamental control flow and data handling. Restarting the application resets the in-memory product list; there is no database or file persistence.

## Team attribution

This repository is a fork of [alanabyan/fix-tubes-alpro](https://github.com/alanabyan/fix-tubes-alpro) and preserves the original contributor history. The original project contributors include Alan Abyan, Faqih Alfarobahrudin, Raffata Izacky Yuargya Aletama, and Evelyne Santoso.

## Scope

This is an academic console project, not a production e-commerce platform. It is intended to demonstrate programming fundamentals rather than authentication, persistence, inventory concurrency, or payment processing.
