In order to streamline the review of the contribution we ask you
to ensure the following steps have been taken:

1. Create a folder under `/tokens`, the folder name is your token symbol in the `lowercase` format

2. Upload your logo in your folder

- [ ] Filename in the `uppercase` format with suffix
- [ ] Image format: `png`
- [ ] Image size: `256 by 256 px`

3. Upload a json file for additional info. File name is your token symbol in the `uppercase` format with suffix

* `asset` must be your token's symbol
* `assetMap` must be your token's symbol without suffix
* `market` must be `ALTS` or `FIAT`. It determines which market the pair will be listed in when this token is the quote symbol.
* `display`'s default value is `true`, which means the information will be available in the explorer

The following contacts are supported in `contact`:
* Twitter
* Facebook
* Reddit
* Instagram
* Medium
* Steemit
* Coinmarketcap
* Binance Info
* Youtube
* Telegram
* Discord
* Linkedin
* Github
* Binance Research

> Note: you must use the right key name

Example:

```json
{
  
  "asset":"ANK-5D8M",
"assetMap":"ANK",
"market": "ALTS",
"officialSiteUrl":"https://5dd9b81c0890c.site123.me/",
"contactEmail":"applenetwork@mail.com",
"display":true,
"contact":{
"Twitter":"https://twitter.com/Applenetwork4",
"Facebook":"https://www.facebook.com/apple.ank.315",
"Coinmarketcap":"https://coinmarketcap.com/currencies/apple-network/",
"Telegram":"https://t.me/AppleNetwork4/",
"LinkedIn":"https://www.linkedin.com/in/ank-apple-547773199/",


    }
}

```
