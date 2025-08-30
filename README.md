# HydroLocate Frontend

This is the frontend application for HydroLocate, a platform for mapping hydrogen infrastructure and generating site recommendations for new hydrogen facilities.

## Features

- Interactive map visualization of hydrogen assets and recommended sites
- Dashboard for managing hydrogen infrastructure assets
- Site recommendation generator based on proximity to demand and renewable energy sources
- User authentication and profile management
- Leaderboard to track user contributions

## Tech Stack

- React.js for the UI framework
- React Router for navigation
- React Bootstrap for UI components
- Leaflet.js for interactive maps
- Axios for API requests
- FontAwesome for icons

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Navigate to the frontend directory: `cd HydroLocate/frontend`
3. Install dependencies: `npm install` or `yarn install`
4. Start the development server: `npm start` or `yarn start`

### Environment Variables

Create a `.env` file in the frontend directory with the following variables:

```
REACT_APP_API_URL=http://localhost:5000/api
```

## Project Structure

```
src/
├── api/              # API service functions
├── components/       # Reusable UI components
│   ├── dashboard/    # Dashboard-specific components
│   ├── layout/       # Layout components (Header, Footer)
│   └── map/          # Map-related components
├── context/          # React context providers
├── pages/            # Page components
├── utils/            # Utility functions
├── App.js            # Main application component
└── index.js          # Application entry point
```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## Contributing

1. Create a feature branch: `git checkout -b feature/your-feature-name`
2. Commit your changes: `git commit -m 'Add some feature'`
3. Push to the branch: `git push origin feature/your-feature-name`
4. Submit a pull request

## License

This project is licensed under the MIT License.