# Java Virtual Machine (JVM) Handbook

Repository ini berisi dokumentasi dari cara kerja dan gambaran besar
cara kerja dari JVM (Java Virtual Machine). Dokumen ini dibuat oleh 
pengembang [blibli.com](https://www.blibli.com/) sebagai acuan untuk:

1. mendalami cara kerja dari JVM, 
2. melakukan *tuning* dari berbagai aspek dalam JVM, dan
3. menjadi wadah referensi detil tentang JVM berbahasa Indonesia.

Dokumen ini dikembangkan menggunakan [asciidoctor](http://asciidoctor.org).

## Akses Dokumen

Hasil kompilasi buku ini dapat dibaca pada:

1. [Format HTML](#)
2. [Format PDF](#)

## Cara Membuat Dokumen

Untuk dapat membuat keluaran HTML dari dokumen ini, terlebih dahulu
pastikan anda memiliki:

* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [asciidoctor](http://www.asciidoctor.org/)

Jalankan perintah berikut untuk membuat HTML dari sumber kode:

```bash
$ asciidoctor source/index.adoc
```

dan hasil dokumen dapat diakses pada `source/index.html`. Script 
pembuatan PDF dan HTML yang baik akan dikembangkan sesegara mungkin.

## Kontribusi

Jika anda menemukan kesalahan, kekurangan, atau perbaikan yang dapat 
dilakukan, silahkan berikan kontribusi anda melalui pull request! 
Kontribusi anda sangat diharapkan dan diinginkan!
