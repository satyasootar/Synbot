# Synbot

**Synbot** is a friendly and highly knowledgeable chatbot designed to answer both technical and general knowledge questions. This project leverages Google's Generative AI to create a personalized conversational experience, with Synbot adapting responses based on the user’s name for a more engaging interaction.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Personalized Conversations**: Greets users and personalizes responses based on their name.
- **Contextual Understanding**: Handles both technical queries and general knowledge questions.
- **Flexible Responses**: Adjusts tone and complexity based on user inputs.
- **Built-in Safety**: Configured with Google Generative AI’s harm-category detection.

## Setup

To run Synbot locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/satyasootar/Synbot.git
   cd Synbot
   ```

2. **Install Dependencies**:
   Make sure you have [Node.js](https://nodejs.org/) installed, then run:
   ```bash
   npm install
   ```

3. **Environment Variables**:
   Synbot requires a Google Generative AI API key. Create a `.env` file in the project root:
   ```plaintext
   GEMINI_API_KEY=your-google-generative-ai-api-key
   ```

4. **Start the Application**:
   ```bash
   node server.js
   ```

## Usage

1. **Start the Server**:
   Run `node server.js` to start Synbot.
2. **Interaction**:
   Once the server is running, Synbot will greet the user, ask for their name, and tailor responses based on the user’s input.

## Environment Variables

- **GEMINI_API_KEY**: API key for Google Generative AI to connect with the `gemini-1.5-pro` model.


## Contributing

Contributions are welcome! To contribute to Synbot:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License.

---

This should provide a strong foundation for your Synbot project’s README. Let me know if you’d like to add any additional sections!
