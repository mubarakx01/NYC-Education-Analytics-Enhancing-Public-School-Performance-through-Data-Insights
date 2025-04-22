
# NYC School Analytics Dashboard

A React-based web application for analyzing school performance data and predicting student risk factors. This project demonstrates data visualization, predictive analytics, and modern web development techniques.

## Project Overview

This dashboard allows users to:

- View school performance metrics across multiple NYC schools
- Analyze demographic distributions within schools
- Compare test scores and attendance rates
- Predict student risk status based on performance metrics
- Understand risk distribution across the school system

## Features

- **Interactive Charts**: Bar charts for test scores, pie charts for demographics
- **School Selection**: Dynamically view data for different schools
- **Risk Prediction**: Input student metrics to predict risk status
- **Responsive Design**: Works on desktop and mobile devices

## Technology Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **State Management**: React Query for data fetching
- **Visualization**: Recharts for interactive data visualization
- **UI Components**: shadcn/ui component library
- **Routing**: React Router for navigation

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <your-repo-url>

# Navigate to the project directory
cd nyc-school-analytics

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Project Structure

- `/src/components`: UI components including charts and forms
- `/src/data`: Mock data models and utility functions
- `/src/hooks`: Custom hooks for data fetching
- `/src/pages`: Main application pages

## Future Enhancements

- Connect to a real backend API for live data
- Add user authentication for administrative features
- Implement time-series analysis for tracking performance over time
- Add export functionality for reports

## Deployment

This project can be easily deployed to platforms like Vercel, Netlify, or GitHub Pages:

```bash
# Build for production
npm run build

# Deploy (example for Vercel)
vercel deploy
```

## License

MIT

## Author

[Your Name] - [Your Portfolio/GitHub URL]

## Acknowledgments

- Data inspired by NYC Department of Education metrics
- Built as a portfolio project to demonstrate web development and data visualization skills
