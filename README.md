# buildspace Solana NFT Drop Project
### Welcome 👋
To get started with this course, clone this repo and follow these commands:

1. cd into the `app` folder
2. Run `npm install` at the root of your directory
3. Run `npm run start` to start the project
4. Start coding!

### What is the .vscode Folder?
If you use VSCode to build your app, we included a list of suggested extensions that will help you build this project! Once you open this project in VSCode, you will see a popup asking if you want to download the recommended extensions :).

### My Notes:  
1. Set up the web app and build a connect function to the _Phantom Wallet_ in `App.js`. 
2. Install the pre-reqs: 
```
git version
> git version 2.31.1 (or higher!)

node --version
> v14.17.0 (or higher, below v17 -- we found that node v16 works best)

yarn --version
> 1.22.11 (or higher!)

ts-node --version
> v10.2.1 (or higher!)
```
3. If any of these commands are not found, please make sure to install it before moving on. 
4. Be sure to install `ts-node` globally: 
   `npm install -g ts-node`
5. Install Solana. See https://docs.solana.com/cli/install-solana-cli-tools
6. After Solana is installed, do the following: 
```
solana --version

// Run these commands separately
solana config set --url https://api.devnet.solana.com
solana config get
```

It will output something like this: 
```
Config File: /Users/flynn/.config/solana/cli/config.yml
RPC URL: https://api.devnet.solana.com
WebSocket URL: wss://api.devnet.solana.com/ (computed)
Keypair Path: /Users/flynn/.config/solana/id.json
Commitment: confirmed
```
7. Install _Metaplex CLI_
8. Create the NFTs collection. 
9. Deploy your NFTs to Solana's Devnet and upload to Arweave. 
10. Verify NFTs. 
11. Deploy candy machine to Metaplex's contract.
12. Set drop date.
13. Call your candy machine from your web app.
14. Set up you .env variables and change the network to devnet in the Phantom wallet.      


### Questions?
Have some questions make sure you head over to your [buildspace Dashboard](https://app.buildspace.so/projects/CO77556be5-25e9-49dd-a799-91a2fc29520e) and link your Discord account so you can get access to helpful channels and your instructor!

