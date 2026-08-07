---
title: "Blend"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan pola pencampuran."
type: docs
weight: 11
url: /id/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Mendefinisikan pola campuran. Kelas ini tidak dapat diwarisi.

Penggunaan tipikal kelas blend adalah mendefinisikan pola campuran untuk kuas. Oleh karena itu properti blend harus diinisialisasi dengan hati-hati. Array null tidak diizinkan. Kuas akan melempar pengecualian yang sesuai jika array faktor blend atau posisi kosong atau panjangnya tidak sama. Jika terdapat dua atau lebih elemen dalam array posisi, maka elemen pertama harus 0 dan yang terakhir harus 1.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Blend()](#Blend--) | Menginisialisasi sebuah instance baru dari kelas  Blend . |
| [Blend(int count)](#Blend-int-) | Menginisialisasi sebuah instance baru dari kelas  Blend  dengan jumlah faktor dan posisi yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Menguji apakah objek yang ditentukan adalah kelas  com.aspose.psd.Blend  dan setara dengan kelas  com.aspose.psd.Blend  ini. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Mendapatkan array faktor blend untuk gradien. |
| [getPositions()](#getPositions--) | Mendapatkan array posisi blend untuk gradien. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Mengatur array faktor blend untuk gradien. |
| [setPositions(float[] value)](#setPositions-float---) | Mengatur array posisi blend untuk gradien. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Menginisialisasi sebuah instance baru dari kelas  Blend . Jumlah elemen dalam array faktor dan blend akan sama dengan 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Menginisialisasi sebuah instance baru dari kelas  Blend  dengan jumlah faktor dan posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| count | int | Jumlah elemen dalam array faktor dan posisi. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menguji apakah objek yang ditentukan adalah kelas  com.aspose.psd.Blend  dan setara dengan kelas  com.aspose.psd.Blend  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - True jika  obj  adalah kelas  com.aspose.psd.Blend  yang setara dengan kelas  com.aspose.psd.Blend  ini; jika tidak, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Mendapatkan array faktor blend untuk gradien.

**Returns:**
float[] - Array faktor blend yang menentukan persentase warna awal dan warna akhir yang akan digunakan pada posisi yang bersesuaian.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Mendapatkan array posisi blend untuk gradien.

**Returns:**
float[] - Array posisi blend yang menentukan persentase jarak sepanjang garis gradien.
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




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Mengatur array faktor blend untuk gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float[] | Array faktor blend yang menentukan persentase warna awal dan warna akhir yang akan digunakan pada posisi yang bersesuaian. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Mengatur array posisi blend untuk gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float[] | Array posisi blend yang menentukan persentase jarak sepanjang garis gradien. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

