# Final UAT Galeri

Dokumen ini mencatat pemeriksaan otomatis untuk urutan galeri dan status placeholder pada sumber konten runtime.

Kriteria wajib:

- galeri terurut dari item terbaru ke terlama;
- setiap item baru memiliki `createdAt` bila timestamp dapat diturunkan dari nama file atau ID;
- `galleryIsPlaceholder` otomatis menjadi `false` bila seluruh item galeri aktif memiliki gambar;
- perubahan memperbarui `settings.updatedAt`.
