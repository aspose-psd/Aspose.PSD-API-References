---
title: "Kelas TiffSRational"
type: docs
weight: 40
url: /id/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Menginisialisasi sebuah instance baru dari kelas [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Menginisialisasi sebuah instance baru dari kelas [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| EPSILON [statis] | double | r | Epsilon untuk perhitungan pecahan |
| penyebut | int | r | Mendapatkan penyebut. |
| pembilang | int | r | Mendapatkan pembilang. |
| value | float | r | Mendapatkan nilai float. |
| value_d | double | r | Mendapatkan nilai double. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Menginisialisasi sebuah instance baru dari kelas [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pembilang | int | Pembilang. |
| penyebut | int | Penyebut. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | int | Nilai pembilang. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Sebuah bilangan rasional yang memiliki kesalahan kurang dari [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Sebuah bilangan rasional yang memiliki kesalahan kurang dari [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Sebuah bilangan rasional dengan kesalahan kurang dari <paramref name="epsilon" />. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Sebuah bilangan rasional dengan kesalahan kurang dari <paramref name="epsilon" />. |


