# Welcome to our ReefRunner game!

A sidescroller game underneath the sea where the aim is to get the highest score possible. The longer you last in the game without being killed by a shark or being pushed of the screen by a rock of ship, the higher your score! Extra features such as bubbles make you rise up and a can of worms brings you down. Don't avoid them though as they add 1000 points to your score. Also, don't forget to catch octopus Stephen, as he will make you go twice as fast to make it easier to catch those bubbles and worms and avoid any obstacles.

This game is using Phaser as the main framework with JavaScript and HTML/CSS. Playable on both your laptop (recommended on Chrome) and phone.

[Start playing!](https://reef-runner.vercel.app/)

## Dependencies

### Update npm and install dependencies

```bash
npm update
npm install
```

### Installing serve

```bash
npm i serve -g
npm add serve
```

### Installing cypress

```bash
npm install cypress --save-dev
npm install -g @cypress/chrome-recorder
```

## Servers

#### Start

1. Start the server
   ```bash
   serve
   ```
2. Browse to [http://localhost:3000](http://localhost:3000)

#### Start test server

The server must be running locally with test configuration for the
integration tests to pass.

```bash
npm run 3030
```

<!-- npm install cypress --save-dev
npx cypress open -->

## Testing

- Run all cypress tests
  ```bash
  npm run test
  ```
- Run a check
  ```bash
  npx cypress run --spec <FILE PATH>
  ```
