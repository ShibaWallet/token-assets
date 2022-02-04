# ShibaWallet Token Assets
Listen Sie Ihre Krypto-Token und Informationen zu Multi-Chains auf, die auf der ShibaWallet-App wirken

<br/>

- [English Doc.](https://github.com/ShibaWallet/token-assets/) <br/>
- [Deutsche Dokumentation](https://github.com/ShibaWallet/token-assets/blob/main/README-German.md) <br/>
- [हिंदी दस्तावेज़ीकरण](https://github.com/ShibaWallet/token-assets/blob/main/README-Hindi.md) <br/>
- [Bahasa Indo](https://github.com/ShibaWallet/token-assets/blob/main/README-Indonesian.md) <br/>
- [한국어](https://github.com/ShibaWallet/token-assets/blob/main/README-Korean.md) <br/>

Bei Problemen senden Sie eine E-Mail an support@shibawallet.cc

<br/>

# <a name="GermanDoc"></a> 6-Schritte zum Hinzufügen eines Logos
- [1.] Forken Sie das Github-Repository

- [2.] Erstellen Sie einen Ordner mit dem Namen der Token-Smartcontact-Adresse im **CHECKSUM**-Format `bsc/<token_smartcontract_address>/`.

- [3.] Sagen Sie Ihrem Designer, dass das Token-Bild im PNG-Format vorliegen muss, transparenten Hintergrund vermeiden, empfohlene Größe 256 x 256 Pixel, mit einer maximalen Dateigröße von 100 KB.

- [4.] Laden Sie Ihr Logo mit der Datei „logo.png“ in den zuvor erstellten Ordner mit der Smartcontract-Adresse hoch, und wenn Sie alles richtig gemacht haben, sollte Ihr Pfad so aussehen. `bsc/<token_smartcontract_address>/logo.png`

- [5.] Erstellen Sie eine Datei mit dem Namen „info.json“ im Ordner „bsc/<token_smartcontract_address>/“, und bearbeiten Sie Ihre Token-Informationen

- [6.] Reichen Sie in Ihrem gegabelten „Token-Assets“-Repo zuerst Ihre oben genannten Änderungen ein und erstellen Sie dann eine Pull-Anforderung an das Haupt-Repo

- Optional ist es ein guter Vorschlag, die Pull-Anforderung zu kommentieren, wie viele Token (je nach Ihrer Wahl, jede Menge ist in Ordnung) Sie den Community-Benutzern aus der Luft werfen möchten, damit Sie mehr Follower/Gruppenmitglieder erhalten können.

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