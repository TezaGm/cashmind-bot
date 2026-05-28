CASHMIND BOT — Bot Keuangan Telegram dengan Google Sheet.

Dibuat dengan Python, Telegram Bot API, Groq AI, dan gspread. Versi: Multi-User

Telegram : https://t.me/repmanbot
----------------------------------------------------------------
DESKRIPSI
----------------------------------------------------------------
CashMind Bot adalah bot Telegram untuk mencatat keuangan
pribadi secara otomatis menggunakan kecerdasan buatan (Groq AI).

Setiap pengguna memiliki Google Sheet-nya sendiri. Data transaksi
dan cicilan dicatat langsung dari chat Telegram ke spreadsheet
masing-masing secara terpisah.

Fitur utama:
  - Catat pemasukan & pengeluaran dengan bahasa natural
  - Kategorisasi otomatis menggunakan AI (Groq / LLaMA)
  - Pelacakan cicilan & hutang per bulan
  - Ringkasan saldo keuangan
  - Riwayat transaksi & hapus data
  - Multi-user: setiap user punya Google Sheet sendiri
  - Kontrol akses: hanya user terdaftar yang bisa menggunakan
    
----------------------------------------------------------------
PERINTAH BOT
----------------------------------------------------------------
- /start    - Tampilkan panduan & status akses
- /myid     - Tampilkan Telegram ID kamu (untuk registrasi)
- /cek      - Ringkasan saldo pemasukan & pengeluaran
- /cicilan  - Daftar cicilan aktif & jadwal jatuh tempo
- /riwayat  - 10 transaksi terakhir
- /riwayat 20 - Tampilkan 20 transaksi terakhir (max 30)
- /hapus 15 - Hapus transaksi di baris nomor 15

----------------------------------------------------------------
CONTOH PENGGUNAAN
----------------------------------------------------------------
Transaksi biasa (ketik langsung, tanpa command):
  - "Beli beras 77k"
  - "Gaji bulanan 5jt"
  - "Bayar listrik 250rb"
  - "Makan siang 35000"
  - "Ngopi starbucks 65k"

Tambah cicilan baru:
  - "Tambah cicilan SPinjam 24 bulan 188862 tgl 15 mulai Mei 2026"
  - "Catat hutang SeaBank tenor 12 bulan 1033000 tgl 1"

Bayar cicilan:
  - "Bayar SPinjam 188862 bulan Mei 2026"
  - "Sudah bayar SeaBank 465000 Juni 2026"

----------------------------------------------------------------
KATEGORI OTOMATIS (50/30/20)
----------------------------------------------------------------
Bot secara otomatis mengkategorikan transaksi ke dalam:

- Kebutuhan (50%) - transportasi, makan harian, tagihan, BPJS
- Keinginan (30%) - jajan, kopi, streaming, fashion, hiburan
- Investasi (20%) - tabungan, saham, emas, reksa dana
- Pemasukan      - gaji, bonus, THR, freelance, cashback

#Terima kasih telah menggunakan CashMind Bot!
