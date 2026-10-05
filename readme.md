# Lab3Web - CSS Dasar

Repository ini berisi hasil praktikum Pemrograman Web pertemuan 3 dengan materi CSS Dasar.

## Tujuan

Praktikum ini bertujuan untuk:

1. Memahami konsep dasar CSS.
2. Memahami aturan penulisan CSS.
3. Memahami selector sebagai pengontrol CSS.
4. Membuat pengaturan CSS pada HTML.

## Struktur File

```text
Lab3Web/
├── lab3_css_dasar.html
├── lab3_css_eksternal.html
├── style_eksternal.css
└── README.md
```

## Langkah 1 - Membuat Dokumen HTML

Membuat file `lab2_css_dasar.html` dengan struktur dasar HTML.

Pada tahap ini dibuat halaman sederhana yang berisi header, navigation, heading, paragraf, dan tombol.

## Langkah 2 - CSS Internal

CSS internal ditambahkan pada bagian `<head>` menggunakan tag `<style>`.

CSS digunakan untuk mengatur font, header, heading, warna teks, dan tampilan elemen lainnya.

## Langkah 3 - Inline CSS

Inline CSS diterapkan secara langsung pada elemen HTML menggunakan atribut `style`.

Contohnya:

```html
<p style="text-align: center; color: #ccd8e4;">
    Contoh Inline CSS
</p>
```


## Langkah 4 - CSS Eksternal

Membuat file `style_eksternal.css` untuk menyimpan aturan CSS secara terpisah dari dokumen HTML.

File CSS kemudian dipanggil menggunakan:

```html
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
```


## Langkah 5 - CSS Selector

Pada tahap ini digunakan ID Selector dan Class Selector.

Contoh ID Selector:

```css
#intro {
    background: #418fb1;
}
```

Contoh Class Selector:

```css
.button {
    padding: 15px 20px;
}

.btn-primary {
    background: #E42A42;
}
```

## Langkah 6 - Eksperimen CSS

Dilakukan perubahan dan penambahan beberapa properti CSS seperti:

* `border`
* `padding`
* `margin`
* `border-radius`
* `font-size`
* `line-height`
* `font-weight`
* `opacity`

Contoh:

```css
#intro {
    border: 2px solid #099249;
    padding: 20px;
    margin: 20px;
    border-radius: 10px;
}
```


## Kesimpulan

Pada praktikum ini dipelajari dasar-dasar CSS, cara penulisan CSS secara internal, eksternal, dan inline, serta penggunaan element selector, ID selector, dan class selector.

Selain itu, dilakukan eksperimen dengan beberapa properti CSS untuk mengetahui pengaruhnya terhadap tampilan halaman web.
