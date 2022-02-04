# ShibaWallet Token Assets
List your crypto tokens & info on multi-chains acting upon ShibaWallet app 

<br/>

- [English Doc.](#EnglishDoc) <br/>
- [Deutsche Dokumentation](#GermanDoc) <br/>
- [हिंदी दस्तावेज़ीकरण](#HindiDoc) <br/>
- [Bahasa Indo](#IndonesianDoc) <br/>
- [한국어](#KoreanDoc) <br/>

Any issues by sending email to support@shibawallet.cc

<br/>

# <a name="EnglishDoc"></a> 6-Step To Add Logo
- [1.] Fork the Github repository

- [2.] Create folder with name of token smartcontact address in **CHECKSUM** format `bsc/<token_smartcontract_address>/`.

- [3.] Tell your designer that token image must be in PNG format, avoid transparent background, recommended size 256x256px, with max file size of 100kB.

- [4.] Upload your logo with file named `logo.png` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `bsc/<token_smartcontract_address>/logo.png`

- [5.] Create a file with name `info.json` inside the folder `bsc/<token_smartcontract_address>/`, and edit your token information

- [6.] On your forked `token-assets` repo, submit your changes above mentioned firstly, and then create a pull request to the main repo.

- Optionally, it's a good suggestion that comment on the Pull Request, how many tokens (depending your choice, any amount is okay) you'd like to airdrop to the community users so that you can get more followers/group-members.


<br/>

### Info.json Specification

Take the token `SHWA` for example, the content of file `info.json` as below shown:
```
{
    // Your token - smart contract address CHECKSUM
    "id": "0x7B8274CcECD5BBCFe18958C3dB6471C5E3e1FBbf",  

    // The type of your contract
    "type": "BEP20",

    // The name of your token
    "name": "ShibaWallet",

    // The symbol of your token
    "symbol": "SHWA",

    // The decimal places of your token
    "decimals": 18,

    // The token explorer url
    "explorer": "https://bscscan.com/address/0x7b8274ccecd5bbcfe18958c3db6471c5e3e1fbbf",

    // The current status of the token project: in-development, active, suspension
    "status": "active",

    // The token official website
    "website": "https://shibawallet.cc",

    // The token logo with pixel size [ 256px * 256px ], up to file size that's under 100kB. 
    // The url preferred to be hosting on IPFS or Arweave or Storej
    "logourl": "https://bafkreibyqzxcnxqdcnhf2d2zeywja4frpi4jkdxzauqmtez3xmub7angz4.ipfs.dweb.link",

    // The description of your token (preferred to be under 150 length)
    "description": "ShibaWallet is a decentralized wallet for unified all your NFT artworks and meme crypto coins in one app, self-governance and non-custodial entirely.",

    // The social accounts/platforms that the token has been operating all the time
    "socials": [
        {
            "name": "Twitter",
            "url": "https://twitter.com/ShibaWalletPro"
        },
        {
            "name": "Medium",
            "url": "https://shibawallet.medium.com/"
        },
        {
            "name": "Telegram Channel",
            "url": "https://t.me/ShibaWalletPro"
        },
        {
            "name": "Telegram Group",
            "url": "https://t.me/ShibaWalletPro_Official"
        },
        {
            "name": "Discord",
            "url": "https://discord.gg/QqPgzVHyZb"
        },
        {
            "name": "Github",
            "url": "https://github.com/ShibaWallet"
        }
    ]
}
```



