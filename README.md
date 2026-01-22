🏦 Banking Management System - C++ Console Application
A simple yet functional Banking Management System built entirely in C++ using file-based storage. This console application simulates real-world banking operations with separate user and administrator interfaces.

✨ Features
👤 User Functionalities
----> Secure login with user ID and password
----> View account balance
----> Transfer money to other accounts
----> Deposit cash into account
----> Withdraw cash from account
----> Change account password

👨‍💼 Admin Functionalities
----> Administrator login system
----> Search for user account details
----> Open new customer accounts
----> Close existing accounts
----> View complete account information

🛠️ Technical Implementation
----> Pure C++ with Standard Library components
----> File-based storage using text files (no external databases)
----> Modular function-based architecture
----> Persistent data storage between sessions
----> Menu-driven console interface

📁 File Structure
----> accounts.txt – Stores all user account data (ID, password, name, balance)
----> adminAccounts.txt – Stores administrator credentials
----> temp.txt – Temporary file for data manipulation operations

🚀 Getting Started
:) Prerequisites
----> C++ Compiler (GCC, MinGW, or Visual Studio)
----> Basic understanding of C++ file operations
----> Compilation & Execution

bash
g++ ConsoleApplication1.cpp -o BankingSystem
./BankingSystem

📋 Usage Example
----> Run the executable
----> Choose User Login or Admin Login
----> Enter credentials (stored in respective text files)
----> Perform banking operations through the intuitive menu system
----> Data automatically saves to files for future sessions

🔧 Project Highlights
----> Clean, organized code structure
----> Recursive menu navigation
----> Input validation and error handling
----> Complete CRUD operations for accounts
----> Real-world banking simulation

⚠️ Note
This is an educational project demonstrating file handling and basic banking operations in C++. For production use, additional security measures (encryption, database integration, input sanitization) would be required.

📝 Learning Objectives
----> File I/O operations in C++
----> Data persistence techniques
----> Menu-driven console applications
----> User authentication systems
----> Banking system logic implementation

Perfect for students learning C++, file handling, and basic application development!
