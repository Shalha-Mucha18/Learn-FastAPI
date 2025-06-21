# 🚀 Blog Application using FastAPI

A production-ready blog API featuring user authentication, role-based access control, and CRUD operations for blog posts.

## 🔧 Built With

- **FastAPI** - Python web framework for building APIs
- **SQLAlchemy** - ORM for database operations
- **SQLite** - Lightweight database (can be easily switched to PostgreSQL/MySQL)
- **JWT** - Secure token-based authentication
- **BCrypt** - Password hashing for security

## ✨ Features

### Authentication & Authorization
- JWT token-based authentication
- Password hashing with BCrypt
- Protected routes with dependency injection
- Token expiration 

### Blog Management
- Full CRUD operations for blog posts
- User-blog relationship (each post tied to an author)
- Data validation with Pydantic models
- Comprehensive error handling

### API Features
- Auto-generated interactive documentation
- Clean RESTful endpoint design
- SQLite for development (easy production DB switch)
- Well-structured project architecture

## Installation

1. Clone the repository:
   ```bash
   git clone <https://github.com/Shalha-Mucha18/Learn-FastAPI>
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
3. Running the Application
   ```bash
   uvicorn main:app --reload
 
