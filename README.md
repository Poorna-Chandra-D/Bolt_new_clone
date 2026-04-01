# Bolt.new Clone

An AI-powered web development tool that brings full-stack application development directly to your browser. This project is a clone implementation of [Bolt.new](https://bolt.new), created for educational purposes.

![UI](UI.png)

## 🚀 Overview


Bolt.new Clone enables developers to build, test, and deploy full-stack web applications entirely within the browser, combining cutting-edge technologies to streamline the development workflow without requiring extensive local setups.

## ✨ Key Features

- **🧠 AI-Powered Development** - Intelligent code suggestions and automated development assistance using Anthropic's Claude AI
- **🖥️ In-Browser IDE** - Complete development environment with Monaco Editor for seamless code editing
- **⚡ WebContainers** - Run Node.js environments natively in the browser
- **🎯 Full-Stack Support** - Build both frontend and backend applications
- **📦 Zero Setup** - No local installation required, everything runs in the browser

## 🏗️ Architecture

The project consists of two main components:

### Backend (`/be`)
- **Express.js** server for API endpoints
- **Anthropic AI SDK** integration for AI-powered features
- **TypeScript** for type-safe development
- CORS-enabled for cross-origin requests

### Frontend (`/frontend`)
- **React** with **TypeScript** for UI development
- **Vite** for fast development and building
- **Monaco Editor** for in-browser code editing
- **WebContainer API** for browser-based Node.js runtime
- **TailwindCSS** for styling
- **Axios** for API communication

![Internal File System](Internal%20file%20syatem.png)

## 🛠️ Tech Stack

### Frontend
- React 18
- TypeScript
- Vite
- Monaco Editor
- WebContainer API
- TailwindCSS
- Lucide React (icons)
- React Router

### Backend
- Node.js
- Express
- TypeScript
- Anthropic AI SDK
- CORS
- dotenv

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Anthropic API key

## 🚦 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Poorna-Chandra-D/Bolt_new_clone.git
cd Bolt_new_clone
```

### 2. Setup Backend

```bash
cd be
npm install

# Create .env file and add your Anthropic API key
echo "ANTHROPIC_API_KEY=your_api_key_here" > .env

# Start the backend server
npm run dev
```

### 3. Setup Frontend

```bash
cd frontend
npm install

# Start the development server
npm run dev
```

### 4. Access the Application

Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

## 📁 Project Structure

```
Bolt_new_clone/
├── be/                      # Backend server
│   ├── src/                 # Source files
│   ├── dist/                # Compiled files
│   └── package.json
├── frontend/                # Frontend application
│   ├── src/                 # React components and logic
│   ├── public/              # Static assets
│   └── package.json
├── UI.png                   # UI screenshot
├── Internal file syatem.png # Architecture diagram
└── README.md
```

## 🔧 Available Scripts

### Backend
- `npm run dev` - Build and run the development server

### Frontend
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌟 How It Works

1. **User Input**: Enter prompts or code requirements through the UI
2. **AI Processing**: Backend processes requests using Anthropic's Claude AI
3. **Code Generation**: AI generates appropriate code solutions
4. **WebContainer Execution**: Code runs in browser-based Node.js environment
5. **Live Preview**: See results instantly without leaving the browser

## ⚠️ Important Notes

- This is an educational clone created to understand the technologies behind Bolt.new
- All credits for the original concept go to the [Bolt.new](https://bolt.new) team
- Requires valid Anthropic API key for AI features
- WebContainers may have limitations compared to local development environments

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

ISC

## 👨‍💻 Author

**Poorna Chandra Dinesh**

---

> **Note**: AI is here to assist humans, not to replace our jobs. Make sure to learn and use it to enhance your daily tasks and productivity.

## 🙏 Acknowledgments

- [Bolt.new](https://bolt.new) - Original concept and inspiration
- [StackBlitz](https://stackblitz.com/) - WebContainer technology
- [Anthropic](https://www.anthropic.com/) - Claude AI
