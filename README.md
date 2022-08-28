# Colour Minter

## Installation

First ensure you are in a new and empty directory.

1. Clone repository and navigate to the repo

   ```js
   git clone
   cd NFT-Dapp-Boilerplate
   ```

2. Create .env file and add environment variables, you can refer .env.example file

   ```javascript
   REACT_APP_COLOR_ADDRESS= // Contract address to interact,
   REACT_APP_RPC_URL_1= // Your Infura RPC URL
   REACT_APP_RPC_URL_3= // Your Infura RPC URL
   REACT_APP_POLLING_INTERVAL= // Polling time interval, you can set it to 15000
   REACT_APP_INFURA_KEY= // Your Infura Key

   // Fortmatic Wallet
   REACT_APP_FORTMATIC_API_KEY= // Your Fortmatic Key
   REACT_APP_FORTMATIC_CHAIN_NAME= // Supported Fortmatic Network i.e, ropsten

   // Unstoppable Wallet
   REACT_APP_UNSTOPPABLE_CLIENT_ID= // Your Client Id
   REACT_APP_UNSTOPPABLE_REDIRECT_URI= //Your Redirect URL
   REACT_APP_UNSTOPPABLE_POST_LOGOUT_REDIRECT_URI= // Your Logout Redirect URL

   ```



3. Install dependencies and start project.

   ```javascript
   npm install
   npm run start
   ```

4. To build the application for production, use the build script. A production build will be in the `build` folder.
   ```javascript
   npm run build
   ```
