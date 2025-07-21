# 🔗 URL Shortener

A simple and efficient **URL Shortener** built with the **MERN stack** (MongoDB, Express, React, Node.js), featuring Tailwind CSS for styling. This application allows users to convert long URLs into short, shareable links and track them in a clean, user-friendly interface.

## 🚀 Features

- 🌐 Shorten any valid URL
- 📋 One-click copy for shortened links
- 🧠 Generates unique short codes
- ✅ URL validation before shortening
- 📊 Displays a list of previously shortened URLs
- 💅 Clean and modern UI built with Tailwind CSS

## 📁 Project Structure

```bash
URL-SHORTENER/
├── client/                 # React frontend
│   ├── public/
│   ├── src/
│   ├── tailwind.config.js
│   ├── package.json
│   └── ...
├── server/                 # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   ├── .env
│   └── ...
⚙️ Tech Stack
Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB (via Mongoose)

Others: dotenv, CORS

🔧 Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/URL-Shortener.git
cd URL-Shortener
2. Set Up the Server
bash
Copy
Edit
cd server
npm install
Create a .env file in the server directory:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000
PORT=5000
Start the server:

bash
Copy
Edit
npm start
3. Set Up the Client
bash
Copy
Edit
cd client
npm install
npm start
Visit the frontend at: http://localhost:3000

🧠 How It Works
Enter a long URL in the input field.

Click on "Shorten it!" to generate a short version.

The app sends a POST request to the backend, where:

The URL is validated.

A short code is generated (if not already present).

Data is stored in MongoDB.

A shortened URL is returned and displayed along with a Copy button.

The user can copy and use the short URL anywhere.

👨‍💻 Contributors
Frontend (React + Tailwind): Abdul Haseeb Alam

Backend (Express + MongoDB): Zeeshan Ibrar

🤝 Contributing
Fork the repo

Create your feature branch: git checkout -b feature/your-feature

Commit your changes: git commit -m 'Add some feature'

Push to the branch: git push origin feature/your-feature

Open a pull request

📄 License
This project is open source and available under the MIT License.

yaml
Copy
Edit

---

Let me know if you'd like to:
- Add live deployment links (e.g., Vercel/Render)
- Include instructions for Docker
- Write a shorter version for a portfolio or Devpost
