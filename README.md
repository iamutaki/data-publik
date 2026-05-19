# Data Publik

Kumpulan dataset publik Indonesia. Seluruh data menggunakan lisensi [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) - bebas digunakan tanpa batasan.

## Dataset

### Kode Pos

- **[Kode Pos](dataset/kode_pos.csv)** - 83.761 data

Data kode pos seluruh Indonesia yang mencakup wilayah dari tingkat provinsi hingga kelurahan/desa.

### Wilayah

Data wilayah Indonesia berdasarkan hierarki Kemendagri.

- **[Provinsi](dataset/wilayah/provinsi.csv)** - 38 provinsi
- **[Kota/Kabupaten](dataset/wilayah/kota_kabupaten.csv)** - 514 kota/kabupaten
- **[Kecamatan](dataset/wilayah/kecamatan.csv)** - 7.277 kecamatan
- **[Kelurahan/Desa](dataset/wilayah/kelurahan_desa.csv)** - 82.978 kelurahan/desa

### Bank

- **[Bank](dataset/bank.csv)** - 141 data

Daftar kode bank Indonesia yang digunakan pada sistem perbankan (transfer, payment gateway, dll).

| Kolom | Tipe | Deskripsi |
| --- | --- | --- |
| `kode` | string | Kode bank (3 digit, dikeluarkan oleh Bank Indonesia) |
| `nama` | string | Nama bank/penyedia layanan keuangan |
| `url` | string | Website resmi |
