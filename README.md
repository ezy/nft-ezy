# To develop

- `npm run develop`
- In truffle:
    - `migrate`
    - `nft = await ERC721PresetMinterPauserAutoId.deployed()` to gen contract
    - `await nft.name()`
    - `await nft.symbol()`
    - `await nft.baseURI()`
    - `await nft.mint("0x0445c33bdce670d57189158b88c0034b579f37ce")`
    - `await nft.ownerOf(0)`