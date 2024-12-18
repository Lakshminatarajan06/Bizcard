# Bizcard
BizCardX: Extracting Business Card Data with OCR

Business Card Information Extractor
Overview
This project is a Streamlit-based application that allows users to upload an image of a business card and extract relevant information from it using EasyOCR. The application extracts key details such as:

Company Name
Cardholder Name
Designation
Mobile Number
Email Address
Website URL
Area
City
State
Pin Code
The extracted information is displayed in a clean and organized interface within the application.

Features
Upload and Extract Information:
Users can upload an image of a business card, and the application will extract its details using EasyOCR.

Save to Database:
Users can save the extracted information along with the uploaded business card image to a database (SQLite or MySQL).

CRUD Operations:

Read: View the saved information and images in the database.
Update: Modify existing entries directly through the Streamlit UI.
Delete: Remove unwanted entries from the database.
User-Friendly Interface:
A simple and intuitive GUI guides users through the process of uploading, extracting, and managing business card information.

Technologies Used
Python: For the application logic.
Streamlit: For building the graphical user interface.
EasyOCR: For optical character recognition to extract information from images.
SQLite/MySQL: For database management and data persistence.
Application Architecture
The application is designed to be:

Scalable: Easily adaptable for new features.
Maintainable: Modular and well-documented code for easy updates.
Extensible: Allows the integration of additional functionality as needed.
Getting Started
Prerequisites
Ensure you have the following installed:

Python 3.x
Required Python packages (Streamlit, EasyOCR, Pillow, sqlite3 or MySQL connector)
Installation
Clone the repository:
bash
Copy code
git clone <repository-url>
cd <repository-folder>
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the application:
bash
Copy code
streamlit run app.py
Documentation
The repository contains detailed documentation for:

Setting up the project
How to use the application
Database schema
