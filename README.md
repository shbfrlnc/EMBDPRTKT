# EMBDPRTKT

EMBDPRTKT adalah aplikasi untuk memproteksi video YouTube embed atau file PDF embed.

Untuk mendownloadnya, kunjungi bagian Releases.

Untuk menjalankannya, ekstrak file zipnya, kemudian jalankan:

```
npm install
```

Selanjutnya, perhatikan folder bernama "engines".

Folder tersebut harus berisi file executable terkompresi dari NWJS.

Keterangan lebih lanjut bisa dibaca pada catatan teks dalam folder tersebut.

Di sana disediakan link downloadnya.

Setelah NWJS yang dibutuhkan selesai didownload, masukkan ke dalam folder tersebut tanpa mengubah nama file nya.

Kemudian, jalankan:

```
npm run dev // untuk menjalankan aplikasi dengan script plaintext
```

Atau

```
npm run obfuscate
npm run start // untuk menjalankan aplikasi dengan script yang sudah di-obfuscate
```

Untuk mem-build aplikasi ini menjadi installer (aplikasi Windows):

```
npm run obfuscate // obfuscate dulu, karena yang di production bukan dalam bentuk plaintext
npm run dist // build installer, hasilnya ada di ../_Release/EMBDPRTKT
```

## Info Tambahan

Traktir Saya:

https://sociabuzz.com/lsfkrshb/tribe

Channel YouTube Saya:

https://www.youtube.com/c/SHBFRLNC
