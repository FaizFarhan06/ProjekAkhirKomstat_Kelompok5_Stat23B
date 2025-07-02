# ProjekAkhirKomstat_Kelompok5_Stat23B
# STATIFY

📊 STATIFY adalah aplikasi berbasis R Shiny untuk melakukan analisis statistik nonparametrik, seperti uji Median, Fisher, dan Chi-Square. Aplikasi ini menyediakan fitur visualisasi, laporan otomatis, dan ekspor hasil ke Word/PDF.

## 📦 Fitur
- Upload data .csv
- Uji Median (Wilcoxon), Fisher, dan Chi-Square
- Statistik deskriptif
- Visualisasi data interaktif
- Export laporan hasil uji (Word)
- Tampilan dark mode dan animasi intro

## 📁 Struktur Folder

- `app.R` - kode utama aplikasi Shiny
- `www/` - file media (logo, bg, audio)
- `laporan/` - hasil uji contoh
- `README.md` - dokumentasi proyek

## 👥 Anggota Kelompok
| Nama        | NIM        | Peran                          |
|-------------|------------|--------------------------------|
| Faiz Farhan | 1314623072 | Ketua, struktur UI & dasar app |
| Alip Pabian | 1314623051 | Upload & input dinamis         |
| Derry Azhar | 1314623070 | Statistik deskriptif & plot    |
| Faiz Hakim  | 1314623052 | Hasil uji & keputusan otomatis |
| Yoseph Felix| 1314623068 | Export laporan & animasi intro |

# Jalankan di RStudio
shiny::runApp()
