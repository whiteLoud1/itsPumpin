# PUMP SNIPER & CRACKER

## Description
This version: Free Tier: Snipe coins, fast buy koth, set buy sell percentage, check socials mint freeze auth, custom rpc endpoint and priv key management local (no trusting random servers). 
DM for a PRO version: faster snipes, mev protect, better api's for socket listening, copy trade faster, buy from multiple wallets and more.

## Prerequisites
- Ensure you have the necessary permissions to execute files on your operating system.
- Install Node Js and npm for your machine

## Setup

1. **Environment Variables**:
   - Rename `env.template` to `.env`. If you face issues with the env file,just set the `CUSTOM_RPC_URL & PRIVATE_KEY` in the json file manually and run
   - Ensure you install node js on your computer + npm (if you have the node modules folder, then npm is optional)
   - Open `.env` and fill in your `RPC_ENDPOINT` and `PRIVATE_KEY`.

     ```env
     RPC_ENDPOINT=your_rpc_endpoint_here
     PRIVATE_KEY=your_private_key_here
     ```

2. **Configuration Files**:
   - Ensure `settings.json` and `buyHistory.json` are in the same directory as the executable.

## Running the Tool
- `npm install` in the directory to get the modules and dependencies
- `npm start` to start the tool
Alternatively you can run: `node pump_fun.js` to run the tool as well but you will need the node modules

## Notes
- Ensure your `.env` file is kept secure and not shared with anyone.
- The tool writes to `settings.json` and `buyHistory.json` to store your settings and purchased coin data.

