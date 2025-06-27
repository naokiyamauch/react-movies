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
    git clone https://github.com/your_username/react-movies.git
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

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.