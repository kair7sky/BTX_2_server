# Snake Game Leaderboard Smart Contract

Welcome to the Snake Game Leaderboard smart contract project! This project maintains a ranked list of players based on their final scores in the Snake game. The smart contract is designed to ensure secure and accurate ranking, providing a seamless gaming experience.

# Screenshots
![image](https://github.com/kair7sky/BTX_2_server/assets/118976474/84523a83-0f30-49c7-91f7-4eb564680ec7)
![image](https://github.com/kair7sky/BTX_2_server/assets/118976474/cb04c52e-d735-4149-9f90-868ef4838579)
![image](https://github.com/kair7sky/BTX_2_server/assets/118976474/ba2ceae4-74eb-41a8-b605-a10f0d61ecc1)
![image](https://github.com/kair7sky/BTX_2_server/assets/118976474/7e68c48f-9087-4d87-b14b-4adcd1af8bc8)


## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The Snake Game Leaderboard smart contract is developed to maintain a ranked leaderboard of players based on their scores in the Snake game. The contract ensures security and correctness through extensive unit testing, identifying potential vulnerabilities and verifying expected behaviors under various game scenarios.

## Features

- Maintain a ranked leaderboard of players.
- Securely store and update player scores.
- Retrieve the top players and their scores.
- Connect with a wallet for player authentication.
- Different difficulty levels (Easy, Medium, Hard) affecting scores.

## Getting Started

To get a local copy of the project up and running, follow these steps.

### Prerequisites

- Node.js and npm
- Hardhat
- Git
- Metamask or any other Ethereum wallet

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/snake-game-leaderboard.git
    ```
2. Navigate to the project directory:
    ```sh
    cd snake-game-leaderboard
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Usage

1. Compile the smart contract:
    ```sh
    npx hardhat compile
    ```
2. Deploy the smart contract to a local network:
    ```sh
    npx hardhat node
    npx hardhat run scripts/deploy.js --network localhost
    ```
3. Open the game interface by navigating to the `index.html` file in your browser or start a local server to host the game.

### Connect Wallet

To interact with the smart contract, you need to connect your Ethereum wallet (e.g., Metamask) to the application.

### Select Level

Choose a difficulty level (Easy, Medium, Hard) to start playing the game. Your score will be submitted to the leaderboard once the game ends.

## Testing

Unit testing is crucial for ensuring the security and functionality of the smart contract.

1. Run the tests:
    ```sh
    npx hardhat test
    ```

The unit tests cover various scenarios, including:

- Adding a new score.
- Updating an existing score.
- Retrieving the top players.
- Ensuring security and preventing unauthorized access.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
