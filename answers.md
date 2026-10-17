Salin template berikut ke `answers.md`. Isi sambil mengerjakan.

```markdown
# Jawaban Praktikum: <Ulawiyatul Karomah> (<10224157>)

## Bagian 1: Pemanasan
Pada aturan `nav a.active:hover { color: red; }`, tunjukkan mana **selector**, **deklarasi**, **property**, **value**, dan **pseudo-class**-nya.
1. selector: nav a.active:hover
   deklarasi:color: red;
   property: color
   value: red
   Pseudo-code: hover
2. block: p, li, h2
   inline: span, a, strong
3. Paragraf yang berwarna hijau adalah A dan B
4. Warnanya adalah merah karena selector #title memiliki specificity lebih tinggi daripada .heading dan h1. Selector ID mengalahkan selector class dan selector elemen selama tidak ada aturan lain dengan prioritas yang lebih tinggi.
5. Kode <p>Hello <strong>world</p></strong> memiliki urutan penutup tag yang salah. Tag <strong> dibuka di dalam <p>, sehingga harus ditutup sebelum tag </p>.
Perbaikan:
<p>Hello <strong>world</strong></p>

## Bagian 3: Prediksi Selector Golf
P1. Prediksi warna teks
a. "Weekly hack nights." = hijau (green), karena cocok dengan selector section p.
b. "Bring your own laptop." = oranye (orange), karena cocok dengan selector .note, yang lebih spesifik daripada selector section p.
c. "© 2026 Student Affairs" = biru (blue), karena hanya cocok dengan selector p.
P2. Urutan specificity tertinggi ke terendah
1.#tech p
2..club p
3.main section p
4.p
Setelah diuji (hasil sebenarnya):

## Bagian 4: Box model
Q1 (content-box):Lebar yang terlihat dari tepi border ke tepi border dihitung dengan rumus:
300 + 16 + 16 + 1 + 1 = 334\text{ px}
Jadi, lebar kartu adalah 334 px. Margin 24 px di setiap sisi tidak dihitung karena margin berada di luar border.
Q2 (border-box): Jika ditambahkan box-sizing: border-box, lebar 300 px sudah mencakup content, padding, dan border.
Jadi, lebar kartu menjadi 300 px, sedangkan area content di dalamnya menjadi lebih kecil.
Pengecekan DevTools: Inspect salah satu section kartu melalui DevTools, lalu buka Computed → Box Model. Catat nilai content, padding, border, dan margin sesuai nilai yang benar-benar tampil pada browser.

## Bagian 5: Tabel debug

| # | Baris | Bug | Perbaikan | Cara menemukannya |
|---|---|---|---|---|
| 1 | 6 | Property `colour` tidak valid dalam CSS | Ganti menjadi `color` | Membaca kode CSS |
| 2 | 11 | Tidak ada titik koma setelah deklarasi `background` | Tambahkan `;` setelah `#dbe7f3` | Membaca kode CSS |
| 3 | 16 | Selector `.Card` tidak cocok dengan class `card` karena huruf besar dan kecil berbeda | Ganti `.Card` menjadi `.card` | Memeriksa selector CSS dan class HTML |
| 4 | 23 | Nilai `18 px` memiliki spasi yang tidak tepat | Ganti menjadi `18px` | Memeriksa CSS |
| 5 | 28 | Nilai `centre` bukan nilai yang valid untuk `text-align` | Ganti menjadi `center` | Memeriksa CSS |
| 6 | 40 | Tag `<h1>` ditutup menggunakan `</h2>` | Ganti menjadi `</h1>` | W3C Validator |
| 7 | 46 | Atribut `href` pada link About tidak memiliki tanda kutip penutup | Ganti menjadi `href="about.html"` | W3C Validator |
| 8 | 56 | Gambar tidak memiliki atribut `alt` | Tambahkan `alt="Ilustrasi berita kampus"` | Pemeriksaan aksesibilitas |
| 9 | 58 | Selector menggunakan `#news-list`, tetapi ID HTML adalah `newsList` | Samakan selector CSS menjadi `#newsList` | Memeriksa ID HTML dan selector CSS |

## Bagian 6: Tabel Code Review
| # | Baris | Masalah | Mengapa penting | Perbaikan saya |
|---|-------|---------|-----------------|----------------|

Refleksi:
1.
2.
3.

## Bagian 7: Exit ticket
1.
2.
3.
```

---