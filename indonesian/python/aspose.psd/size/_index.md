---
title: "Kelas Size"
type: docs
weight: 4080
url: /id/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Size()](#Size__1) | Menginisialisasi instance baru dari kelas Size |
| [Size(point)](#Size_point_2) | Menginisialisasi instance baru dari struktur [Size](/psd/python-net/aspose.psd/size/) dari [Point](/psd/python-net/aspose.psd/point/) yang ditentukan. |
| [Size(width, height)](#Size_width_height_3) | Menginisialisasi instance baru dari struktur [Size](/psd/python-net/aspose.psd/size/) dari dimensi yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Mendapatkan instance baru dari struktur [Size](/psd/python-net/aspose.psd/size/) yang memiliki nilai [Size.width](/psd/python-net/aspose.psd/size/) dan [Size.height](/psd/python-net/aspose.psd/size/) diatur ke nol. |
| height | int | r/w | Mendapatkan atau mengatur komponen vertikal dari [Size](/psd/python-net/aspose.psd/size/) ini. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah [Size](/psd/python-net/aspose.psd/size/) ini memiliki lebar dan tinggi 0. |
| width | int | r/w | Mendapatkan atau mengatur komponen horizontal dari [Size](/psd/python-net/aspose.psd/size/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Menambahkan lebar dan tinggi satu struktur [Size](/psd/python-net/aspose.psd/size/) ke lebar dan tinggi struktur [Size](/psd/python-net/aspose.psd/size/) lainnya. |
| [ceiling(size)](#ceiling_size_2) | Mengonversi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan ke struktur [Size](/psd/python-net/aspose.psd/size/) dengan membulatkan nilai-nilai struktur [Size](/psd/python-net/aspose.psd/size/) ke nilai bilangan bulat lebih tinggi berikutnya. |
| [round(size)](#round_size_3) | Mengonversi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan menjadi struktur [Size](/psd/python-net/aspose.psd/size/) dengan membulatkan nilai-nilai struktur [SizeF](/psd/python-net/aspose.psd/sizef/) ke nilai bulat terdekat. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Mengurangi lebar dan tinggi satu struktur [Size](/psd/python-net/aspose.psd/size/) dari lebar dan tinggi struktur [Size](/psd/python-net/aspose.psd/size/) lainnya. |
| [truncate(size)](#truncate_size_5) | Mengonversi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan menjadi struktur [Size](/psd/python-net/aspose.psd/size/) dengan memotong nilai-nilai struktur [SizeF](/psd/python-net/aspose.psd/sizef/) ke nilai bulat lebih rendah berikutnya. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Menginisialisasi instance baru dari kelas Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Menginisialisasi instance baru dari struktur [Size](/psd/python-net/aspose.psd/size/) dari [Point](/psd/python-net/aspose.psd/point/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) dari mana untuk menginisialisasi [Size](/psd/python-net/aspose.psd/size/) ini. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Menginisialisasi instance baru dari struktur [Size](/psd/python-net/aspose.psd/size/) dari dimensi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Komponen lebar dari [Size](/psd/python-net/aspose.psd/size/) baru. |
| height | int | Komponen tinggi dari [Size](/psd/python-net/aspose.psd/size/) baru. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Menambahkan lebar dan tinggi satu struktur [Size](/psd/python-net/aspose.psd/size/) ke lebar dan tinggi struktur [Size](/psd/python-net/aspose.psd/size/) lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) pertama untuk ditambahkan. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) kedua untuk ditambahkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Sebuah struktur [Size](/psd/python-net/aspose.psd/size/) yang merupakan hasil operasi penjumlahan. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Mengonversi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan ke struktur [Size](/psd/python-net/aspose.psd/size/) dengan membulatkan nilai-nilai struktur [Size](/psd/python-net/aspose.psd/size/) ke nilai bilangan bulat lebih tinggi berikutnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Struktur [Size](/psd/python-net/aspose.psd/size/) yang dikonversi oleh metode ini. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Mengonversi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan menjadi struktur [Size](/psd/python-net/aspose.psd/size/) dengan membulatkan nilai-nilai struktur [SizeF](/psd/python-net/aspose.psd/sizef/) ke nilai bulat terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Struktur [Size](/psd/python-net/aspose.psd/size/) yang dikonversi oleh metode ini. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Mengurangi lebar dan tinggi satu struktur [Size](/psd/python-net/aspose.psd/size/) dari lebar dan tinggi struktur [Size](/psd/python-net/aspose.psd/size/) lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Struktur [Size](/psd/python-net/aspose.psd/size/) di sisi kiri operator pengurangan. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Struktur [Size](/psd/python-net/aspose.psd/size/) di sisi kanan operator pengurangan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) yang merupakan hasil operasi pengurangan. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Mengonversi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan menjadi struktur [Size](/psd/python-net/aspose.psd/size/) dengan memotong nilai-nilai struktur [SizeF](/psd/python-net/aspose.psd/sizef/) ke nilai bulat lebih rendah berikutnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Struktur [Size](/psd/python-net/aspose.psd/size/) yang dikonversi oleh metode ini. |


