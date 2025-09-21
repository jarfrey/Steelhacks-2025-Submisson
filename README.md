# Steelhacks-2025-Submisson

Dynamic Homepage Extension
This is a dynamic, customizable homepage built as a browser extension. It features a clean, modern design with a full-screen background and modular content widgets.

Key Features
Dynamic Layout: The app uses a flexible CSS layout to arrange different content modules.

Live Time Display: A large, centered clock displays the current time.

Animated Search Bar: A stylish search bar opens a Google search in a new tab upon pressing Enter.

AI-Powered Chat: Integrates with the Gemini API to provide an interactive AI assistant.

Live Weather Widget: Displays live weather data for the user's location using the react-weather-widget library.

Dynamic To-Do List: A functional widget for managing tasks.

Calendar Widget: A calendar component for a quick view of the month.

Timer Widget: A simple timer with start, pause, and reset functionality.

Local Image Upload: A photo widget that allows users to upload and display a local image.

Accessibility Features: Designed with accessibility in mind, though specific features are not yet detailed in the provided code.

Project Structure
The project is organized into a modular component-based architecture for easy maintenance.

src/
├── components/
│   ├── boxComponents/      // Modular Widgets
│   ├── Search.tsx
│   ├── Background.tsx
│   └── App.tsx           
├── App.css                 
├── App.tsx
├── ...

How to Run Locally
Clone the repository:

Bash

git clone [(https://github.com/jarfrey/Steelhacks-2025-Submisson)]
Install dependencies:

Bash

npm install
Set up API keys:
Create a .env file in the project's root directory and add your API keys.

VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY

Start the development server:

Bash

npm run dev






