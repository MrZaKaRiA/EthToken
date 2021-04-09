# Start creating Token
- Open http://remix.ethereum.org/ and paste the code from Token.sol
- Change the total supply on line 21, default is 10 million: 
      uint256 private constant _tTotal = 10 * 10**6 * 10**9;
- change token name and symbol on lines 25 26 default is Token / TKN
      string private _name = 'Token';
      string private _symbol = 'TKN';
- Compile Token.sol

# Metamask Wallet
- Add metamask Wallet Extention to Chrome browser https://metamask.io/
- Connect MetaMask to Binance Smart Chain https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain
    
    -- Mainnet (This is the one you are probably looking for)
    -Network Name: Smart Chain
    -New RPC URL: https://bsc-dataseed.binance.org/
    -ChainID: 56
    -Symbol: BNB
    -Block Explorer URL: https://bscscan.com

    -- Testnet
    -Network Name: Smart Chain - Testnet
    -New RPC URL: https://data-seed-prebsc-1-s1.binance.org:8545/
    -ChainID: 97
    -Symbol: BNB
    -Block Explorer URL: https://testnet.bscscan.com
    
# Token Deployment and Test
- Go to Deploy, choose Injected Web3 Then Deploy
- Then a gas fees payment window will pop up, if it didn't make sure your opnin remix on http:// not https://
- Test the existance of Token by name on Binance Testnet Explorer https://testnet.bscscan.com
- Copy Token Contract Address
- Add Token to Mestmask wallet by pasting Token Contract Address
- Congratulations, Token can be sent and received by now
