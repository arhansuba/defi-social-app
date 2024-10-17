# DeFi Social App

A decentralized social media application with DeFi features, built on Internet Computer and Stacks.

## Features

- Create and view social media posts
- View STX token balance
- Stake STX tokens

## Prerequisites

- Node.js (v14 or later)
- dfx (Internet Computer SDK)
- Stacks wallet (for interacting with Stacks blockchain features)

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/arhansuba/defi-social-app.git
   cd defi-social-app
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory and add your canister ID:
   ```
   REACT_APP_CANISTER_ID=your_canister_id_here
   ```

4. Start the Internet Computer local replica:
   ```
   dfx start --background
   ```

5. Deploy the canister:
   ```
   dfx deploy
   ```

6. Start the React development server:
   ```
   npm start
   ```

7. Open your browser and navigate to `http://localhost:3000`

## Development

- The `src/components` directory contains React components
- The `src/services` directory contains services for interacting with Internet Computer and Stacks
- Modify `src/App.js` to change the main application structure

## Deployment

To deploy to the Internet Computer mainnet, follow the dfx deployment guide in the Internet Computer documentation.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.# defi-social-app
