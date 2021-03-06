# P2P OnePoker browser game

> OnePoker browser P2P Game

## External Libraries

All Library are already included in project:

- [material-colors](https://github.com/shuhei/material-colors): Colors from [Google's Material Design](https://material.io/guidelines/style/color.html#color-color-palette) made available to coders with CSS's classes.

- [deck-of-cards](https://github.com/pakastin/deck-of-cards): Js & Css library to manipulate a deck of cards.

- [pokersolver](https://github.com/goldfire/pokersolver): Js library to calc score in different card games.

- [Spectre.css](https://picturepan2.github.io/spectre/index.html): Lightweight, responsive and modern CSS framework.

- [PEERJS](http://peerjs.com/): PeerJS simplifies WebRTC peer-to-peer data, video, and audio calls.

## Installation

### Node.js

Install latest version of [NodeJS](https://nodejs.org/it/) and **npm**.

### Install Dependencies

Open terminal in the root directory of project

```bash
$> npm install
```

## Execution

### Development

To start watch server during development

```bash
$> npm start
```

### Peer Server

```bash
$> npm run server
```

### Test Client

```bash
$> npm test
```

## Project Structure

### src/css

Stylesheets for the project. To change CSS styles edit **style.css**.

### src/assets/images

Contains all image use in website.

### src/js

Scripts style for project. Edit **script.js** to enter custom scripts.

### src/scss

Sass files for styles.

## Game Rules

### Goal

Reach **502** points for first. In case, two or more player reach 502 in the same turn, the one with the highest score at the end of the turn won. If at the flop you find a poker on the table, you instantly won the game.

### Scores

- **Royal Flush**: 200
- **Four of a Kind**: 100
- **Full House**: 50
- **Flush**: 30
- **Straight**: 15
- **Three of a Kind**: 10
- **Two Pairs**: 3
- **One Pair**: 1