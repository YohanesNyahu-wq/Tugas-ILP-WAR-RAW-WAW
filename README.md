# Tugas Kelompok 6: Instruction-Level Parallelism (ILP)

## Deskripsi
Proyek ini merupakan implementasi simulasi Instruction-Level Parallelism (ILP) menggunakan Python dan Google Colab, dengan fokus pada analisis ketergantungan data RAW, WAR, dan WAW.

## Anggota dan Pembagian Tugas

| Nama | Kontribusi |
|---|---|
| Fery | Implementasi RAW dan dependency graph RAW |
| Yohanes | Implementasi WAR dan dependency graph WAR |
| Irwansyah | Implementasi WAW, pengujian, dan penyusunan laporan PDF |

## Implementasi
- RAW (Read After Write): Instruksi membaca hasil penulisan instruksi sebelumnya.
- WAR (Write After Read): Instruksi menulis register yang sebelumnya dibaca.
- WAW (Write After Write): Dua instruksi menulis register tujuan yang sama.

Setiap implementasi dilengkapi dependency graph.

## Cara Menjalankan
1. Unduh file `.ipynb` dari repository.
2. Buka file menggunakan Google Colab.
3. Jalankan seluruh sel kode secara berurutan.
4. Amati hasil analisis dependency dan graph yang ditampilkan.

## Teknologi
Python, Google Colab, Matplotlib, dan GitHub.

## Repository
https://github.com/YohanesNyahu-wq/Tugas-ILP-WAR-RAW-WAW

## Referensi Simulator
https://github.com/harshitasingh4863/instruction-level-parallelism-simulator
