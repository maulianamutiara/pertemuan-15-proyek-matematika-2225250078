# Program Rekap dan Analisis Nilai Matematika Kelas

## Identitas Mahasiswa

- Nama: Mauliana Mutiara
- NIM: 2225250078
- Kelas: 3A
- Mata Kuliah: Algoritma dan Pemrograman
- Pengerjaan: Individu

## Deskripsi

Program ini dibuat untuk membantu proses rekap dan analisis nilai matematika siswa. Program menerima nilai siswa, kemudian menghitung rata-rata, nilai minimum, nilai maksimum, jumlah siswa yang lulus, dan jumlah siswa yang tidak lulus.

## Fitur

1. Memasukkan jumlah siswa dan nilai masing-masing siswa.
2. Menghitung rata-rata nilai.
3. Menentukan nilai minimum dan maksimum.
4. Menghitung jumlah siswa yang lulus dan tidak lulus.
5. Memvalidasi input agar berupa angka dalam rentang 0 sampai 100.
6. Menangani kondisi ketika data kosong pada fungsi analisis.

## Persyaratan

- Python 3
- Visual Studio Code

## Cara Menjalankan

1. Buka folder proyek di VS Code.
2. Buka terminal.
3. Jalankan perintah:

   `python main.py`

4. Masukkan jumlah siswa.
5. Masukkan nilai setiap siswa sesuai petunjuk program.

## Struktur Folder

- `main.py`: program utama dan interaksi dengan pengguna.
- `proses.py`: fungsi validasi dan analisis nilai.
- `tests/test_case.md`: dokumentasi pengujian.
- `docs/bug_log.md`: catatan bug dan perbaikan.
- `.gitignore`: daftar file yang tidak perlu diunggah.

## Aturan Kelulusan

Siswa dinyatakan lulus jika nilai lebih besar dari atau sama dengan 60.

## Pengujian

Pengujian mencakup perhitungan rata-rata, batas kelulusan, input huruf, nilai di luar rentang, nilai minimum dan maksimum, data kosong, dan jumlah siswa yang tidak valid.

Hasil pengujian akhir dicatat dalam `tests/test_case.md`.

## Known Issues

Program belum menyimpan hasil analisis ke file. Hasil ditampilkan melalui terminal.

## Kontribusi

Proyek ini dikerjakan secara individu oleh Mauliana Mutiara.

## Bantuan dan Referensi

- Modul Bahan Ajar Pertemuan 15 Algoritma dan Pemrograman.
- Dokumentasi Python: https://docs.python.org/3/
- Bantuan AI digunakan untuk membantu memahami struktur program dan pengujian.
