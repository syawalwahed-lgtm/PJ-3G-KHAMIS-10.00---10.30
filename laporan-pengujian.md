# Laporan Pengujian

## Status
**Belum diuji secara manual dalam pelayar sebenar.** Fail ini dihasilkan dan diperiksa secara statik dalam sesi pembinaan. Tiada dakwaan bahawa ujian rentas peranti atau cetakan fizikal telah berjaya dilaksanakan.

## Pemeriksaan statik yang dibuat
- [x] `index.html` merangkumi halaman utama, taklimat, kuiz, keputusan dan menu.
- [x] Bank data mengandungi tepat 25 item; setiap item mempunyai empat pilihan, indeks jawapan dan penerangan.
- [x] Markah dikira berdasarkan satu jawapan tersimpan bagi setiap soalan; klik tambahan tidak mengira markah berganda.
- [x] Peratus menggunakan bilangan betul dibahagi 25 dan didarab 100.
- [x] Semakan jawapan memaparkan pilihan murid, jawapan betul dan penerangan.
- [x] Percubaan semula dan tetapan semula meminta pengesahan.
- [x] Fungsi cetak menggunakan `window.print()`; simpan PDF bergantung pada pelayar.
- [x] Kemajuan cuba disimpan dalam `localStorage` dan kegagalan storan ditangani.
- [x] CSS mempunyai aturan responsif dan gaya cetak.
- [x] Tiada video/audio luaran diperlukan; aplikasi berfungsi tanpa media luar.

## Ujian manual yang masih perlu dilakukan
- [ ] Buka `index.html` dalam Chrome/Edge/Firefox/Safari.
- [ ] Uji nama kosong dan nama yang sah.
- [ ] Jawab semua 25 soalan dengan pilihan betul dan salah; pastikan maklum balas sepadan.
- [ ] Pastikan semua soalan bergerak dengan betul dan markah tidak dikira dua kali.
- [ ] Uji keputusan 0/25, 13/25 dan 25/25 serta sempadan lencana.
- [ ] Muat semula halaman dan periksa pemulihan kemajuan.
- [ ] Uji percubaan semula, dialog tetapan semula dan pembatalan dialog.
- [ ] Uji cetakan dan pilihan Simpan sebagai PDF.
- [ ] Uji telefon, tablet, komputer dan navigasi papan kekunci.
- [ ] Semak semula standard dengan dokumen kurikulum rasmi sekolah.

## Batasan
- Tiada ujian automatik browser atau ujian peranti sebenar dijalankan.
- Audio, suara sintesis dan video tidak disertakan.
- Pautan pratonton GitHub Pages tidak tersedia kerana aplikasi belum diterbitkan.
