echo "# README.md" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/justinnicolow0/README.md.git
git push -u origin main
import { Magic } from 'magic-sdk';

let magic;

// Construct with an API key:
magic = new Magic('PUBLISHABLE_API_KEY');

// Construct with an API key and locale:
magic = new Magic('PUBLISHABLE_API_KEY', { locale: 'es' });

// Construct with an API key and testMode enabled:
magic = new Magic('PUBLISHABLE_API_KEY', { testMode: true });

// Construct with an API key and defer the loading of the Magic Iframe's assets
magic = new Magic('PUBLISHABLE_API_KEY', { deferPreload: true });

// Construct with an API key plus options:
magic = new Magic('PUBLISHABLE_API_KEY', { network: 'sepolia', endpoint: '...' });

// Construct with API key and custom node options:
const customNodeOptions = {
  rpcUrl: 'https://polygon-rpc.com', // your ethereum, polygon, or optimism mainnet/testnet rpc URL
  chainId: 137 // corresponding chainId for your rpc url
}

magic = new Magic('PUBLISHABLE_API_KEY', { 
  network: customNodeOptions, // connected to Polygon Mainnet!
});npx make-magic \
    --template nextjs-dedicated-wallet \
    --network ethereum \
    --publishable-api-key pk_live_86CAD2AE450E5378 \
    --login-methods EmailOTP --login-methods SMSOTPpk_live_86CAD2AE450E5378sk_live_1EA29A95755D0162⁠npm install magic-sdk
npm i magic-sdk@21.0.0npm i magic-sdk@21.0.0![1000004354](https://github.com/user-attachments/assets/946cfa17-89d1-493b-b3e4-b0281f40ffe0)
# README.md
