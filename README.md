# Trending Movies App

A modern web application that displays trending movies using the TMDB (The Movie Database) API, built with React and Vite, with Appwrite as the backend-as-a-service for user authentication and data storage. The app is deployed on Vercel.animations for seamless hosting and scalability.

## Features

- Fetches and displays trending movies from the TMDB API.
- Responsive design with Tailwind CSS.
- Fast development and build process using Vite.
- Deployed on Vercel for automatic scaling and easy deployment.

## Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **Backend-as-a-Service**: Appwrite
- **API**: TMDB (The Movie Database) API
- **Deployment**: Vercel
- **Language**: JavaScript (with JSX)

## Prerequisites

Before you begin, ensure you have the following:

- Node.js (v16 or higher) installed
- A TMDB API key from [TMDB](https://www.themoviedb.org/)
- An Appwrite instance (self-hosted or cloud) with a project set up
- A Vercel account for deployment

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/thisisfaizanali/trending-movie-shower.git
   cd trending-movie-shower
   ```
2. **Install dependencies**:

```bash
npm install
```

3. **Set up environment variables: Create a .env file in the project root and add the following**:

```bash
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
```

4. **Run the development server**:

```bash
npm run dev
```
