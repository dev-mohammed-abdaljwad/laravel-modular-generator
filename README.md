# Laravel Modular API Generator

A custom Artisan command to generate a clean, modular, **API-first architecture**
using Repository Pattern & Service Layer in Laravel.

This tool is opinionated by design and focuses on **consistency, scalability, and developer productivity**.

---

## ✨ Why This Tool?

In medium to large Laravel projects, repeatedly creating:

- Model
- Repository
- Service
- Controller
- Requests
- Transformer

often leads to:
- Boilerplate repetition
- Namespace mistakes
- Inconsistent architecture
- Wasted setup time

This command solves that by generating a **fully structured module** in seconds.

---

## 🧱 Generated Architecture

When running:

```bash
php artisan make:module User --all
