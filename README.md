# YouTube Analytics Dashboard

A modern, interactive dashboard for analyzing YouTube channel and video performance, built with React, Vite, Tailwind CSS, and Recharts. This dashboard provides real-time insights, AI-powered analytics, and beautiful data visualizations for YouTube creators and analysts.

## Features

*YouTube Channel Analytics:* Enter any YouTube channel URL to fetch real data (subscribers, views, videos, etc.).   
  
*Video Overview:* See detailed stats for the latest video, including views, likes, comments, and average view duration.    
   
*Performance Analysis:* AI-powered performance scoring, trends, and actionable recommendations.    
   
*Engagement Metrics:* Visualize engagement rate, likes/dislikes ratio, and comment sentiment.   
    
*Sentiment Analysis:* Analyze comment sentiment using LLMs (e.g., Gemini AI) and VADER, with CSV export.    
   
*Interactive Charts:* Responsive charts for likes/dislikes, audience retention, and more using Recharts.    
   
*Auto-Refresh:* Data auto-refreshes at configurable intervals.     
  
*Dark/Light Mode:* Toggle between day and night modes.   
     
*API Fallback:* Uses mock data if the backend API is unavailable.     
  

## Tech Stack 
 
*Frontend:* React 19, Vite, Tailwind CSS, Recharts, Lucide Icons   
    
*Backend API:* Expects endpoints at https://backend-dashboard-kyeo.onrender.com (not included)    
   
*Linting:* ESLint with React Hooks and Vite support     
  


## Project Structure

```
frontend-dashboard/
├── src/
│   ├── App.jsx                # Main dashboard component
│   ├── main.jsx               # React entry point
│   ├── index.css              # Tailwind and global styles
│   ├── App.css                # App-specific styles
│   ├── assets/
│   │   └── react.svg
│   └── components/
│       ├── EngagementRateCard.jsx
│       ├── LikesDislikesChart.jsx
│       ├── PerformanceAnalysis.jsx
│       └── SentimentAnalysis.jsx
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
├── eslint.config.js
└── .gitignore
```

## Quick Start

### Prerequisites
Node.js (v18+ recommended)
npm

### Option 1: Automated Startup (Recommended)
Clone the repository:

```bash
git clone <repo-url>
cd frontend-dashboard
```
Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

Open in browser: Visit http://localhost:5173 (or as indicated in the terminal).

## Usage
Enter a YouTube channel URL to fetch analytics.   
   
Explore tabs for Overview, Sentiment Analysis, and Performance.   
  
Use the "Export Data" button to download analytics as CSV.   
  
Toggle between Day/Night mode for your preference.   
  
## Customization
API Endpoint: The frontend expects a backend at https://backend-dashboard-kyeo.onrender.com. You can change this in the source files if needed.   
  
Styling: Modify tailwind.config.js and index.css for custom themes.   
  
Components: Extend or replace components in components as needed.   
  
Scripts 

```bash
npm run dev – Start development server
npm run build – Build for production
npm run preview – Preview production build
npm run lint – Lint code with ESLint
```

   
## License   
  
This project is for educational/demo purposes. Please adapt as needed for your use case.   
  

Credits:
React  
Vite  
Tailwind CSS  
Recharts  
Lucide Icons  


Notes
If the backend API is unavailable, the dashboard will use mock data for demonstration.
For full functionality, ensure the backend API is running and accessible.
