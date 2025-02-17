Front-End
Sign-In & Sign-Up Pages
Users can register and log in securely.
Token-based authentication ensures only registered users can access the website.
Password hashing using Passport.js for secure storage.
Profile Page
Displays all relevant information about the signed-in user.
City Selection
Users can choose their starting city and destination city from a list of available cities.
Flight Listings
Displays a list of flights from different airlines with various details such as departure time, arrival time, price, etc.
Seat Selection
User-friendly seat selection interface.
Dynamic forms are generated for storing passenger data based on the number of seats selected.
Confirmation Page
Collects debit card information using react-credit-cards .
Note: This version does not handle the actual payment process.
Boarding Pass
Displays all passenger data and generates a random transaction ID as part of the boarding pass.
Ticket Cancellation
Allows users to cancel their booked tickets.
AI Chatbot
Integrated AI chatbot for user assistance.
Back-End
Express.js Application
Handles backend processes including user authentication, flight data management, and ticket booking.
MongoDB Atlas
Cloud-based database service for storing user data, flight details, and booking information.
Passport.js
Middleware for user authentication and token-based system.
Passwords are hashed before being stored in the cloud.
Dynamic Seat Data
Note: This version does not support dynamic seat data being stored in the cloud.
Technologies Used
Visual Studio Code : A source code editor developed by Microsoft for Windows, Linux, and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring.
Node.js : JavaScript runtime built on Chrome's V8 JavaScript engine.
React.js : A JavaScript library for building user interfaces.
Axios : Promise-based HTTP client for the browser and Node.js.
Express.js : Minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
MongoDB Atlas : Global cloud database service for modern applications.
Passport.js : Authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped into any Express-based web application.
React-Credit-Cards : A React component for displaying credit card information.
