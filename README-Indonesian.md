# ShibaWallet Token Assets
Buat daftar token & info crypto Anda tentang multi-rantai yang bekerja pada aplikasi ShibaWallet

<br/>

- [English Doc.](https://github.com/ShibaWallet/token-assets/) <br/>
- [Deutsche Dokumentation](https://github.com/ShibaWallet/token-assets/blob/main/README-German.md) <br/>
- [हिंदी दस्तावेज़ीकरण](https://github.com/ShibaWallet/token-assets/blob/main/README-Hindi.md) <br/>
- [Bahasa Indo](https://github.com/ShibaWallet/token-assets/blob/main/README-Indonesian.md) <br/>
- [한국어](https://github.com/ShibaWallet/token-assets/blob/main/README-Korean.md) <br/>

Masalah apa pun dengan mengirim email ke support@shibawallet.cc

<br/>

# <a name="IndonesianDoc"></a> 6 Langkah Untuk Menambahkan Logo
- [1.] Garpu repositori Github

- [2.] Buat folder dengan nama alamat token smartcontact dalam format **CHECKSUM** `bsc/<token_smartcontract_address>/`.

- [3.] Beri tahu desainer Anda bahwa gambar token harus dalam format PNG, hindari latar belakang transparan, ukuran yang disarankan 256x256px, dengan ukuran file maksimal 100kB.

- [4.] Unggah logo Anda dengan file bernama `logo.png` ke folder yang dibuat sebelumnya dengan alamat smartcontract, dan jika Anda melakukan semuanya dengan benar, jalur Anda akan terlihat seperti ini. `bsc/<token_smartcontract_address>/logo.png`

- [5.] Buat file dengan nama `info.json` di dalam folder `bsc/<token_smartcontract_address>/`, dan edit informasi token Anda

- [6.] Pada repo `token-assets` bercabang Anda, kirimkan perubahan Anda yang disebutkan di atas terlebih dahulu, lalu buat permintaan tarik ke repo utama

- [7.] Opsional, tetapi kami menyarankan Anda untuk mengirimkan beberapa token ke pengikut baru Anda melalui udara. Cukup beri komentar di Permintaan Tarik tentang berapa banyak token (tergantung pilihan Anda, jumlah berapa pun tidak apa-apa) yang ingin Anda airdrop ke pengguna komunitas Anda sehingga Anda bisa mendapatkan lebih banyak pengikut/anggota grup.
   - Langkah 1: Transfer token proyek Anda ke [ShibaWallet Airdrop Contract](https://bscscan.com/address/0xeD72Ab545E7B9B435bCaEa7f843A7326C359857a) atau kontrak BSC: 0xeD72Ab545E7B9B435bCaEa7f843A7326C
   - Langkah 2: Kontrak kami akan menahan token Anda terlebih dahulu, setelah pendiri proyek Anda mengkonfirmasi waktu pengiriman, Anda perlu mengirim email ke support@shibawallet.cc termasuk alamat pengikut baru BSC ini sehingga [Kontrak Airdrop ShibaWallet] (https://bscscan.com/address/0xeD72Ab545E7B9B435bCaEa7f843A7326C359857a) mampu mengetahui bagaimana token proyek Anda dikirim ke siapa.
   - Langkah 3: Kemudian, pengikut proyek Anda dapat mengklaim token mereka di aplikasi ShibaWallet.
   - Langkah 4: [ShibaWallet Twitter](https://twitter.com/ShibaWalletPro) akan secara resmi memposting tweet untuk proyek Anda Airdropping & menarik lebih banyak pengikut/anggota grup baru.
   
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