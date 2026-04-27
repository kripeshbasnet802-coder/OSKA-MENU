# 🎮 OSKA IMPOSTER - Social Deduction Game

A browser-based multiplayer social deduction game inspired by Among Us. One player is secretly an imposter while others are crewmates trying to find them through discussion and voting.

## Features

### 🎯 Core Gameplay
- **Role Assignment**: Players are randomly assigned as Crewmates or Imposters
- **Discussion Phase**: Players discuss and debate who might be the imposter
- **Voting Phase**: Players vote to eliminate a suspect
- **Real-time Chat**: In-game communication system
- **Multiple Rounds**: Game continues until imposters or crewmates win

### 👥 Player Roles
- **Crewmate**: Complete tasks and identify the imposter
  - Objective: Vote out all imposters
  - Win Condition: All imposters eliminated

- **Imposter**: Create chaos and eliminate crewmates
  - Objective: Kill crewmates and avoid detection
  - Win Condition: Imposters equal or outnumber crewmates

### ⏱️ Game Phases
1. **Lobby Phase**: Players join/create games
2. **Role Assignment**: Roles revealed to players
3. **Discussion Phase** (120s): Players discuss and accuse
4. **Voting Phase** (60s): Players vote to eliminate someone
5. **Results**: Win/loss screen and stats

## How to Play

### Starting a Game
1. Enter your player name
2. Click "Create Game" to host or "Join Game" to join with a code
3. Wait for 3+ players to start
4. Roles will be assigned automatically

### During the Game
- **Discussion Phase**:
  - Chat with other players
  - Discuss who you think is suspicious
  - Click "Accuse" to point fingers  
  
- **Voting Phase**:
  - Vote to eliminate a player
  - The player with most votes is eliminated
  - Continue the cycle

### Winning
- **Crewmates Win**: When all imposters are voted out
- **Imposters Win**: When imposters equal or outnumber crewmates

## Game Balance

| Players | Imposters |
|---------|-----------|
| 3-5     | 1         |
| 6-8     | 2         |
| 9+      | 3         |

## Timings

- **Discussion**: 120 seconds
- **Voting**: 60 seconds
- **Max Players**: 10

## Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Node.js (optional for multiplayer)
- **Communication**: WebSockets (planned enhancement)

## File Structure

```
imposter-game/
├── index.html          # Game UI and screens
├── game.js             # Core game logic
├── styles.css          # Game styling
├── server.js           # Backend server (optional)
└── README.md           # Documentation
```

## Getting Started

1. Clone or download the repository
2. Open `index.html` in a web browser
3. Enter your name and create/join a game
4. Play!

## Future Enhancements

- [ ] Multiplayer networking with WebSockets
- [ ] Task system for crewmates
- [ ] Sabotage abilities for imposters
- [ ] Persistent player statistics
- [ ] Custom game settings
- [ ] Cosmetics and customization
- [ ] Spectator mode
- [ ] Anonymous voting
- [ ] Mobile app version
- [ ] Sound effects and music

## Game Rules

1. **No outside communication**: Discuss only in-game
2. **Report immediately**: Dead players cannot communicate
3. **No screen-looking**: Hide your role from others
4. **Vote logically**: Use discussion to make decisions
5. **Have fun**: It's just a game!

## Tips for Crewmates

- Work in pairs when possible
- Pay attention to suspicious behavior
- Watch for inconsistencies in stories
- Call out unusual activity
- Don't trust anyone completely

## Tips for Imposters

- Blend in with crewmates
- Use chaos to your advantage
- Create false accusations
- Act natural when suspicious
- Sabotage strategically

## License

MIT License - Feel free to use and modify

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## Support

For issues, questions, or suggestions, please open an issue on GitHub.

---

**Made with ❤️ by OSKA Team**

Enjoy the game and may the best social engineer win! 🎮