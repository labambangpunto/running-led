# Checklist Dokumentasi Proyek PCB

## 1. File Desain PCB (source, bukan cuma gambar)

- File project native dari software yang kamu pakai (KiCad `.kicad_pro`/`.kicad_sch`/`.kicad_pcb`, atau Eagle `.sch`/`.brd`, atau software lain) — ini yang memungkinkan orang membuka dan mengedit desainmu.
- Skematik rangkaian dalam format gambar juga (PDF/PNG) untuk yang tidak punya software EDA, supaya tetap bisa dipelajari secara visual.

## 2. File Fabrikasi (Gerber)

- Folder Gerber files (hasil export, biasanya `.gbr`, `.drl`, dll) — ini yang dipakai kalau orang mau pesan PCB fisik ke pabrikan (JLCPCB, PCBWay, dll).

## 3. Bill of Materials (BOM)

- Daftar komponen: nama IC (misal 555, 4017), resistor, kapasitor, LED, nilai masing-masing, jumlah, dan idealnya link datasheet atau part number.

## 4. Dokumentasi Perakitan

- Foto PCB jadi (top & bottom).
- Diagram/petunjuk penempatan komponen (bisa dari fitur "assembly drawing" di software EDA).
- Instruksi solder/perakitan singkat kalau ada langkah yang perlu perhatian khusus.

## 5. Media Pendukung (opsional tapi sangat membantu)

- Video/GIF singkat menunjukkan efek running LED-nya menyala.
- Foto proses pembuatan kalau ada.

## 6. File Legal & Administratif

- `LICENSE` — teks lengkap CC BY-NC-SA 4.0.
- `README.md` — jelaskan: apa proyeknya, cara kerja rangkaian, cara pakai (cukup + dan -), spesifikasi tegangan input, daftar isi repo, dan lisensi.
