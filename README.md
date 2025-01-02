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
