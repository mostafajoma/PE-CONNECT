# Singing Pig Capital      
![N|Solidity](https://static-s.aa-cdn.net/img/ios/1246087548/aa4ec7698dc9740e026aa5fe06815e62?v=1)

## Breakdown

The core goals of the project are to:
- Develop a fundraising mechanism for a proxy/dummy private equity fund in the form of a tokenized crowdsale on an ethereum blockchain network, in which a fixed number of tokens represent a fraction of the total value of the fund (primary market). E.g. if we had a $500M fundraising target and minted 50M tokens, each token would be worth $10 at inception. 
- Develop a mechanism for trading these tokens between investors via smart contracts (secondary market). 
- Develop a mechanism for the value of these tokens to float in response to the fund’s performance (we will use a PE index as a proxy for our fund’s performance). 
- Stretch goal to have the token market price respond to the output of some sort of asset pricing model,  supply/demand factors, expected returns from ML projections, etc. 
- We probably don’t want too much variation  in the value of the coin
- Determine how we would like these tokens to behave as a security - i.e. do we want them to have dividends, a large principal payout at fund termination, etc.? - and develop both the logic and mechanism for coordinating these payouts.

## Technologies
![N|Solidity](https://hackernoon.com/hn-images/1*6hFbv6Q21jOuBbpVRtmnDg.png)

### Solidity for minting tokens, defining token behavior, and smart contracts

![N|Python](https://awaywithideas.com/wp-content/uploads/2019/10/Python.svg_-e1571602766898.png)   ![N|ML](https://cdn.iconscout.com/icon/premium/png-256-thumb/machine-learning-23-911028.png)

### Python SciKit LSTM machine learning models for token price forecasting 


![N|Metamask](https://walletconnect.org/static/metamask-69ce6b56bbc9953dfb4aecebdf88729b.png)
### Ganache for ethereum account / wallet creation 
### Metamask for simulating trades + payouts





[![N|Solid](https://img.icons8.com/bubbles/2x/github.png)](https://github.com/mostafajoma/project-3.git)
