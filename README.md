# sepolia-agent
Sepolia poweragent for use without dappnode

To install, perform the following:
1. Clone the directory
2. Upload your config into the config directory, setting RPC to your RPC of choice, and admin and keeper addresses to your own. 
3. Run `npm i`
4. Run `node jsongen.js ${YOUR_WORKER_PRIVATE_KEY} ${PASSWORD_OF_YOUR_CHOOSING}`
5. Run docker compose up -d in the command line. 
