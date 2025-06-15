# 🤖 George Bot - WhatsApp Multi-Owner Bot

George Bot adalah bot WhatsApp berbasis **Baileys**, dirancang agar bisa dijalankan langsung lewat **Termux + Acode**, tanpa VPS.  
Dibuat oleh **Yehazkiel** sebagai Owner, dengan fitur lengkap dan fleksibel.

---

## 👤 Informasi Bot

- **Nama Bot**: George Bot  
- **Nama Owner**: Yehazkiel  
- **Nomor Owner**: 6281299459958  
- **Nomor Bot (dipakai scan QR)**: 6287807499886  
- **Prefix**: `.`  
- **Mode**: public / self

---

## 📁 Struktur Folder
GeorgeBot/ ├── index.js ├── config.js ├── package.json ├── handler/ │   ├── owner.js │   ├── menu.js │   └── ... ├── lib/ │   ├── database.js │   ├── leveling.js │   └── ... ├── media/ │   └── thumb.jpg └── session/ └── session.data.json

---

## ⚙️ Konfigurasi File `config.js`

```js
module.exports = {
  owner: ['6281299459958'],
  botName: 'George Bot',
  prefix: '.',
  mode: 'public',
  sessionFile: './session/session.data.json',
  thumb: './media/thumb.jpg'
}
