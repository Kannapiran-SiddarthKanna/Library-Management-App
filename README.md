# Library-Management-App

This project is a Java-based Library Management System, designed to help libraries manage their inventory, track item rentals, and manage user accounts. The system is built using object-oriented principles and incorporates multiple design patterns to ensure modularity, scalability, and ease of maintenance.

**Features**

**User Management:**
-  Register and authenticate users.
-  Manage different user roles (e.g., Admin, Librarian, Member).
-  Allow users to update their personal information.
-  View and manage user activity logs.

**Inventory Management:**
-  Add, remove, and update library items, including books, journals, and media.
-  Categorize items by type, genre, and availability status.
-  Maintain item details, such as title, author, publisher, and ISBN.

**Rental System:**
-  Manage item rentals, including checkouts and returns.
-  Track overdue items and calculate late fees.
-  Send reminders and notifications for due dates and overdue items.

**Search and Filter:**
-  Search for items by title, author, category, or keyword.
-  Apply filters to narrow down search results based on item type, availability, or other criteria.
-  Sort search results by relevance, title, or publication date.

**Reservation System:**
-  Allow members to reserve items that are currently unavailable.
-  Notify users when reserved items become available.
-  Manage reservation queues for high-demand items.

**GUI Interface:**
-  Intuitive and user-friendly graphical interface for easy navigation and operation.
-  Support for multiple views (e.g., list view, detailed view) and responsive design.
-  Interactive elements such as buttons, dropdowns, and modals for user interaction.

**Data Persistence:**
-  Uses CSV files to simulate a database, ensuring data is saved between sessions.
-  Support for data backup and recovery to prevent data loss.

**Reporting and Analytics:**
- Generate reports on library usage, such as most borrowed items, popular genres, and active users.
- View detailed analytics on rental trends, overdue items, and user activity.
- Export reports in various formats (e.g., CSV, PDF) for further analysis.

**Design Patterns Used**

-  Singleton: Ensures only one instance of the main library system is created and used throughout the application.
-  Observer: Implements event-driven updates between user actions and system responses.
-  Factory: Simplifies the creation of different types of library items and user roles.
-  Decorator: Adds functionality to existing objects dynamically, such as enhanced search capabilities.
-  Strategy: Allows for different search algorithms to be easily swapped and used.
-  MVC (Model-View-Controller): Separates the application logic, user interface, and control flow for modular development.

**Getting Started**
**Prerequisites**
-  Java Development Kit (JDK) 8 or higher
-  Java IDE: IntelliJ IDEA, Eclipse, or similar for running and modifying the code.

**Installation**
Clone the Repository:
``` git clone https://github.com/Kannapiran-SiddarthKanna/library-management-system.git ```

Navigate to the Project Directory:
``` cd library-management-system ```

Compile the Project:
-  Use your IDE to open the project and build it, or
-  Use the command line to compile the Java files:
``` javac -d bin src/*.java ```

**Running the Application**

1. **Run the Main Application:**
``` java -cp bin Main ```
Replace Main with the actual main class name in your project.

2. **Explore Features:** Use the graphical interface to explore the features of the library management system.

**Testing**
JUnit Tests: Automated tests are included to ensure the functionality of core components. Run these tests using your IDE’s testing framework or via the command line.

**Video Walkthrough**
Watch the [video walkthrough](https://youtu.be/KPgj2q0m95E) of the Library Management System to see it in action!!
