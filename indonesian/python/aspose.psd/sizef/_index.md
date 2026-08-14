---
title: "Kelas SizeF"
type: docs
weight: 4090
url: /id/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [SizeF()](#SizeF__1) | Menginisialisasi instance baru dari kelas SizeF |
| [SizeF(point)](#SizeF_point_2) | Menginisialisasi instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. |
| [SizeF(size)](#SizeF_size_3) | Menginisialisasi instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan. |
| [SizeF(width, height)](#SizeF_width_height_4) | Menginisialisasi instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari dimensi yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Mendapatkan instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang memiliki nilai [SizeF.width](/psd/python-net/aspose.psd/sizef/) dan [SizeF.height](/psd/python-net/aspose.psd/sizef/) diatur ke nol. |
| height | float | r/w | Mendapatkan atau mengatur komponen vertikal dari [SizeF](/psd/python-net/aspose.psd/sizef/) ini. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah [SizeF](/psd/python-net/aspose.psd/sizef/) ini memiliki lebar dan tinggi nol. |
| width | float | r/w | Mendapatkan atau mengatur komponen horizontal dari [SizeF](/psd/python-net/aspose.psd/sizef/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Menambahkan lebar dan tinggi dari satu struktur [SizeF](/psd/python-net/aspose.psd/sizef/) ke lebar dan tinggi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) lainnya. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Mengurangi lebar dan tinggi dari satu struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari lebar dan tinggi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) lainnya. |
| [to_point_f()](#to_point_f__3) | Mengonversi [SizeF](/psd/python-net/aspose.psd/sizef/) menjadi [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Mengonversi [SizeF](/psd/python-net/aspose.psd/sizef/) menjadi struktur [Size](/psd/python-net/aspose.psd/size/) dengan nilai ukuran terpotong. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Menginisialisasi instance baru dari kelas SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Menginisialisasi instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) dari mana untuk menginisialisasi [SizeF](/psd/python-net/aspose.psd/sizef/) ini. |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Menginisialisasi instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari [SizeF](/psd/python-net/aspose.psd/sizef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | [SizeF](/psd/python-net/aspose.psd/sizef/) dari mana untuk membuat [SizeF](/psd/python-net/aspose.psd/sizef/) baru. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Menginisialisasi instance baru dari struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari dimensi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | float | Komponen lebar dari [SizeF](/psd/python-net/aspose.psd/sizef/) baru. |
| height | float | Komponen tinggi dari [SizeF](/psd/python-net/aspose.psd/sizef/) baru. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Menambahkan lebar dan tinggi dari satu struktur [SizeF](/psd/python-net/aspose.psd/sizef/) ke lebar dan tinggi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Yang pertama [SizeF](/psd/python-net/aspose.psd/sizef/) untuk ditambahkan. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Yang kedua [SizeF](/psd/python-net/aspose.psd/sizef/) untuk ditambahkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Sebuah struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang merupakan hasil operasi penjumlahan. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Mengurangi lebar dan tinggi dari satu struktur [SizeF](/psd/python-net/aspose.psd/sizef/) dari lebar dan tinggi struktur [SizeF](/psd/python-net/aspose.psd/sizef/) lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Struktur [SizeF](/psd/python-net/aspose.psd/sizef/) di sisi kiri operator pengurangan. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Struktur [SizeF](/psd/python-net/aspose.psd/sizef/) di sisi kanan operator pengurangan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Struktur [SizeF](/psd/python-net/aspose.psd/sizef/) yang merupakan hasil operasi pengurangan. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Mengonversi [SizeF](/psd/python-net/aspose.psd/sizef/) menjadi [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Mengembalikan sebuah struktur [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Mengonversi [SizeF](/psd/python-net/aspose.psd/sizef/) menjadi struktur [Size](/psd/python-net/aspose.psd/size/) dengan nilai ukuran terpotong.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Mengembalikan sebuah struktur [Size](/psd/python-net/aspose.psd/size/). |


