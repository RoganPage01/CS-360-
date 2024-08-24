# CS-360-Summary of App Requirements and Goals:

The app I developed is an inventory management system designed to help users track items in stock and manage quantities effectively. The app's primary goal is to streamline the inventory process, allowing users to add, delete, update, and read inventory items from a database. Additionally, the app includes SMS notifications for low inventory alerts. This app was developed to address user needs for a simple yet functional tool for inventory tracking, ensuring that businesses or individuals could monitor stock levels and receive timely notifications when action is needed.

Screens and Features Supporting User Needs:

The app includes several key screens:

A login screen that ensures security and saves user credentials in a persistent database.
An inventory screen that displays the inventory items in a grid format for easy visualization.
A data input form for adding new inventory items and updating existing ones.
An SMS feature to send notifications when inventory levels are low.
The UI designs kept users in mind by ensuring that the app was intuitive and user-friendly. The grid layout for inventory data made it easy for users to understand and navigate, while the simple login and SMS notifications enhanced the user experience. The design succeeded because it focused on ease of use and streamlined inventory tracking, aligning with the needs of both small business owners and individual users.

Approach to Coding the App:

The coding process began with setting up a solid database foundation using SQLite. From there, I created a modular structure with individual components responsible for handling database interactions, user input, and SMS functionality. I followed best practices like in-line commenting, clear naming conventions, and iterative testing to ensure smooth functionality. In the future, these strategies can be applied to larger-scale projects by breaking down complex systems into manageable components and testing frequently.

Testing and Debugging Process:

To ensure the functionality of the app, I used the Android Emulator extensively, running the app in different scenarios to simulate real-world use. This allowed me to test the login process, database operations (CRUD), and SMS notifications. The testing process was crucial because it revealed areas where the app needed adjustments—especially in handling user permissions and database consistency—before final deployment.

Innovative Solutions to Overcome Challenges:

One of the main challenges was ensuring that the app's SMS notification system functioned even when user permissions were denied. I had to innovate by implementing fallbacks so that the core inventory management system would continue to function seamlessly, regardless of SMS permission status. This required researching Android permission handling and creating robust error management systems.

Successful Components:

I was particularly successful in demonstrating my knowledge of database management and SMS integration. The SQLite database was designed and implemented in a way that ensures data persistence, while the SMS notification feature effectively alerted users of low inventory levels, meeting the core requirements of the app. These components demonstrated a strong understanding of mobile app development principles and user-centered design.
