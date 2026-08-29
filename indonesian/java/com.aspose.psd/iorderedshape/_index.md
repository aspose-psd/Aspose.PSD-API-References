---
title: "IOrderedShape"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili bentuk terurut."
type: docs
weight: 129
url: /id/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Mewakili sebuah ordered shape. Ordered shape adalah sekumpulan titik kontinu yang memiliki titik awal dan titik akhir. Sekumpulan titik kontinu tersebut terhubung menggunakan aturan tertentu.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Mendapatkan titik akhir shape. |
| [getStartPoint()](#getStartPoint--) | Mendapatkan titik awal shape. |
| [isClosed()](#isClosed--) | Mendapatkan nilai yang menunjukkan apakah ordered shape tertutup. |
| [reverse()](#reverse--) | Membalik urutan titik untuk shape ini. |
| [setClosed(boolean value)](#setClosed-boolean-) | Menetapkan nilai yang menunjukkan apakah ordered shape tertutup. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Mendapatkan titik akhir shape.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Mendapatkan titik awal shape.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Mendapatkan nilai yang menunjukkan apakah ordered shape tertutup. Saat memproses ordered shape yang tertutup, titik awal dan akhir tidak memiliki arti.

**Returns:**
boolean -  true  jika bentuk terurut ini tertutup; jika tidak,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Membalik urutan titik untuk shape ini.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Mengatur nilai yang menunjukkan apakah bentuk terurut tertutup. Saat memproses bentuk terurut tertutup, titik awal dan akhir tidak memiliki arti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika bentuk terurut ini tertutup; jika tidak,  false . |

