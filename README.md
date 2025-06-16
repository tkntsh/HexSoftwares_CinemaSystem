# HexSoftwares Cinema System

A simple Java-based Cinema System application that connects to a Microsoft Access database and handles movie, ticket, and user data management. This system uses object-oriented principles and includes core classes for interacting with the database and managing cinema-related entities.

## 📁 Project Structure

- `DBManager.java`: Handles the database connection and executes SQL queries (select and update).
- `Movie.java`: Represents the movie entity with attributes like ID, name, release date, capacity, price, and age restriction.
- `Ticket.java`: Represents a cinema ticket with attributes like ticket ID, movie ID, user ID, and seat number.
- `User.java`: Represents the user (customer or manager) with personal and login-related information.

## 💡 Features

- **Database Connectivity**  
  Connects to an MS Access database using the UCanAccess JDBC driver.

- **Movie Management**  
  - Create, update, and manage movie records.
  - Attributes: Movie ID, Name, Release Date, Age Restriction, Capacity, Price.

- **Ticket Management**  
  - Handles ticket creation and retrieval.
  - Attributes: Ticket ID, Movie ID, User ID, Seat Number.

- **User Management**  
  - Supports both regular users and managers.
  - Stores user credentials and personal details.

## 🛠️ Technologies Used

- Java
- JDBC (UCanAccess Driver for MS Access)
- Microsoft Access Database (`CinemaSystem.accdb`)

## 🔧 Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/tkntsh/HexSoftwares_CinemaSystem.git
   cd HexSoftwares_CinemaSystem
