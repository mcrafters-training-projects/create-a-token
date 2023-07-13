# ETH Beginner course: Create a token

This is a Smart Contract which simullates that creation of a new token on Ethereum Blockchain using Solidity.

## Description

The Smart Contract has variables such as `tokenName`, `tokenAbbreviation` to identify the token and `totalSupply` to keep track of the number tokens in supply. \
There is a mapping called `tokenMapping` that keeps track of which address holds what amount of tokens. \
The initial supply is set to 6023, which is increased/decreased on calling the `mint()` or `burn()` functions.

## Getting Started

### Installing

There is no need to install any tools or software as the Smart Contract can be compiled and tested on an online IDE knowm as Remix IDE.

### Executing program

- Create a new .sol file from the file manager at the left side.
- View `newToken.sol` code from this repo and copy it to the .sol file you just created.
- From the compile tab, click Compile Contract, the code should compile without errors.
- Open the deploy tab and click deploy smart contract.
- The contract should now be deployed and you can access its functions of the left pane.


## Authors

[Ankush Singh](https://ankushKun.github.io)


## License

This project is licensed under the [GNU GPL] License
