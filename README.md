# ShelfLife: A Simple Library Management System

**Streamlining book tracking and lending for small libraries**

ShelfLife is a comprehensive Python-based web application designed to empower small libraries and personal book collections with efficient management tools. It offers a user-friendly interface for librarians and users to seamlessly handle book registrations, user accounts, loan transactions, and generate insightful reports.

## Features

* **Book Management:**
    * Add, edit, and delete books with detailed information (title, author, ISBN, publication year, genre, available copies).
    * Bulk import and export book data using CSV files.
    * Track book availability and manage multiple copies.

* **User Management:**
    * Register new users and assign roles (librarian/user) with granular permissions.
    * Manage user accounts and update user information.
    * Enforce strong password policies and email uniqueness.

* **Loan Management:**
    * Record book loans and returns, automatically updating book availability.
    * Track due dates and generate overdue notifications via email.
    * Calculate and manage late fees (optional).
    * Allow users to renew loans (subject to library policies).

* **Advanced Search:**
    * Search for books using various criteria (title, author, ISBN, genre, publication year).
    * Filter and sort search results for precise book discovery.

* **Reports:**
    * Generate reports on book popularity, overdue books, and user activity.
    * Export reports in CSV or PDF format for further analysis.

* **User Dashboard:**
    * View current loans, due dates, and any outstanding fines.
    * Renew loans and manage personal information.

## Technologies Used

* **Backend:** Python, Flask, SQLite
* **Frontend:** HTML, CSS, JavaScript
* **Email:** SMTP server for sending notifications

## Installation

1. Clone the repository: `git clone https://github.com/YousssefJamal/ShelfLife.git`
2. Navigate to the project directory: `cd ShelfLife`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
    * Windows: `venv\Scripts\activate`
    * macOS/Linux: `source venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Set up the database: `flask db init`, `flask db migrate`, and `flask db upgrade`
7. Configure email settings in `config.py`
8. Run the application: `flask run`

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.

## License

This project is licensed under the MIT License.

## Author

* Youssef Ahmed - Full-Stack Engineer

## Acknowledgments

* Thanks to the open-source community for providing valuable tools and resources.
* Special thanks to Flask, SQLite, and the countless tutorials and guides that helped shape this project.

