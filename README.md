# Cari Cuan POS — Starter Project

## Stack
React + Vite, IndexedDB (idb), PWA Service Worker, Capacitor Android.

## Jalankan web
- Install Node.js 20+
- Ekstrak ZIP dan jalankan `npm install`
- `npm run dev` untuk development
- `npm run build` untuk build web

## Android
- Install Android Studio dan Android SDK
- `npm run android:add` (sekali)
- `npm run android:sync`
- Buka folder android di Android Studio untuk build APK.

## Modul yang sudah disediakan
Dashboard, POS, keranjang, kategori produk, stok, metode Tunai/QRIS/Transfer (QRIS placeholder), dine-in/takeaway, katalog, pembelian bahan, riwayat transaksi, performa dasar, arus kas, pelanggan, laporan dasar, backup/import JSON, impor produk manual melalui form, PWA cache, IndexedDB lokal, dan TanyaKasirGue berbasis ringkasan lokal.

## Batasan sebelum produksi
Ini fondasi aplikasi lokal, bukan SaaS produksi. Sinkronisasi cloud multi-device, login, multi-cabang, role karyawan, QRIS dinamis, printer thermal, impor XLSX/PDF/Google Sheets, AI generatif dan suara live, laporan pajak, resep bahan, retur, hutang-piutang, serta backup terjadwal memerlukan backend dan integrasi provider. Rekomendasi backend: Supabase/PostgreSQL + Auth + Row Level Security + Edge Functions. Gunakan payment gateway/acquirer QRIS resmi dan verifikasi pembayaran via webhook. Simpan API key AI hanya di backend.
