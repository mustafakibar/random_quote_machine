# FCC Random Quote Machine

React app that displays a random quote and lets the user tweet it, built for the FreeCodeCamp Front End Libraries certification.

## Features

- Fetches a list of quotes from the `type.fit` public API on mount.
- Displays a randomly selected quote and its author each render
- "Get another quote" button selects and displays a new random quote
- Twitter intent link lets the user tweet the current quote with hashtags
- Loading state shown while quotes are being fetched

## Tech Stack

- Class component; the new-quote button calls `forceUpdate()` to pick a new random quote from already-fetched state.
- JavaScript
- Create React App (react-scripts 5)

## Requirements

- Node.js 16+
- Yarn 1.x (matching the `yarn.lock` in the repo)

## Installation

```bash
yarn install
```

## Usage

```bash
yarn start
```

Open `http://localhost:3000` in your browser.

## Build

```bash
yarn build
```

## Testing

```bash
yarn test
```

## Project Structure

```
.
├── public/
├── src/
├── package.json
└── README.md
```

## License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file.
