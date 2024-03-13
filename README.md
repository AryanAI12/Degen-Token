# Degen-Token

 A unique token for Degen Gaming Studio to reward players and enhance their gaming experience using the Avalanche blockchain. 🛒 Players can redeem tokens for various items, transfer tokens, and burn tokens through the Degen Mart website.

# Introduction
The Degen Gaming Token (DGN) is a custom ERC20 token designed for Degen Gaming Studio. It enables players to earn rewards while playing the game and transfer or redeem these tokens for various items on the dengen mart webiste.

# Website Details
The Degen Gaming website allows you to redeem tokens for special items, transfer DGN tokens to other accounts, and burn tokens for removal. It provides a seamless experience for managing and utilizing your DGN tokens within the game ecosystem.

# Contract Details
The DegenToken contract is implemented in Solidity version 0.8. It inherits from the IERC20 interface, providing standard ERC20 functionality. The contract has the following features:

1.Token name: DegenToken
2.Token symbol: DGN
# Token Functionality
1.totalSupply(): Returns the total supply of DegenTokens.
2.balanceOf(address account): Returns the token balance of the specified account.
3.transfer(address to, uint256 value): Transfers tokens from the sender's account to the specified recipient.
4.burn(uint256 value): Burns tokens from the sender's account, reducing the total supply.
5.mint(address to, uint256 value): Mints new tokens and assigns them to the specified recipient. Only the contract owner can perform this operation.
6.getPurchases(address account): Retrieves the list of purchases made by the specified account.
7.redeem(string memory itemName, uint256 value): Allows the sender to redeem tokens for an item in the in-game store.
8.allowance(address owner, address spender): Returns the amount of tokens that the spender is allowed to spend on behalf of the owner.
9.approve(address spender, uint256 value): Approves the spender to transfer a specific amount of tokens from the sender's account.
10.transferFrom(address from, address to, uint256 value): Transfers tokens from one address to another on behalf of a specified address.
