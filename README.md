# E-Commerce Product Management System

A console-based product management system developed in C# for an Algorithm and Programming course. The project models essential product operations for a small e-commerce workflow and is designed to practice structured program flow, validation, and array-based data handling.

## Snapshot

| Item | Detail |
| --- | --- |
| Project type | Academic team project |
| Language | C# |
| Runtime | .NET 9.0 |
| Interface | Console application |
| Main capabilities | Product CRUD, search, category filtering, input validation |

## Features

The console menu supports listing products, adding a product, editing a product, deleting a product, searching product records, and filtering products by category. Product data is held in an array, while console input is validated to reduce empty, negative, or non-numeric values.

## Run locally

Install the .NET 9.0 SDK, then run the project from the repository root:

```bash
dotnet run --project tubesalproarray.csproj
```

## Project structure

| File | Purpose |
| --- | --- |
| `Program.cs` | Console menu, product model, CRUD logic, search, filtering, and validation. |
| `tubesalproarray.csproj` | .NET project configuration targeting `net9.0`. |
| `tubesalproarray.sln` | Visual Studio solution file. |

## Team attribution

This repository is a fork of [alanabyan/fix-tubes-alpro](https://github.com/alanabyan/fix-tubes-alpro) and intentionally preserves its history and contributor attribution. The original project contributors include Alan Abyan, Faqih Alfarobahrudin, Raffata Izacky Yuargya Aletama, and Evelyne Santoso. Raffata is listed as a contributor in the original commit history.

## Notes

This is an academic console project, not a production e-commerce platform. It is published as a compact example of programming fundamentals: clean menu flow, input validation, CRUD operations, searching, and category filtering.
