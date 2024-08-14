# Youtube2Quiz

## Overview

Youtube2Quiz is a web application designed to generate quiz questions from YouTube video content. Users submit a YouTube video link, and the application uses AI to analyze the video's transcript, generating a set of questions to test the user's understanding of the video.

## Features

- **Submit YouTube Video Links:** Users can input a YouTube video link to generate quiz questions.
- **AI-Powered Question Generation:** The application analyzes video transcripts using AI to create relevant questions.
- **User-Friendly Interface:** Built with React and styled using Tailwind CSS for a responsive and modern UI.
- **Scalable Backend:** Developed with .NET and C# for robust performance.

## Technologies Used

- **Frontend:**
  - Vite
  - React
  - TypeScript
  - Tailwind CSS

- **Backend:**
  - .NET Core
  - C#
  - Entity Framework Core

- **AI Integration:**
  - TBD (Depending on the chosen AI service or model)

## Project Structure

- **Root Directory**
  - Contains general documentation like the README and `LICENSE` files.
  
- **Youtube2QuizApi** (Backend)
  - All backend-related code, including API endpoints, models, controllers, and database configurations.

- **youtube-quiz-frontend** (Frontend)
  - All frontend-related code, including React components, styles, and assets.

## Setup / Getting Started

### Backend Setup (Youtube2QuizApi)

1. **Navigate to the backend directory:**

   ```bash
   cd Youtube2QuizApi
   ```

2. **Restore and build the backend project:**

   ```bash
   dotnet restore
   dotnet build
   ```
   

3. **Run the backend:**

   ```bash
   dotnet run
   ```

### Frontend Setup (youtube-quiz-frontend)

1. **Navigate to the frontend directory:**

   ```bash
   cd youtube-quiz-frontend
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   ```

## Usage

1. **Run the Backend and Frontend:**
   - Ensure the backend (API) is running before starting the frontend.
   - Open the frontend application in your browser.

2. **Submit a YouTube Video URL:**
   - Enter a YouTube video URL into the input field on the homepage and submit.

3. **Generate and View Questions:**
   - The application will process the video and display the generated quiz questions.

## Contributors

- [Ibrahim Houissa](https://github.com/ihouissa) - Project Lead

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
