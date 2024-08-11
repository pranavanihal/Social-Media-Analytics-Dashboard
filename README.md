# Social Media Dashboard

## Overview

This project is a Social Media Dashboard built with Flask, designed to provide insights into YouTube channel statistics and Instagram user information. It integrates data from both platforms and visualizes it using interactive charts.

## Features

- **YouTube Dashboard:**
  - View detailed channel statistics including subscribers, total views, and number of videos.
  - Explore individual video metrics with comprehensive details.
  - Visualize data with interactive charts using Plotly.

- **Instagram Dashboard:**
  - Retrieve and display Instagram user information such as username, follower count, and bio.
  - View recent posts with details including likes, comments, and hashtags.
  - Visualize user engagement metrics with charts created using Chart.js.

## Technologies Used

- **Backend:**
  - Flask (Python web framework) for server-side logic.
  - YouTube Data API for retrieving YouTube video and channel data.
  - Instaloader library for accessing Instagram user data.

- **Frontend:**
  - HTML templates with Jinja templating for dynamic content rendering.
  - Bootstrap for responsive and aesthetically pleasing user interface design.
  - Chart.js and Plotly for creating interactive data visualizations.

## Getting Started

To set up and run the Social Media Dashboard locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AdityaKanawade0565/social-media-dashboard.git
   cd social-media-dashboard
2. **Install Dependencies:**
    pip install -r requirements.txt
3. **SetUp the Api keys:**
4. **Run the application:**
     python app.py
5. **Access the Dashboard:**
   Open your web browser and navigate to http://localhost:5000 to view the dashboard.

## Folder Structure

static/: Contains static files like CSS, JavaScript, and images used for styling and frontend functionality.
templates/: Includes HTML templates rendered by Flask with Jinja templating for dynamic content.
