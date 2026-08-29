---
title: "ColorComponent"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Komponen warna adalah abstraksi atas Nilai Kanal dan Nilai Kanal."
type: docs
weight: 10
url: /id/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Komponen warna adalah abstraksi atas Channel Value dan Channel Value. Setiap warna terdiri dari array ColorComponent
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Menginisialisasi instance baru dari kelas [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Mendapatkan kedalaman bit dari Komponen Warna/Saluran |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Mendapatkan deskripsi Komponen Warna |
| [getFullName()](#getFullName--) | Mendapatkan nama lengkap komponen warna dengan nama dan deskripsi dipisahkan spasi |
| [getName()](#getName--) | Mendapatkan nama komponen warna. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Mendapatkan nama lengkap yang diizinkan. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Mendapatkan atau mengatur nilai. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Menginisialisasi instance baru dari kelas [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Silakan periksa

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitDepth | byte | Kedalaman bit |
| fullName | java.lang.String | Nama lengkap. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Mendapatkan kedalaman bit dari Komponen Warna/Saluran

Nilai: Kedalaman bit.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Mendapatkan deskripsi Komponen Warna

Nilai: Deskripsi.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Mendapatkan nama lengkap komponen warna dengan nama dan deskripsi dipisahkan spasi

Nilai: Nama lengkap.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama komponen warna.

Nilai: Nama.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Mendapatkan nama lengkap yang diizinkan.

Nilai: Nama lengkap yang diizinkan.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Mendapatkan atau mengatur nilai. Harap perhatikan, jika Anda mencoba mengatur nilai yang lebih besar daripada yang dapat disimpan dalam kedalaman bit saat ini, Anda akan mendapatkan pengecualian

Nilai: Nilai.

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Mendapatkan atau mengatur nilai. Harap perhatikan, jika Anda mencoba mengatur nilai yang lebih besar daripada yang dapat disimpan dalam kedalaman bit saat ini, Anda akan mendapatkan pengecualian

Nilai: Nilai.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

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

