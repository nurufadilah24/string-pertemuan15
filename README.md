## Nama:Nurul fadilah
## nim :312410689
## kls :TI.24.A3
# string-pertemuan15

## hasil imput 1

```python
txt = 'Hello World'

Hitung jumlah karakternya
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)

Ambil karakter terakhir
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)

Ambil karakter index ke-2 sampai index ke-4 (llo)
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)

Hilangkan spasi pada teks tersebut (HelloWorld)
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)

Ubah teks menjadi huruf besar
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)

Ubah teks menjadi huruf kecil
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)

Ganti karakter H dengan karakter J
ganti_h = txt.replace("M", "D")
print("Teks setelah mengganti M dengan D:", ganti_h)
```
## Hasil imput latihan 2

```python
umur = 19
txt = 'Hello, nama saya nurul, dan umur saya adalah {} tahun'

print(txt.format(umur))
```
## Hasil Output 1

```Markdown
Jumlah karakter: 11
Karakter terakhir: d
Karakter index ke-2 sampai index ke-4: llo
Teks tanpa spasi: HelloWorld
Teks dalam huruf besar: HELLO WORLD
Teks dalam huruf kecil: hello world
Teks setelah mengganti M dengan D: Hello World
```

## Hasil Output 2
```Markdown
Hello, nama saya nurul, dan umur saya adalah 19 tahun
```
## penjelasan hasil input latihan 1
Berikut adalah penjelasan tentang program yang Anda berikan langkah demi langkah:

```python
txt = 'Hello World'
```

- Di sini, Anda mendeklarasikan sebuah string `txt` yang berisi teks `'Hello World'`. Ini adalah string yang akan diproses dalam berbagai operasi di program.

### 1. Menghitung jumlah karakter dalam string
```python
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)
```

- **`len(txt)`** digunakan untuk menghitung jumlah karakter dalam string `txt`. Dalam hal ini, string `'Hello World'` memiliki 11 karakter (termasuk spasi).
- Program akan mencetak hasilnya: `Jumlah karakter: 11`.

### 2. Mengambil karakter terakhir dari string
```python
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)
```

- **`txt[-1]`** digunakan untuk mengambil karakter terakhir dari string `txt`. Indeks negatif di Python berarti menghitung dari belakang, jadi `txt[-1]` mengambil karakter terakhir.
- Untuk string `'Hello World'`, karakter terakhirnya adalah `'d'`.
- Program akan mencetak hasilnya: `Karakter terakhir: d`.

### 3. Mengambil substring dari index ke-2 hingga index ke-4
```python
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)
```

- **`txt[2:5]`** digunakan untuk mengambil substring dari `txt`, dimulai dari indeks ke-2 hingga indeks ke-4 (indeks akhir tidak termasuk, jadi ini berarti indeks ke-2, ke-3, dan ke-4).
- Dalam hal ini, substring yang diambil adalah `'llo'`, karena pada indeks 2 hingga 4 (dimulai dari 0) dari string `'Hello World'` terdapat karakter 'l', 'l', dan 'o'.
- Program akan mencetak hasilnya: `Karakter index ke-2 sampai index ke-4: llo`.

### 4. Menghilangkan spasi pada string
```python
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)
```

- **`txt.replace(" ", "")`** digunakan untuk mengganti semua spasi (`" "`) dalam string dengan string kosong (`""`). Ini akan menghapus semua spasi dari string.
- Pada string `'Hello World'`, setelah spasi dihapus, hasilnya menjadi `'HelloWorld'`.
- Program akan mencetak hasilnya: `Teks tanpa spasi: HelloWorld`.

### 5. Mengubah string menjadi huruf besar
```python
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)
```

- **`txt.upper()`** mengubah semua karakter dalam string menjadi huruf besar.
- Pada string `'Hello World'`, hasilnya akan menjadi `'HELLO WORLD'`.
- Program akan mencetak hasilnya: `Teks dalam huruf besar: HELLO WORLD`.

### 6. Mengubah string menjadi huruf kecil
```python
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)
```

- **`txt.lower()`** mengubah semua karakter dalam string menjadi huruf kecil.
- Pada string `'Hello World'`, hasilnya akan menjadi `'hello world'`.
- Program akan mencetak hasilnya: `Teks dalam huruf kecil: hello world`.

### 7. Mengganti karakter "M" dengan "D" dalam string
```python
ganti_h = txt.replace("M", "D")
print("Teks setelah mengganti M dengan D:", ganti_h)
```

- **`txt.replace("M", "D")`** akan mengganti setiap karakter "M" dalam string dengan "D". Namun, dalam string `'Hello World'`, tidak ada karakter "M", jadi string ini tetap tidak berubah.
- Hasilnya adalah string `'Hello World'` tanpa ada perubahan.
- Program akan mencetak hasilnya: `Teks setelah mengganti M dengan D: Hello World`.

### Kesimpulan:
Program ini mengilustrasikan beberapa operasi dasar pada string dalam Python, seperti:

- Menghitung panjang string dengan `len()`.
- Mengakses karakter tertentu dengan indeks.
- Mengambil substring dengan slicing.
- Mengganti karakter tertentu dengan `replace()`.
- Mengubah kasus huruf dengan `upper()` dan `lower()`.

Perhatikan bahwa di bagian terakhir, ada sedikit kesalahan logika di mana karakter yang ingin diganti (`"M"`) tidak ada dalam string yang diberikan, sehingga hasilnya tidak berubah.

## penjelasaan hasil input latihan 2
Program yang Anda berikan menggunakan **string formatting** di Python untuk menyisipkan nilai variabel ke dalam string. Berikut adalah penjelasan lengkap tentang program tersebut:

```python
umur = 19
txt = 'Hello, nama saya nurul, dan umur saya adalah {} tahun'

print(txt.format(umur))
```

### Penjelasan Langkah demi Langkah:

1. **Mendeklarasikan variabel `umur`:**
   ```python
   umur = 19
   ```
   Di sini, variabel `umur` di-set dengan nilai `19`, yang berarti umur seseorang adalah 19 tahun.

2. **Mendeklarasikan string template `txt`:**
   ```python
   txt = 'Hello, nama saya nurul, dan umur saya adalah {} tahun'
   ```
   String `txt` adalah sebuah template atau format string yang memiliki satu placeholder yang ditandai dengan `{}`. Placeholder ini nantinya akan digantikan dengan nilai yang diberikan pada saat string tersebut diproses menggunakan metode `format()`.

   - **`{}`** adalah tempat untuk menyisipkan nilai variabel ke dalam string.

3. **Menggunakan metode `format()` untuk menggantikan placeholder:**
   ```python
   print(txt.format(umur))
   ```
   - **`txt.format(umur)`** memanggil metode `format()` pada string `txt`. Metode ini menggantikan setiap placeholder `{}` dalam string dengan argumen yang diberikan di dalam `format()`. Dalam hal ini, argumen yang diberikan adalah nilai dari variabel `umur`, yaitu `19`.
   
   Jadi, `{}` dalam string `'Hello, nama saya nurul, dan umur saya adalah {} tahun'` akan digantikan dengan nilai `19`.

4. **Mencetak hasil:**
   Program kemudian mencetak hasilnya, yang merupakan string yang sudah diubah. Setelah proses penggantian, hasil akhir dari string yang dicetak akan menjadi:

   ```
   Hello, nama saya nurul, dan umur saya adalah 19 tahun
   ```

### Ringkasan:

- Program ini menggunakan **string formatting** dengan `format()` untuk menyisipkan nilai variabel `umur` ke dalam string yang sudah ada.
- Placeholder `{}` akan digantikan dengan nilai yang diteruskan ke dalam metode `format()`.
- Hasil akhirnya adalah string yang sudah terisi dengan nilai umur (`19`), yang kemudian dicetak ke layar.

Jika ada pertanyaan lebih lanjut atau jika Anda ingin memodifikasi program ini, silakan beri tahu!
 

## penjelasan hasil output 1

Tentu! Mari kita jelaskan hasil output yang muncul berdasarkan program yang Anda jalankan dengan lebih detail:

### **Kode Program yang Dijalankan:**

```python
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)

# Hilangkan spasi pada teks tersebut (HelloWorld)
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)

# Ubah teks menjadi huruf besar
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)

# Ubah teks menjadi huruf kecil
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)

# Ganti karakter M dengan karakter D
ganti_h = txt.replace("M", "D")
print("Teks setelah mengganti M dengan D:", ganti_h)
```

### **Penjelasan Output:**

1. **Jumlah karakter: 11**
   - Program menggunakan **`len(txt)`** untuk menghitung panjang string `'Hello World'`. 
     - String `'Hello World'` terdiri dari 11 karakter, termasuk spasi.
     - Hasil yang benar adalah: **Jumlah karakter: 11**.

2. **Karakter terakhir: d**
   - Program menggunakan **`txt[-1]`** untuk mengakses karakter terakhir dari string. 
     - Pada string `'Hello World'`, karakter terakhir adalah `'d'`.
     - Hasil yang benar adalah: **Karakter terakhir: d**.

3. **Karakter index ke-2 sampai index ke-4: llo**
   - Program menggunakan **`txt[2:5]`** untuk mengambil substring dari indeks 2 sampai indeks 4 (indeks akhir tidak termasuk).
     - Pada string `'Hello World'`, indeks 2 sampai 4 berisi karakter `'l'`, `'l'`, dan `'o'`, yang membentuk substring `'llo'`.
     - Hasil yang benar adalah: **Karakter index ke-2 sampai index ke-4: llo**.

4. **Teks tanpa spasi: HelloWorld**
   - Program menggunakan **`txt.replace(" ", "")`** untuk menghilangkan semua spasi dalam string `'Hello World'`.
     - Setelah spasi dihapus, hasilnya adalah `'HelloWorld'`.
     - Hasil yang benar adalah: **Teks tanpa spasi: HelloWorld**.

5. **Teks dalam huruf besar: HELLO WORLD**
   - Program menggunakan **`txt.upper()`** untuk mengubah seluruh string menjadi huruf besar.
     - Hasil dari `'Hello World'` setelah diubah menjadi huruf besar adalah `'HELLO WORLD'`.
     - Hasil yang benar adalah: **Teks dalam huruf besar: HELLO WORLD**.

6. **Teks dalam huruf kecil: hello world**
   - Program menggunakan **`txt.lower()`** untuk mengubah seluruh string menjadi huruf kecil.
     - Hasil dari `'Hello World'` setelah diubah menjadi huruf kecil adalah `'hello world'`.
     - Hasil yang benar adalah: **Teks dalam huruf kecil: hello world**.

### **Hasil Output yang Tidak Terubah:**
7. **Teks setelah mengganti M dengan D: Hello World**
   - Program mencoba mengganti karakter `'M'` dengan `'D'` dalam string `'Hello World'` menggunakan **`txt.replace("M", "D")`**.
     - Namun, pada string `'Hello World'`, tidak ada karakter `'M'`. 
     - Jadi, operasi **`replace("M", "D")`** tidak mengubah apa pun pada string karena karakter `'M'` tidak ditemukan dalam string.
     - Dengan demikian, string tetap tidak berubah dan hasilnya adalah `'Hello World'`.
     - Hasil yang benar adalah: **Teks setelah mengganti M dengan D: Hello World**.

### **Kesimpulan Hasil Output:**
- Semua operasi yang dilakukan pada string `'Hello World'` bekerja dengan baik, kecuali pada bagian **"Teks setelah mengganti M dengan D"**, di mana penggantian karakter `'M'` dengan `'D'` tidak menghasilkan perubahan, karena karakter `'M'` tidak ada dalam string `'Hello World'`.
- Berikut adalah penjelasan rinci untuk setiap operasi yang dilakukan:
  1. **Menghitung panjang string** (jumlah karakter): `11`
  2. **Mengambil karakter terakhir**: `'d'`
  3. **Mengambil substring pada indeks 2 sampai 4**: `'llo'`
  4. **Menghilangkan spasi**: `'HelloWorld'`
  5. **Mengubah menjadi huruf besar**: `'HELLO WORLD'`
  6. **Mengubah menjadi huruf kecil**: `'hello world'`
  7. **Mengganti karakter M dengan D**: tidak ada perubahan (tetap `'Hello World'`).

Jika Anda ingin mengganti karakter yang memang ada dalam string (misalnya mengganti `'H'` menjadi `'J'`), Anda bisa mengganti kode menjadi:

```python
ganti_h = txt.replace("H", "J")
print("Teks setelah mengganti H dengan J:", ganti_h)
```

Hasilnya akan menjadi: **Teks setelah mengganti H dengan J: Jello World**

Apakah penjelasan ini membantu? Jika ada yang ingin Anda coba atau modifikasi lebih lanjut, beri tahu saja!

## hasil output latihan 2
Tentu! Mari kita jelaskan secara rinci bagaimana program yang menghasilkan kalimat berikut:

```
Hello, nama saya nurul, dan umur saya adalah 19 tahun
```

### Penjelasan Hasil Program:

Kalimat ini kemungkinan merupakan **output dari program Python** yang menggunakan **string formatting**. Berdasarkan format yang umum digunakan dalam Python, kemungkinan besar program yang menghasilkan kalimat tersebut menggunakan **metode `.format()`**. 

Berikut adalah contoh program Python yang menghasilkan output tersebut:

### Contoh Program:

```python
umur = 19
txt = 'Hello, nama saya nurul, dan umur saya adalah {} tahun'

# Format string dan cetak hasilnya
print(txt.format(umur))
```

### Langkah-langkah Penjelasan:

1. **Mendeklarasikan Variabel `umur`:**
   ```python
   umur = 19
   ```
   - Program ini mendeklarasikan sebuah variabel bernama `umur` dan memberikan nilai `19`. Nilai ini akan digunakan dalam string untuk menyebutkan umur seseorang.

2. **Mendeklarasikan String Template `txt`:**
   ```python
   txt = 'Hello, nama saya nurul, dan umur saya adalah {} tahun'
   ```
   - Variabel `txt` berisi sebuah string yang memiliki **placeholder** `{}`. Placeholder ini adalah tempat yang nantinya akan digantikan oleh nilai variabel saat menggunakan **metode `.format()`**.

3. **Menggunakan `.format()` untuk Menyisipkan Nilai ke dalam String:**
   ```python
   print(txt.format(umur))
   ```
   - Di sini, program memanggil **`txt.format(umur)`** untuk menggantikan placeholder `{}` dalam string `txt` dengan nilai dari variabel `umur`, yaitu `19`.
   - Jadi, string `'Hello, nama saya nurul, dan umur saya adalah {} tahun'` setelah diproses akan menjadi `'Hello, nama saya nurul, dan umur saya adalah 19 tahun'`.

4. **Mencetak Hasil:**
   - Hasil akhir yang dicetak ke layar adalah:
   
   ```
   Hello, nama saya nurul, dan umur saya adalah 19 tahun
   ```

### Penjelasan Metode `.format()`:

- **`.format()`** adalah metode yang digunakan untuk **memasukkan variabel atau nilai** ke dalam string template.
- Anda bisa menggunakan placeholder `{}` di dalam string dan menggantinya dengan nilai yang dimasukkan melalui `.format()`.
- Sintaks umumnya adalah seperti ini:
  ```python
  "template string {}".format(value)
  ```

  - **`{}`** adalah tempat untuk memasukkan nilai.
  - **`.format(value)`** menggantikan `{}` dengan nilai yang diberikan (dalam hal ini `umur` yang berisi angka `19`).

### Contoh Lain Menggunakan `.format()`:

```python
nama = "Nurul"
umur = 19
txt = "Halo, nama saya {}, dan umur saya adalah {} tahun"
print(txt.format(nama, umur))
```

Hasil outputnya akan menjadi:

```
Halo, nama saya Nurul, dan umur saya adalah 19 tahun
```

### **Kesimpulan:**

Program yang menghasilkan kalimat ini menggunakan **string formatting** dengan metode `.format()`. Berikut adalah langkah-langkah yang dilakukan:
1. **Variabel `umur`** diisi dengan nilai 19.
2. **String template `txt`** berisi placeholder `{}` untuk menyisipkan nilai `umur`.
3. **`txt.format(umur)`** digunakan untuk menggantikan placeholder `{}` dengan nilai dari variabel `umur`, menghasilkan kalimat lengkap.
4. Program mencetak kalimat yang sudah diformat dengan benar: 
   
   ```
   Hello, nama saya nurul, dan umur saya adalah 19 tahun
   ```

Jika ada pertanyaan lebih lanjut atau hal lain yang ingin Anda bahas, silakan beri tahu!




