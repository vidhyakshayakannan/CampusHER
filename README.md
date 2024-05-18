### CampusHER

## Introduction
CampusHER is a mobile application designed to provide university women with access to health resources, appointment scheduling, health tips, and more. The backend is developed using Python with Flask (or Django), and the frontend is built using React Native.

## Features
- User Registration and Authentication
- Personal Health Dashboard
- Appointment Scheduling with Campus Health Services
- Health Tips and Articles
- Chat/Consultation with Health Experts
- Symptom Checker
- Notification System for Reminders

## Tech Stack
**Backend:**
- Python
- Flask or Django
- SQLAlchemy (for ORM)

**Frontend:**
- React Native

**Database:**
- PostgreSQL or MySQL
- MongoDB (optional)

## Setup Instructions

### Backend Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/healthapp.git
    cd healthapp/backend
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```python
    from app import db
    db.create_all()
    ```

5. Run the backend server:
    ```sh
    flask run
    ```

### Frontend Setup

1. Navigate to the frontend directory:
    ```sh
    cd ../frontend
    ```

2. Install the required packages:
    ```sh
    npm install
    ```

3. Start the React Native app:
    ```sh
    npx react-native run-android  # for Android
    npx react-native run-ios      # for iOS
    ```

## Project Structure
```plaintext
healthapp/
|-- backend/
|   |-- app.py
|   |-- models.py
|   |-- routes/
|   |   |-- auth.py
|   |   |-- health.py
|   |-- templates/
|   |-- requirements.txt
|-- frontend/
|   |-- src/
|   |   |-- App.js
|   |   |-- components/
|   |   |-- screens/
|   |-- package.json
```

## API Endpoints
- `POST /register`: Register a new user
- `POST /login`: Login a user
- `GET /appointments`: Get a list of appointments
- `POST /appointments`: Schedule a new appointment
- `GET /health-tips`: Get health tips and articles
- `POST /chat`: Start a chat with a health expert

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries or further information, please contact:
- **Gayanthika Shankar**, Developer  
  <a href="mailto:gayanthika.s-26@scds.saiuniversity.edu.in"><img src="https://img.icons8.com/ios-glyphs/30/000000/email.png"/> gayanthika.s-26@scds.saiuniversity.edu.in</a>
  
- **Shravanthi Balasubramaniam**, Developer  
  <a href="mailto:shravanthi.b-26@scds.saiuniversity.edu.in"><img src="https://img.icons8.com/ios-glyphs/30/000000/email.png"/> shravanthi.b-26@scds.saiuniversity.edu.in</a>

- **Vidhyakshaya Kannan**, Developer  
  <a href="mailto:vidhyakshaya.k-26@scds.saiuniversity.edu.in"><img src="https://img.icons8.com/ios-glyphs/30/000000/email.png"/> vidhyakshaya.k-26@scds.saiuniversity.edu.in</a>

