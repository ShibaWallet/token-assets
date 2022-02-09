# ShibaWallet Token Assets
ShibaWallet 앱에서 작동하는 다중 체인에 대한 암호화 토큰 및 정보 나열

<br/>

- [English Doc.](https://github.com/ShibaWallet/token-assets/) <br/>
- [Deutsche Dokumentation](https://github.com/ShibaWallet/token-assets/blob/main/README-German.md) <br/>
- [हिंदी दस्तावेज़ीकरण](https://github.com/ShibaWallet/token-assets/blob/main/README-Hindi.md) <br/>
- [Bahasa Indo](https://github.com/ShibaWallet/token-assets/blob/main/README-Indonesian.md) <br/>
- [한국어](https://github.com/ShibaWallet/token-assets/blob/main/README-Korean.md) <br/>

support@shibawallet.cc로 이메일을 보내 문제가 있는 경우

<br/>

# <a name="KoreanDoc"></a> 6-Step To Add Logo
- [1.] Github 저장소 포크

- [2.] **CHECKSUM** 형식 `bsc/<token_smartcontract_address>/`로 토큰 스마트 연락처 주소의 이름으로 폴더를 만듭니다.

- [3.] 디자이너에게 토큰 이미지는 PNG 형식이어야 하며 투명한 배경을 피하고 권장되는 크기는 256x256px이며 최대 파일 크기는 100kB임을 알립니다.

- [4.] 이전에 생성된 smartcontract 주소로 폴더에 `logo.png`라는 파일이 있는 로고를 업로드하고, 모두 올바르게 수행했다면 경로가 다음과 같아야 합니다. `bsc/<token_smartcontract_address>/logo.png`

- [5.] `bsc/<token_smartcontract_address>/` 폴더 안에 `info.json`이라는 이름의 파일을 만들고 토큰 정보를 편집합니다.

- [6.] 분기된 `token-assets` 저장소에서 위에서 언급한 변경 사항을 먼저 제출한 다음 기본 저장소에 대한 pull 요청을 생성합니다.

- [7.] 선택 사항이지만 새 팔로워에게 일부 토큰을 에어드롭할 수 있습니다. 더 많은 추종자/그룹 구성원을 확보할 수 있도록 커뮤니티 사용자에게 에어드롭할 토큰(선택에 따라 얼마든지 상관없음)에 대한 Pull Request에 대한 설명입니다.
   - 1단계: 프로젝트 토큰을 [ShibaWallet 에어드롭 계약](https://bscscan.com/address/0xeD72Ab545E7B9B435bCaEa7f843A7326C359857a) 또는 BSC 계약: 0xeD72Ab547584B9E3로 이전합니다.
   - 2단계: 프로젝트 설립자가 에어드롭 시간을 확인한 후 당사 계약은 귀하의 토큰을 미리 보유할 것입니다. [ShibaWallet 에어드롭 계약] (https://bscscan.com/address/0xeD72Ab545E7B9B435bCaEa7f843A7326C359857a)는 프로젝트 토큰이 누구에게 에어드롭하는지 알 수 있습니다.
   - 3단계: 그러면 프로젝트 팔로워가 ShibaWallet 앱에서 토큰을 요청할 수 있습니다.
   - 4단계: [ShibaWallet Twitter](https://twitter.com/ShibaWalletPro)에서 프로젝트 Airdropping에 대한 트윗을 공식적으로 게시하고 더 많은 새 팔로워/그룹 구성원을 유치합니다.

<br/>

### Info.json 사양

토큰 `SHWA`를 예로 들면 아래와 같이 `info.json` 파일의 내용이 표시됩니다.
```
{
    // 귀하의 토큰 - 스마트 계약 주소 CHECKSUM
    "id": "0x7B8274CcECD5BBCFe18958C3dB6471C5E3e1FBbf",  

    // 계약 유형
    "type": "BEP20",

    // 토큰 이름
    "name": "ShibaWallet",

    // 토큰의 상징
    "symbol": "SHWA",

    // 토큰의 소수점 이하 자릿수
    "decimals": 18,

    // 토큰 탐색기 URL
    "explorer": "https://bscscan.com/address/0x7b8274ccecd5bbcfe18958c3db6471c5e3e1fbbf",

    // 토큰 프로젝트의 현재 상태: 개발 중, 활성, 중단
    "status": "active",

    // 토큰 공식 웹사이트
    "website": "https://shibawallet.cc",

    // 픽셀 크기가 [ 256px * 256px ]인 토큰 로고, 최대 파일 크기가 100kB 미만입니다. 
    // IPFS 또는 Arweave 또는 Storej에서 호스팅하려는 URL
    "logourl": "https://bafkreibyqzxcnxqdcnhf2d2zeywja4frpi4jkdxzauqmtez3xmub7angz4.ipfs.dweb.link",

    // 토큰에 대한 설명(150자 미만이 바람직함)
    "description": "ShibaWallet is a decentralized wallet for unified all your NFT artworks and meme crypto coins in one app, self-governance and non-custodial entirely.",

    // 토큰이 항상 운영되고 있는 소셜 계정/플랫폼
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
