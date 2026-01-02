# Pharmacy-Management-System
This project demonstrates a dual-database architecture, implementing the same application using Oracle SQL (Relational) and MongoDB (NoSQL) while maintaining identical functionality and user experience.
The system automates core pharmacy operations including inventory control, sales billing, supplier management, and secure user access through a modern web-based interface.

🔧 Key Features
✅ Secure Authentication & Authorization
• JWT-based login system
• Role-based access control (Admin & Pharmacist)
• Password hashing using bcrypt

💊 Inventory (Drug) Management
• Add / update / delete medicines
• Real-time stock updates
• Expiry date tracking & validation
• Prevention of expired drug sales

🧾 Sales & Billing Module (POS)
• Barcode/search-based sales entry
• Atomic transactions with rollback support
• Digital receipt generation
• Complete sales & audit history

👥 Customer Dashboard
• Browse available medicines
• Search & filter drugs
• Persistent cart management
• Order placement with stock verification
• Built-in messaging system with admin

🏭 Supplier & Purchase Management
• Supplier registry
• Purchase & restocking records
• Inventory auto-update on purchase
• Complete purchase history for audits

🗄 Dual Database Support
• Phase 1: Oracle Database (Normalized Relational Schema)
• Phase 2: MongoDB (Document-based JSON Schema)
• Seamless data synchronization across both systems

🛠 Technologies Used
• React.js
• Node.js & Express.js
• Oracle Database
• MongoDB
• JWT & bcrypt
• Mongoose & OracleDB Driver
• VS Code
