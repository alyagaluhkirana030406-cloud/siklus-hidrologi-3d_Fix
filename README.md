# Simulasi 3D Siklus Hidrologi

## Menjalankan di VS Code
1. Ekstrak folder proyek.
2. Buka folder `siklus-hidrologi-3d` di VS Code.
3. Pastikan Node.js versi 18 atau lebih baru sudah terpasang.
4. Buka Terminal, jalankan:
   ```bash
   npm install
   npm run dev
   ```
5. Buka alamat lokal yang muncul di terminal (biasanya http://localhost:5173).

## Fitur
- Dua mode: Jelajahi Alam dan Pelajari Siklus.
- Scene 3D yang dapat diputar dan di-zoom.
- Hotspot proses pada mode pembelajaran.
- Panel penjelasan konsep.
- Kontrol tampilan untuk hujan, intensitas cahaya, jumlah vegetasi, dan penampang tanah.
- Panduan pengamatan pada mode eksplorasi.

## Catatan
Ini adalah prototipe visual edukatif, bukan simulasi fisika atmosfer atau model prediksi cuaca. Kontrol vegetasi/cahaya mengubah tampilan, bukan menghitung perubahan hidrologi secara kuantitatif. Koneksi internet diperlukan untuk memuat Google Fonts; simulasi inti tetap dapat berjalan tanpa font tersebut.
