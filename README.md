# 🤖 NeuralMate

[![MIT License](https://img.shields.io/github/license/H0NEYP0T-466/NeuralMate?style=flat&color=blue)](https://github.com/H0NEYP0T-466/NeuralMate/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/H0NEYP0T-466/NeuralMate?style=flat&color=yellow)](https://github.com/H0NEYP0T-466/NeuralMate/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/H0NEYP0T-466/NeuralMate?style=flat&color=green)](https://github.com/H0NEYP0T-466/NeuralMate/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/H0NEYP0T-466/NeuralMate?style=flat&color=red)](https://github.com/H0NEYP0T-466/NeuralMate/issues)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/H0NEYP0T-466/NeuralMate/blob/main/CONTRIBUTING.md)

> 🌟 An intelligent AI-powered personal assistant that combines seamless voice recognition, context-aware memory, and conversational charm to enhance productivity and simplify daily tasks.

## 📑 Table of Contents

- [🚀 Installation](#-installation)
- [💻 Usage](#-usage)
- [✨ Features](#-features)
- [📂 Folder Structure](#-folder-structure)
- [🛠️ Tech Stack](#️-tech-stack)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [🗺️ Roadmap](#️-roadmap)
- [🙏 Acknowledgements](#-acknowledgements)

## 🚀 Installation

### Prerequisites

Ensure you have the following installed on your system:

- **Node.js** (v16.0.0 or higher) - [Download here](https://nodejs.org/)
- **npm** (v7.0.0 or higher) - Comes with Node.js
- **MongoDB** - [Installation Guide](https://docs.mongodb.com/manual/installation/)
- **Git** - [Download here](https://git-scm.com/)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/H0NEYP0T-466/NeuralMate.git
   cd NeuralMate
   ```

2. **Install frontend dependencies**
   ```bash
   npm install
   ```

3. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   cd ..
   ```

4. **Set up environment variables**
   ```bash
   cd backend
   cp .env.example .env
   # Edit .env file with your configuration:
   # - MongoDB connection string
   # - Gemini API key
   # - Server port (default: 8000)
   ```

5. **Start the development servers**

   **Terminal 1 - Backend:**
   ```bash
   cd backend
   npm start
   ```

   **Terminal 2 - Frontend:**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   
   Navigate to `http://localhost:5173` to start using NeuralMate!

## 💻 Usage

### Basic Interaction

1. **Voice Commands**: Click the microphone button and speak naturally
   ```
   "Hello Isabella, how are you today?"
   "Can you help me organize my tasks?"
   "Review my latest project files"
   ```

2. **Text Input**: Type your messages in the chat interface
   ```
   Type: "What's the weather like?"
   Type: "Help me with my coding project"
   ```

3. **Project Analysis**: Upload files or share code snippets for AI-driven feedback
   ```
   Upload: project.zip
   Share: GitHub repository link
   ```

### Advanced Features

- **Context Awareness**: NeuralMate remembers your conversation history
- **Multi-language Support**: Communicate in your preferred language
- **Task Automation**: Set up recurring tasks and reminders
- **Voice Synthesis**: Listen to responses with natural speech

### Example Workflow

```bash
# Start a conversation
User: "Hey Isabella, I need help planning my day"
NeuralMate: "Good morning! I'd be happy to help you plan your day..."

# Get project feedback
User: "Can you review this React component?"
NeuralMate: "I'll analyze your code. Please share the component..."

# Set reminders
User: "Remind me to call mom at 6 PM"
NeuralMate: "I've set a reminder for 6 PM to call mom..."
```

## ✨ Features

- 🎙️ **Voice Recognition** - Natural speech input using Web Speech API
- 🧠 **Context-Aware Memory** - Remembers preferences and conversation history
- ⚡ **Real-Time Responses** - Lightning-fast AI-powered replies
- 🔄 **Task Automation** - Automate repetitive tasks and workflows
- 🛠️ **Code Review** - AI-driven project analysis and feedback
- 🌟 **Intuitive UI** - Clean, responsive design for all devices
- 🌍 **Multi-language** - Support for multiple languages
- 💾 **Persistent Storage** - MongoDB-backed conversation history
- 🔊 **Speech Synthesis** - Natural voice responses
- 📱 **Cross-Platform** - Works on desktop and mobile browsers

## 📂 Folder Structure

```
NeuralMate/
├── backend/                    # Backend server implementation
│   ├── config/                # Configuration and database setup
│   │   ├── DB.js              # MongoDB connection configuration
│   │   └── saveMessages.js    # Message persistence utilities
│   ├── controller/            # API route handlers and business logic
│   │   └── controller.js      # Main application controller
│   ├── gemini/                # AI model integration layer
│   │   └── ai.model.js        # Gemini API integration and prompts
│   ├── model/                 # Database schemas and models
│   │   └── user.model.js      # User and message data models
│   ├── .gitignore             # Backend-specific ignore patterns
│   ├── index.js               # Express server entry point
│   ├── package.json           # Backend dependencies and scripts
│   └── package-lock.json      # Backend dependency lock file
├── public/                    # Static assets and resources
│   ├── assets/               # SVG icons and graphics
│   │   └── react.svg         # React logo
│   ├── pic.jpg               # Application icon/avatar
│   └── vite.svg              # Vite logo
├── src/                       # Frontend React application
│   ├── App.css               # Main application styles
│   ├── App.jsx               # Root React component
│   ├── index.css             # Global CSS styles and variables
│   └── main.jsx              # React application entry point
├── .gitignore                 # Project-wide ignore patterns
├── README.md                  # Project documentation (this file)
├── eslint.config.js           # ESLint configuration and rules
├── index.html                 # HTML template and metadata
├── package.json               # Frontend dependencies and scripts
├── package-lock.json          # Frontend dependency lock file
└── vite.config.js             # Vite build tool configuration
```

## 🛠️ Tech Stack

### Frontend
- **React** (v19.1.1) - Modern UI library with hooks and context
- **Vite** (v7.1.0) - Lightning-fast build tool and dev server
- **React Markdown** - Rich text rendering for AI responses
- **Axios** - HTTP client for API communication
- **Web Speech API** - Browser-native voice recognition

### Backend
- **Node.js** - JavaScript runtime for server-side development
- **Express.js** (v5.1.0) - Minimal and flexible web application framework
- **MongoDB** - NoSQL database for scalable data storage
- **Mongoose** (v8.17.1) - MongoDB object modeling for Node.js

### AI & External Services
- **Google Gemini API** - Advanced language model for intelligent responses
- **Web Speech API** - Cross-platform speech recognition
- **MyMemory Translation API** - Multi-language support

### Development Tools
- **ESLint** - Code linting and quality enforcement
- **Git** - Version control and collaboration
- **npm** - Package management and script execution

## 🤝 Contributing

We welcome contributions from developers of all skill levels! Here's how you can help make NeuralMate even better:

### Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally
   ```bash
   git clone https://github.com/your-username/NeuralMate.git
   ```
3. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-new-feature
   ```
4. **Make your changes** and commit them
   ```bash
   git commit -m "Add amazing new feature"
   ```
5. **Push to your fork**
   ```bash
   git push origin feature/amazing-new-feature
   ```
6. **Open a Pull Request** with a clear description

### Contribution Guidelines

- 🐛 **Bug Reports**: Use the issue template and provide detailed reproduction steps
- ✨ **Feature Requests**: Clearly describe the problem and proposed solution
- 📝 **Documentation**: Help improve our docs and code comments
- 🧪 **Testing**: Add tests for new features and bug fixes
- 🎨 **UI/UX**: Enhance the user interface and experience

### Code Style

- Follow the existing ESLint configuration
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions small and focused

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 NeuralMate Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🗺️ Roadmap

### Version 2.0 (Q2 2024)
- [ ] 📅 **Calendar Integration** - Google Calendar and Outlook sync
- [ ] 🌍 **Enhanced Multi-language** - Support for 20+ languages
- [ ] 📱 **Mobile App** - React Native companion app

### Version 2.1 (Q3 2024)
- [ ] ⏰ **Smart Reminders** - Context-aware notification system
- [ ] 🐞 **Code Debugging** - Automated bug detection and fixes
- [ ] 🎨 **Theme Customization** - Dark mode and custom themes

### Version 3.0 (Q4 2024)
- [ ] 📴 **Offline Mode** - Local AI processing capabilities
- [ ] 🔌 **Plugin System** - Third-party integrations and extensions
- [ ] 🤖 **Advanced AI** - Multi-modal AI with image and document analysis

### Long-term Vision
- [ ] 🏠 **Smart Home Integration** - IoT device control
- [ ] 🧠 **Predictive Analytics** - Proactive task suggestions
- [ ] 🌐 **Enterprise Edition** - Team collaboration features

## 🙏 Acknowledgements

We're grateful to the amazing open-source community and the following projects that make NeuralMate possible:

- 🚀 **[React Team](https://react.dev/)** - For the incredible UI library
- ⚡ **[Vite](https://vitejs.dev/)** - For the blazing-fast build tool
- 🤖 **[Google AI](https://ai.google/)** - For the powerful Gemini API
- 💚 **[MongoDB](https://www.mongodb.com/)** - For the flexible database solution
- 🔧 **[Express.js](https://expressjs.com/)** - For the robust web framework
- 📝 **[React Markdown](https://github.com/remarkjs/react-markdown)** - For beautiful text rendering
- 🎯 **[Axios](https://axios-http.com/)** - For reliable HTTP requests

### Special Thanks

- 💡 **All Contributors** - Everyone who has contributed code, ideas, or feedback
- 🐛 **Bug Reporters** - Helping us improve and fix issues
- 📖 **Documentation Writers** - Making the project accessible to everyone
- ⭐ **Stargazers** - Your support motivates us to keep building

---

<div align="center">

**Built with ❤️ by the NeuralMate Team**

[⬆ Back to Top](#-neuralmate)

</div>