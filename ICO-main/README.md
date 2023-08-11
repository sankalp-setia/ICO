# Initial Coin Offering (ICO)

Enables [BPH NFT holders](https://sepolia.etherscan.io/token/0xe68efffb7cad10c0add9522055c4c9f2ee0e2393#balances) to mint `BPH tokens`([ERC-20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)) on the Sepolia testnet. These tokens empower the [DAO](https://dao-omega-teal.vercel.app/) to create proposals and act on them while allowing the holders to cast their vote. <br />
The project can be viewed [here](https://ico-two-henna.vercel.app/). <br />
The contract can be accessed [here](https://sepolia.etherscan.io/address/0x27357ef37b72726dbd6a15b9f5e9ba9729327fcd). <br />
The BPH Token can be viewed [here](https://sepolia.etherscan.io/token/0x27357ef37b72726dbd6a15b9f5e9ba9729327fcd).

## More Details

The dApp has been deployed on Sepolia Testnet of Ethereum. The backend of the dApp has been created using [Hardhat](https://hardhat.org/) and is available in the [hardhat-tutorial](https://github.com/Tanmay-Bhatnagar-03/ICO/tree/main/hardhat-tutorial) directory. Smart contracts for the project are available in [hardhat-tutorial/contracts](https://github.com/Tanmay-Bhatnagar-03/ICO/tree/main/hardhat-tutorial/contracts) directory and it is written in [Solidity](https://soliditylang.org/). The deployment script for the smart contract is written in [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript). <br />

The frontend of the website has been created by [Next.js](https://nextjs.org/) and deployed on [Vercel](https://vercel.com/). The website automatically sends a prompt to connect your wallet ([MetaMask](https://metamask.io/)) and you are then required to approve the request in the wallet.<br />

The token price is set at `0.001 eth` initially. Only the BPH NFT holders are allowed to mint and claim tokens, and the smart contract has a logic in place for checking the same. Upto 10,000 total BPH tokens can be minted and claimed.<br />

### Follow these steps to mint and claim BPH Tokens:
- Open the [dApp](https://ico-two-henna.vercel.app/)
- Connect your wallet([MetaMask](https://metamask.io/)) and change your network to [Sepolia](https://sepolia.dev/)
- Enter the amount of tokens you would like to mint, click the `Mint Tokens` button and pay the minting cost.
- Upon minting, two buttons appear `Claim Tokens` (to claim minted tokens) and `Withdraw Tokens` (to withdraw your tokens from the [ICO](https://www.investopedia.com/terms/i/initial-coin-offering-ico.asp#:~:text=Initial%20coin%20offerings%20(ICOs)%20are,have%20yielded%20returns%20for%20investors.)). 

## Features (Current and Upcoming)

- [x] The dApp connects to the wallet automatically and checks whether the user is a [BPH NFT holders](https://sepolia.etherscan.io/token/0xe68efffb7cad10c0add9522055c4c9f2ee0e2393#balances).
- [x] Only NFT holders can mint `BPH Tokens` for the collection.
- [x] Project has been deployed on Sepolia and hence, users have to change their network to Sepolia before site can be accessed.
- [x] Upper limit of the total amount of tokens to be minted has been set to `10,000`.
- [x] Simplistic website allows user to interact with the contract hassle-free.
- [ ] Verifying and publishing the contract on [Sepolia Blockchain Explorer](https://sepolia.etherscan.io/).

## Contribution

Feel free to contribute to this project to make it better!

## License

This project has an MIT License.

## Made by love

- [StarterTemplates](https://twitter.com/startertemp)
- [LearnWeb3DAO](https://learnweb3.io)
