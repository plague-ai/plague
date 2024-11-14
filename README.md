# Plague Ai Game Frontend

The **Plague Ai Game** is an web-based simulation inspired by Plague Inc., where an Ai Bot aim to spread virus globally, visualizing the spread rate on a world map. Unlike traditional simulations, this game displays the spread based on real-time transactions and other factors. Built using **Next.js** and **Mapbox API**, this frontend renders dynamic pop-ups, markers, and interactive data visualizations that change based on transactions on the token.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Global Virality Map**: Uses Mapbox for real-time, interactive visualization of viral spread across different regions.
- **Dynamic Pop-ups**: Displays factors that affect virus spread.
- **Transaction-based Spread**: The game's virality is influenced by the number of Solana token transactions.
- **User Interactivity**: Players can observe and influence the spread of information in various ways, adjusting different factors and strategies.
- **Responsive Design**: Fully responsive and optimized for desktop and mobile viewing.

## Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/), [React](https://reactjs.org/)
- **Map Integration**: [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/)
- **Database**: MongoDB (used via an API to fetch data on virality)

## Getting Started

### Prerequisites

- **Node.js** (v14.x or higher)
- **MongoDB** database access (you can use MongoDB Atlas for a cloud database)

### Installation

**Clone the repository**:

```bash
git clone https://github.com/yourusername/viral-network-game.git
cd viral-network-game
npm run dev
```

The app will be available at http://plagueai.com.

### Environmental Variables

The project requires the following environment variables:

- **NEXT_PUBLIC_MAPBOX_KEY**: Your Mapbox public key for map rendering
- **NEXT_MONGODB_URI**: MongoDB connection string for connecting to your MongoDB instance.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
