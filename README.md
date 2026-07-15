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
