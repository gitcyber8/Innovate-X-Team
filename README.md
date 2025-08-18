# Health Buddy - A Next.js AI-Powered App

This is a Next.js starter app created in Firebase Studio. It demonstrates how to build a simple health assistant using AI features powered by Google's Gemini models through Genkit.

## Features

- **Smart Medical ID**: Summarizes your health information using AI.
- **Medicine Reminders**: Helps you keep track of your medications.
- **First-Aid Chatbot**: Provides AI-powered first-aid guidance.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18 or later recommended)
- `npm` (comes with Node.js)

### 1. Set Up Your Gemini API Key

This project uses the Gemini API to power its AI features.

1.  Create a free API key at [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  Open the `.env` file in the root of this project.
3.  Replace the placeholder `"your-api-key-here"` with the key you just created.

```
GEMINI_API_KEY="your-api-key-here"
```

### 2. Install Dependencies

Open your terminal, navigate to the project directory, and run:

```bash
npm install
```

### 3. Run the Application

You'll need to run two processes in separate terminal windows for the app to work correctly.

**In your first terminal:** Start the Genkit AI flows.

```bash
npm run genkit:dev
```

**In your second terminal:** Start the Next.js frontend application.

```bash
npm run dev
```

Now, you can open your web browser and navigate to [http://localhost:9002](http://localhost:9002) to see the app in action.
