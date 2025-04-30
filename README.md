
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
2. **Install PHP dependencies**:

 composer install
 
3. **Install Node.js dependencies and compile assets**:
   ```bash
    npm install
    npm run dev

4. **Set up environment variables**:
    ```bash
    Copy the .env.example file to .env:
    cp .env.example .env

Update database and other environment configuration in .env.

5. **Generate application key**:
    ```bash
    php artisan key:generate
6. **Run database migrations (if applicable)**:
    ```bash
    php artisan migrate
7. **Start the Laravel development server**:
    ```bash
    php artisan serve
The application will typically be available at http://localhost:8000

📊 **Features**
Visual analysis of:

Landholding patterns

Irrigation sources

Cropping types

Well depths across regions

Admin panel for data management (if implemented)

Responsive UI built with Blade templates and Bootstrap/CSS

Modular Laravel MVC structure

📷 **Screenshots**

![Screenshot 2025-04-30 104703](https://github.com/user-attachments/assets/ef143506-958b-4775-9c94-66337ab9d746)

![Screenshot 2025-04-30 104715](https://github.com/user-attachments/assets/86234870-7fe8-4849-bd6a-6c071310832c)

![Screenshot 2025-04-30 104728](https://github.com/user-attachments/assets/e3ceadc3-9333-4ddb-94b9-7bb1d5c30e85)

![Screenshot 2025-04-30 104737](https://github.com/user-attachments/assets/fa307be9-982c-458a-8daf-49761d876088)

![Screenshot 2025-04-30 104749](https://github.com/user-attachments/assets/2234f462-b60d-4986-b525-13eb0b2a2c69)

![Screenshot 2025-04-30 104801](https://github.com/user-attachments/assets/5b9b59bf-8564-47ee-b47e-aa1863e67ca8)

![Screenshot 2025-04-30 104818](https://github.com/user-attachments/assets/32e89484-c053-4258-874e-33e135240a49)

![Screenshot 2025-04-30 104831](https://github.com/user-attachments/assets/a67f30cd-daa1-4177-887a-baea40cb373a)

![Screenshot 2025-04-30 104848](https://github.com/user-attachments/assets/79ac6b26-3569-46df-a189-60eee02b0e7f)

![Screenshot 2025-04-30 104903](https://github.com/user-attachments/assets/392ef283-5afa-4ab3-9a46-1baafb7f5749)

![Screenshot 2025-04-30 104915](https://github.com/user-attachments/assets/dc28c756-4cb4-4846-b106-e3bc12d887c2)

![Screenshot 2025-04-30 104925](https://github.com/user-attachments/assets/99559e7b-1993-4a04-bcf8-71fecfa727b3)

![Screenshot 2025-04-30 104937](https://github.com/user-attachments/assets/9b9c2062-1d96-42e6-a26b-3540eae7c5db)

![Screenshot 2025-04-30 104949](https://github.com/user-attachments/assets/e3b74ece-2602-4236-b603-42690c199f03)

![Screenshot 2025-04-30 104957](https://github.com/user-attachments/assets/c4d0e41f-2fca-4608-ba0f-b15822a63a6f)


**🙋‍♂️ Author**
**Created by Harshit Sharma**
**📧 Email: ihspvt@gmail.com**
**🔗 GitHub | LinkedIn**
