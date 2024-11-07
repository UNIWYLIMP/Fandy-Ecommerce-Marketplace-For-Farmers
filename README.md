# 🌾 Fandy Ecommerce Marketplace for Farmers

Fandy is an eCommerce platform that connects farmers directly with consumers, enabling them to buy and sell fresh, farm-to-table goods. Built to support sustainable agriculture and empower local farmers, Fandy offers a streamlined marketplace for fresh produce, dairy, grains, and more, creating a seamless farm-to-consumer experience.

---

## 📌 Overview

**Fandy Ecommerce Marketplace** provides an easy-to-use interface where farmers can list their goods and consumers can browse and purchase fresh produce directly from farms. This marketplace aims to boost farmers' income, reduce food miles, and promote fresh, high-quality produce for consumers.

---

## 🚀 Key Features

- **🌱 Direct Farm-to-Table Sales**  
  Enables farmers to sell their products directly to consumers, ensuring freshness and minimizing middlemen.

- **📋 Farmer Listings & Profiles**  
  Farmers can create profiles, showcase their farms, and list available produce with detailed descriptions.

- **🛒 User-Friendly Shopping Experience**  
  Consumers can easily browse products by category, view farmer profiles, and make purchases with a simple checkout process.

- **📦 Order Management**  
  Farmers can track and manage orders, including setting availability for different seasons and produce varieties.

- **💸 Secure Payments**  
  Integrated secure payment options provide a safe transaction environment for both farmers and buyers.

- **📍 Local Farm Finder**  
  Consumers can discover farms nearby, supporting local agriculture and reducing delivery distances.

---

## 📂 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/UNIWYLIMP/Fandy-Ecommerce-Marketplace-For-Farmers.git
   cd fandy-ecommerce-marketplace
   ```

2. Set up a virtual environment and install dependencies:
   ```bash
   python3 -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

---

## ⚙️ Configuration

1. **Database Setup**: Configure your database settings (e.g., PostgreSQL, SQLite) in `settings.py`.
2. **Environment Variables**: Set up environment variables for sensitive information like payment gateway keys and database credentials.
3. **Run Migrations**: Initialize the database tables with:
   ```bash
   python manage.py migrate
   ```
4. **Create an Admin User**: Set up an admin account to manage platform settings:
   ```bash
   python manage.py createsuperuser
   ```

---

## 🛠 Usage

1. **Start the Development Server**:
   ```bash
   python manage.py runserver
   ```
2. **Register as Farmer/Consumer**: Use the web interface to register as a farmer and list products or as a consumer to start shopping.
3. **Browse & Purchase**: Consumers can explore local farm goods, add items to the cart, and complete purchases securely.

---

## 📝 Requirements

- **Python** >= 3.8
- **Django** >= 3.2
- **Database**: PostgreSQL, MySQL, or SQLite

---

## 🤝 Contributing

We welcome contributions to improve Fandy!

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---

## 💬 Support

If you have questions or run into issues, open a [GitHub Issue](https://github.com/UNIWYLIMP/Fandy-Ecommerce-Marketplace-For-Farmers/issues) or contact [Support](mailto:uniwylimp@gmail.com).

---

### 🌿 Support Local Farmers and Enjoy Fresh Produce with Fandy

Shop farm-fresh goods while supporting local farmers through **Fandy Ecommerce Marketplace for Farmers**.
