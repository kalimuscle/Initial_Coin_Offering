This project demonstrates how create an ICO in Ethereum. Tes network: Goerli and localnetwork

Try running some of the following tasks:

Backend

npm install

If you using local network

npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
if using Goerli network - npx hardhat run scripts/deploy.js --network goerli

Frontend

npm install

Update filee /constants/index.js

npm run dev