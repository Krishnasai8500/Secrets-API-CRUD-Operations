# 🔐 Secrets API Interaction Project

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat)](https://expressjs.com/)

A robust Express.js application demonstrating secure API interactions with the Secrets API. This project showcases best practices for handling CRUD operations with bearer token authentication.

## ✨ Features

### API Operations
- 📥 **GET Secret**: Retrieve secrets by ID
- 📤 **POST Secret**: Create new secrets
- 🔄 **PUT Secret**: Full secret updates
- 📝 **PATCH Secret**: Partial secret modifications
- 🗑️ **DELETE Secret**: Remove secrets by ID

### Technical Highlights
- Bearer token authentication
- RESTful API integration
- Dynamic response handling
- Error management
- Real-time UI updates

## 🚀 Getting Started

### Prerequisites
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
```bash
# Create .env file
echo "BEARER_TOKEN=your-bearer-token" > .env
```

4. Launch the application
```bash
npm start
```

## 💻 Usage

1. Access the application at `http://localhost:3000`
2. Use the interactive interface to:
   - Submit new secrets
   - Retrieve existing secrets
   - Update secret content
   - Remove secrets
3. View real-time API responses in the UI

## 🛠️ Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **HTTP Client**: Axios
- **View Engine**: EJS
- **Parser**: body-parser

## 📡 API Reference

Base URL: `https://secrets-api.appbrewery.com`

### Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /secrets/:id | Retrieve a secret |
| POST   | /secrets | Create a secret |
| PUT    | /secrets/:id | Update entire secret |
| PATCH  | /secrets/:id | Partial update |
| DELETE | /secrets/:id | Remove a secret |

## 📦 Project Structure

```
secrets-api-project/
├── app.js
├── public/
│   ├── css/
│   └── js/
├── views/
│   └── index.ejs
├── routes/
│   └── secrets.js
├── package.json
└── .env
```

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Secrets API](https://secrets-api.appbrewery.com) for providing the API service
- The Express.js community for excellent documentation
- All contributors who help improve this project

---

<div align="center">
Made with ❤️ by Krishna Sai
</div>
