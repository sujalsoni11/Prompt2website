# AI Website Builder

AI Website Builder is a full-stack web application that transforms natural language prompts into responsive website layouts using Generative AI. Users can describe their desired website in plain English, and the platform generates website code, provides a live preview, and allows iterative modifications through follow-up prompts.

## 🚀 Features

* Generate websites from natural language prompts
* AI-powered code generation
* User authentication and authorization
* Save and manage multiple projects
* Responsive website layouts
* Real-time preview of generated websites
* Secure API integration
* Modern and intuitive user interface

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* React Router

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT (JSON Web Tokens)

### AI Integration

* Google Gemini API

### Deployment

* Vercel (Frontend)
* Render / Railway / Other Cloud Platforms (Backend)

---

## 📂 Project Structure

```bash
project-root/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json
```

## ⚙️ Environment Variables

Create a `.env` file in the backend directory and add:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key

CLIENT_URL=http://localhost:5173
```

## 🏃 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/ai-website-builder.git
cd ai-website-builder
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../server
npm install
```

### Start Backend

```bash
npm run dev
```

### Start Frontend

```bash
cd ../client
npm run dev
```

The application will be available at:

```text
Frontend: http://localhost:5173
Backend: http://localhost:5000
```

## 🔒 Security

* JWT-based authentication
* Protected API routes
* Environment variable protection
* Secure credential handling

## 📈 Future Improvements

* Drag-and-drop website editing
* Multi-page website generation
* Code export functionality
* Template marketplace
* Team collaboration features
* Deployment directly from the platform

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Sujal Soni**

B.Tech Computer Science Engineering
Madhav Institute of Technology and Science (MITS), Gwalior

GitHub: https://github.com/sujalsoni11
