🌾 Farmart Frontend

Farmart is a web-based platform that connects farmers directly with buyers to sell animals. This is the frontend of the Farmart application, built with React, Redux Toolkit, React Router, and plain CSS. It interfaces with the Farmart Flask backend to offer a seamless experience for farmers managing their profiles, animals, and feedback.
🚀 Features

    🔐 Farmer Authentication (Login/Register)

    👤 Farmer Profile Management (View, Edit, Upload Profile Picture)

    🐄 Animal Listings (View, Add, Edit, Delete Animals)

    🖼️ Image Slideshows for Multiple Animal Images

    💬 User Feedback View

    🔎 Search & Filter Animal Listings

    🧭 Sidebar Navigation for Farmers

    💻 Fully responsive design with plain CSS

🏗️ Tech Stack

    Frontend Framework: React (Vite)

    State Management: Redux Toolkit

    Routing: React Router DOM

    Styling: CSS

    API Communication: Fetch API

    Authentication: JWT (Token-based, integrated with backend)

📁 Project Structure

farmart-frontend/
│
├── public/
│   └── index.html
│
├── src/
│   ├── assets/               # Images and static assets
│   ├── components/           # Reusable UI components
│   ├── pages/                # Route-level pages
│   ├── Routes/               # React Router route config
│   ├── Stylesheets/          # CSS files
│   ├── App.jsx               # Main app structure
│   └── main.jsx              # Entry point
│
├── .env                     # Environment variables (e.g. API URL)
├── package.json
└── vite.config.js

⚙️ Setup Instructions

    Clone the repository

git clone https://github.com/yourusername/farmart-frontend.git
cd farmart-frontend

Install dependencies

npm install

Configure environment variables

Create a .env file in the root directory and add:

VITE_API_BASE_URL=https://your-backend-api-url.com

Run the app

    npm run dev

🔗 Backend API

Make sure the Farmart Flask Backend is up and running. The frontend communicates with it for authentication, data fetching, and CRUD operations.
📌 Future Enhancements

    Payment integration (M-Pesa, card)

    Real-time chat system

    Notifications for feedback/sales

    Mobile app version

🤝 Contributors

    Gedion Kipkoech

    Shuaib Muhamed

    Kariuki Kihikah

    Enoch Chisiwa

📝 License

This project is licensed under the MIT License.
