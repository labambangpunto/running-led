# Running LED — Custom PCB

![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)

Rangkaian running LED (LED berjalan) dengan PCB custom. Cukup hubungkan
sumber daya ke pin **+** dan **−**, LED akan langsung menyala dan
berjalan secara otomatis — tanpa mikrokontroler, tanpa firmware.

## ✨ Fitur

- Plug and play — tinggal beri daya, langsung jalan
- Tidak butuh pemrograman / firmware
- [tambahkan detail: berapa banyak LED, pola animasi, dll]

## ⚡ Spesifikasi

| Parameter        | Nilai              |
|-------------------|---------------------|
| Tegangan input    | [misal: 5V / 9V DC] |
| Arus              | [isi]                |
| Jumlah LED        | [isi]                |
| Dimensi PCB       | [isi]                |

## 🔧 Cara Kerja

[Jelaskan singkat cara kerja rangkaian, misal: menggunakan IC 4017
sebagai decade counter yang dipicu oleh astable multivibrator 555
timer untuk menghasilkan efek LED berjalan.]

## 📁 Isi Repository

```
├── hardware/
│   ├── schematic/       # Skematik rangkaian (source + PDF)
│   ├── pcb/             # File project PCB (KiCad/Eagle)
│   └── gerber/          # File Gerber siap fabrikasi (JLCPCB, PCBWay, dll)
├── docs/
│   ├── BOM.md           # Daftar komponen (Bill of Materials)
│   ├── assembly.md      # Panduan perakitan
│   └── images/          # Foto PCB, diagram, dll
├── LICENSE
└── README.md
```

## 🚀 Cara Menggunakan

1. Fabrikasi PCB menggunakan file di folder `hardware/gerber/`
2. Rakit komponen sesuai `docs/BOM.md` dan `docs/assembly.md`
3. Hubungkan sumber daya ke pin `+` dan `−`
4. LED akan langsung menyala dan berjalan otomatis

## 📜 Lisensi

Proyek ini dilisensikan di bawah
**[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)**.

Ringkasnya:
- ✅ Boleh dipelajari, dimodifikasi, dan dibagikan ulang
- ✅ Wajib mencantumkan kredit ke pembuat asli
- ✅ Karya turunan wajib pakai lisensi yang sama
- ❌ **Tidak boleh digunakan untuk tujuan komersial** (termasuk
  menjual PCB/kit/produk jadi dari desain ini) tanpa izin tertulis

Lihat file [LICENSE](./LICENSE) untuk detail lengkap.

## 🙋 Kontak

Ada pertanyaan atau ingin izin penggunaan komersial? Hubungi:
[isi kontak kamu — email/GitHub profile]
