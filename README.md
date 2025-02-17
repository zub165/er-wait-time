# ER Wait Time

A modern web application that shows emergency room wait times and allows patient registration. Built with HTML, CSS, and JavaScript using the Google Maps API.

## Data Storage

The application stores data in `data.json` using GitHub's API. The file contains:
- Patient registration records
- Hospital wait times
- System configuration

## Security Note

The application uses GitHub for data storage. Make sure to:
- Keep the GitHub token secure
- Never commit the token to the repository
- Regularly rotate the token
- Monitor repository access

## Features

- Search for nearby emergency rooms
- View estimated wait times
- Patient registration system
- Distance calculation
- Responsive design

## Setup

1. Clone the repository
2. Get a Google Maps API key from the Google Cloud Console
3. Replace `YOUR_GOOGLE_API_KEY` in the index.html file
4. Open index.html in a browser
5. Create a GitHub Personal Access Token
6. Update the token in the application
7. Initialize data.json in the repository
8. Configure repository permissions

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Maps API
- Google Places API

## API Usage

The application uses:
- GitHub API for data storage
- Google Maps API for location services
- Places API for hospital data 