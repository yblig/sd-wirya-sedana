# SD Wirya Sedana

Web profil sekolah satu halaman: profil, visi & misi, program sekolah, galeri kegiatan, dan lokasi dengan peta. Dioptimalkan untuk HP.

## Mengubah data

Semua data ada di objek `SEKOLAH` di bagian bawah `index.html`:

| Isian | Keterangan |
|---|---|
| `telepon` | Nomor WhatsApp/telepon format `62xxxxxxxxxx` (kosong = disembunyikan) |
| `email`, `instagram` | Kosong = disembunyikan (instagram tanpa `@`) |
| `linkMaps` | Link "Bagikan" dari Google Maps (opsional) |
| `visi`, `misi`, `program` | Teks visi, daftar misi, dan program sekolah |
| `galeri` | Foto di folder `images/` + keterangan, contoh `{ foto: "images/kegiatan-3.jpg", ket: "Lomba menggambar" }` |
