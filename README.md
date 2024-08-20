# NFT_auctioneer_pro
Decentralized NFT marketplace with auction support, dynamic pricing, and reentrancy protection.
NFT Auctioneer Pro is an advanced smart contract for a decentralized NFT marketplace that allows users to sell their NFTs through listings or auctions. The contract is built on BNB Chain and supports the ERC-721 standard.

This project is designed to provide a convenient and secure platform for trading NFTs, with auction and dynamic pricing capabilities. It allows users to maximize the value of their NFTs while ensuring fairness and transparency in the trading process.

What functions can it perform?

NFT Listing: Users can list their NFTs for sale at a fixed price.
Auction: Users can create auctions where others can place bids on NFTs. Auctions support dynamic time extensions if bids are placed in the last few minutes.
Cancellation: Sellers can cancel listings or auctions before they are finalized.
Security: The contract includes built-in reentrancy protection and other mechanisms to prevent abuse.
How to work with it?

Listing: Users can list their NFTs for sale by specifying the desired price.
Auction: Users can start auctions by setting a starting price and duration.
Bidding: Other users can place bids on the auctions.
Completion: After the auction ends, the NFT is transferred to the winner, and the seller receives the funds minus the platform fee.
Cancellation: If needed, a seller can cancel a listing or auction before it ends.
