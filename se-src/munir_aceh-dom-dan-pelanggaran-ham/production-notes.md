# Catatan produksi

- Sumber dan keterangan edisi: lihat `se-imprint.md` dan `se-colophon.md` (dapat disunting langsung). Teks berasal dari OCR (TurboOCR), bukan dari ketik ulang.
- Naskah dibaca langsung dari `book.md`; edisi ini dibangun ulang dengan `pipeline.py --steps se`.
- Koreksi OCR hanya pada kesalahan yang jelas (pemeriksa ejaan SymSpell, ditinjau manual). Ejaan lama dan tidak baku dari narasumber dipertahankan.
- Kutip lurus dan kutip tunggal diubah menjadi kutip lengkung ganda sesuai manual SE; titik dan koma ditaruh di dalam tanda kutip.
- Singkatan ditulis tanpa titik sesuai kaidah Indonesia dan ditandai z3998:acronym; aturan lint s-023 (kapitalisasi judul gaya Inggris) tidak berlaku untuk bahasa Indonesia.
- Edisi white-label, bukan rilis Standard Ebooks: tanpa logo atau klaim SE. Halaman lisensi menggantikan Uncopyright SE karena teks sumber tidak berada di domain publik.
- Label navigasi (Daftar Isi, Penanda, Halaman Judul) diterjemahkan setelah `se build`; sumber tetap sesuai SE agar `se lint` lolos.
- Sampul sengaja dibuat sampul tipografi polos 1400 x 2100 (huruf League Spartan bawaan alat SE), bukan lukisan. Panduan sampul Standard Ebooks mensyaratkan lukisan cat minyak berwarna yang terbukti domain publik AS dan disetujui editor SE; edisi ini tidak memiliki karya seperti itu dan bukan rilis Standard Ebooks.
- Subjek LCSH dipilih dari id.loc.gov (Human rights--Indonesia, Civil-military relations--Indonesia, Political violence--Indonesia); belum ditinjau editor.
- Pindaian memuat teks margin yang diputar dan cap perpustakaan di tepi halaman pertama; hasil OCR-nya berupa deretan huruf tak bermakna, sehingga dibuang dari teks. Judul tercetak di kepala halaman pertama sudah menjadi judul buku.
- Satu paragraf yang terpotong batas halaman pindaian (halaman 3 ke halaman 4: 'bagian dari' / 'intrumen penegakan hukum') digabung. Kalimat 'satuan organik' / 'DOM, yaitu' yang terpotong batas halaman pada halaman 1 dibiarkan seperti hasil OCR karena sambungannya tidak dapat dipastikan tanpa pindaian.
- Ejaan naskah (mis. 'intrumen', 'berekpresi', 'tehnis', 'simbul', 'dipertunjukan') dipertahankan sebagaimana tercetak; hanya salah baca OCR yang jelas diperbaiki, dan setiap perbaikan tercatat di corrections.json. Perbaikan tidak dibandingkan dengan gambar pindaian.
- Tanda baca dan awal paragraf yang tampak janggal bagi se lint berasal dari hasil OCR atau naskah sumber dan tidak diubah; peringatan tinjau-manual didaftarkan di se-lint-ignore.xml dengan alasan masing-masing.
- Tanggal penulisan (Jakarta, 19 April 1999) tercetak di akhir naskah; dicantumkan di abstrak dan deskripsi.
- Subjek berbahasa Indonesia (Hak asasi manusia, Hubungan sipil-militer, Daerah operasi militer) diambil dari istilah yang muncul di Daftar Tajuk Subjek Perpustakaan Nasional (edisi kumulasi 2002-2010); bentuk tajuk pilihannya tidak diperiksa terhadap edisi terbaru atau tajukonline.perpusnas.go.id, sehingga dicantumkan sebagai subjek bebas tanpa otoritas dan belum ditinjau.
