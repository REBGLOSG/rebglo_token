# Overview
The REBGLO's smart contracts allow investors to buy REB tokens during the its crowdsale event.

# REBGLO token
REBGLO will be powered by the REB token on Ethereum. REB is an ERC20 token, of which a total supply of 10 billion will be issued.
The REB token will be divisible by 18 decimal places to make sure no issues arise when the token value increases.
This is the token contract and specifies the token name, symbol and decimals.
Upon token deployment the token is paused for transfers. This means that the owner is able to create/mint tokens for not to transfer from user to user. 
Note: Token contract ownership needs to be given to crowdsale contract so it is allowed to mint REBGLO token during crowdsale.

There is a function to check user's balance tier. It is called checkBalanceTier. By passing an Ethereum address to this function it returns a string with the address balance tier such as Gold, Platinum, etc.

# Deployed contracts
### Token contract
Address: 0x61383Ac89988B498dF5363050ff07fE5C52ecDDA

URL: https://etherscan.io/address/0x61383ac89988b498df5363050ff07fe5c52ecdda

### Crowdsale contract
Address: 0x4D0269b1898bEE6aA94F54D1724F9862aAbdd010

URL: https://etherscan.io/address/0x4d0269b1898bee6aa94f54d1724f9862aabdd010
