# Front-end focused recruitment test

Create a delightful, original, nice-looking, dead-simple, webapp for compound v2.  

Use Next, rainbowkit, tailwind (best if paired with daisyUI components), wagmi.sh, viem.sh if needed (best if its not). Do not query the blockchain directly, use exclusively
[theGraph](https://thegraph.com/hosted-service/subgraph/graphprotocol/compound-v2) with Apollo client for read queries.
Focus on the borrower experience only, not assuming a tech-savy user, the ideal being an app usable by your mother
while being clear enough so she clearly understand what she is doing using it.
As a borrower, I should be able to supply my collateral, borrow cryptos and repay them, while having a clear vue of my position and the terms I'm experiencing. Support only one loan: I'm supplying ETH and borrowing DAI.
Alternatively, you can use the same requirements for [morpho](https://thegraph.com/hosted-service/subgraph/morpho-association/morpho-subgraphs) (morpho-compound / morpho-aave-v2 / morpho-aave-v3) if you prefer.
Fork this repo to implement the app, the app should launch in one command after git clone + dependencies installation.
To make the app usable to test, have it live online, pointing on a testnet or a mainnet dev fork.

Send your repo link when you are finished. Show your knowledge of best practices along the way.
Don't worry if you choke on any part of this test (conception or implementation), but don't stay stuck, [reach out](https://t.me/t0bou) and we will unblock you, or implement what you can and circumvent the part you can't.

The overall quality of security, code clarity, UI/UX etc. matters to us.
