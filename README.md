<p style="font-size:14px" align="right">
<a href="https://t.me/PemulungAirdropID" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/72949170/194228482-0f875615-e155-4b12-8716-8111addd6cba.jpg" width="30"/></a>
</p>

<p align="center">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/4c3db4b0-e129-4f63-a818-1523038dd86d">
</p>

# DEPLOY SMARTCONTRACT ETHEREUM (ERC-20)

Untuk deploy sebuah smartcontract di Ethereum memiliki beberapa cara, disini saya akan menggunakan Thirdweb dan Remix untuk deploynya dan di jaringan Scroll Mainnet.


Explorer
> https://scrollscan.com

ThirdWeb
> https://thirdweb.com

Remix
> https://remix.ethereum.org/

## Deploy via ThirdWeb

### 1. Pastikan kalian menyiapkan ETH sebagai fee deploy
Untuk bridge di jaringan Scroll Mainnet kalian bisa menggunakan <a href="https://scroll.io/bridge" target="_blank">Official Bridge </a> atau bisa juga dengan <a href="https://s.id/owlto" target="_blank"> Owlto </a>

### 2. Masuk ke website Thirdweb
https://thirdweb.com/explore
- Connect wallet
- Klik bagian "Token"

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/2c45f6df-7939-4ac2-8e89-7a4079159e3f">
</p>

### 3. Isi detail token contract kalian
- Masukan nama, symbol, dan deskripsi contract
- Pilih jaringan
- Klik "Deploy Now", Lalu sign melalui wallet kalian

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/b73faf51-bdda-4eb5-b67d-6d2d93614818">
</p>

### 4. Konfirmasi Deploy
Konfirmasi melalui wallet kalian

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/6b8b4b76-00a5-41f6-a88d-5dc38547f065">
</p>

### 5. Done Deployed, Edit supply contract
Jika sudah deploy, kalian bisa mint supply contract 
- Pergi ke "Token"
- Klik "Mint"
- Lalu edit supply

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/e03776be-ba94-4a26-aa00-72a57ce90b1b">
</p>

### DONE
Cek Contract kalian di Explorer
https://scrollscan.com/

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/7ca6ccdc-0463-4fb8-aeb3-6e7bb369227d">
</p>


# Deploy via Remix

### 1. Pastikan kalian menyiapkan ETH sebagai fee deploy
Untuk bridge di jaringan Scroll Mainnet kalian bisa menggunakan <a href="https://scroll.io/bridge" target="_blank">Official Bridge </a> atau bisa juga dengan <a href="https://s.id/owlto" target="_blank"> Owlto </a>

### 2. Masuk ke website Remix
https://remix.ethereum.org/
- Create Workspace
<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/fd23c785-1c8c-4138-bd56-bd5fd0dc4d03">
</p>

- Pilih ERC-721 dan Buat nama workspace kalian
<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/b6ed85cd-8b29-4963-8500-411cc5767919">
</p>

### 3. Edit Contract
- Pergi ke folder "Contract"
- Lalu klik "MyToken.sol"

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/2771d569-c4c5-4f6e-95e0-13c26a4919d0">
</p>

- Edit "MyToken" dan "MTK" menjadi nama token kalian

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/8d9eadba-bd26-4411-94b1-c51ada35463d">
</p>

### 4. Compile Contract
- Pergi ke "Solidity Compiler"
- Lalu klik "Compile MyToken.sol"

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/ad6fe52c-8e12-4f75-9980-002b9cbf20e7">
</p>


### 5. Deploy Contract
- Pergi ke "Deploy & Run Transaction"
- Pilih "Injected Provider - Metamask" sebagai environment
- Connect Metamask Wallet

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/e4d10e3a-f376-4806-8563-6d3a176d6d27">
</p>

- Lalu klik "Deploy"
- Sign transaksi di Metamask

### Done, Cek Contract di Explorer
- Buka Explorer https://scrollscan.com/
- Klik "Contract Creation"
  
<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/58de57c5-6546-414a-8dad-fd67fb55b4bc">
</p>

Done, Contract Deployed

<p align="left">
  <img width="auto" height="auto" src="https://github.com/muhamad-ramadhani/deploy-contract/assets/72949170/d6d2a517-daad-4082-859c-2e47b9c1883a">
</p>
