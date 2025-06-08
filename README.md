

# 🤖 SmartAssist

This project is an AI-driven real-time customer support chatbot, featuring a React frontend paired with a Node.js/Express backend. It leverages the OpenAI API to provide intelligent, context-aware responses, demonstrating how modern AI models can seamlessly integrate with user-friendly interfaces.

SmartAssist can be effortlessly embedded into e-commerce websites, SaaS products, or any platform seeking to offer automated customer service.

## 🚀 Key Features

* **Live Chat Experience:** Real-time conversation flow between users and AI for smooth interactions.
* **Intelligent Answers via OpenAI:** Utilizes OpenAI’s text-davinci-003 model to interpret questions and generate personalized, accurate replies.
* **Robust Backend:** Node.js and Express handle API calls to OpenAI and manage communication with the frontend.
* **Clean, Responsive UI:** Built with React, featuring styled components for an intuitive and attractive user experience.
* **Easy Configuration:** Simply add your OpenAI API key in the `.env` file and get started right away!

## 📂 Project Structure

```
/client          # React frontend source
  /src
    /components  # UI components
    /styles      # CSS files
    App.js       # Root React component
    index.js     # React entry point
  package.json   # Frontend dependencies

/server          # Backend API built with Node.js and Express
  /routes        # API route handlers
  /controllers   # Business logic and request handlers
  app.js         # Express server setup
  package.json   # Backend dependencies
.env             # Environment variables (including API keys)
```

## 🛠 Technology Stack

**Frontend:**

* React — UI library
* Axios — HTTP client

**Backend:**

* Node.js — JavaScript runtime
* Express.js — Web framework
* OpenAI API — AI language model

## 🔧 Installation and Running Instructions

### Prerequisites

* Node.js (v14 or above)
* NPM or Yarn package manager
* OpenAI API key

### Steps to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/shreyapillai819/fullstack.git
   ```

2. Move to the backend folder and install dependencies:

   ```bash
   cd server
   npm install
   ```

3. Create a `.env` file inside the `server` folder and insert your OpenAI API key:

   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

5. Open a new terminal window, navigate to the frontend directory, and install dependencies:

   ```bash
   cd ../client
   npm install
   ```

6. Launch the frontend application:

   ```bash
   npm start
   ```

