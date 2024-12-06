# Opay Clone

A Laravel-based clone of the Opay platform, featuring payment processing, user management, and an intuitive admin dashboard. This project aims to replicate the core functionalities of Opay, providing a full-fledged payment solution with a customizable backend.

---

## Features

- **User Authentication:** Register, login, and manage users with secure authentication.
- **Payment Gateway Integration:** Process payments using popular payment APIs.
- **Admin Dashboard:** Manage users, payments, and other platform settings.
- **Laravel Backend:** Utilizes Laravel’s powerful features such as Eloquent ORM, routing, and security.
- **Blade Templating:** Clean, responsive front-end powered by Blade.
- **Role-based Access Control:** Separate user roles with different permissions for admin and regular users.
- **Notifications:** Receive payment success/failure notifications.

---

## Installation

Follow these steps to set up the project locally:

### Prerequisites

- PHP >= 8.0
- Composer
- Node.js and npm
- MySQL or any other database supported by Laravel
- Git

### 1. Clone the repository

Clone the repository to your local machine:

```bash
git clone https://github.com/certifiedcoder001/opay-clone.git
cd opay-clone
```
### 2. Install dependencies
Run the following commands to install the necessary PHP and JS dependencies:

```bash
composer install
npm install
```
### 3. Set up environment
Create a copy of the .env.example file:

```bash
cp .env.example .env
```
Then, open the .env file and configure your database and other settings as needed.

### 4. Generate application key
Generate the application key by running:
```
bash
php artisan key:generate
```
### 5. Run migrations
Migrate the database to create all necessary tables:

```
bash
php artisan migrate
```
### 6. Install assets
To compile your assets, run:

```
bash
npm run dev
```
This will compile your CSS, JavaScript, and other assets.

### 7. Start the development server
Finally, serve the application:

```
bash
php artisan serve
```
The application should now be available at http://localhost:8000.


