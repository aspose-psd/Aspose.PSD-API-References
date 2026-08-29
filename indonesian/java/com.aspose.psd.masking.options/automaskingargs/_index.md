---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili argumen yang ditentukan untuk metode masking otomatis"
type: docs
weight: 11
url: /id/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Mewakili argumen yang ditentukan untuk metode masking otomatis
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Mendapatkan jumlah iterasi maksimum. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Mendapatkan jumlah objek untuk memisahkan gambar awal menjadi (opsional), nilai default adalah 2 (objek dan latar belakang). |
| [getObjectsPoints()](#getObjectsPoints--) | Mendapatkan titik-titik yang termasuk dalam objek yang dipisahkan (opsional) koordinat NumberOfObjects yang termasuk dalam NumberOfObjects objek dari gambar awal. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Mendapatkan persegi panjang objek yang termasuk dalam objek yang dipisahkan (opsional). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Mendapatkan titik-titik yang tidak lagi termasuk dalam objek apa pun (opsional). |
| [getPrecision()](#getPrecision--) | Mendapatkan presisi metode segmentasi (opsional). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Mengatur jumlah iterasi maksimum. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Mengatur jumlah objek untuk memisahkan gambar awal menjadi (opsional), nilai default adalah 2 (objek dan latar belakang). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Mengatur titik-titik yang termasuk dalam objek yang dipisahkan (opsional) koordinat NumberOfObjects yang termasuk dalam NumberOfObjects objek dari gambar awal. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Mengatur persegi panjang objek yang termasuk dalam objek yang dipisahkan (opsional). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Mengatur titik-titik yang tidak lagi termasuk dalam objek apa pun (opsional). |
| [setPrecision(double value)](#setPrecision-double-) | Mengatur presisi metode segmentasi (opsional). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Mendapatkan jumlah iterasi maksimum.

Nilai: Jumlah maksimum iterasi maksimum.

**Returns:**
int - jumlah iterasi maksimum.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Mendapatkan jumlah objek untuk memisahkan gambar awal menjadi (opsional), nilai default adalah 2 (objek dan latar belakang).

Nilai: Jumlah objek.

**Returns:**
int - jumlah objek untuk memisahkan gambar awal menjadi (opsional), nilai default adalah 2 (objek dan latar belakang).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Mendapatkan titik-titik yang termasuk dalam objek yang dipisahkan (opsional) koordinat NumberOfObjects yang termasuk dalam NumberOfObjects objek dari gambar awal. Parameter ini digunakan untuk meningkatkan presisi metode segmentasi.

Nilai: Titik objek.

**Returns:**
com.aspose.psd.Point[][] - titik yang termasuk dalam objek terpisah (opsional) NumberOfObjects koordinat yang termasuk dalam NumberOfObjects objek dari gambar awal.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Mendapatkan persegi panjang objek yang termasuk dalam objek terpisah (opsional). Parameter ini digunakan untuk meningkatkan presisi metode segmentasi.

Nilai: Persegi panjang objek.

**Returns:**
com.aspose.psd.Rectangle[] - persegi panjang objek yang termasuk dalam objek terpisah (opsional).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Mendapatkan titik yang tidak lagi termasuk dalam objek apa pun (opsional). Parameter ini hanya digunakan dalam kasus resegmentasi.

Nilai: Titik yang terasing.

**Returns:**
com.aspose.psd.Point[] - titik yang tidak lagi termasuk dalam objek apa pun (opsional).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Mendapatkan presisi metode segmentasi (opsional).

Nilai: Presisi metode segmentasi (opsional).

**Returns:**
double - presisi metode segmentasi (opsional).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Mengatur jumlah iterasi maksimum.

Nilai: Jumlah maksimum iterasi maksimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | jumlah maksimum iterasi. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Mengatur jumlah objek untuk memisahkan gambar awal menjadi (opsional), nilai default adalah 2 (objek dan latar belakang).

Nilai: Jumlah objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | jumlah objek untuk memisahkan gambar awal menjadi (opsional), nilai default adalah 2 (objek dan latar belakang). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Mengatur titik yang termasuk dalam objek terpisah (opsional) NumberOfObjects koordinat yang termasuk dalam NumberOfObjects objek dari gambar awal. Parameter ini digunakan untuk meningkatkan presisi metode segmentasi.

Nilai: Titik objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | titik yang termasuk dalam objek terpisah (opsional) NumberOfObjects koordinat yang termasuk dalam NumberOfObjects objek dari gambar awal. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Mengatur persegi panjang objek yang termasuk dalam objek terpisah (opsional). Parameter ini digunakan untuk meningkatkan presisi metode segmentasi.

Nilai: Persegi panjang objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | persegi panjang objek yang termasuk dalam objek terpisah (opsional). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Mengatur titik yang tidak lagi termasuk dalam objek apa pun (opsional). Parameter ini hanya digunakan dalam kasus resegmentasi.

Nilai: Titik yang terasing.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | titik yang tidak lagi termasuk dalam objek apa pun (opsional). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Mengatur presisi metode segmentasi (opsional).

Nilai: Presisi metode segmentasi (opsional).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | presisi metode segmentasi (opsional). |

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

