# Smart Email Assistant

A Chrome extension powered by Spring Boot and React that helps you write better emails using AI.

## Features

- 🤖 AI-powered email response generation
- 🔌 Chrome extension integration with Gmail
- ⚡ Fast and responsive React frontend
- 🌱 Spring Boot backend with Spring AI

## Project Components

### Chrome Extension
- Seamlessly integrates with Gmail's interface
- Adds an AI reply button to email compose window
- Communicates with backend API for email generation

### React Frontend
- Modern UI built with React and Vite
- Real-time email generation preview
- Customizable email tone and style options

### Spring Boot Backend
- RESTful API endpoints for email generation
- Spring AI integration for natural language processing
- Secure and scalable architecture

## Tech Stack

- **Frontend**: React, Vite
- **Backend**: Java 17, Spring Boot, Spring AI
- **Browser Extension**: Chrome Extensions API
- **Build Tools**: Maven, npm

## Getting Started

### Prerequisites

- Node.js (v18+)
- Java 17+
- Maven 3.6+
- Chrome browser

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/smart-email-assistant.git
cd smart-email-assistant
```

2. **Setup Backend**
```bash
cd email-writer-sb
mvn clean install
mvn spring-boot:run
```

3. **Setup Frontend**
```bash
cd email-writer-react
npm install
npm run dev
```

4. **Install Chrome Extension**
- Open Chrome
- Go to `chrome://extensions/`
- Enable "Developer mode"
- Click "Load unpacked"
- Select the `email-writer-extension` folder

## Development

### Backend Development
```bash
cd email-writer-sb
mvn spring-boot:run -Dspring-boot.run.profiles=dev
```

### Frontend Development
```bash
cd email-writer-react
npm run dev
```

### Extension Development
- Make changes in `email-writer-extension` folder
- Reload the extension in Chrome

## Project Structure

```
smart-email-assistant/
├── email-writer-extension/   # Chrome extension files
├── email-writer-react/       # React frontend
└── email-writer-sb/         # Spring Boot backend
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## Acknowledgments

- Spring Boot team for the excellent framework
- React team for the frontend library
- Chrome Extensions team for the browser integration capabilities