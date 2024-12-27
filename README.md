<p align="center"><img width="400" src="https://github.com/movecrm/MoveCRM/blob/main/Logo-movecrm-small.svg"></a></p>

# MoveCRM - Open-Source CRM & ERP

MoveCRM is an innovative open-source CRM and ERP system built on **Laravel**, designed to streamline your business processes and enhance customer relationships. MoveCRM's modular architecture allows seamless integration of new features, making it the perfect choice for businesses of all sizes.

## 🚀 Key Features

### 🌐 Modular System
- Add or remove features based on your business needs.
- Custom modules for sales, support, project management, and more.

### 🔒 Secure and Scalable
- Built with Laravel 11, ensuring top-tier security and performance.
- Easily scalable as your business grows.

### 🎨 User-Friendly Interface
- Modern, responsive UI crafted with **Material Web** for an intuitive experience.
- Fully customizable dashboards and views.

### 📊 Advanced Data Management
- Powerful filtering and data table tools for seamless data analysis.
- Supports Advanced Tables (formerly Filter Sets) for better data visualization.

### 📅 Calendar & Scheduling
- Full-featured calendar system for scheduling and task management.
- Integrates directly with Google Calendar and Sheets.

### 🛠️ Developer-Friendly
- Open-source and fully documented.
- Easy to extend and integrate with third-party APIs.

---

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/movecrm//movecrm.git

# Navigate into the directory
cd movecrm

# Install dependencies
composer install

# Environment setup
cp .env.example .env
php artisan key:generate

# Database migration
php artisan migrate

# Serve the application
php artisan serve

# Add Partners Module
git submodule add https://github.com/username/movecrm-partners.git modules/partners
php artisan module:migrate partners
```

---

## 💼 Use Cases
- **Customer Management**: Track leads, manage contacts, and automate follow-ups.
- **Project Management**: Organize tasks, deadlines, and team collaboration.
- **Inventory & Orders**: Keep track of inventory and automate order processing.
- **Billing & Invoicing**: Generate invoices and track payments effortlessly.

---

## 🌍 Why Choose MoveCRM?
- **Free and Open-Source** – No licensing fees.
- **Community-Driven** – Contribute and shape the future of MoveCRM.
- **Highly Customizable** – Tailor MoveCRM to fit your unique business needs.

---

## 🤝 Contributing
We welcome contributions from the community! Whether it's bug fixes, new features, or documentation, feel free to submit a pull request.

---

## 📞 Support
For support or inquiries, please reach out to our [support team](mailto:support@movecrm.com) or open an issue on GitHub.

---

**Star** ⭐ this project to show your support!

---

## Sponsors

MoveCRM is proudly supported by our amazing sponsors. A big thank you to:

[![themeselection.com](https://hf2kfb.infiniteuploads.cloud/thegem-logos/logo_80fe48c54d95b89dfcc63d4b263e38b6_1x.png)](https://themeselection.com/)

---

### License
MoveCRM is licensed under the [MIT License](LICENSE).
