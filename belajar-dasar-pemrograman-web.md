# Belajar Dasar Pemrograman Web 

## A. Pendahuluan

### apa itu website?

**Website adalah sebuah halaman yang menampilkan informasi berupa teks atau gambar.** Berbeda dengan koran, majalah ataupun media informasi lainnya, **website dapat diakses melalui internet menggunakan browser. Website ini unik karena tiap halaman dapat saling terhubung dengan menggunakan hypertext links.** 

Website merupakan teknologi yang sudah ada sejak 30 tahun silam. Tim Berners-Lee seorang ilmuwan Inggris menemukan World Wide Web (WWW) pada tahun 1989 ketika ia bekerja di CERN (Conseil Européen pour la Recherche Nucléaire). Web awalnya dibuat dan dikembangkan untuk memenuhi permintaan dalam berbagi informasi secara otomatis antar ilmuwan di universitas dan lembaga di seluruh dunia.

Kini, website sudah berkembang sangat pesat. Website digunakan tidak hanya untuk media berbagi informasi atau berita. Layaknya sebuah aplikasi pada komputer dan handphone kita, website dapat digunakan untuk komunikasi secara real-time, mendengarkan sebuah lagu, bahkan photo editing sekarang dapat dilakukan pada sebuah website.

Informasi pada sebuah website disimpan pada server (web server). client (browser) dapat melakukan request ke server kemudian server akan memberi respon. dalam prosesnya terdapat http server dan dns server. 

Proses client melakukan request, terjadi di sisi client (client side) sementara proses menanggapi, menyediakan, dan mengelola data yang diminta oleh client, terjadi di sisi server (server side).

Istilah server merujuk pada sebuah software yg bertugas menanggapi, menyediakan, dan mengelola data yang diminta oleh client. komputer yg dijadikan server biasanya berspek tinggi, tujuannya agar bisa mengakomodir semua kebutuhan client.

### anatomi website
Tiga teknologi utama dalam membangun website:  
* HTML for content (mengatur format dan struktur pada website)  
* CSS for presentation  
* Javascript for behavior  

---

## B. Pengenalan HTML
### struktur html
```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible"  content="IE=edge">
  <meta name="viewport"  content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <p>ini konten</p>
</body>
</html>
```
Elemen `<head>` pada berkas HTML berfungsi sebagai tempat disimpannya informasi tambahan dari dokumen HTML.

Sementara seluruh tag yang terdapat pada elemen `<body>` akan ditampilkan pada halaman website. 

### tag-tag pada HTML
Kita akan berkenalan lebih dalam mengenai elemen yang ada pada HTML. Sehingga, kita dapat memilih elemen yang sesuai dalam menampilkan sebuah konten pada website.

* attribute  
contoh tag `<p>` menggunakan atribut `class` dengan nilai `"konten-utama"`
```bash 
<p class="konten-utama">ini adalah konten</p>
```

    <html>
      <head></head>
      <body>
        <p>halo</p>
      </body>
    </html>

ada 2 jenis attribute, global attribute dan attribute yg hanya bisa digunakan pada elemen tertentu.

  **Global attribute**
  | Attribute       | Description                                                                                                |
  | --------------- | ---------------------------------------------------------------------------------------------------------- |
  | accesskey       | Menentukan tombol shortcut untuk mengaktifkan/memfokuskan pada sebuah element.                             |
  | contenteditable | Menentukan konten dari elemen merupakan konten yang dapat diubah atau tidak.                               |
  | data-*          | Digunakan untuk menyimpan sebuah data pribadi khusus ke halaman atau aplikasi.                             |
  | dir             | Menentukan arah teks untuk konten pada suatu elemen.                                                       |
  | draggable       | Menentukan apakah suatu elemen dapat di-drag atau tidak.                                                   |
  | dropzone        | Menentukan apakah data yang di-drag adalah data yang disalin, dipindahkan, atau ditautkan saat dijatuhkan. |
  | hidden          | Menentukan apakah suatu elemen ditampilkan atau tidak pada browser.                                        |
  | spellcheck      | Menentukan apakah elemen harus diperiksa ejaannya dan tata bahasanya atau tidak.                           |
  | id              | Menetapkan id pada elemen.                                                                                 |
  | lang            | Menentukan bahasa pada konten elemen.                                                                      |
  | tabindex        | Menentukan urutan dari suatu elemen.                                                                       |
  | translate       | Menentukan apakah konten elemen harus diterjemahkan atau tidak.                                            |
  | style           | Menentukan styling secara satu baris untuk suatu elemen.                                                   |
  | title           | Menentukan informasi tambahan tentang suatu elemen.                                                        |
 
 * paragraf
   ```bash
   <p>ini adalah paragraf</p>
   ```
   result:
   <p>ini adalah paragraf</p>
 * heading
   ```bash
    <h1>ini heading 1</h1>
    <h2>ini heading 2</h2>
    <h3>ini heading 3</h3>
    <h4>ini heading 4</h4>
    <h5>ini heading 5</h5>
    <h6>ini heading 6</h6>
   ```
   result:
   <h1>ini heading 1</h1>
   <h2>ini heading 2</h2>
   <h3>ini heading 3</h3>
   <h4>ini heading 4</h4>
   <h5>ini heading 5</h5>
   <h6>ini heading 6</h6>
 * list  
   **unordered list**
      ```bash
      <ul>
        <li>daftar tanpa urutan</li>
        <li>daftar tanpa urutan</li>
        <li>daftar tanpa urutan</li>
      </ul>
      ```
      result:
      <ul>
        <li>daftar tanpa urutan</li>
        <li>daftar tanpa urutan</li>
        <li>daftar tanpa urutan</li>
      </ul>  

   **ordered list** 
      ```bash
      <ol>
        <li>daftar terurut</li>
        <li>daftar terurut</li>
        <li>daftar terurut</li>
      </ol>
      ```
      **attribute**  
      type="1"

      result:
      <ol>
        <li>daftar terurut</li>
        <li>daftar terurut</li>
        <li>daftar terurut</li>
      </ol> 

   **description list**    

 * gambar
 * teks terformat
 * link/anchor, emphasized text, important text, dan short quotation
 * citation
 * semantic HTML
 * generic element
 * tabel
 * special character
 * form

> Teks yang berada pada dokumen HTML tanpa tags disebut “anonymous text” dan ini dapat menyebabkan dokumen HTML menjadi tidak valid.

---

## C. Pengenalan CSS
### melampirkan berkas CSS
### konsepsi pada CSS
### tipe selector
   #### basic selector
   type, class, id, attribute, universal selector
   #### combinator
   adjacent sibling selector (+), seinduk dan tepat setelah elemen pertama

   general sibling selector (~), seinduk dan semua elemen setelah elemen pertama

   child selector (>), semua 'child langsung'
   descendant selector (spasi), semua turunan meski bukan child langsung
   #### pseudo selector
   pseudo-class selector (`:`) => a:hover
   pseudo-elemen selector (`::`) => a::hover
### formatting text
   #### text style
   #### font style
### warna
### box model 
### positioning
### layouting
   #### teknik floating.
   #### teknik flexbox.


 