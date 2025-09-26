# Weather Agent Chat

A simple, pastel-themed chat application built with Next.js and React that allows users to ask for weather information. The app interacts with a weather agent API, handling streaming responses and providing fallback data if the API is unavailable.

---

## Features

- Chat interface with conversation history  
- User messages aligned right, agent messages aligned left  
- Streaming API response handling with fallback mock responses  
- Clear chat functionality  
- Loading indicators during API calls  
- Error messages for failed requests  
- Responsive, mobile-first pastel-themed UI  
- Keyboard support (Enter to send message)  
- Timestamps on messages for context  

---

## Getting Started

### Prerequisites

- Node.js (v14 or later recommended)  
- npm (comes with Node.js)

### Installation and Running

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-agent-chat.git
   cd weather-agent-chat
2. Install dependencies:
npm install
3. Start the development server:
npm run dev
Open your browser and navigate to http://localhost:3000

## How It Works
-Users type weather-related queries into the chat interface.
-The app sends the query to a weather agent API and streams the response back.
-While waiting, the input is disabled and a loading indicator is shown.
-If the API is unavailable, a fallback mock response is displayed using the city name parsed from the user's query.
-Users can clear the chat history anytime using the Clear Chat button.

-> Example Output
Here is a sample interaction:
->User: What is the weather in Mumbai?
->Agent:
🌦️ Weather in Mumbai:
Temperature: 28.0°C (Feels like 33.0°C)
Humidity: 81%
Wind: 9.6 km/h (gusts up to 11.9 km/h)
Conditions: Overcast

## Technologies Used
-Next.js
-React
-TypeScript
-CSS Modules / Styled Components (adjust if applicable)

## Assumptions & Limitations
-The fallback response shows a generic weather summary if the API is unavailable.
-Streaming API responses are handled line-by-line; changes may be required if the API format changes.
-The app currently supports only English language queries.
-Error handling is basic and does not include retries or detailed diagnostics.
-UI design prioritizes simplicity and readability; advanced animations or themes are not included.

## Future Improvements
-Dark mode toggle
-Integration with real-time weather APIs
-Unit and integration testing
-Enhanced error handling and retry logic
-Improved accessibility and keyboard navigation

## Contact
For any questions or feedback, please contact: mishra.suhani008@.com
Thank you for checking out Weather Agent Chat!
— Suhani Mishra