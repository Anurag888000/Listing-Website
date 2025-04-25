# Crypto Tracker

Crypto Tracker is a web application that allows you to track the latest cryptocurrency prices, changes in market data, and other relevant information in real-time. The application displays detailed information for various cryptocurrencies like Bitcoin, Ethereum, Tether, XRP, Solana, and others, using **sample data** for testing and demo purposes.

## Features

- Real-time tracking of cryptocurrency prices and market data (using sample data).
- Displays price changes over the last hour, 24 hours, and 7 days.
- Embedded 7-day charts for each cryptocurrency (using sample data).
- Responsive design for mobile and desktop devices.

## Tech Stack

- **Frontend**: React.js
- **State Management**: Redux Toolkit
- **Styling**: CSS (including custom animations and transitions)
- **Data**: Sample JSON data used for demo purposes, no API integration.

## Architecture

- **Component-based Structure**: The application is built using React components, making it modular and reusable.
- **State Management with Redux Toolkit**: All cryptocurrency data is stored in the Redux store for global state management, ensuring that the data is consistent across components.
- **Responsive Layout**: The UI is responsive, adapting to both mobile and desktop screen sizes using media queries in CSS.
- **Animations and Transitions**: Hover effects and smooth transitions are applied to enhance the user experience, including hover effects on table headers and images.
- **Sample Data**: The app uses hardcoded sample data for cryptocurrencies instead of fetching data from an external API.

## Setup Instructions

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Anurag888000/crypto-tracker.git
