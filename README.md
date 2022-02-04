# ShibaWallet Token Assets
List your crypto tokens & info on multi-chains acting upon ShibaWallet app 

<br/>

- 1.[English Doc.](#EnglishDoc) <br/>
- 2.[Deutsche Dokumentation](#GermanDoc) <br/>
- 3.[हिंदी दस्तावेज़ीकरण](#HindiDoc) <br/>
- 4.[Bahasa Indo](#IndonesianDoc) <br/>
- 5.[한국어](#KoreanDoc) <br/>


<br/>

# <a name="EnglishDoc"></a> 6-Step To Add Logo
- [1.] Fork the Github repository

- [2.] Create folder with name of token smartcontact address in **CHECKSUM** format `bsc/<token_smartcontract_address>/`.

- [3.] Tell your designer that token image must be in PNG format, avoid transparent background, recommended size 256x256px, with max file size of 100kB.

- [4.] Upload your logo with file named `logo.png` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `bsc/<token_smartcontract_address>/logo.png`

- [5.] Create a file with name `info.json` inside the folder `bsc/<token_smartcontract_address>/`, and edit your token information

- [6.] On your forked `token-assets` repo, submit your changes above mentioned first, and then create a pull request to the main repo

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
            "name": "Github",
            "url": "https://github.com/ShibaWallet"
        }
    ]
}
```


<br/>
<br/>

=============================================================================

<br/>
<br/>


# <a name="GermanDoc"></a> 6-Schritte zum Hinzufügen eines Logos
- [1.] Forken Sie das Github-Repository

- [2.] Erstellen Sie einen Ordner mit dem Namen der Token-Smartcontact-Adresse im **CHECKSUM**-Format `bsc/<token_smartcontract_address>/`.

- [3.] Sagen Sie Ihrem Designer, dass das Token-Bild im PNG-Format vorliegen muss, transparenten Hintergrund vermeiden, empfohlene Größe 256 x 256 Pixel, mit einer maximalen Dateigröße von 100 KB.

- [4.] Laden Sie Ihr Logo mit der Datei „logo.png“ in den zuvor erstellten Ordner mit der Smartcontract-Adresse hoch, und wenn Sie alles richtig gemacht haben, sollte Ihr Pfad so aussehen. `bsc/<token_smartcontract_address>/logo.png`

- [5.] Erstellen Sie eine Datei mit dem Namen „info.json“ im Ordner „bsc/<token_smartcontract_address>/“, und bearbeiten Sie Ihre Token-Informationen

- [6.] Reichen Sie in Ihrem gegabelten „Token-Assets“-Repo zuerst Ihre oben genannten Änderungen ein und erstellen Sie dann eine Pull-Anforderung an das Haupt-Repo

<br/>

### Info.json-Spezifikation

Nehmen Sie zum Beispiel das Token `SHWA`, den Inhalt der Datei `info.json` wie unten gezeigt:
```
{
    // Ihr Token - Smart-Contract-Adresse PRÜFSUMME
    "id": "0x7B8274CcECD5BBCFe18958C3dB6471C5E3e1FBbf",  

    // Die Art Ihres Vertrages
    "type": "BEP20",

    // Der Name Ihres Tokens
    "name": "ShibaWallet",

    // Das Symbol Ihres Tokens
    "symbol": "SHWA",

    // Die Dezimalstellen Ihres Tokens
    "decimals": 18,

    // Die Token-Explorer-URL
    "explorer": "https://bscscan.com/address/0x7b8274ccecd5bbcfe18958c3db6471c5e3e1fbbf",

    // Der aktuelle Status des Token-Projekts: in Entwicklung, aktiv, ausgesetzt
    "status": "active",

    // Die offizielle Token-Website
    "website": "https://shibawallet.cc",

    // Das Token-Logo mit einer Pixelgröße von [ 256px * 256px ] bis zu einer Dateigröße von unter 100 KB.
    // Die URL sollte bevorzugt auf IPFS oder Arweave oder Storej gehostet werden
    "logourl": "https://bafkreibyqzxcnxqdcnhf2d2zeywja4frpi4jkdxzauqmtez3xmub7angz4.ipfs.dweb.link",

    // Die Beschreibung Ihres Tokens (bevorzugt unter 150 Länge)
    "description": "ShibaWallet is a decentralized wallet for unified all your NFT artworks and meme crypto coins in one app, self-governance and non-custodial entirely.",

    // Die sozialen Konten/Plattformen, die der Token die ganze Zeit betrieben hat
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
            "name": "Github",
            "url": "https://github.com/ShibaWallet"
        }
    ]
}
```

<br/>
<br/>

=============================================================================

<br/>
<br/>

# <a name="HindiDoc"></a> लोगो जोड़ने के लिए 6-कदम
- [1.] गीथूब भंडार कांटा

- [2.] **CHECKSUM** प्रारूप `bsc/<token_smartcontract_address>/` में टोकन स्मार्ट संपर्क पते के नाम से फ़ोल्डर बनाएं।

- [3.] अपने डिजाइनर को बताएं कि टोकन छवि पीएनजी प्रारूप में होनी चाहिए, पारदर्शी पृष्ठभूमि से बचें, अनुशंसित आकार 256x256px, अधिकतम फ़ाइल आकार 100kB के साथ।

- [4.] अपने लोगो को `logo.png` नाम की फ़ाइल के साथ स्मार्ट अनुबंध पते के साथ पहले बनाए गए फ़ोल्डर में अपलोड करें, और यदि आपने सब कुछ सही ढंग से किया है तो आपका पथ इस तरह दिखना चाहिए। `बीएससी/<token_smartcontract_address>/logo.png`

- [5.] फ़ोल्डर `bsc/<token_smartcontract_address>/` के अंदर `info.json` नाम से एक फ़ाइल बनाएं, और अपनी टोकन जानकारी संपादित करें

- [6.] अपने फोर्कड `टोकन-एसेट्स` रेपो पर, पहले ऊपर बताए गए अपने परिवर्तन जमा करें, और फिर मुख्य रेपो के लिए एक पुल अनुरोध बनाएं

<br/>

### Info.json विशिष्टता

उदाहरण के लिए टोकन `SHWA` लें, फ़ाइल `info.json` की सामग्री जैसा कि नीचे दिखाया गया है:
```
{
    // आपका टोकन - स्मार्ट अनुबंध पता CHECKSUM
    "id": "0x7B8274CcECD5BBCFe18958C3dB6471C5E3e1FBbf",  

    // आपके अनुबंध का प्रकार
    "type": "BEP20",

    // आपके टोकन का नाम
    "name": "ShibaWallet",

    // आपके टोकन का प्रतीक
    "symbol": "SHWA",

    // आपके टोकन के दशमलव स्थान
    "decimals": 18,

    // टोकन एक्सप्लोरर यूआरएल
    "explorer": "https://bscscan.com/address/0x7b8274ccecd5bbcfe18958c3db6471c5e3e1fbbf",

    // टोकन परियोजना की वर्तमान स्थिति: विकास में, सक्रिय, निलंबन
    "status": "active",

    // टोकन आधिकारिक वेबसाइट
    "website": "https://shibawallet.cc",

    // 100kB से कम फ़ाइल आकार तक पिक्सेल आकार [ 256px * 256px ] के साथ टोकन लोगो।
    // URL को IPFS या Arweave या Storej पर होस्ट करना पसंद है
    "logourl": "https://bafkreibyqzxcnxqdcnhf2d2zeywja4frpi4jkdxzauqmtez3xmub7angz4.ipfs.dweb.link",

    // आपके टोकन का विवरण (150 लंबाई से कम होना पसंद किया जाता है)
    "description": "ShibaWallet is a decentralized wallet for unified all your NFT artworks and meme crypto coins in one app, self-governance and non-custodial entirely.",

    // सामाजिक खाते/प्लेटफ़ॉर्म जो टोकन हर समय संचालित होते रहे हैं
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
            "name": "Github",
            "url": "https://github.com/ShibaWallet"
        }
    ]
}
```



