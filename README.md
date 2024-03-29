# Vocalython
Teknik Kompilasi
Vocalython dibuat dengan library sly
[Library SLY](https://sly.readthedocs.io/en/latest/sly.html).

## Anggota Kelompok:
- Amira Hevatasha       
- Dian Alya Korzakhin
- Kibar Laksono

---

# Dokumentasai

## Tentang

- [x] Vocalython dibuat dengan library SLY [PYTHON version 3.7.1](https://www.python.org/ "Python")
- [x] Vocalython berekstensi .vcl

## Sintaks

| Vocalython |  MEAN  |
| ---------- |  ----  |
| JK         |  IF    |
| CTK        |  PRINT |
| MK         |  THEN  |
| LN         |  ELSE  |
| NTK        |  FOR   |
| FNGS       |  FUN   |
| SMP        |  TO    |
| ->         |  ARROW |


## CARA MENGGUNAKAN 

**Langkah-langkah**

1. Buka CMD atau terminal dengan direktori berikut `cd .../Vocalython/`
2. Lalu run file main.py in the Vocalython folder

for ex:
copy paste teks berikut ke CMD/terminal
```
python .main.py .bahasa.vcl
```

**_Vocalython siap dijalankan_**

> edit dan sesuaikan `Bahasa.vcl`

## Contoh penggunaan Vocalython

### Mencetak "Hello world"

**Contoh 1:**
```
CTK "Hello World" 
```

**Hasil**
```
Hello World
```

**Contoh 2:**
```
a= "Hello World"
CTK a 
```

**Hasil**
```
"Hello World"
```

### Penjumlahan, Pengurangan, Perkalian, Pembagian


**Contoh 1:**
```
8+1
5-1
2*4
8/4
```

**Hasil**
```
9
4
8
2
```

**Contoh 2:**
```
a=8
b=4
CTK a+b
CTK a-b
CTK a*b
CTK a/b
```

**Hasil**
```
12
4
32
2
```

### IF ELSE 

> IF _expr_ THEN _stmt1_ ELSE _stmt2_

**Contoh:**
```
a=6
b="benar"
c="salah"
JK a==6 MK CTK b LN CTK c
```

**Hasil**
```
"benar"
```

### FOR

> FOR _expr_ TO _stmt1_ THEN _stmt2_

**Contoh:**
```
NTK i=0 OT 5 MK CTK i
```

**hasil**
```
0
1
2
3
4
```

### Function

> NUF functionName() -> Your Code Here...

**Contoh 1::**
```
FNGS Contoh1() -> CTK "Penggunaan Fungsi"

Contoh1()
```

**Hasil**
```
Penggunaan Fungsi
```

### Menggunakan Komentar

> Menggunakan Komentar bisa dengan menambahkan `"#"` di awal code.

**Contoh**
```
I = "U" #tapi U bukan I
JK I == "U" MK CTK "Bagus" LN CTK "Jelek"
#Begitulah cara menggunakan komentar
```

**result**
```
"Bagus"
```

Terima kasih

# NOTE
This is a modified source code for the howCode programming language series.

You can watch the video accompanying this series here: [https://www.youtube.com/playlist?list=PLBOh8f9FoHHgPEbiK-FSdSw3FiyP78fbk](https://www.youtube.com/playlist?list=PLBOh8f9FoHHgPEbiK-FSdSw3FiyP78fbk)