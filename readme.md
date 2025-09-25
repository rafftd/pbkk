| No | Fitur                  | Test Case                        | Langkah Uji                               | Expected Result                                        | Status |
|----|-------------------------|----------------------------------|-------------------------------------------|--------------------------------------------------------|--------|
| 1  | Authentication          | Login dengan akun valid          | Input email + password benar > klik login  | User berhasil masuk ke dashboard                      | Pass / Fail     |
| 2  | Authentication          | Login dengan password salah      | Input email benar + password salah        | Pesan error muncul “Password salah”                    | Pass / Fail       |
| 3  | Upload CV               | Upload file PDF valid            | Klik upload > pilih file PDF              | File tersimpan & teks berhasil diproses                | Pass / Fail       |
| 4  | Upload CV               | Upload file non-PDF/DOCX (JPG)   | Klik upload > pilih file JPG              | Muncul pesan error “Format tidak didukung”             | Pass / Fail     |
| 5  | Matching & Scoring      | Input jobdesc + CV sesuai        | Masukkan jobdesc > sistem hitung score    | Skor relevansi muncul dengan feedback                  | Pass / Fail       |
| 6  | Matching & Scoring      | Input jobdesc + CV tidak sesuai  | Masukkan jobdesc > sistem hitung score    | Skor rendah + saran perbaikan muncul                   | Pass / Fail      |
| 7  | History Review          | Cek riwayat analisis             | Klik menu History                         | Daftar analisis CV sebelumnya tampil                   | Pass / Fail       |
| 8  | Export Report           | Export hasil ke PDF              | Klik Export > pilih PDF                   | File report berhasil diunduh                           | Pass / Fail      |
| 9  | Comparison Mode         | Bandingkan 2 CV berbeda          | Upload CV A & CV B                        | Sistem menampilkan perbandingan skor                   | Pass / Fail     |
| 10 | Skill Recommendation    | Cek saran skill                  | Upload CV > analisis skill                | Sistem menampilkan rekomendasi kursus/skill            | Pass / Fail       |
| 11 | CV Template             | Generate template                | Pilih template > isi data                 | CV baru dihasilkan sesuai template                     | Pass / Fail       |
| 12 | Admin – Jobdesc     | Tambah jobdesc baru              | Admin isi form > simpan                   | Jobdesc tersimpan & bisa dipakai user                  | Pass / Fail      |
| 13 | Admin – Monitoring      | Cek analytics                    | Admin buka menu analytics                 | Statistik jumlah user & upload muncul                  | Pass / Fail      |
| 14 | Paket Premium           | Gagal bayar Premium                   | Klik "Pesan Sekarang" > cancel/invalid pay   | Transaksi gagal, pesan error muncul, paket tidak aktif | Pass / Fail      |
| 15 | Paket Roating           | Pilih paket Roating & bayar sukses    | Klik "Pesan Sekarang" > proses pembayaran    | Fitur Roating aktif + invoice/payment success muncul   | Pass / Fail      |
| 16 | Paket Roating           | Gagal bayar Roating                   | Klik "Pesan Sekarang" > cancel/invalid pay   | Transaksi gagal, pesan error muncul, paket tidak aktif | Pass / Fail      |

``Untuk tool yang digunakan Browser (Chrome, Firefox, Edge) untuk uji kompatibilitas dan Excel/Markdown untuk catat test case & hasil uji.``
