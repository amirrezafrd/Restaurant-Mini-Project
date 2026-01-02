# Restaurant Menu Management System

A simple command-line Python application for managing a restaurant menu.  
All data is stored persistently in a CSV file called `restaurant_menu.txt`.

## Features

- Add new dishes
- View all dishes in a formatted table
- Search dishes by name or category
- Update existing dish information
- Delete dishes
- Case-insensitive duplicate name checking
- Automatic file & header creation if the file doesn't exist

## Technologies

- Python 3.x
- Only built-in modules: os, csv, sys

## Project Structure
restaurant-menu-management/
├── main.py               # Main application file
├── restaurant_menu.txt   # Data storage (auto-generated)
└── README.md             # This file
text## Installation & Usage

1. Make sure you have Python 3 installed  
2. Clone or download the repository  
3. Navigate to the project directory  
4. Run the program:

```bash
python main.py
# or
python3 main.py
Main Menu Preview
text========================================
  RESTAURANT MENU MANAGEMENT SYSTEM  
========================================
1. Add new dish
2. Show all dishes
3. Search dish
4. Update dish
5. Delete dish
0. Exit

Enter your choice (0-5):
Important Notes

Prices must be positive integers (in Rials)
Dish names are case-insensitive
The file restaurant_menu.txt is automatically created if it doesn't exist
When updating a dish, leave any field empty to keep the current value

Sample restaurant_menu.txt content
csvDish Name,Description,Price,Category
Ghormeh Sabzi,Traditional Persian herb stew with meat,185000,Stew
Kebab Koobideh,Fresh minced meat kebab,220000,Kebab

Lightweight menu management system — great for small restaurants or as a learning project.
