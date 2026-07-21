# Kandangndalem

Farm ayam laga dan kebutuhan ayam rawatan.

## Kalkulator Produksi KNJ — Gramasi, HPP & Harga Jual

Aplikasi web mandiri (satu berkas, tanpa internet & tanpa instalasi) untuk
menghitung kebutuhan bahan, HPP, dan harga jual seluruh produk KNJ:

1. **RootCore** — jamu serbuk
2. **StemDrive Apex Prime — Balung Wesi** — jamu serbuk
3. **Kamlang Ndalem** — minyak balur
4. **Arak Gosok Sultan's Pusaka** — cairan gosok
5. **Kemin Brajamusti** — param / lulur
6. **Dry Foot Tapak Wojo** — salep kaki

### Cara pakai

1. Unduh / buka berkas [`index.html`](index.html) dengan browser apa pun
   (HP Android/iPhone maupun laptop). Tidak butuh koneksi internet.
2. Tab **Produk & Resep** → sesuaikan gramasi bahan, harga belanja, kemasan,
   biaya tenaga kerja/overhead, dan markup. *(Resep bawaan hanyalah contoh —
   ganti dengan resep asli Anda.)*
3. Tab **Kalkulator Produksi** → masukkan target jumlah unit, aplikasi
   menghitung daftar timbang bahan + total biaya + HPP otomatis.
4. Tab **Ringkasan** → HPP & harga jual semua produk dalam satu tabel.
5. Tab **SOP** → prosedur baku produksi & perhitungan harga.

Semua perubahan tersimpan otomatis di perangkat. Gunakan tombol
**Ekspor Data / Impor Data** untuk mencadangkan atau memindahkan resep
antarperangkat.

### Fitur

- ⚖️ **Kalkulator gramasi** — skala resep otomatis ke berapa pun target produksi
- 💰 **HPP** — bahan (+ % susut), kemasan, tenaga kerja, overhead, per batch & per unit
- 🏷️ **Harga jual** — markup reseller & retail, pembulatan otomatis ke Rp 500
- 📊 **Ringkasan** — tabel HPP & harga semua produk
- 📋 **SOP** — prosedur produksi, QC, pengemasan, dan penetapan harga
- 🖨️ Cetak kartu resep / daftar timbang
- 💾 Ekspor–impor data (JSON), simpan otomatis (localStorage)

### Dokumen

- [`SOP.md`](SOP.md) — SOP lengkap produksi & perhitungan harga (siap cetak)

## KNJ Sales OS — Bagan Otomatisasi Penjualan (Juli 2026)

Aplikasi web mandiri kedua: [`penjualan/index.html`](penjualan/index.html) —
satu berkas, tanpa internet & tanpa instalasi, data tersimpan di perangkat.
Berisi **mesin penjualan 9 tahap** untuk lini ayam dan lini produk KNJ,
dengan ilmu yang diperas dari perusahaan kelas dunia (Amazon, Toyota, Apple,
McDonald's, Salesforce, Zappos, Starbucks, Nike, Dropbox):

- 🗺 **Bagan** — alur otomatisasi penjualan 9 tahap (konten → lead →
  kualifikasi → penawaran → follow-up 1-3-7 → closing → kirim → after-sales
  → repeat/referral ↺ flywheel), tiap tahap berisi aturan main, jalur khusus
  ayam vs produk, referensi dunia, dan bagian yang diotomatiskan aplikasi
- 📇 **Pipeline (CRM)** — catat semua lead; aplikasi menghitung sendiri
  jadwal follow-up **1-3-7** (H+1, H+3, H+7), menandai yang jatuh tempo,
  dan menyiapkan **template pesan WA** sesuai tahap — tinggal ketuk 💬
- 📜 **Aturan 2026** — 12 aturan penjualan KNJ beserta ukuran keberhasilannya
- 🎯 **Target & KPI** — buku penjualan harian, omzet per lini, konversi,
  AOV, corong bulanan, dan progres terhadap target
- ⏰ **Ritme** — checklist harian/mingguan/bulanan yang reset otomatis
  (kaizen mingguan ala Toyota)
- 💾 Ekspor–impor data (JSON), simpan otomatis (localStorage), siap cetak

Dokumen pendamping: [`SOP-PENJUALAN.md`](SOP-PENJUALAN.md) — SOP penjualan
SOP-P01 s/d SOP-P09 + 12 aturan (siap cetak).

## Kandang Ndalem — Kelas Makrifat

Ruang dalam yang terpisah dari urusan dagang: [`makrifat/index.html`](makrifat/index.html).
Aplikasi mandiri (satu folder, tanpa internet, tanpa server) berisi khazanah
tasawuf & kejawen yang dibedah empat lapis — syariat → tarekat → hakikat →
makrifat — lalu dipulangkan ke bahasa sehari-hari; lengkap dengan sayap para
penunjuk jalan: kafilah para nabi, pintu para sahabat, para arif dan
kitab-kitabnya, Wali Songo, cahaya dari Timur, hingga para filsuf Yunani. Tulis satu istilah, ia
langsung dibedah; ketik `/godmode` untuk menyingkap seluruh lapisan sekaligus.
Seluruh catatan tinggal di perangkat sendiri, tidak dikirim ke mana pun.
