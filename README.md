# polygon-buidl-it-summer-2022-summary

## Play

Fishin Friends and Cozy Islands 

Judges please contact Zoogie via DMs or email (zoogie@cozylabs.xyz, personal email on devpost, or @ZoogieNFT on twitter) for a free Cozy Penguin or to schedule a live demo.

Cozyland:

- Go to cozyland-staging.cozyverse.xyz
- click the "mint" button
- connect to metamask and mumbai testnet
- click the "0E" button to mint a land of your choice
- click on the land to redirect to staging.cozyverse.xyz/land
- Make sure you are logged in with an NFT first via staging.cozyverse.xyz
- Go play or configure your land! If you need items, claim some free ones in staging.cozyverse.xyz/shop

Cozy Fishing
- Make sure you are logged in with an NFT first via staging.cozyverse.xyz
- Go to staging.cozyverse.xyz/game/2
- If you need items, claim a bundle in staging.cozyverse.xyz/shop


## Code
Below are relevant areas of our code base that was built during the hackathon

### Fishin Frens

- [Game contracts](https://github.com/CozyReef/cozyverse/tree/main/contracts/src/games) - Biomes (region), Costmetics, and World contracts
- [Game UI](https://github.com/CozyReef/cozyverse/tree/main/app/src/scenes/Game2) - Frontend code to render Fishin Frens

### Cozy Islands

- [CozyIsland contract](https://github.com/CozyReef/cozyverse/blob/dev/contracts/src/land/CozyIsland.sol) - Cozy Island NFT contract
- [CozyIsland Personalization contract](https://github.com/CozyReef/cozyverse/blob/dev/contracts/src/land/CozyIslandPersonalization.sol) - Decorating your island with Cozyverse items
- [CozyLand recipes](https://github.com/CozyReef/cozyverse/blob/dev/contracts/src/land/CozyIslandRecipes.sol) - Combining land plots
- [CozyLand UI](https://github.com/CozyReef/cozyland) - Minting site
- [Cozyverse land](https://github.com/CozyReef/cozyverse/tree/dev/app/src/pages/land) - In game UI

### Store

- [Cozy Store](https://github.com/CozyReef/cozyverse/blob/dev/contracts/src/store/PermanentStore.sol) - Permanent storefront to mint basic items for Cozy Land
- [Cozy Store UI](https://github.com/CozyReef/cozyverse/tree/dev/app/src/scenes/Shop) - Permanent item store was built during the hackthon, allowlist was built beforehand

### Infrastructure

- [Terraform](https://github.com/CozyReef/infrastructure/commit/56f4f0904a74cd1e4151db269f2b9cb9b80635ad) - Terraform the Cozy Land minting site to AWS. Deploys managed via github action
