# Book Management System

This project is a simple book management system built using Flask and SQLAlchemy. It demonstrates how to perform basic CRUD operations with a database using SQLAlchemy and Flask.

## Features

- **Add Book**: Users can add new books to the database.
- **Edit Rating**: Users can update the rating of an existing book.
- **Delete Book**: Users can delete a book from the collection.
- **View Books**: Display a list of all books with their details.

## Technologies Used

- **Flask**: A lightweight web framework for Python.
- **SQLAlchemy**: An SQL toolkit and ORM library for Python.
- **SQLite**: A lightweight database that stores data in a local file.

## Setup and Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/book-management-system.git
    cd book-management-system
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:

    ```bash
    flask run
    ```

5. **Access the application**:

    Open your web browser and go to `http://127.0.0.1:5000` to access the book management system.

## Application Structure

- `app.py`: The main application file that contains routes and application logic.
- `templates/`: Directory containing HTML templates.
- `static/`: Directory containing static files like CSS and images.
- `requirements.txt`: List of dependencies for the project.

## Contributing

Feel free to fork the repository and submit pull requests. If you find any issues or have suggestions, please open an issue on GitHub.



