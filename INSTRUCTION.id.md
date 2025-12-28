# Cara Penggunaan / Instruksi

## Metode Rekomendasi: Gemini Gems / System Instructions

Untuk pengalaman terbaik, kami menyarankan penggunaan **Gemini Gems** (tersedia di Gemini Advanced) atau kolom **System Instructions** di Google AI Studio. Metode ini memastikan persona karakter tetap konsisten dan stabil selama percakapan berlangsung.

### Langkah-langkah:

1.  **Pilih Karakter**: Buka folder karakter yang Anda inginkan (contoh: `25-ji-nightcord/yoisaki_kanade/`) dan buka file `.xml` nya.
2.  **Salin Kode**: Salin (copy) seluruh isi file XML tersebut.
3.  **Atur Nama Anda**:
    *   Sebelum atau sesudah menempelkan (paste) kode, cari bagian `<UserConfiguration>` di bagian atas XML.
    *   Ubah nilai di dalam `<Name>...</Name>` menjadi nama panggilan yang Anda inginkan.
    *   *Contoh:*
        ```xml
        <UserConfiguration>
            <Name>Pit</Name>  <!-- Ubah ini jadi nama Anda -->
            <Gender>Male</Gender>
        </UserConfiguration>
        ```
    *   Karakter sekarang akan memanggil Anda dengan nama ini (contoh: "Ah... Pit...") alih-alih menggunakan kata ganti umum seperti "Kamu".
4.  **Tempel ke Instruksi**:
    *   **Untuk Gemini Gems**: Buat Gem baru dan tempel XML yang sudah diedit ke dalam kotak **Instructions**.
    *   **Untuk AI Studio**: Tempel ke dalam blok **System Instructions**.
5.  **Mulai Mengobrol**: Simpan (Save) dan sapa karakter tersebut atau mulai skenario roleplay!

## Metode Alternatif: Chat Biasa

Jika Anda menggunakan versi standar Gemini langsung di jendela obrolan:

1.  Salin seluruh konten XML.
2.  (Opsional) Edit bagian `<Name>` seperti dijelaskan di atas.
3.  Tempel (paste) seluruh blok XML ke dalam kolom chat.
4.  Kirim pesan tersebut.
5.  Gemini akan mengonfirmasi persona tersebut (atau langsung membalas sesuai karakter). Anda bisa mulai roleplay.

---

## 💡 Tips

*   **Tanpa Tanda Kutip (No Quotes)**: Persona ini dirancang untuk menggunakan *huruf miring (italics)* untuk aksi/narasi dan teks biasa untuk ucapan. Mereka **tidak** akan menggunakan tanda kutip (" ") untuk bicara. Ini bertujuan agar gaya penulisan lebih ekspresif dan luwes.
*   **Mode Imersif**: Anggap karakter ini nyata dan sedang bersama Anda. Mereka diprogram untuk bertindak sebagai pasangan/pacar Anda dalam setting dunia nyata.
