# RentZone6,1
🏠 RentZone – Rental Platform for Properties and Services 🚀
🌟 Overview
RentZone is a full-stack web platform designed to streamline the renting process of various assets such as hotels, villas, islands, beach wedding halls, and more. It provides a seamless user experience for both asset owners and renters, offering features like real-time availability, interactive maps, secure authentication, and detailed listing management.

🌐 Live Links
🔗 Live Website: RentZone Live Website
📦 GitHub Repository: RentZone Repo

🎯 Key Features
👤 User Functionality:
Register and log in securely

Browse rental assets by category, location, or availability

View detailed property pages with descriptions, amenities, pricing, and reviews

Book assets with live availability updates

Submit and view reviews

🏘️ Owner/Host Functionality:
Add new listings with images (via Cloudinary integration)

Edit or delete existing rental items

Manage bookings and customer inquiries

📍 Map Integration:
Interactive maps powered by Mapbox to show property locations

🔒 Authentication:
Secure login and registration with password hashing (bcrypt)

Session and JWT-based authentication

Google OAuth integration (if implemented)

🛠️ Tech Stack
Frontend

React.js

Bootstrap

JavaScript

Backend

Node.js

Express.js

Database

MongoDB (hosted on MongoDB Atlas)

Cloud Services

Cloudinary for image uploads

Mapbox for interactive map display

Deployment

Render for hosting backend

Netlify / Vercel (optional) for frontend

⚙️ Installation and Setup
bash
Copy
Edit
# Clone the repository
git clone https://github.com/yourusername/rentzone.git
cd rentzone

# Install dependencies for both frontend and backend
npm install

# Set up environment variables
Create a `.env` file in the root directory and add:
MONGO_URI=your_mongodb_connection_string  
CLOUDINARY_CLOUD_NAME=your_cloud_name  
CLOUDINARY_API_KEY=your_api_key  
CLOUDINARY_API_SECRET=your_api_secret  
JWT_SECRET=your_jwt_secret  
bash
Copy
Edit
# Run the server
npm start

# Access the app
Visit http://localhost:3000
📸 Screenshots
Feature	Description
Homepage	Browse all listings with filters
Map Integration	View properties on a map
Booking Page	Rent properties with calendar selection
Admin Panel	Add, update, or remove listings

💻 Contribution
Contributions are welcome! Follow these steps:

bash
Copy
Edit
# Fork the repository
git clone https://github.com/yourusername/rentzone.git

# Create a new branch
git checkout -b feature-name

# Make your changes and commit
git commit -m "Add feature-name"

# Push to GitHub
git push origin feature-name
Then, create a pull request.

📧 Contact
For queries or suggestions, feel free to reach out:

Developer: Siddheshwar Magar
📧 Email: siddheshwarmagar4141@gmail.com
📞 Phone: 7397911356