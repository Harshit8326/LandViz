
# LandViz 🌾

**LandViz** is a Laravel-based web application for land analysis across various regions of India. It visualizes landholding patterns, sources of irrigation, cropping practices, and well depths in a structured and interactive way.

---

## 📁 Project Structure

This repository includes:

- `app/`: Core application logic (Controllers, Models).
- `routes/`: Web routes (`web.php`) for navigation and request handling.
- `resources/views/`: Blade templates for frontend UI.
- `public/`: Frontend assets like CSS, JS, and images.
- `.env.example`: Example environment file for configuration.
- `composer.json`: Dependency manager for Laravel packages.
- `package.json`: Frontend dependencies.
- `webpack.mix.js`: Laravel Mix asset compilation.

> ❌ **Note**: The `vendor/` directory has been removed to keep the repository clean. Run `composer install` after cloning to regenerate it.

---

## 🛠 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Harshit8326/LandViz.git
   cd LandViz
2. **Install PHP dependencies:

 composer install
 
3. **Install Node.js dependencies and compile assets:
   ```bash
    npm install
    npm run dev

4. **Set up environment variables:
    ```bash
    Copy the .env.example file to .env:
    cp .env.example .env

Update database and other environment configuration in .env.

5. **Generate application key:
    ```bash
    php artisan key:generate
6. **Run database migrations (if applicable):
    ```bash
    php artisan migrate
7. **Start the Laravel development server:
    ```bash
    php artisan serve
The application will typically be available at http://localhost:8000

📊 **Features
Visual analysis of:

Landholding patterns

Irrigation sources

Cropping types

Well depths across regions

Admin panel for data management (if implemented)

Responsive UI built with Blade templates and Bootstrap/CSS

Modular Laravel MVC structure

📷 **Screenshots


**🙋‍♂️ Author
**Created by Harshit Sharma
**📧 Email: ihspvt@gmail.com
**🔗 GitHub | LinkedIn
