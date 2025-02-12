# RoemahJaseb Userbot  
Bot Telegram berbasis Userbot yang memiliki berbagai fitur canggih untuk mempermudah aktivitas di Telegram.  

![Logo](https://link-ke-logo-kamu.com/logo.png)  

## 🔹 Cara Deploy  
Klik tombol di bawah untuk langsung deploy ke **Heroku**:  

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Falkanakenan%2FRoemahjaseb)  

## 🔹 Konfigurasi  
Setelah deploy, kamu perlu mengisi **Config Vars** di Heroku:  

| Variable | Deskripsi |
|----------|-----------|
| `API_ID` | API ID dari [my.telegram.org](https://my.telegram.org) |
| `API_HASH` | API Hash dari [my.telegram.org](https://my.telegram.org) |
| `SESSION` | String Session untuk userbot |
| `REDIS_URI` | Redis Database (opsional) |
| `REDIS_PASSWORD` | Password Redis (opsional) |

---

## 📌 **Daftar Fitur & Cara Penggunaan**  
Berikut adalah daftar fitur yang tersedia di **RoemahJaseb Userbot**:  

### 🔹 **Jaseb FW (Auto-Forward)**  
- **Perintah:** `.fw (jeda) (jumlah) (pesan)`  
- **Contoh:** `.fw 5s 10 Halo semua!`  

### 🔹 **Spam & Delay Spam**  
- **Perintah Spam:** `.spam (jumlah) (pesan)`  
- **Contoh:** `.spam 5 Halo!`  
- **Perintah Delay Spam:** `.delayspam (jeda) (jumlah) (pesan)`  
- **Contoh:** `.delayspam 3s 5 Halo!`  

### 🔹 **Broadcast (BC)**  
- **Perintah:** `.broadcast (pesan)`  
- **Catatan:** Hanya dikirim ke kontak yang pernah chat dengan bot  

### 🔹 **PM Permintaan (Auto-Reply di DM)**  
- **Perintah:** `.pmpermit (pesan otomatis)`  
- **Contoh:** `.pmpermit Halo! Ada yang bisa saya bantu?`  

### 🔹 **Anti-Delete Message**  
- **Fungsi:** Otomatis menyimpan pesan yang dihapus  

### 🔹 **Auto Reply Chatbot**  
- **Perintah:** `.autoreply (kata kunci) (balasan)`  
- **Contoh:** `.autoreply Halo Hai, ada yang bisa saya bantu?`  

### 🔹 **Auto React**  
- **Perintah:** `.react (emoji) (pesan)`  
- **Contoh:** `.react ❤️ Halo!`  

### 🔹 **Backup Chat**  
- **Perintah:** `.backup` → Untuk ekspor percakapan  

### 🔹 **Instagram & YouTube Downloader**  
- **Fungsi:** Cukup kirim link video Instagram/YouTube  

*(Lanjutkan dengan fitur lainnya di **FEATURES.md** jika terlalu panjang!)*  

---

## 🔹 **Credits**  
- **Base Repo:** [Kazu-Ubot](https://github.com/ionmusic/Kazu-Ubot)  
- **Developer & Maintainer:** [@RoemahJaseb](https://t.me/RoemahJaseb)  

## 🔹 **Support & Diskusi**  
Join **Grup Support** di Telegram: [Klik di sini](https://t.me/RoemahJaseb)
