# Password Manager GUI - README

## Project Overview
The **Password Manager GUI** is a Python-based application that allows users to store, manage, and retrieve credentials for different websites. Built using the **Tkinter** library, this tool offers a simple graphical user interface for easy interaction, while securely storing credentials in a **JSON file**.

## Features
- **Credential Storage**: Save usernames, passwords, and website details for easy retrieval.
- **Password Generator**: Generate strong, random passwords to enhance security.
- **User Notifications**: Informative message boxes notify users when credentials are saved, retrieved, or when no credentials are available.
- **Data Persistence**: All credentials are stored in a JSON file, which is automatically created if it doesn't exist.
  
## How It Works
1. **Store Credentials**: Enter your website, username, and password. Click the "Add" button to save your credentials.
2. **Generate Password**: Use the "Generate Password" button to create a strong, random password.
3. **Find Credentials**: Enter the website name to retrieve the associated credentials.
4. **Empty File Handling**: If the JSON file has no credentials stored, a message box will notify you.

## Dependencies
- **Python 3.x**
- **Tkinter** (Standard with Python)
- **JSON** (Standard with Python)

## Installation
1. Clone the repository or download the project files.
2. Ensure Python 3.x is installed on your system.
3. Run the main Python script to start the application:

```bash
python main.py
```

## Usage
- Upon launching, the application window will open where you can store, retrieve, or generate credentials.
- Follow on-screen prompts and use the message boxes for confirmation or warnings.
  
## Future Enhancements
- Add encryption for stored passwords.
- Implement a search and filter feature for large sets of credentials.

---


