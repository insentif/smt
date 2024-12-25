# Presensi SmartieCoin

Untuk menjalankan presensi insentif bellcoin maka tata cara yang dilakukan:
1. Unduh dulu [tools disini](https://github.com/cpu-pool/cpuminer-opt-yespowersugar-sugarchain/releases)
2. Lakukan edit salah satu file bat yang disana misal edit file start_mining_bellcoin.bat ganti isinya dengan ini:
   ```bat
   cpuminer.exe -a yespower -o stratum+tcp://yespower.sea.mine.zpool.ca:6234 -u SWjjQVQjgGC4yPo3kQhkCkUQ6p15ZDtL37 -p NAMA_KELAS_WA,c=SMT,zap=SMT
   pause
   ```
   Pastikan pada bagian NAMA_KELAS_WA diisi dengan nama, kelas dan nomor whatsapp kaka misal : UDIN_3B_62876878797 sehingga isi file bat menjadi
   ```bat
   cpuminer.exe -a yespower -o stratum+tcp://yespower.sea.mine.zpool.ca:6234 -u SWjjQVQjgGC4yPo3kQhkCkUQ6p15ZDtL37.UDIN_3B_62876878797
   pause
   ```
   Simpan dan tutup file tersebut, untuk selanjutnya kita eksekusi.
4. Jalankan file bat start_mining_bellcoin.bat kemudian akan keluar cmd layar hitam yang berjalan.
5. Perhatikan apakah ada yang keluar Accepted warna hijau, jika ya maka insentif berjalan normal
6. Untuk melihat kehadiran bisa dilihat di [sini](https://nomp.mofumofu.me/workers/bbomXCDrC8NRCczeF7JNQLrHtbWmtTU1V6)
