# Video Streaming Platform (Work in Progress)

## Description

This project is a YouTube-like video streaming platform built with **React** and **Material-UI**, with routing handled by **React Router**. The platform will eventually fetch video content from external APIs (like **RapidAPI**) and display it in a clean, user-friendly interface. The application includes features like a navigation bar with a search functionality, video feed, and individual video detail pages.

**Note**: The project is still under development and key features are yet to be fully implemented.

---

## Table of Contents

- [Project Structure](#project-structure)
- [Features (Work in Progress)](#features)
- [To-Do List](#to-do-list)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Technologies Used](#technologies-used)

---

## Project Structure

```
/src
 ├── /components       # Reusable UI components
 │   ├── Navbar.jsx    # Top navigation bar (includes logo and search bar)
 │   ├── Feed.jsx      # Displays list of videos on the homepage
 │   ├── VideoDetail.jsx  # Shows video details and player for individual videos
 │   ├── ChannelDetail.jsx # Shows channel details and videos from the channel
 │   ├── SearchFeed.jsx # Displays search results for user queries
 │   └── SearchBar.jsx # Search bar component in the Navbar
 ├── /utils            # Utility files like constants
 │   └── constants.js  # API URLs, demo data, and reusable icons
 ├── App.jsx           # Main app structure with routing
 ├── index.js          # Application entry point
 └── index.css         # Global CSS
```

---

## Features (Work in Progress)

- **Navbar**:
  - Includes a logo that links to the home page.
  - A search bar is implemented but still needs full API functionality.

- **Feed**:
  - Displays a list of videos on the homepage.
  - Currently uses demo data, but will be hooked to **RapidAPI** to fetch live video content.

- **Video Detail Page**:
  - Displays details about a selected video.
  - Will show video description, comments, and suggested videos related to the content.

- **Channel Detail Page**:
  - Displays information about a YouTube channel.
  - Will include a feed of videos from the respective channel.

- **Search Functionality**:
  - Allows users to search for videos based on a search term.
  - Will dynamically show search results when integrated with the API.

---

## To-Do List

- [ ] Connect the app to the **RapidAPI** service to fetch real-time video data.
- [ ] Implement search functionality to display search results from the API.
- [ ] Build out the **VideoDetail** and **ChannelDetail** pages with dynamic content.
- [ ] Style the app using **Material-UI** for a fully responsive design.
- [ ] Add error handling and loading states when fetching API data.
- [ ] Deploy the app on a hosting platform like **Netlify** or **Vercel**.

---

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/video-streaming-platform.git
   ```
2. Navigate into the project directory:
   ```bash
   cd video-streaming-platform
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Run the development server:
   ```bash
   npm start
   ```

5. Open your browser at `http://localhost:3000` to view the app.

---

## Installation

This project requires **Node.js** and **npm** (Node Package Manager) to run. Make sure you have these installed before proceeding.

1. Install project dependencies by running:

   ```bash
   npm install
   ```

2. Start the application:

   ```bash
   npm start
   ```

---

## Technologies Used

- **React** - Frontend library for building the user interface.
- **Material-UI** - For building responsive and customizable components.
- **React Router** - For navigation and routing between pages.
- **RapidAPI** - (Will be used) for fetching video data and related content.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.