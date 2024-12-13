
![Build the SaaS you want](.github/assets/banner.jpg "Build the SaaS you want")

<p align="center">
  <br/>
  <strong>SASSTER</strong>: The Symfony SaaS Web App Template  
  <br/>
  <em>Your all-in-one solution to supercharge your SaaS development with PHP.</em>  
  <br/><br/>
</p>

<div align="center">

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/jensone/sasster/blob/main/LICENSE) [![Symfony 7.2](https://img.shields.io/badge/Symfony-%23000000.svg?logo=symfony&logoColor=white)](https://symfony.com/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/) [![Stripe](https://img.shields.io/badge/Stripe-%23008cdd.svg?logo=stripe&logoColor=white)](https://stripe.com/)

</div>

---

## 🚀 Why SASSTER?

SASSTER is designed for **developers of all levels**, from **junior** devs taking their first steps into SaaS, to **senior engineers** who need a fast and robust starting point.  
Forget repetitive setups—jump straight into building **the SaaS of your dreams**.

### ✨ What's Inside?

- **User Management**: Authentication, registration, and more out of the box.
- **Subscription Management**: Integrates seamlessly with Stripe for recurring payments.
- **Invoice Management**: Generate and manage customer invoices effortlessly.
- **Modern Design**: Pre-configured with **Tailwind CSS** for stunning UIs.
- **Developer-Friendly**: Built with **Symfony 7.2**, ensuring speed, security, and flexibility.

---

## 🛠️ Installation & Setup

Follow these simple steps to get started:

### 1. Clone the Repository

```bash
git clone https://github.com/jensone/sasster.git
cd sasster
```

### 2. Install Dependencies

```bash
composer install
```

### 3. Setup the Environment

Add all the required environment variables to the `.env` file.

```env
DATABASE_URL=
MAILER_DSN=
STRIPE_KEY=
STRIPE_SECRET=
```

### 4. Setup the Database

I strongly recommend using [**symfony-cli**](https://symfony.com/download) to setup the database.

```bash
php bin/console doctrine:database:create
php bin/console doctrine:schema:create
php bin/console doctrine:fixtures:load
```

### 6. Start the Development Server

```bash
symfony server:start
```

---

### Switch from Stripe to another Payment Gateway

If you're using Stripe, you can switch to another payment gateway by changing the environment variable in the `.env` file and implement your own `PaymentService.php`.

### Switch from Tailwind to another CSS Framework

If you're using Tailwind, you can switch to another CSS framework like Bootstrap or Bulma. Feel free to remove the Tailwind CSS config and replace them with your own.

---

## 🎯 Perfect for...

- **Startups**: Get your SaaS idea up and running in no time.  
- **Freelancers**: Build client projects faster with a reliable foundation.  
- **Agencies**: Standardize your SaaS development process and save hours.

---

## 🌟 Contribute

Have an idea to improve SASSTER?  
Feel free to **fork** the repo, create a branch, and open a **pull request**. Contributions are always welcome!

---

## 📄 License

SASSTER is open source and available under the **MIT License**.
