Restaurant POS System
A fully responsive, single-page web application that simulates a Point of Sale (POS) system for a restaurant. This project is built entirely with front-end technologies and uses mock data to demonstrate its functionality. It features role-based access, table management, order taking, a kitchen display system, and a sales dashboard.

The entire application is self-contained in a single index.html file, making it extremely portable and easy to run without any server or build steps.

Features
Role-Based Access Control: Log in as one of four different user roles (Admin, Manager, Waiter, Kitchen) to see a customized interface and feature set.

Interactive Table Layout: A visual grid of restaurant tables showing their current status:

Available (Gray): Ready for new customers.

Occupied (Blue): An order is in progress.

Billing (Yellow): The order is complete and ready for payment.

Intuitive Order Management:

Click on a table to open a detailed order modal.

Easily add items from a categorized menu.

Adjust item quantities or remove them from the current order.

Real-time calculation of the order total.

Kitchen Display System (KDS / KOT):

A dedicated screen for the kitchen staff.

Orders appear in real-time in the "New" column.

Track order progress by moving them from "New" -> "Preparing" -> "Ready".

Billing & Payment: Once an order is served, the table status changes to "Billing". Clicking the table opens a billing modal with a complete summary, including taxes and service charges, and options to process payment.

Manager/Admin Dashboard:

At-a-glance view of key metrics: Total Sales, Active Orders, Completed Orders, and Low Stock Items.

Lists of Top Selling Items and Recent Orders.

Inventory Management: A simple table view to monitor the stock levels of all menu items, with visual indicators for low-stock items.

Fully Responsive: The user interface is designed to work seamlessly on desktops, tablets, and mobile phones.

Technologies Used
HTML5: Structures the application.

CSS3: Provides custom styling for the dark theme, color scheme, and animations.

JavaScript (ES6+): Handles all the application logic, state management, and dynamic rendering.

jQuery: Used for DOM manipulation and simplified event handling.

Bootstrap 5: Powers the responsive grid system, modals, buttons, and other core UI components.

Bootstrap Icons: Provides a clean and comprehensive set of icons used throughout the application.

Google Fonts: The "Inter" font is used for clean and modern typography.

How to Run
This project is designed for simplicity and requires no complex setup.

Download the File: Save the index.html file to your local machine.

Open in Browser: Right-click the index.html file and choose "Open with" your favorite web browser (e.g., Google Chrome, Firefox, Microsoft Edge).

That's it! The application will run directly in your browser. No web server, dependencies, or build process is needed.