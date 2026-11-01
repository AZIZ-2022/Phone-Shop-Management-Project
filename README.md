# 📱 Phone Shop Management System

A management system for a mobile phone retail shop. It helps the shop owner and staff keep track of phone stock, record sales, manage customers and suppliers, and see how the business is doing, replacing handwritten registers and spreadsheets.

---

## 🎯 What the System Does

- Keeps an accurate record of every phone and accessory in stock
- Records each sale and produces a bill for the customer
- Tracks purchases from suppliers and updates stock automatically
- Shows what is selling, what is running low, and how much profit the shop makes

---

## ✨ Functionality

### 1. User Login & Roles
- Secure login and logout
- **Admin / Owner:** full access, including reports and user management
- **Staff / Salesperson:** day-to-day sales and stock lookup

### 2. Product & Inventory Management
- Add, edit, and delete phones and accessories
- Store brand, model, color, storage, RAM, condition (new / used), purchase price, and selling price
- Track unique **IMEI / serial number** for each phone
- Live stock quantity, updated automatically after every sale or purchase
- Low-stock alerts
- Search and filter by brand, model, price range, and availability

### 3. Sales
- Create a sale by selecting products and quantity
- Automatic total, discount, and payable amount calculation
- Stock is reduced as soon as the sale is saved
- Payment types: cash, card, mobile banking, or partial payment with due
- Printable invoice for the customer
- Sales history with search by date, customer, or invoice number

### 4. Purchases & Suppliers
- Manage supplier information
- Record purchases from suppliers; stock increases automatically
- Track amount paid to suppliers and amount still due
- Purchase history per supplier

### 5. Customer Management
- Save customer name, phone number, and address
- View each customer's purchase history
- Track customer dues and payments

### 6. Warranty & Returns
- Record warranty period for each sold phone
- Look up a phone's warranty status by IMEI
- Handle returns and exchanges, with stock adjusted accordingly

### 7. Dashboard & Reports
- Dashboard: today's sales, total stock, low-stock items, pending dues
- Daily, weekly, and monthly sales reports
- Profit report (selling price minus purchase price)
- Best-selling brands and models
- Stock report

---

## 🔄 Typical Workflow

```
Buy stock from supplier → Add to inventory (IMEI, price) → Customer picks a phone
      → Create sale and apply discount → Collect payment (full or partial)
      → Print invoice → Stock updates automatically → Reports update
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/AZIZ-2022/Phone-Shop-Management-Project.git
cd Phone-Shop-Management-Project
```

Follow the setup steps for the project's framework (install dependencies, configure the database connection, and run the application).

---

## 🗺️ Roadmap

- [ ] Barcode / IMEI scanner support
- [ ] SMS notification for dues and warranty expiry
- [ ] Multi-branch support
- [ ] Online order integration

---

## 👤 Author

**AZIZ-2022**: [GitHub](https://github.com/AZIZ-2022)
