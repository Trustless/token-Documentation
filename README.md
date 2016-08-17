# Trustless - Token Management for Humans

Token Management Information System (TMIS)

Trustless TMIS provides an Ethereum user an open source standard system for trustlessly minting, monitoring, or manipulating any number of approved tokens in exchange for ether. This code heavily borrows from code originating from ConsenSys, Ethereum, Slock and others leading the development of Ethereum token solutions.

## [Token Factory] (https://github.com/Trustless/Factory)

Trustless Token Factory is built to be Ethereum token minting-as-a-service residing completely on the blockchain, yet will be one of the services which can be accessibly managed via a graphical user interface. 

Tokens can be used in a variety of creative and perhaps even innovative ways. Tokens and 'token data sets' could be used to fulfill a diverse set of various requirements including but not limited to assigning permissions, recognizing achievements or even storing value. 

With strategic use of standard functions we forsee early relational database capability. For this reason our factory will consider Create, Read, Update and Destroy methods upon deployment of their tokens.  

### [Token Templates] (https://github.com/Trustless/Factory/tree/master/Token_Contracts/contracts)

Trustless Token Templates is a github repository which include libraries and components slated to build tokens derived from [EIP #20 Standard Tokens] (https://github.com/ethereum/EIPs/issues/20) such as the original token template: [StandardToken.sol] (https://github.com/Trustless/Factory/blob/master/Token_Contracts/contracts/StandardToken.sol).

### Token Registry

Trustless Token Registry is eluded to in [EIP #22 Standard Token Registries] (https://github.com/ethereum/EIPs/issues/22) which are based on blockchain-side namespaces. 

Tokens generated by a Token Factory can automatically register via that Factory's Registry. This saves time, reduces errors, and accomodate other human friendly features such as automated Accounting. However, Trustless Tokens not deployed in this manner may be registered by way of bytecode verification (expensive).

## [Token Wallet] (https://github.com/Trustless/Wallet)

Trustless Token Wallet is a GUI (graphical user interface) which offer intuitive human interaction with the Token Accounting, Token Factory and Token Trading functions.

### Token Accounting

Trustless Token Accounting is essentially a top-level Token Registry for reporting on any number of registries, monitoring every assortment of tokens, and accessing their metadata. Accounting will allow the TMIS to automatically populate a user's Wallet with all the "Trustless" Tokens the user holds.

### [Token Trading] (https://github.com/Trustless/Trading)

Trustless Token Trading (TTT) will allow buys and sells to be made as well using the ether market as a baseline value rating systems for the tokens held in managed accounts. Essentially tokens you are selling will also be the preferred tokens spent and the tokens you are seeking become the tokens you prefer to recieve for any trades. All the Buy and Sell orders deployed by the users of the network work double-time as the actual trading marketplace they are participating in.

## Token Trust

Trustless Token Trust is a decentralized autonomous organization operating to accumulate wealth and value by collecting Ethereum tokens. Proposals typically will request a sendout to a Token Factory or some crowdsale already deployed, with bytecode validated, the token Registered and Accounted for. 

### Liquid Democracy
