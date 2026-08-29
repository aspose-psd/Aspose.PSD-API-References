---
title: "SolidBrush"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Brush solid dimaksudkan untuk menggambar secara berkelanjutan dengan warna tertentu."
type: docs
weight: 17
url: /id/java/com.aspose.psd.brushes/solidbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class SolidBrush extends Brush
```

Solid brush dimaksudkan untuk menggambar secara terus-menerus dengan warna tertentu. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Menginisialisasi instance baru dari kelas  SolidBrush . |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.psd.Color-) | Menginisialisasi instance baru dari kelas  SolidBrush . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Membuat klon mendalam baru dari Brush saat ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna kuas. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getOpacity()](#getOpacity--) | Mendapatkan opasitas kuas. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur warna kuas. |
| [setOpacity(float value)](#setOpacity-float-) | Mengatur opasitas kuas. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Menginisialisasi instance baru dari kelas  SolidBrush .

### SolidBrush(Color color) {#SolidBrush-com.aspose.psd.Color-}
```
public SolidBrush(Color color)
```


Menginisialisasi instance baru dari kelas  SolidBrush .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Warna solid brush. |

### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Membuat klon mendalam baru dari Brush saat ini.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

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
### getColor() {#getColor--}
```
public Color getColor()
```


Mendapatkan atau mengatur warna kuas.

Nilai: Warna kuas.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Mendapatkan opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus.

**Returns:**
float - Nilai opasitas kuas.
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




### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Mendapatkan atau mengatur warna kuas.

Nilai: Warna kuas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus pandang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai opasitas kuas. |

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

