# Laravel Make Module Command

A custom Artisan command to generate a full modular API structure following
Repository Pattern & Service Layer.

## Features
- Model
- Migration
- Factory
- Repository (Interface + Eloquent)
- Service Layer
- API Controller (V1)
- Form Requests
- Transformer

## Usage

```bash
php artisan make:module User --all
php artisan make:module User --model --repository --service
```
## Folder Structure
app/
 ├── Models
 ├── Repositories
 ├── Services
 ├── Transformers
 ├── Http/Controllers/Api/V1
 └── Http/Requests/Api/V1
 
