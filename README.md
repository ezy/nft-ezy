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

You can run the app in rinkeby with `npm run rinkeby`.

You can run the app in ropsten with `npm run ropsten`.

Don't forget to add funds using:

https://faucet.rinkeby.io
https://faucet.ropsten.be

Tutorial at https://forum.openzeppelin.com/t/migrations-transaction-could-not-be-decoded-could-not-recover-secp256k1-key-calculated-rx-is-larger-than-curve-p/6405/6