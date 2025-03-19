# JellyGame

A multiplayer underwater adventure game where you navigate through jellyfish-filled waters to reach your goal. Created for the 2025 Vibe Coding Game Jam.

## Features

- Real-time multiplayer gameplay
- Beautiful underwater 3D environment
- Mobile-friendly controls
- Radar-style minimap
- Global leaderboard
- Progressive difficulty levels
- Smooth animations and effects
- WebGL with fallback 2D mode

## Quick Start

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

3. Open `http://localhost:3000` in your browser

## Deployment

The game can be easily deployed to platforms like Vercel, Heroku, or Railway with zero configuration. Just connect your repository and deploy.

For manual deployment:
1. Clone the repository
2. Install dependencies with `npm install`
3. Set environment variables if needed (PORT)
4. Run `npm start`
5. Configure your web server to proxy requests to the Node.js application

## Controls

- Arrow Up/Down: Move up/down
- Arrow Left/Right: Turn left/right
- F: Move forward
- R: Move backward
- V: Toggle view (First/Third person)
- Mobile: Use on-screen joysticks

## Technical Details

- Built with Three.js for 3D graphics
- Socket.IO for real-time multiplayer
- Express.js backend
- Responsive design for all devices
- WebGL with automatic fallback to 2D canvas
- Optimized for performance with minimal loading time

## Credits

Created by [Your Name] with assistance from AI (Claude). All code and assets are generated or created specifically for this game jam.

## License

MIT License 