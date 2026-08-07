---
title: "TiffSRational"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Tipe rasional tiff."
type: docs
weight: 13
url: /id/java/com.aspose.psd.fileformats.tiff/tiffsrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Tipe rasional tiff.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Menginisialisasi instance baru dari kelas TiffSRational. |
| [TiffSRational(int value)](#TiffSRational-int-) | Menginisialisasi instance baru dari kelas TiffRational. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Menginisialisasi instance baru dari kelas TiffSRational. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Epsilon](#Epsilon) | Epsilon untuk perhitungan pecahan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximateFraction(float value)](#approximateFraction-float-) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Mendekati nilai yang diberikan menjadi sebuah pecahan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Object yang ditentukan sama dengan instance ini. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Mendapatkan penyebut. |
| [getNominator()](#getNominator--) | Mendapatkan pembilang. |
| [getValue()](#getValue--) | Mendapatkan nilai float. |
| [getValueD()](#getValueD--) | Mendapatkan nilai double. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan sebuah  System.String  yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Menginisialisasi instance baru dari kelas TiffSRational.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Menginisialisasi instance baru dari kelas TiffRational.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Nilai pembilang. |

Pembilang akan digunakan sebagai nilai yang ditentukan dan penyebut akan sama dengan 1. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Menginisialisasi instance baru dari kelas TiffSRational.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pembilang | int | Pembilang. |
| penyebut | int | Penyebut. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


Epsilon untuk perhitungan pecahan

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai. |
| epsilon | double | Kesalahan yang diizinkan. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Mendekati nilai yang diberikan menjadi sebuah pecahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai. |
| epsilon | double | Kesalahan yang diizinkan. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Object yang ditentukan sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Object yang akan dibandingkan dengan instance ini. |

**Returns:**
boolean -  true  jika Object yang ditentukan sama dengan instance ini; jika tidak,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Mendapatkan penyebut.

Nilai: Penyebut.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Mendapatkan pembilang.

Nilai: Pembilang.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Mendapatkan nilai float.

Nilai: Nilai float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Mendapatkan nilai double.

Nilai: Nilai double.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Mengembalikan sebuah  System.String  yang mewakili instance ini.

**Returns:**
java.lang.String - Sebuah  System.String  yang mewakili instance ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

