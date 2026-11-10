Laptop Techno Store
Introduction
This project is a simple laptop information display application developed using Python and Streamlit.
It retrieves laptop information from an SQLite database and displays the products in a wide web interface.
Features
Connect to an SQLite database.
Read laptop information from the database.
Display laptop images.
Show laptop descriptions.
Display laptop prices.
Provide links to view products.
Display products in a four-column layout.
Technologies
Python
Streamlit
SQLite
Pandas
Database
The project uses the following database:
LaptopData.db 
The database contains a table named:
laptop_techno 
Database Columns
image_url: Laptop image URL.
description: Laptop description.
price: Laptop price.
link: Product webpage.
Project Structure
Laptop_Techno/ ├── main.py ├── LaptopData.db └── README.md 
Installation
Install the required libraries:
pip install streamlit pip install pandas 
How to Run
Open the project in VS Code.
Make sure LaptopData.db is available in the project folder.
Run the application:
streamlit run main.py 
Open the application in your browser.
How It Works
The application connects to the SQLite database and retrieves laptop information using SQL.
Pandas loads the database records into a DataFrame.
Streamlit displays each laptop in a four-column layout with its image, description, price, and product link.
Output
The application displays laptop products in a web interface.
Each product includes:
Image
Description
Price
View button
Author
Python Programming Student
