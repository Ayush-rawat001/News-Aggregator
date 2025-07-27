# News Aggregator

A responsive web application that fetches and displays real-time news articles from various sources using the NewsAPI.

## Features

- Real-time news fetching from multiple sources
- Category navigation (IPL, Finance, Politics)
- Search functionality for specific topics
- Responsive design for all devices
- Click on news cards to read full articles

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- NewsAPI

## Setup

1. Get a free API key from [NewsAPI](https://newsapi.org/)
2. Replace the API key in `script.js`:
   ```javascript
   const API_KEY = "your-api-key-here";
   ```
3. Open `index.html` in your browser

## Usage

- Click on categories (IPL, Finance, Politics) to view specific news
- Use the search bar to find news on any topic
- Click on news cards to read full articles
- Click the logo to reload with default news

## Project Structure

```
news-aggregator/
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
├── stylr.css          # CSS styling
├── assets/
│   └── logo.jpg       # Application logo
└── README.md          # Project documentation
``` 