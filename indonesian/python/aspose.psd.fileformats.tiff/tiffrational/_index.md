---
title: "Kelas TiffRational"
type: docs
weight: 30
url: /id/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| EPSILON [statis] | double | r | Epsilon untuk perhitungan pecahan |
| penyebut | uint | r | Mendapatkan penyebut. |
| pembilang | uint | r | Mendapatkan pembilang. |
| value | float | r | Mendapatkan nilai float. |
| value_d | double | r | Mendapatkan nilai double. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pembilang | uint | Pembilang. |
| penyebut | uint | Penyebut. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | uint | Nilai pembilang. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | double | Nilai value. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Sebuah bilangan rasional dengan kesalahan kurang dari [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | float | Nilai value. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Sebuah bilangan rasional dengan kesalahan kurang dari [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | double | Nilai value. |
| epsilon | double | Kesalahan yang diizinkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Sebuah bilangan rasional dengan kesalahan kurang dari <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | float | Nilai value. |
| epsilon | double | Kesalahan yang diizinkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Sebuah bilangan rasional dengan kesalahan kurang dari <paramref name="epsilon" />. |


