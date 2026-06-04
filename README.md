# Proyek Akhir Kalkulus Integral — Kelompok 6

**Mata Kuliah:** Kalkulus Integral  
**Dosen:** Dzul Fadli Rahman S.Kom., M.Sc.  
**Program Studi:** Teknologi Informasi  
**Universitas Negeri Yogyakarta — 2026**

---

## Anggota Kelompok

| No | Nama | NIM | Peran | Kontribusi |
|----|------|-----|-------| ---------- |
| 1 | Elvina Yahya Griselda | 25051130007 | Modeling Lead | Menyusun laporan bagian B. Problem Formulation dan C. Metode Penyelesaian. Membuat kode program bagian A, B, dan C. Solusi Simbolik (SymPy) cell 1  |
| 2 | Arlina Dewi Kusumawati | 25051130011 | Numeric & Validation Lead | Menyusun laporan bagian E. Hasil dan Validasi. Membuat kode program bagian E. Validasi - Simbolik vs Numerik + Error Analysis.|
| 3 | Tashfia Eka Salma Aulia | 25051130014 | Visualization & Reporting Lead | Menyusun laporan bagian G. Kesimpulan dan F. Visualisasi dan Interpretasi. Membuat kode program bagian F. Visualisasi Kurva v(t) dan Area per Fase serta membuat G. Interpretasi Hasil dan Kesimpulan. |
| 4 | Nalar Ratih | 25051130016 | Numeric & Validation Lead | Menyusun laporan bagian C. Solusi Simbolik (SymPy) cell 1 dan E. Hasil dan Validasi. Membuat kode program bagian F. Visualisasi Kurva v(t) dan Area per Fase. |
| 5 | Aista Bening Istiqomah | 25051130018 | Symbolic Lead | Menyusun laporan bagian D. Metode Penyelesaian. Membuat kode program bagian D. Solusi Numerik (NumPy) - 2 Resolusi Sampling.|
| 6 | Shelfa Qorianisa Dayani | 25051130020 | Koordinator Proyek | Menyusun laporan bagian A. Tujuan Praktikum dan B. Tabel Kontribusi. Menyusun timeline, memastikan integrasi output dan standar guideline terpenuhi. Membuat kode program bagian C. Solusi Simbolik (SymPy) cell 3. |


---

## Deskripsi Proyek

Proyek ini memodelkan pergerakan kendaraan selama 100 detik yang dibagi menjadi 4 fase kecepatan berbeda. Total jarak tempuh dihitung menggunakan dua pendekatan yaitu simbolik dengan SymPy dan numerik dengan metode trapesium NumPy, kemudian hasilnya divalidasi dan divisualisasikan.

---

## Isi File

| File | Keterangan |
|------|-----------|
| `UAS_KalkulusIntegral_Kelompok6.ipynb` | File utama notebook Google Colab |
| `Laporan_UAS_Kalkulus_Integral_Kelompok6.pdf` | Laporan lengkap dalam format PDF |

---

## Cara Menjalankan

1. Buka file `.ipynb` di Google Colab
2. Klik Runtime lalu Run All
3. Semua output akan muncul otomatis

---

## Library yang Digunakan

- `sympy` — perhitungan integral simbolik
- `numpy` — perhitungan numerik trapesium
- `matplotlib` — visualisasi grafik

---

## Hasil Singkat

| Fase | Deskripsi | Jarak |
|------|-----------|-------|
| Fase 1 (0–25 s) | Akselerasi Linier | 625,00 m |
| Fase 2 (25–50 s) | Kecepatan Konstan | 1.250,00 m |
| Fase 3 (50–75 s) | Akselerasi Kuadratik | 1.458,33 m |
| Fase 4 (75–100 s) | Deselerasi Linier | 937,50 m |
| **Total** | | **4.270,83 m** |

---

## Pernyataan Integritas Akademik

- Kode terinspirasi dari contoh kelas, namun seluruh solusi dan narasi ditulis sendiri oleh kelompok.
- Kami menggunakan bantuan AI untuk keperluan debugging dan formatting laporan.
- Seluruh isi proyek bukan hasil menyalin dari kelompok lain.
- Setiap anggota bertanggung jawab atas keseluruhan isi proyek, bukan hanya bagiannya masing-masing.

---

*Yogyakarta, Juni 2026 — Kelompok 6, Teknologi Informasi UNY*
