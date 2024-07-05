# PUMP SNIPER & CRACKER

## Description
Solana tool to buy the latest coins on Pump.Fun as well as the King of The Hill coins. Set your intended profit % to automatically sell once reached. Custom RPC support. Simply add your private key, the RPC you wish to use, and you're ready to go.

## Prerequisites
- Ensure you have the necessary permissions to execute files on your operating system.

## Setup

1. **Environment Variables**:
   - Rename `.env.template` to `.env`.
   - Open `.env` and fill in your `RPC_ENDPOINT` and `PRIVATE_KEY`.

     ```env
     RPC_ENDPOINT=your_rpc_endpoint_here
     PRIVATE_KEY=your_private_key_here
     ```

2. **Configuration Files**:
   - Ensure `settings.json` and `buyHistory.json` are in the same directory as the executable.

## Running the Tool

- For Windows:
  1. Open a Command Prompt.
  2. Navigate to the directory containing the executable.
  3. Run the executable: `pump_fun.exe`

- For macOS/Linux:
  1. Open a Terminal.
  2. Navigate to the directory containing the executable.
  3. Run the executable: `./pump_fun`

## Notes
- Ensure your `.env` file is kept secure and not shared with anyone.
- The tool writes to `settings.json` and `buyHistory.json` to store your settings and purchased coin data.

