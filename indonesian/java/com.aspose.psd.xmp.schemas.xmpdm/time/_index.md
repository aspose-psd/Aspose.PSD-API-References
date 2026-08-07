---
title: "Time"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Representasi nilai waktu dalam detik."
type: docs
weight: 13
url: /id/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Representasi nilai waktu dalam detik.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Menginisialisasi sebuah instance baru dari kelas Time. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Mendapatkan atau mengatur skala untuk nilai waktu. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai waktu dalam skala yang ditentukan. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Mendapatkan nilai string yang terkandung dalam format XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Mendapatkan atau mengatur skala untuk nilai waktu. |
| [setValue(int value)](#setValue-int-) | Mendapatkan atau mengatur nilai waktu dalam skala yang ditentukan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Menginisialisasi sebuah instance baru dari kelas Time.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | Skala. |
| nilai | int | Nilai. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getScale() {#getScale--}
```
public Rational getScale()
```


Mendapatkan atau mengatur skala untuk nilai waktu.

Untuk NTSC, gunakan 1001/30000, atau yang kurang akurat 100/2997. Untuk PAL, gunakan 1/25. Nilai: Skala untuk nilai waktu.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Mendapatkan atau mengatur nilai waktu dalam skala yang ditentukan.

Nilai: Nilai waktu dalam skala yang ditentukan.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Mendapatkan nilai string yang terkandung dalam format XMP.

**Returns:**
java.lang.String - Mengembalikan nilai string yang terkandung dalam format XMP.
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Mendapatkan atau mengatur skala untuk nilai waktu.

Untuk NTSC, gunakan 1001/30000, atau yang kurang akurat 100/2997. Untuk PAL, gunakan 1/25. Nilai: Skala untuk nilai waktu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Mendapatkan atau mengatur nilai waktu dalam skala yang ditentukan.

Nilai: Nilai waktu dalam skala yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

