# sikepo-pantau

Pemantau luar untuk SIKEPO (https://sikepo2.batangharikab.go.id). Tiap ±5 menit GitHub Actions
mengecek halaman web, `/api/sehat` (Node + MariaDB), dan umur sertifikat SSL. Bila gagal,
GitHub mengirim email "Run failed" ke pemilik repo. Riwayat ada di tab **Actions**.
