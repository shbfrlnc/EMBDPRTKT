# EMBDPRTKT

## Download

Untuk mendownloadnya, kunjungi halaman Releases.

## Info Lebih Lanjut

WEBSITE:

- https://shbfrlnc.github.io

## Intro

EMBDPRTKT adalah aplikasi untuk memproteksi YouTube video embed or PDF file embed.

Dibuat dengan Electronjs.

Untuk menjalankan aplikasi ini, ekstrak file zip nya, masuk ke dalam foldernya via command line, lalu:

```
npm install
```

Selanjutnya, perhatikan folder "engines".

Folder tersebut harus diisi dengan executable terkompresi dari NWJS.

Info lebih lanjut ada di catatan yang ada di dalam folder tersebut.

Download link nya ada di sana.

Setelah mendownload NWJS executables, simpan di sana, tanpa mengubah nama file nya.

Selanjutnya, jalankan:

```
// untuk menjalankan kode dalam bentuk plaintext
npm run dev
```

Or:

```
// obfuscate kode plaintext nya
npm run obfuscate

// jalankan kode yang sudah di-obfuscate
npm run start
```

Untuk mem-build installer untuk Windows:

```
// obfuscate dahulu, karena kode plaintext untuk development, bukan production
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