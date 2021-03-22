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

Generate the secrets file using `npm run genSecret`.
Generate a mnemonic phrase using `npm i genWords`

Add the mnemonic to your secrets.json file with your `alchemyApiKey` from https://dashboard.alchemyapi.io/apps.