# 🚀 Sistema básico de Notas

![Laravel](https://img.shields.io/badge/Laravel-12.x-red?style=flat&logo=laravel)  
> Um simples projeto em laravel que cria notas e armazena em uma base de dados. 

## 🎥 Demonstração
![Image](https://github.com/user-attachments/assets/a4eaac39-f451-4bda-9417-3290a2a6a4c1)

## 📂 Tecnologias Utilizadas
- ✅ Laravel 12.3.0
- ✅ MySQL  
- ✅ Bootstrap  

## 📦 Instalação e Execução  
```bash
# Clone o repositório
git clone https://github.com/phesgot/notas.git

# Entre na pasta do projeto

# Abra o projeto na IDE e abra o terminal

# Instale as dependências do Laravel
composer update

# Configure o banco de dados no .env e rode as migrations
php artisan migrate

# Alimente a base de dados rode o sedder
php artisan db:seed --class=UserTableSeeder

# Inicie o servidor local
php artisan serve
