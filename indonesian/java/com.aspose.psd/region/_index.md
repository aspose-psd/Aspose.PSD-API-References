---
title: "Region"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Menjelaskan interior bentuk grafis yang terdiri dari persegi panjang dan jalur."
type: docs
weight: 90
url: /id/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Mendeskripsikan interior dari bentuk grafis yang terdiri dari persegi panjang dan jalur. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Region()](#Region--) | Menginisialisasi T:Aspose.Imaging.Region baru. |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Menginisialisasi T:Aspose.Imaging.Region baru dari struktur T:Aspose.Imaging.RectangleF yang ditentukan. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Menginisialisasi T:Aspose.Imaging.Region baru dari struktur T:Aspose.Imaging.Rectangle yang ditentukan. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Menginisialisasi T:Aspose.Imaging.Region baru dengan T:Aspose.Imaging.GraphicsPath yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari com.aspose.psd.GraphicsPath yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini. |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari struktur com.aspose.psd.Rectangle yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini. |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari struktur com.aspose.psd.RectangleF yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari com.aspose.psd.Region yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini. |
| [deepClone()](#deepClone--) | Membuat salinan dalam yang tepat dari com.aspose.psd.region ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan com.aspose.psd.graphicsPath yang ditentukan. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan struktur com.aspose.psd.Rectangle yang ditentukan. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan struktur com.aspose.psd.RectangleF yang ditentukan. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan com.aspose.psd.region yang ditentukan. |
| [getActions_internalized()](#getActions-internalized--) | Mendapatkan tindakan region. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan com.aspose.psd.graphicsPath yang ditentukan. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan struktur com.aspose.psd.Rectangle yang ditentukan. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan struktur com.aspose.psd.RectangleF yang ditentukan. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan com.aspose.psd.region yang ditentukan. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Memeriksa apakah com.aspose.psd.Region ini memiliki interior kosong pada permukaan gambar yang ditentukan. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Memeriksa apakah com.aspose.psd.Region yang ditentukan identik dengan com.aspose.psd.Region ini pada permukaan gambar yang ditentukan. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Memeriksa apakah com.aspose.psd.Region ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Memeriksa apakah struktur com.aspose.psd.Point yang ditentukan berada di dalam com.aspose.psd.region ini. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Memeriksa apakah struktur com.aspose.psd.Point yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Memeriksa apakah struktur com.aspose.psd.PointF yang ditentukan berada di dalam com.aspose.psd.region ini. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Memeriksa apakah struktur com.aspose.psd.PointF yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.Rectangle yang ditentukan berada di dalam com.aspose.psd.region ini. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.Rectangle yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.RectangleF yang ditentukan berada di dalam com.aspose.psd.region ini. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.RectangleF yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Memeriksa apakah titik yang ditentukan berada di dalam com.aspose.psd.region ini. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Memeriksa apakah titik yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.Region  ketika digambar menggunakan yang ditentukan  com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Menguji apakah titik yang ditentukan terkandung dalam ini  com.aspose.psd.Region  objek ketika digambar menggunakan yang ditentukan  com.aspose.psd.Graphics  objek. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.Region  ketika digambar menggunakan yang ditentukan  com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Menginisialisasi ini  com.aspose.psd.Region  menjadi interior kosong. |
| [makeInfinite()](#makeInfinite--) | Menginisialisasi ini  com.aspose.psd.Region  objek menjadi interior tak terbatas. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Mendapatkan atau mengatur wilayah on change. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Mengubah ini  com.aspose.psd.Region  dengan  com.aspose.psd.matrix yang ditentukan . |
| [translate(float dx, float dy)](#translate-float-float-) | Menggeser koordinat ini  com.aspose.psd.Region  sebesar jumlah yang ditentukan. |
| [translate(int dx, int dy)](#translate-int-int-) | Menggeser koordinat ini  com.aspose.psd.Region  sebesar jumlah yang ditentukan. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan  com.aspose.psd.graphicsPath yang ditentukan . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan struktur  com.aspose.psd.Rectangle yang ditentukan. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan struktur  com.aspose.psd.RectangleF yang ditentukan. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan  com.aspose.psd.region yang ditentukan . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan  com.aspose.psd.graphicsPath yang ditentukan . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan struktur  com.aspose.psd.Rectangle yang ditentukan. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan struktur  com.aspose.psd.RectangleF yang ditentukan. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan  com.aspose.psd.region yang ditentukan . |
### Region() {#Region--}
```
public Region()
```


Menginisialisasi T:Aspose.Imaging.Region baru.

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Menginisialisasi T:Aspose.Imaging.Region baru dari struktur T:Aspose.Imaging.RectangleF yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah struktur  T:Aspose.Imaging.RectangleF  yang mendefinisikan interior dari  T:Aspose.Imaging.Region  baru. |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Menginisialisasi T:Aspose.Imaging.Region baru dari struktur T:Aspose.Imaging.Rectangle yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Sebuah struktur  T:Aspose.Imaging.Rectangle  yang mendefinisikan interior dari  T:Aspose.Imaging.Region  baru. |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Menginisialisasi T:Aspose.Imaging.Region baru dengan T:Aspose.Imaging.GraphicsPath yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Sebuah  T:Aspose.Imaging.GraphicsPath  yang mendefinisikan  T:Aspose.Imaging.Region  baru. |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari com.aspose.psd.GraphicsPath yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GrafikPath  com.aspose.psd.GraphicsPath  untuk melengkapi ini  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari struktur com.aspose.psd.Rectangle yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  com.aspose.psd.Rectangle  untuk melengkapi ini  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari struktur com.aspose.psd.RectangleF yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur  com.aspose.psd.RectangleF  untuk melengkapi ini  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Memperbarui com.aspose.psd.Region ini untuk berisi bagian dari com.aspose.psd.Region yang ditentukan yang tidak berpotongan dengan com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Objek  com.aspose.psd.Region  untuk melengkapi objek  com.aspose.psd.Region . |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Membuat salinan dalam yang tepat dari com.aspose.psd.region ini.

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan com.aspose.psd.graphicsPath yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GrafikPath  com.aspose.psd.GraphicsPath  untuk dikecualikan dari ini  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan struktur com.aspose.psd.Rectangle yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  com.aspose.psd.Rectangle  untuk dikecualikan dari ini  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan struktur com.aspose.psd.RectangleF yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF untuk dikecualikan dari com.aspose.psd.region ini. |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Memperbarui com.aspose.psd.Region ini untuk berisi hanya bagian interiornya yang tidak berpotongan dengan com.aspose.psd.region yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region untuk dikecualikan dari com.aspose.psd.region ini. |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Mendapatkan tindakan region.

**Returns:**
com.aspose.internal.RegionAction[] - Aksi region.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan com.aspose.psd.graphicsPath yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath untuk berpotongan dengan com.aspose.psd.region ini. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan struktur com.aspose.psd.Rectangle yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur com.aspose.psd.Rectangle untuk berpotongan dengan com.aspose.psd.region ini. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan struktur com.aspose.psd.RectangleF yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF untuk berpotongan dengan com.aspose.psd.region ini. |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Memperbarui com.aspose.psd.Region ini menjadi irisan dirinya dengan com.aspose.psd.region yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region untuk berpotongan dengan com.aspose.psd.region ini. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Memeriksa apakah com.aspose.psd.Region ini memiliki interior kosong pada permukaan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili permukaan gambar. |

**Returns:**
boolean - true jika interior com.aspose.psd.Region ini kosong ketika transformasi yang terkait dengan g diterapkan; jika tidak, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Memeriksa apakah com.aspose.psd.Region yang ditentukan identik dengan com.aspose.psd.Region ini pada permukaan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili permukaan gambar. |

**Returns:**
boolean - True jika interior region identik dengan interior region ini ketika transformasi yang terkait dengan parameter g diterapkan; jika tidak, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Memeriksa apakah com.aspose.psd.Region ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili permukaan gambar. |

**Returns:**
boolean - true jika interior com.aspose.psd.Region ini tak berhingga ketika transformasi yang terkait dengan g diterapkan; jika tidak, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Memeriksa apakah struktur com.aspose.psd.Point yang ditentukan berada di dalam com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Struktur com.aspose.psd.Point untuk diuji. |

**Returns:**
boolean - true ketika point berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Memeriksa apakah struktur com.aspose.psd.Point yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Struktur com.aspose.psd.Point untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika point berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Memeriksa apakah struktur com.aspose.psd.PointF yang ditentukan berada di dalam com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Struktur com.aspose.psd.PointF untuk diuji. |

**Returns:**
boolean - true ketika point berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Memeriksa apakah struktur com.aspose.psd.PointF yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Struktur com.aspose.psd.PointF untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika point berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.Rectangle yang ditentukan berada di dalam com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur com.aspose.psd.Rectangle untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true ketika bagian mana pun dari rect berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.Rectangle yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur com.aspose.psd.Rectangle untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika bagian mana pun dari rect berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.RectangleF yang ditentukan berada di dalam com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF untuk diuji. |

**Returns:**
boolean - true ketika bagian mana pun dari rect berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Memeriksa apakah bagian mana pun dari struktur com.aspose.psd.RectangleF yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika rect berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Memeriksa apakah titik yang ditentukan berada di dalam com.aspose.psd.region ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - True ketika titik yang ditentukan berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Memeriksa apakah titik yang ditentukan berada di dalam com.aspose.psd.Region ini ketika digambar menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - True ketika titik yang ditentukan berada dalam com.aspose.psd.Region ini; jika tidak, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.region .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x sudut kiri atas persegi panjang untuk diuji. |
| y | float | Koordinat y sudut kiri atas persegi panjang untuk diuji. |
| lebar | float | Lebar persegi panjang untuk diuji. |
| tinggi | float | Tinggi persegi panjang untuk diuji. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada dalam objek  com.aspose.psd.Region  ini; jika tidak, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.Region  ketika digambar menggunakan yang ditentukan  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x sudut kiri atas persegi panjang untuk diuji. |
| y | float | Koordinat y sudut kiri atas persegi panjang untuk diuji. |
| lebar | float | Lebar persegi panjang untuk diuji. |
| tinggi | float | Tinggi persegi panjang untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada dalam  com.aspose.psd.Region  ini; jika tidak, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Menguji apakah titik yang ditentukan terkandung dalam ini  com.aspose.psd.Region  objek ketika digambar menggunakan yang ditentukan  com.aspose.psd.Graphics  objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika titik yang ditentukan berada dalam  com.aspose.psd.Region  ini; jika tidak, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.region .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x sudut kiri atas persegi panjang untuk diuji. |
| y | int | Koordinat y sudut kiri atas persegi panjang untuk diuji. |
| lebar | int | Lebar persegi panjang untuk diuji. |
| tinggi | int | Tinggi persegi panjang untuk diuji. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada dalam  com.aspose.psd.Region  ini; jika tidak, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam ini  com.aspose.psd.Region  ketika digambar menggunakan yang ditentukan  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x sudut kiri atas persegi panjang untuk diuji. |
| y | int | Koordinat y sudut kiri atas persegi panjang untuk diuji. |
| lebar | int | Lebar persegi panjang untuk diuji. |
| tinggi | int | Tinggi persegi panjang untuk diuji. |
| g | [Graphics](../../com.aspose.psd/graphics) | Sebuah com.aspose.psd.Graphics yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada dalam  com.aspose.psd.Region  ini; jika tidak, false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Menginisialisasi ini  com.aspose.psd.Region  menjadi interior kosong.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Menginisialisasi ini  com.aspose.psd.Region  objek menjadi interior tak terbatas.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Mendapatkan atau mengatur wilayah on change.

Nilai: Wilayah saat berubah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Mengubah ini  com.aspose.psd.Region  dengan  com.aspose.psd.matrix yang ditentukan .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix  com.aspose.psd.Matrix  yang digunakan untuk mentransformasi  com.aspose.psd.region  ini. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Menggeser koordinat ini  com.aspose.psd.Region  sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Jumlah untuk menggeser  com.aspose.psd.Region  ini secara horizontal. |
| dy | float | Jumlah untuk menggeser  com.aspose.psd.Region  ini secara vertikal. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Menggeser koordinat ini  com.aspose.psd.Region  sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | int | Jumlah untuk menggeser  com.aspose.psd.Region  ini secara horizontal. |
| dy | int | Jumlah untuk menggeser  com.aspose.psd.Region  ini secara vertikal. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan  com.aspose.psd.graphicsPath yang ditentukan .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GraphicsPath  com.aspose.psd.GraphicsPath  untuk digabungkan dengan  com.aspose.psd.region  ini. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan struktur  com.aspose.psd.Rectangle yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Rectangle  com.aspose.psd.Rectangle  untuk digabungkan dengan  com.aspose.psd.region  ini. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan struktur  com.aspose.psd.RectangleF yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF  com.aspose.psd.RectangleF  untuk digabungkan dengan  com.aspose.psd.region  ini. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dirinya sendiri dengan  com.aspose.psd.region yang ditentukan .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Region  com.aspose.psd.Region  untuk digabungkan dengan  com.aspose.psd.region  ini. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan  com.aspose.psd.graphicsPath yang ditentukan .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GraphicsPath  com.aspose.psd.GraphicsPath  untuk xor dengan  com.aspose.psd.region  ini. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan struktur  com.aspose.psd.Rectangle yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Rectangle  com.aspose.psd.Rectangle  untuk xor dengan  com.aspose.psd.region  ini. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan struktur  com.aspose.psd.RectangleF yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF  com.aspose.psd.RectangleF  untuk xor dengan  com.aspose.psd.region  ini. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Memperbarui ini  com.aspose.psd.Region  menjadi gabungan dikurangi irisan dirinya dengan  com.aspose.psd.region yang ditentukan .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Region  com.aspose.psd.Region  untuk xor dengan  com.aspose.psd.region  ini. |

