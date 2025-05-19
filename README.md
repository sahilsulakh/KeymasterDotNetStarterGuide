🔐 KeymasterDotNetStarterGuide
This repository provides a complete starter guide for integrating KeyMaster — Agni’s secure license key authentication system — into a Windows Forms (.NET Framework) application.

It includes:

✅ Full source code for license key authentication

🔑 Secure HWID (Hardware ID) generation and validation

🛡️ Authentication flow with KeyMaster backend (success/failure handling)

🖥️ Clean and beginner-friendly WinForms UI

📦 Ready-to-use classes for AuthRequest, AuthResponse, and HWID generation

🧪 Easy to extend with username/password authentication (optional)

💼 Ideal For:
.NET Developers building cheat panels, admin tools, or any app requiring secure license validation

Beginners learning how to work with authentication APIs

Projects using KeyMaster for key-based access control

📂 Structure:
AuthRequest.cs / AuthResponse.cs – Data models for API communication

AuthService.cs – Handles communication with the KeyMaster backend

HwidGenerator.cs – Generates and stores a consistent HWID

Form1.cs – UI and logic for license key authentication

🚀 Get Started:
Clone this repo, open it in Visual Studio, set your KeyMaster backend URL, and you're ready to go!
