# DMarket
A decentralized marketplace on Ethereum

How to run DMarket
1. Mongodb
- Go to mongodb install folder
- Run cmd -> mongod

2. Ipfs
- Go to ipfs folder
- Run cmd -> ipfs daemon

3. Ganache-cli
- Run cmd -> ganache-cli

4. Deploy smartcontract
- Go to project folder
- Run PowerShell 
    -> truffle migrate --reset
    -> truffle exec seed.js

5. Start server
- Go to project folder
- Run cmd
    -> node server.js or node_modules\.bin\nodemon server.js

6. Run webapp
- Go to project folder
- Run cmd
    -> npm run dev