# PROJECT: MASHALLAH WHOLESALE

## Complete Wholesale Shop Management & POS System

Act as a senior full-stack software engineer, UI/UX designer and database architect. Build a complete, production-ready wholesale shop management application named **MASHAALLAH WHOLESALE**.

The application must support both Windows Desktop and Web platforms, with offline functionality and secure online cloud synchronization.

### 1. TECHNOLOGY STACK

- Frontend: React + TypeScript
- Styling: Tailwind CSS
- Desktop application: Electron
- Backend: Node.js + Express
- Local database: SQLite
- Cloud database: PostgreSQL
- Charts: Recharts
- Authentication: Secure role-based authentication
- Currency: PKR (Pakistani Rupees)

### 2. PREMIUM UI/UX DESIGN

Create a high-end professional wholesale business dashboard.

Design theme:

- Dark navy blue
- Emerald green
- White and light grey
- No gold colors
- Smooth animations and transitions
- Premium sidebar navigation
- Modern typography and icons
- Beautiful interactive charts
- Responsive layouts
- Light and dark themes

The login page must display MASHAALLAH WHOLESALE branding.

### 3. MAIN DASHBOARD

Display:

- Today's Total Sales
- Today's Gross Profit
- Today's Net Profit
- Monthly Revenue
- Total Expenses
- Total Products
- Total Stock Value
- Low Stock Products
- Customer Outstanding Balance
- Supplier Outstanding Balance

Include:

- Sales analytics chart
- Monthly revenue chart
- Recent transactions
- Top-selling products
- Recent purchases

### 4. POS BILLING SYSTEM

Create a fast and professional billing interface.

Features:

- Search products by name
- Barcode scanner support
- Add products to cart
- Increase/decrease quantity
- Wholesale and retail prices
- Cart editing and product removal
- Automatic subtotal calculation
- Discount management
- Configurable tax
- Cash, bank and other payment methods
- Partial payments and credit sales
- Automatic change calculation
- Save and print invoices
- Thermal receipt printer support (58mm and 80mm)
- Reprint previous receipts
- Sales return and refund functionality

### 5. PRODUCT MANAGEMENT

Allow admin to:

- Add products
- Edit products
- Delete products
- Upload product images
- Create categories
- Add SKU and barcode
- Set purchase prices
- Set selling prices
- Set wholesale prices
- Define minimum stock
- Set expiry dates and batch information

Support multiple units:

- Piece
- Packet
- Dozen
- Box
- Carton

Allow unit conversion, for example:
1 carton = 12 boxes.

Stock calculations must correctly handle unit conversions.

### 6. INVENTORY MANAGEMENT

- Automatic stock reduction after sales
- Automatic stock increase after purchases
- Stock adjustments
- Damaged product records
- Purchase returns
- Sales returns
- Low-stock notifications
- Stock movement history
- Stock valuation
- Expiry alerts

Never allow stock quantities to become incorrect because of duplicate transactions.

### 7. PURCHASE & SUPPLIER MANAGEMENT

- Add suppliers
- Record supplier purchases
- Purchase invoices
- Purchase payment records
- Supplier outstanding balances
- Supplier payment history
- Purchase returns
- Purchase reports

### 8. CUSTOMER MANAGEMENT

- Add and edit customers
- Customer phone numbers
- Customer purchase history
- Credit sales (Udhaar)
- Customer outstanding balances
- Partial payments
- Payment history
- Customer statements

### 9. EXPENSE MANAGEMENT

Create an expense tracking system.

Categories:

- Shop Rent
- Electricity
- Employee Salaries
- Transport
- Internet
- Maintenance
- Other Expenses

Features:

- Add expenses
- Edit and delete with authorization
- Expense dates
- Expense receipts
- Daily and monthly expense reports

### 10. PROFIT & LOSS MANAGEMENT

Calculate actual business performance.

Gross Profit = Net Sales - Cost of Goods Sold.

Net Profit = Gross Profit - Business Expenses.

Include:

- Daily profit
- Weekly profit
- Monthly profit
- Product-wise profit
- Purchase cost tracking
- Discount tracking
- Returns and refunds
- Expense deductions

Use a consistent inventory costing method, preferably weighted average cost, and preserve historical transaction costs.

Do not treat customer credit sales as received cash.

### 11. REPORTS & ANALYTICS

Create professional reports:

- Daily sales
- Weekly sales
- Monthly sales
- Yearly sales
- Purchase reports
- Profit and loss
- Expense reports
- Stock reports
- Customer balance reports
- Supplier balance reports
- Best-selling products

Include date filters, PDF export, Excel export and print functionality.

### 12. USER MANAGEMENT

Create:

- Admin account
- Manager account
- Cashier account

Permissions:

- Admin: Full access
- Manager: Inventory, purchases, reports and sales
- Cashier: Billing and authorized customer operations

Maintain activity logs for important operations.

### 13. OFFLINE + ONLINE SYNCHRONIZATION

This is a critical requirement.

Windows Desktop:

- Must work without internet.
- Save transactions locally in SQLite.
- Allow offline billing and stock management.
- Queue unsynchronized changes.

Web Application:

- Secure online login.
- Cloud database.
- Access authorized business records.

Synchronization:

- Sync local transactions when internet returns.
- Prevent duplicate sales and purchases.
- Handle synchronization conflicts safely.
- Preserve transaction history.
- Display sync status.
- Never delete unsynchronized transactions.

### 14. BACKUP & SECURITY

- Automatic database backup
- Manual backup
- Restore database
- Secure password hashing
- Protected admin access
- Role-based authorization
- Input validation
- Audit logs
- Database transaction integrity

### 15. SETTINGS

- Shop name: MASHAALLAH WHOLESALE
- Shop address
- Contact number
- Shop logo
- PKR currency
- Invoice numbering
- Receipt design
- Printer configuration
- Tax settings
- User management
- Language: English
- Backup settings
- Synchronization settings

### 16. REQUIRED APPLICATION PAGES

Create these pages:

1. Login
2. Dashboard
3. POS Billing
4. Sales History
5. Products
6. Categories
7. Inventory
8. Purchases
9. Suppliers
10. Customers
11. Customer Ledger
12. Supplier Ledger
13. Expenses
14. Reports
15. Users
16. Settings
17. Backup & Restore

### 17. QUALITY REQUIREMENTS

IMPORTANT:

- Do not create a static UI prototype.
- Do not use fake buttons.
- Do not use non-functional forms.
- Do not use temporary browser storage as the only database.
- Implement real CRUD operations.
- Connect every module to the database.
- Implement proper loading and error states.
- Use reusable components.
- Test all calculations.
- Test billing and printing.
- Test offline mode.
- Test cloud synchronization.
- Test backup and restore.
- Prevent duplicate transactions.
- Ensure all reports reconcile with actual transactions.

### 18. FINAL DELIVERY

Deliver:

1. Complete React source code.
2. Complete backend source code.
3. SQLite database implementation.
4. PostgreSQL cloud implementation.
5. Windows Desktop executable installer (.exe).
6. Web deployment version.
7. Database schema.
8. Setup instructions.
9. Admin login setup.
10. Complete user documentation.

Build the application step by step, test each module, fix all errors and deliver a fully functional, professional wholesale management system.

**FINAL GOAL: MASHAALLAH WHOLESALE must look and work like a premium commercial business management product, not a student demo or simple billing page.**
