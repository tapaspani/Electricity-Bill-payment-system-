🧾 Electricity Bill Payment System – Java (Swing | JDBC | MySQL | Twilio | Razorpay)

A complete desktop-based Electricity Bill Payment System built using Java Swing, JDBC, and MySQL, with integrated SMS notifications via Twilio and online payments through Razorpay.
This project allows users to manage electricity bills, view usage details, update customer information, and make secure payments.

🚀 Features
🔹 Customer & Billing Management

Add, update, and delete customer details

Generate monthly electricity bills

Calculate charges based on units consumed

View bill history and previous transactions

Search customers and billing records

🔹 Bill Calculation

Automatic bill generation

Configurable unit rates

Dynamic calculations using Java logic

Printable bill receipts

🔹 Payment Integration

💳 Razorpay Payment Gateway integrated for secure online payments

Payment verification & transaction recording

Supports UPI, Card, Wallet, NetBanking

🔹 SMS Notifications

📩 Twilio API used to send:

Payment confirmation SMS

Bill due reminders

OTP or alerts (if enabled)

🔹 User Interface (Java Swing)

Clean and responsive UI

Separate screens for customer, billing, and payment

Form validations

Real-time status updates

🛠 Tech Stack
Technology	Used For
Java Swing	GUI / Frontend
JDBC	Database Connectivity
MySQL	Backend Database
Twilio API	SMS Messaging
Razorpay API	Online Payment Integration
Java AWT / Swing	UI Components
XAMP / WAMP / MySQL Server	Database Hosting
📂 Project Modules
1️⃣ Customer Module

Register new customers

Update user information

Delete customers

View all customers

2️⃣ Billing Module

Generate bills

Auto calculation by units

View previous bills

Print/download receipts

3️⃣ Payment Module

Razorpay online payment

Auto-update payment status

Store transaction details

Payment success popup / SMS alert

4️⃣ Admin Panel

Manage customers

Modify unit cost

View all transactions

Database overview (optional)

🗄 Database Information
Tables Used

customers

bills

transactions

admins (optional)

Sample Fields:

Customer ID

Name

Address

Units Consumed

Bill Amount

Payment Status

Date / Timestamp

⚙️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/yourusername/Electricity-Bill-Payment-System.git
