
# React OTP Login dashboard

A simple frontend-only React application that demonstrates a 3-step login flow using React Router. The app has three pages: a login page (Gmail + password), an OTP verification page, and a basic dashboard. No backend is required — navigation works with React Router only.


## Features
### Login Page
- Input fields for Gmail and password.
- Login Now” button navigates to OTP screen.
- Basic validation (cannot proceed with empty fields).
### OTP Verification Page
- Input box to type any OTP (no backend check).
- “Submit” button navigates to Dashboard page.
- Basic validation (OTP field cannot be empty).
### Dashboard Page
- Displays a welcome message after successful login + OTP.
- Can be extended later with real dashboard data.
### Client-Side Routing with React Router v6
- Smooth page-to-page navigation without reloading the browser.
- Built with Vite + React.
### Built with Vite + React
- Fast dev server with hot reload.
- Lightweight and easy to extend.
### Built with Vite + React
- Clean, minimal pages with simple inline styling.
- Easy to replace with Tailwind, CSS Modules, or Material UI if needed.
## Tech stack
- Frontend Framework → React 18

- Routing → React Router DOM v6

- Build Tool → Vite

- Language → TypeScript (with .tsx files)

- Styling → Basic CSS (index.css), can be extended with Tailwind or Material UI
## Dependencies

Dev Dependencies (added automatically by Vite when you created the project)

@vitejs/plugin-react	Enables React in Vite

typescript	TypeScript support

@types/react, @types/react-dom	TypeScript type definitions
## project structure
<img width="1024" height="1536" alt="ChatGPT Image Sep 4, 2025, 09_33_45 PM" src="https://github.com/user-attachments/assets/e2e0487a-16c2-4a89-9c18-fd130436d4eb" />

## Installation & Setup

### Make sure Node.js is installed

Download from https://nodejs.org
 (use LTS version).

Verify installation:

node -v
npm -v

### Clone or create project folder
 If you already have the project, open the folder in VS Code.
If not, create a new Vite + React app:

npm create vite@latest my-simple-app
cd my-simple-app
npm install

### Install dependencies
Since we’re using React 18 and React Router DOM 6, install them:

npm install react@18 react-dom@18 react-router-dom@6
### Run the development server

npm run dev
 
 

You’ll see something like:

Local:   http://localhost:5173/


Open that link in your browser.
## Screenshots
<img width="1920" height="1020" alt="Screenshot 2025-09-04 211446" src="https://github.com/user-attachments/assets/fbbfe8f3-9dbd-4519-998a-0317c617d8d6" />
<img width="1920" height="1020" alt="Screenshot 2025-09-04 211458" src="https://github.com/user-attachments/assets/5fce15db-6b86-4f01-a966-91e823e9e0dc" />
<img width="1920" height="1020" alt="Screenshot 2025-09-04 211504" src="https://github.com/user-attachments/assets/29b44d26-bbda-40ed-9734-9baa00f77dbe" />

## Demo

https://github.com/user-attachments/assets/e01b8b8c-f22b-420e-871a-c20fced7fed9

