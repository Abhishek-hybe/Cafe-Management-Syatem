# Cafe-Management-Syatem
The BakeryOrderManagement system is a Python-based order management tool for bakeries. It allows users to add, view, and update orders, and save them to an Excel file. Orders are stored in a pandas DataFrame with details like customer name, item, quantity, and order date, enabling efficient order handling.

Bakery Order Management System
The Bakery Order Management System is a Python-based application that helps manage bakery orders efficiently. It allows users to add, view, and update orders, and save the order data to an Excel file for record-keeping. This system leverages the Pandas library for data manipulation and storage.

Features
Add Order: Allows users to add a new order by providing customer name, item ordered, and quantity.
View Orders: Displays all the orders currently stored in the system.
Update Order: Enables users to update the details of an existing order using the order ID.
Save to Excel: Saves all orders to an Excel file named bakery_orders.xlsx.
Requirements
Python 3.x
pandas
openpyxl (for saving to Excel)
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/bakery-order-management.git
Navigate to the project directory:
bash
Copy code
cd bakery-order-management
Install the required Python packages:
bash
Copy code
pip install pandas openpyxl
Usage
Run the order_management.py script to start the application:

bash
Copy code
python order_management.py
The application will present a menu with the following options:

Add Order:

Enter the customer name, item ordered, and quantity.
The order will be added with the current date.
View Orders:

Displays all orders in a tabular format.
Update Order:

Enter the order ID of the order you want to update.
Provide the new item and quantity for the order.
Save to Excel:

Saves the current orders to bakery_orders.xlsx in the project directory.
Exit:

Exits the application.
Example
mathematica
Copy code
1. Add Order
2. View Orders
3. Update Order
4. Save to Excel
5. Exit

Enter your choice: 1
Enter customer name: John Doe
Enter item ordered: Chocolate Cake
Enter quantity: 2
Order added successfully!

Enter your choice: 2
   Customer Name           Item  Quantity  Order Date
0     John Doe  Chocolate Cake         2  2023-12-05

Enter your choice: 4
Orders saved to 'bakery_orders.xlsx'.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
Acknowledgements
Pandas Documentation
openpyxl Documentation
Feel free to contribute to the project by submitting issues or pull requests!

By using this system, managing bakery orders becomes a streamlined and efficient process, ensuring that all orders are accurately recorded and easily accessible.
