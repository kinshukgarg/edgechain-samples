# edgechain-samples

Overview
Medicine Checker is a web application that provides detailed information about medicines using Bing and OpenAI APIs. Enter the name of a medicine, and the application fetches relevant data from the web and uses AI to generate comprehensive information, including uses, dosage, side effects, and precautions.

Features
Medicine Information: Get detailed information about any medicine.
AI-Driven: Utilizes OpenAI's GPT model to generate detailed reports.
Web Search Integration: Fetches relevant web snippets using Bing API.
Technology Stack
Frontend: React, Vite, Material-UI
APIs: OpenAI, Bing Search API
Utilities: Axios for HTTP requests
Getting Started
Prerequisites
Node.js (v14 or higher)
npm (v6 or higher)
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/kinshukgarg/edgechain-samples
cd medicine-checker/frontend
Install dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env file in the frontend directory with the following content:

plaintext
Copy code
VITE_OPENAI_API_KEY=your_openai_api_key_here
VITE_BING_API_KEY=your_bing_api_key_here
Start the development server:

bash
Copy code
npm run dev
The application will be available at http://localhost:5173
