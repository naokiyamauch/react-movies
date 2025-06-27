# React Movies

This is a simple web application built with React that allows users to search for movies and view trending movies. The application uses the TMDb API to fetch movie data and Appwrite to store and manage trending movie data.

## Features

-   Search for movies by title
-   View a list of trending movies
-   View movie details, including poster, title, and release date
-   Responsive design for a seamless experience on all devices

## Technologies Used

-   React
-   Vite
-   Tailwind CSS
-   Appwrite
-   TMDb API

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

-   Node.js and npm installed on your machine
-   An Appwrite account and a project set up
-   A TMDb API key

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/naokiyamauchi/react-movies.git
    ```
2.  Install NPM packages
    ```sh
    npm install
    ```
3.  Create a `.env` file in the root of the project and add the following environment variables:
    ```
    VITE_APPWRITE_PROJECT_ID=<your-appwrite-project-id>
    VITE_APPWRITE_DATABASE_ID=<your-appwrite-database-id>
    VITE_APPWRITE_COLLECTION_ID=<your-appwrite-collection-id>
    VITE_TMDB_API_KEY=<your-tmdb-api-key>
    ```
4.  Start the development server
    ```sh
    npm run dev
    ```

## Usage

Once the development server is running, you can open your browser and navigate to `http://localhost:5173` to use the application.