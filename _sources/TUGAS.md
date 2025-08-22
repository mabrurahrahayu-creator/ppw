# TUGAS
## Pengantar Web Mining

Penambangan web adalah proses menemukan dan mengekstrak informasi dari internet menggunakan berbagai teknik penambangan data. Informasi ini dapat digunakan oleh perusahaan untuk pengambilan keputusan yang efektif. Berdasarkan tugas pokok yang dilakukan dalam proses menambang, web mining dapat kelompokkan menjadi tiga bentuk, yaitu Web Structure Mining, Web Content Mining, dan Web Usage Mining
1. Web struktur Mining : Web structure mining adalah tugas untuk menemukan pengetahuan yang bermanfaat dari hyperlink (atau link singkatnya), yang menyatakan struktur dari dari web. Misalkan dari link-link kita dapat menemukan web page penting, yang menjadi teknologi utama yang digunakan dalam mesin pencarian. Kita dapat juga menemukan komunitas dalam media sosial. Datamining biasa tidak melakukan tugas tersebut, karena tidak ada struktur link dalam tabel tradisional.
2. Web Content Mining. Web content mining adalah mengektrak atau menambang informasi yang berguna atau pengetahuan dari isi halam web. Misalkan kita dapat secara otomatis mengklasifikasikan dan mengelompokkan halam wen sesuai deng topiknya. Tugas ini sama dengan data mining biasa. Akan tetapi kita juga dapat menemukan pla dalam web site untuk mengektrak data yang berguna seperti deskripsi produk, postingan forum, dan lain sebagainya untuk banyak tujuan. Selanjutnya kita dapa menambang ulasan dan postingan dari forum untuk menemukan opini konsumen. Disin tidak ada pada data mining tradisional.

## Definisi

Penambangan web adalah penggunaan teknik penambangan data untuk secara otomatis menemukan dan mengekstrak informasi dari layanan web" (Etzioni, 1996; CACM 39). 
Penambangan web bertujuan untuk menemukan pola-pola berguna atau  pengetahuan dari struktur hiperlink web, isi halaman web, serta perilaku pengguna." (Bing Liu, 2007, Web Data Mining).

## Tantangan pemrosesan data web 

- Web adalah pangkalan data yang sangat besar.
- Datanya dalam format HTML,XML, text
- Tantangan pemrosesan data Web
    - Web adalah sangat besar untuk dilakukan penambanagn data
    - web sangat komplek
    - web sangat dinamis
    - web bukan domain yang spesifik
    - web adalah segalanya.
    
## Sample Roles and Directives

Roles and directives are two of the most powerful tools in Jupyter Book. They
are like functions, but written in a markup language. They both
serve a similar purpose, but **roles are written in one line**, whereas
**directives span many lines**. They both accept different kinds of inputs,
and what they do with those inputs depends on the specific role or directive
that is being called.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
