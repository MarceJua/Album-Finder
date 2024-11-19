# Spotify Artist Search

This project is a React application that allows users to search for artists on Spotify and view their albums. It uses the Spotify Web API to fetch artist and album data.

![Album Finder](https://i.ibb.co/f2HP7k7/chrome-capture-2024-11-18.gif)

## Features

- Search for artists by name.
- Display a list of albums for the searched artist.
- Uses Spotify's client credentials flow for authentication.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spotify-artist-search.git
   cd spotify-artist-search
2. Install dependencies:
   ```bash
   npm install
3. Create a .env file in the root directory and add your Spotify API credentials:
   ```bash
    REACT_APP_SPOTIFY_CLIENT_ID=your-client-id
    REACT_APP_SPOTIFY_CLIENT_SECRET=your-client-secret
    
## Usage
1. Start the development server:
   ```bash
   npm run dev
2. Open your browser and navigate to http://localhost:3000
3. Enter the name of an artist in the search input and press Enter or click the Search button.
4. View the list of albums for the searched artist.

## Code Overview
**App.jsx**: The main component that handles the search functionality and displays the results.
- Uses `useEffect` to fetch the access token from Spotify API on component mount.
- Contains the `search` function to fetch artist and album data from Spotify API.
- Renders the search input and button, and displays the list of albums.

## Dependencies

- React
- Bootstrap (for styling)
- Spotify Web API