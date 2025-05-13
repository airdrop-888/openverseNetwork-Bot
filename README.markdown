# OpenverseNetwork-Bot 🚀

Script ini digunakan untuk mengotomatiskan tugas di Openverse Network, membantu kamu klaim poin airdrop secara efisien! 🎉  
Dibuat dengan penuh semangat oleh [@balveerxyz](https://t.me/balveerxyz) untuk komunitas airdrop hunter.

![access_token](https://github.com/user-attachments/assets/b80b069c-e7a9-406c-898f-637723f86a47)

## Cara ambil token
- Buka dashboard, pencet F12 >> Application >> Local Storage

---

## 📌 Fitur
- ✅ Auto completion untuk semua tugas (`user_visit` dan `advance_visit`) menggunakan token dari `tokens.txt`
- 🔌 Dukungan proxy (`proxy.txt`) untuk koneksi aman (HTTP, SOCKS4, SOCKS5)
- 🎁 Menampilkan hasil reward (poin) setelah klaim tugas
- ⚡ Filter tugas aktif (`status: 1`) untuk efisiensi maksimal
- 🎨 Console dengan tampilan kece menggunakan `cfonts` dan `chalk`, dilengkapi emoji
- 🛡️ Error handling yang tangguh untuk stabilitas bot

---

## 🚀 Cara Penggunaan

1. **Clone repository ini**
   ```sh
   git clone https://github.com/airdrop-888/openverseNetwork-Bot.git
   cd openverseNetwork-Bot
   ```

2. **Install Dependencies**
   ```sh
   npm install axios chalk@4 cfonts http-proxy-agent socks-proxy-agent readline-sync
   ```

3. **Siapkan file tokens**
   - Buat file `tokens.txt` dan isi dengan token Bearer, satu token per baris. Contoh:
     ```
     00000|0yCasdwAqvUvnPFgnUnnrjMEsda2MyefsaInIJfsqwec222
     ```
   - (Opsional) Buat `proxy.txt` jika ingin menggunakan proxy. Contoh:
     ```
     http://username:password@host:port
     socks5://username:password@host:port
     ```

4. **Jalankan Script**
   ```sh
   node index.obf.js
   ```

5. **Ikuti Instruksi**
   - Pilih apakah ingin menggunakan proxy (y/n)
   - Script akan otomatis mengeksekusi semua tugas aktif

---

## ⚠️ Disclaimer
Gunakan script ini dengan bijak dan sesuai aturan Openverse Network.  
Developer tidak bertanggung jawab atas penyalahgunaan atau banned akun.

---

## 🤝 Kontribusi
Jika ingin berkontribusi, silakan fork repo ini dan ajukan pull request! Kami terbuka untuk ide baru dan perbaikan.

---

## 📞 Kontak
Jika ada pertanyaan, hubungi: [@balveerxyz](https://t.me/balveerxyz)  
Join channel Telegram gratis: [t.me/airdroplocked](https://t.me/airdroplocked)
