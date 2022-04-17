# EMBDPRTKT

## Download

Untuk mendownloadnya, kunjungi bagian Releases.

## Pendahuluan

EMBDPRTKT adalah aplikasi untuk memproteksi video YouTube embed atau file PDF embed.

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
// untuk menjalankan aplikasi dengan script plaintext
npm run dev
```

Atau

```
npm run obfuscate

// untuk menjalankan aplikasi dengan script yang sudah di-obfuscate
npm run start
```

Untuk mem-build aplikasi ini menjadi installer (aplikasi Windows):

```
// obfuscate dulu, karena yang di production bukan dalam bentuk plaintext
npm run obfuscate

// build installer, hasilnya ada di ../_Release/EMBDPRTKT
npm run dist
```

## Screencast

- https://www.youtube.com/playlist?list=PLOg7o5N1MDWRggVrzmtuLP6cq4dsNCOv1

## Screenshot

![ScreenShot](assets/EMBDPRTKT1.png?raw=true)

![ScreenShot](assets/EMBDPRTKT2.png?raw=true)

![ScreenShot](assets/EMBDPRTKT3.png?raw=true)

## Info Tambahan

Traktir Saya, Channel YouTube Saya, dan lain-lain:

- https://sociabuzz.com/lsfkrshb
