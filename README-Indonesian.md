# ShibaWallet Token Assets
Buat daftar token & info crypto Anda tentang multi-rantai yang bekerja pada aplikasi ShibaWallet

<br/>

- [English Doc.](#EnglishDoc) <br/>
- [Deutsche Dokumentation](#GermanDoc) <br/>
- [हिंदी दस्तावेज़ीकरण](#HindiDoc) <br/>
- [Bahasa Indo](#IndonesianDoc) <br/>
- [한국어](#KoreanDoc) <br/>

Masalah apa pun dengan mengirim email ke support@shibawallet.cc

<br/>

# <a name="IndonesianDoc"></a> 6 Langkah Untuk Menambahkan Logo
- [1.] Garpu repositori Github

- [2.] Buat folder dengan nama alamat token smartcontact dalam format **CHECKSUM** `bsc/<token_smartcontract_address>/`.

- [3.] Beri tahu desainer Anda bahwa gambar token harus dalam format PNG, hindari latar belakang transparan, ukuran yang disarankan 256x256px, dengan ukuran file maksimal 100kB.

- [4.] Unggah logo Anda dengan file bernama `logo.png` ke folder yang dibuat sebelumnya dengan alamat smartcontract, dan jika Anda melakukan semuanya dengan benar, jalur Anda akan terlihat seperti ini. `bsc/<token_smartcontract_address>/logo.png`

- [5.] Buat file dengan nama `info.json` di dalam folder `bsc/<token_smartcontract_address>/`, dan edit informasi token Anda

- [6.] Pada repo `token-assets` bercabang Anda, kirimkan perubahan Anda yang disebutkan di atas terlebih dahulu, lalu buat permintaan tarik ke repo utama

- Opsional, itu adalah saran yang baik untuk mengomentari Permintaan Tarik, berapa banyak token (tergantung pilihan Anda, jumlah berapa pun tidak apa-apa) yang ingin Anda kirimkan ke pengguna komunitas sehingga Anda bisa mendapatkan lebih banyak pengikut/anggota grup.

<br/>

### Spesifikasi Info.json

Ambil token `SHWA` misalnya, isi file `info.json` seperti gambar di bawah ini:
```
{
    // Token Anda - alamat kontrak pintar CHECKSUM
    "id": "0x7B8274CcECD5BBCFe18958C3dB6471C5E3e1FBbf",  

    // Jenis kontrak Anda
    "type": "BEP20",

    // Nama token Anda
    "name": "ShibaWallet",

    // Simbol token Anda
    "symbol": "SHWA",

    // Tempat desimal dari token Anda
    "decimals": 18,

    // URL penjelajah token
    "explorer": "https://bscscan.com/address/0x7b8274ccecd5bbcfe18958c3db6471c5e3e1fbbf",

    // Status proyek token saat ini: dalam pengembangan, aktif, penangguhan
    "status": "active",

    // Situs web resmi token
    "website": "https://shibawallet.cc",

    // Logo token dengan ukuran piksel [ 256px * 256px ], hingga ukuran file di bawah 100kB. 
    // Url lebih disukai untuk dihosting di IPFS atau Arweave atau Storej
    "logourl": "https://bafkreibyqzxcnxqdcnhf2d2zeywja4frpi4jkdxzauqmtez3xmub7angz4.ipfs.dweb.link",

    // Deskripsi token Anda (lebih disukai dengan panjang di bawah 150)
    "description": "ShibaWallet is a decentralized wallet for unified all your NFT artworks and meme crypto coins in one app, self-governance and non-custodial entirely.",

    // Akun/platform sosial yang tokennya telah beroperasi sepanjang waktu
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