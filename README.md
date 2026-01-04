# Smart Card Access System

A C# console application for managing university smart cards, tracking attendance, processing payments, and generating reports.

## Features
- **Dual Login System** (Admin & Card Holder)
- **Card Management** (Issue, Block, Unblock)
- **Financial Operations** (Recharge, Cafeteria payments, Bus rides)
- **Attendance Tracking** (Lecture recording, Report generation)
- **Transaction History** (View all payment records)
- **Data Persistence** (Serialization support)

## Technologies
- C# (.NET Core)
- Object-Oriented Programming
- Serialization (BinaryFormatter)
- Console Application

## Project Structure
- `Card.cs` - Smart card entity with balance management
- `Person.cs` - User profiles (Students/Faculty)
- `Transactions.cs` - Financial transaction records
- `Attendance.cs` - Lecture attendance tracking
- `main_Prog.cs` - Core application logic
- `Program.cs` - Main entry point and UI

## How to Run
1. Clone the repository
2. Open in Visual Studio or VS Code
3. Build and run the project
4. Use test credentials from `Def_data()` method

## Sample Credentials
- Admin: Use admin menu options
- Student Card: "30" (active), "20" (blocked)
- Faculty Card: "10" (blocked)
