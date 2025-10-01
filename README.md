# Global Interns: F1 Internship Finder

Global Interns is a web application designed to help F1 students in the U.S. find internships that sponsor international students. The platform streamlines the search and application process by combining an interactive frontend with a dynamic backend, making it easier for students to explore opportunities tailored to their visa requirements.

https://github.com/user-attachments/assets/92e51a15-9393-46ee-be7e-c8435933d61a

## Key Features:
- **Smart Internship Search**: Users can filter internships by role, company, or location.
- **Direct Application**: Apply directly through the platform without navigating multiple websites.
- **Responsive Interface**: Fully functional across desktop and mobile devices.
- **Live Data Integration**: Fetches internship listings in real-time from a MySQL database using Express.js APIs.
- **Smooth Navigation**: Implemented client-side routing with React Router for seamless user experience.
- **Reusable Components**: Card-based layout for internships allows easy expansion and updates.

## Project Structure

### Frontend
The frontend is located in the `Frontend/` directory. The frontend is built with React and Vite and is organized to separate pages, components, and static data.

Key files:
- `src/pages/Home.jsx`: Landing page displaying internship listings.
- `src/pages/cards.jsx`: Component to render each internship in a card format.
- `src/pages/data.jsx`: Sample dataset used for testing UI before backend integration.
- `vite.config.js`: Vite configuration for project build and development.

### Backend
The backend is powered by Node.js and Express.js, connecting to a MySQL database to store and serve internship data.

Main files/folders:
- `server.js`: Sets up API routes and connects to the MySQL database.
- `.env`: Stores database credentials securely using environment variables.
- 
## Installation

### Prerequisites
- Node.js (v16 or later)
- MySQL database

### Setup

1. Clone the repository:
   git clone https://github.com/Sanjina-Kumari/Global-Interns.git
   cd Global-Interns

2. Install backend dependencies:
    - cd ../Backend
    - npm install

3. Install frontend dependencies:
    - cd Frontend
    - npm install

4. Configure database: Create a .env file in the Backend/ directory with:
    >
    HOST=<your-database-host     
    USER=<your-database-username>
    PASSWORD=<your-database-password>
    DATABASE=<your-database-name>

5. Start the MySQL database and ensure it contains a table named internships - opt_cpt     internships with the required data.

## Running the Application

1. Start the Backend:
    - cd Backend
    - node server.js

2. Start the Frontend:
   - cd Frontend
   - npm run dev

Once both servers are running, navigate to http://localhost:5173 (or the port Vite specifies) to explore the application.


## Technologies Used
- **Frontend**: React, Vite, React Router, JavaScript, HTML, CSS

- **Backend**: Node.js, Express.js, MySQL, dotenv

- **Other Tools**: Visual Studio Code, Postman (for API testing), Git/GitHub

## Author & Developer
 Sanjina Kumari 
  
For questions or feedback, feel free to reach out at sanjinamandhwani1@gmail.com!

## 📜 Acknowledgements
This project was created with a group of three students at Pacific Lutheran University.
