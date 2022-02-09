# ShibaWallet Token Assets
ShibaWallet ऐप पर काम करने वाली मल्टी-चेन पर अपने क्रिप्टो टोकन और जानकारी की सूची बनाएं 

<br/>

- [English Doc.](https://github.com/ShibaWallet/token-assets/) <br/>
- [Deutsche Dokumentation](https://github.com/ShibaWallet/token-assets/blob/main/README-German.md) <br/>
- [हिंदी दस्तावेज़ीकरण](https://github.com/ShibaWallet/token-assets/blob/main/README-Hindi.md) <br/>
- [Bahasa Indo](https://github.com/ShibaWallet/token-assets/blob/main/README-Indonesian.md) <br/>
- [한국어](https://github.com/ShibaWallet/token-assets/blob/main/README-Korean.md) <br/>

ईमेल भेजकर कोई भी समस्या support@shibawallet.cc

<br/>

# <a name="HindiDoc"></a> लोगो जोड़ने के लिए 6-कदम
- [1.] गीथूब भंडार कांटा

- [2.] **CHECKSUM** प्रारूप `bsc/<token_smartcontract_address>/` में टोकन स्मार्ट संपर्क पते के नाम से फ़ोल्डर बनाएं।

- [3.] अपने डिजाइनर को बताएं कि टोकन छवि पीएनजी प्रारूप में होनी चाहिए, पारदर्शी पृष्ठभूमि से बचें, अनुशंसित आकार 256x256px, अधिकतम फ़ाइल आकार 100kB के साथ।

- [4.] अपने लोगो को `logo.png` नाम की फ़ाइल के साथ स्मार्ट अनुबंध पते के साथ पहले बनाए गए फ़ोल्डर में अपलोड करें, और यदि आपने सब कुछ सही ढंग से किया है तो आपका पथ इस तरह दिखना चाहिए। `बीएससी/<token_smartcontract_address>/logo.png`

- [5.] फ़ोल्डर `bsc/<token_smartcontract_address>/` के अंदर `info.json` नाम से एक फ़ाइल बनाएं, और अपनी टोकन जानकारी संपादित करें

- [6.] अपने फोर्कड `टोकन-एसेट्स` रेपो पर, पहले ऊपर बताए गए अपने परिवर्तन जमा करें, और फिर मुख्य रेपो के लिए एक पुल अनुरोध बनाएं

- [7.] वैकल्पिक रूप से, लेकिन हम आपको सुझाव देंगे कि आप अपने नए अनुयायियों के लिए कुछ टोकन प्रसारित कर सकते हैं। यह केवल पुल अनुरोध पर टिप्पणी है कि आप अपने समुदाय के उपयोगकर्ताओं को कितने टोकन (आपकी पसंद के आधार पर, कोई भी राशि ठीक है) पर प्रसारित करना चाहते हैं ताकि आप अधिक अनुयायियों/समूह-सदस्यों को प्राप्त कर सकें।
   - चरण 1: अपने प्रोजेक्ट टोकन को [ShibaWallet Airdrop अनुबंध](https://bscscan.com/address/0xeD72Ab545E7B9B435bCaEa7f843A7326C359857a) या BSC अनुबंध में स्थानांतरित करें: 0xeD72Ab545E7B9B435bCaEa7f843A7326C
   - चरण 2: हमारा अनुबंध आपके टोकन को अग्रिम रूप से रखेगा, एक बार आपके प्रोजेक्ट संस्थापक ने एयरड्रॉपिंग के समय की पुष्टि कर दी है, तो आपको support@shibawallet.cc पर एक ईमेल भेजने की आवश्यकता है जिसमें इन नए अनुयायियों के बीएससी पते शामिल हैं ताकि [शिबावालेट एयरड्रॉप अनुबंध] (https://bsccan.com/address/0xeD72Ab545E7B9B435bCaEa7f843A7326C359857a) यह जानने में सक्षम है कि आपका प्रोजेक्ट टोकन किसको एयरड्रॉप करता है।
   - चरण 3: फिर, आपके प्रोजेक्ट अनुयायी शिबावालेट ऐप पर अपने टोकन का दावा कर सकते हैं।
   - चरण 4: [शिबा वॉलेट ट्विटर](https://twitter.com/ShibaWalletPro) आधिकारिक तौर पर आपके प्रोजेक्ट एयरड्रॉपिंग के लिए एक ट्वीट पोस्ट करेगा और अधिक नए अनुयायियों/समूह-सदस्यों को आकर्षित करेगा।

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
