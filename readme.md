✈️ Shubhyatra - Your Ultimate Travel Companion
Shubhyatra (शुभयात्रा - Safe Journey) is a comprehensive, full-stack travel planning and booking application built to provide users with a seamless platform for exploring, planning, and booking all travel-related services in one place.

✨ Key Features
Multi-Service Booking: Find and book Hotels, Trains , Buses , and Car Rentals  through a centralized interface.

Tourist Spot Discovery: Explore and find beautiful tourist places  in various cities to help plan your itinerary.

Data Aggregation: Utilizes advanced web scraping techniques to aggregate real-time travel data, which is then preprocessed and served through a fast, robust API.

Robust Backend: Built on the high-performance FastAPI framework, ensuring rapid response times and scalable service.

Secure Authentication: Features secure, database-based user authentication and session management using JWTs.

💻 Tech Stack
Component

Technology

Description

Backend API

Python, FastAPI

High-performance, asynchronous web framework.

Server

Uvicorn

ASGI Server for running the FastAPI application.

Database

SQL / TBD

Used for secure user authentication and persistent data storage.

Scraping

Requests, Beautiful Soup

For fetching and parsing live travel data.

Frontend

HTML, CSS, JavaScript

Responsive and user-friendly web interface (as seen in ).

Security

passlib (Bcrypt), PyJWT

Password hashing and JSON Web Token management.

🚀 Getting Started
Follow these steps to set up and run the Shubhyatra project locally.

Prerequisites
You need Python 3.8+ installed on your system.

Clone the Repository

git clone [https://github.com/YourUsername/Shubhyatra.git](https://github.com/YourUsername/Shubhyatra.git)
cd Shubhyatra


Create and Activate Virtual Environment

# Create the environment
python -m venv venv

# Activate the environment (Windows)
.\venv\Scripts\activate

# Activate the environment (macOS/Linux)
source venv/bin/activate


Install Dependencies

Install the necessary libraries listed in the requirements.txt file (which is also available in the Canvas):

pip install -r requirements.txt


Running the Application
Set Environment Variables

Create a file named .env in the root directory to store sensitive configuration (database credentials, JWT secret key, etc.).

# Example .env content:
SECRET_KEY="YOUR_SUPER_SECRET_KEY_HERE"
DATABASE_URL="sqlite:///./shubhyatra.db"


Run Database Migrations (if using a migration tool)

(Add specific commands here based on your database setup.)

# Execute migration commands here, if applicable


Start the Backend Server

Run the FastAPI application using Uvicorn. Assuming your main file is main.py and the app instance is named app:

uvicorn main:app --host 0.0.0.0 --port 8000 --reload


The server will be available at http://127.0.0.1:8000.

Access the Frontend

Open the main HTML file (index.html or similar) in your browser, or configure the frontend to communicate with the running API server.

🖼️ Screenshots
Description

Screenshot

Homepage/Popular Destinations

assets\Screenshot 2025-10-07 115721.png
Hotel Search Results

assets\Screenshot 2025-10-07 115747.png
Train Search Results

assets\Screenshot 2025-10-07 115829.png
Bus Search Results

🤝 Contribution
We welcome contributions! Please feel free to submit issues or pull requests to help improve Shubhyatra.

Fork the repository.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📧 Contact
Project Link: https://github.com/YourUsername/Shubhyatra
