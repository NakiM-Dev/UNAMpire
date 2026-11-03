# UNAMpire

### One world. Ten nations. One empire.

**UNAMpire** is a single-player, Risk-inspired geopolitical strategy game where players compete for territorial dominance through strategic planning, troop management and turn-based combat.

Built around a world map and a dark navy and metallic gold visual identity, UNAMpire brings a classic territory-conquest experience into a modern web application.

<p align="center">
  <a href="https://unampire.vercel.app">
    <strong>⚔️ PLAY UNAMPIRE</strong>
  </a>
</p>

<p align="center">
  <a href="https://unampire.vercel.app">Live Game: unampire.vercel.app</a>
</p>

---

## About the Game

The objective of UNAMpire is to build an empire by expanding your territorial control, managing military resources and making strategic decisions throughout the campaign.

Players select countries, deploy troops, engage in dice-based battles and attempt to conquer territories while competing against automated opponents.

Every turn presents new strategic opportunities and challenges. Success depends on how effectively players manage their forces, choose their battles and plan their expansion.

## Game Features

| Feature | Description |
|---|---|
| **World Map** | Explore the world map and select countries for your campaign. |
| **Campaign Setup** | Set up a campaign and choose countries, including random country selection. |
| **Troop Management** | Manage troop allocations and reinforcements throughout the game. |
| **Turn-Based Gameplay** | Take turns making strategic decisions and expanding your territory. |
| **Dice-Based Combat** | Resolve battles using a dice-based combat system. |
| **Territorial Conquest** | Defeat opponents and expand your empire by conquering territories. |
| **Automated NPC Opponents** | Compete against computer-controlled opponents that make automated strategic decisions. |
| **Activity Feed** | Follow campaign events and track important gameplay actions. |
| **Campaign Management** | Save, load and reset campaign progress. |

## Screenshots

Explore the UNAMpire interface and gameplay.

> Screenshots will be added here to showcase the world map, campaign setup, gameplay interface and territorial battles.

Suggested screenshots:
- Main landing page
- Campaign setup and country selection
- World map during gameplay
- Troop allocation interface
- Battle and conquest results

## Technology Stack

UNAMpire is developed using modern web technologies.

| Technology | Purpose |
|---|---|
| [Next.js 15](https://nextjs.org/) | React framework and application architecture |
| [React 19](https://react.dev/) | User interface development |
| [TypeScript](https://www.typescriptlang.org/) | Type-safe application development |
| [Tailwind CSS](https://tailwindcss.com/) | Styling and responsive design |
| [Clerk](https://clerk.com/) | User authentication |
| [react-simple-maps](https://www.react-simple-maps.io/) | Interactive map visualisation |
| [world-atlas](https://www.npmjs.com/package/world-atlas) | Geographic map data |
| [topojson-client](https://github.com/topojson/topojson-client) | Processing TopoJSON geographic data |

## Getting Started

Follow these instructions to run UNAMpire locally.

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- A code editor such as Visual Studio Code

### Installation

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate into the project directory**

```bash
cd UNAMpire
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure environment variables**

Create a `.env.local` file in the project root and use `.env.example` as a reference.

Add your own Clerk credentials:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key
```

You must obtain these credentials from your own Clerk application.

**5. Start the development server**

```bash
npm run dev
```

**6. Open the application**

Visit:

```text
http://localhost:3000
```

The terminal will display the correct local address if another port is selected.

## Environment Variables

UNAMpire uses Clerk for authentication.

The following environment variables are required:

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` | Clerk publishable key |
| `CLERK_SECRET_KEY` | Clerk secret key |

Create your own `.env.local` file and configure the appropriate credentials.

**Security notice:** Never commit `.env.local`, API keys, secret keys or other sensitive credentials to GitHub. The file should remain excluded through `.gitignore`.

## Project Structure

The application follows a Next.js project structure.

```text
UNAMpire/
├── public/              # Static assets and public resources
├── src/
│   ├── app/             # Application routes and pages
│   │   ├── game/        # Game page
│   │   ├── sign-in/     # Sign-in route
│   │   ├── sign-up/     # Sign-up route
│   │   ├── layout.tsx   # Root application layout
│   │   └── page.tsx     # Landing page
│   ├── components/      # Reusable interface components
│   └── middleware.ts    # Clerk authentication middleware
├── .env.example         # Example environment configuration
├── .gitignore           # Git ignored files
├── next.config.ts       # Next.js configuration
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

*Note: The structure above is a simplified overview. Refer to the repository for the complete file structure.*

## Gameplay Overview

A typical UNAMpire campaign follows a strategic progression:

1. **Prepare your campaign** – Enter the game and configure your campaign.
2. **Select countries** – Choose countries for the campaign or use random selection.
3. **Manage your troops** – Allocate available troops and prepare your territories.
4. **Take your turn** – Make strategic decisions about expansion and combat.
5. **Engage in battles** – Use dice-based combat to determine battle outcomes.
6. **Expand your empire** – Conquer territories and strengthen your position.
7. **Track your progress** – Follow campaign activity and manage saved games.

## Future Development

Potential future improvements include:

- More advanced NPC decision-making.
- Expanded strategic and diplomatic options.
- Additional gameplay modes.
- Improved campaign statistics and leaderboards.
- Enhanced map interactions and visual effects.
- Multiplayer gameplay.

These are possible future enhancements and are not necessarily part of the current implementation.

## Live Demo

Experience UNAMpire:

https://unampire.vercel.app/

---

<p align="center">
  <strong>UNAMpire</strong><br>
  One world. Ten nations. One empire.
</p>
