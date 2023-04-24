# On-chain NFT with Metadata

NFT Contract Address: https://mumbai.polygonscan.com/address/0xa6051e1975A656054F93926FD02699ddd5716890

Functions:

1) Mint an NFT
2) Train NFT to level up

Example NFT: https://testnets.opensea.io/assets/mumbai/0xa6051e1975a656054f93926fd02699ddd5716890/1

<img width="1830" alt="Screenshot 2023-04-24 at 4 41 24 PM" src="https://user-images.githubusercontent.com/29926698/233944870-edd42648-829d-4f74-aeed-4f448334c69d.png">

Further improvements:

At the moment we're only storing the level of our NFTs, we can try to substitute the current tokenIdToLevels[] mapping with a struct that stores:

- Level
- Speed
- Strength
- Life
