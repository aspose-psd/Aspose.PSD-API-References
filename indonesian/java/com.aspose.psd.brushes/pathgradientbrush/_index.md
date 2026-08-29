---
title: "PathGradientBrush"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mengkapsulkan objek Aspose.Imaging.Brush dengan gradien."
type: docs
weight: 14
url: /id/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Mengkapsulkan objek Aspose.Imaging.Brush dengan gradien. Kelas ini tidak dapat diwarisi.

Warna tengah secara default adalah putih. Pengguna dapat mengubah nilai ini kapan saja nanti.

Array warna sekeliling diinisialisasi dengan satu elemen yang berisi warna putih secara default. Warna sekeliling dapat diubah nanti, namun setidaknya satu elemen diperlukan saat mengatur warna sekeliling.

Lihat  Blend  untuk detail lebih lanjut tentang inisialisasinya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan dan mode pembungkus. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan dan mode pembungkus. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan jalur yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Membuat klon mendalam baru dari Brush saat ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Mendapatkan sebuah  Aspose.Imaging.Blend  yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [getCenterColor()](#getCenterColor--) | Mendapatkan warna di pusat gradien jalur. |
| [getCenterPoint()](#getCenterPoint--) | Mendapatkan atau mengatur titik pusat gradien jalur. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFocusScales()](#getFocusScales--) | Mendapatkan titik fokus untuk penurunan gradien. |
| [getGraphicsPath()](#getGraphicsPath--) | Mendapatkan jalur grafis yang kuas ini dibangun di atasnya. |
| [getInterpolationColors()](#getInterpolationColors--) | Mendapatkan com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna. |
| [getOpacity()](#getOpacity--) | Mendapatkan opasitas kuas. |
| [getPathPoints()](#getPathPoints--) | Mendapatkan titik-titik jalur yang menjadi dasar kuas ini. |
| [getSurroundColors()](#getSurroundColors--) | Mendapatkan array warna yang sesuai dengan titik-titik pada jalur yang diisi oleh  PathGradientBrush  ini. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini. |
| [getWrapMode()](#getWrapMode--) | Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini. |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | Mendapatkan nilai yang menunjukkan apakah transformasi diubah dengan cara tertentu. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Mengalikan Aspose.Imaging.Matrix yang mewakili transformasi geometris lokal LinearGradientBrush ini dengan Aspose.Imaging.Matrix yang ditentukan dengan menambahkan Aspose.Imaging.Matrix yang ditentukan di depan. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Mengalikan Aspose.Imaging.Matrix yang mewakili transformasi geometris lokal LinearGradientBrush ini dengan Aspose.Imaging.Matrix yang ditentukan dalam urutan yang ditentukan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Mengatur ulang properti TransformBrush.Transform ke identitas. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Mengatur sebuah  Aspose.Imaging.Blend  yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Membuat gradien dengan warna pusat dan penurunan linear ke satu warna di sekitarnya. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Membuat gradien dengan warna pusat dan penurunan linear ke setiap warna di sekitarnya. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Mengatur warna di pusat gradien jalur. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Mendapatkan atau mengatur titik pusat gradien jalur. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Mengatur com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna. |
| [setOpacity(float value)](#setOpacity-float-) | Mengatur opasitas kuas. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Mengatur array warna yang sesuai dengan titik-titik pada jalur yang diisi oleh  PathGradientBrush  ini. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini. |
| [setWrapMode(int value)](#setWrapMode-int-) | Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Sebuah array struktur Aspose.Imaging.PointF yang mewakili titik-titik yang membentuk simpul-simpul jalur. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan dan mode pembungkus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Sebuah array struktur Aspose.Imaging.PointF yang mewakili titik-titik yang membentuk simpul-simpul jalur. |
| wrapMode | int | Sebuah  Aspose.Imaging.WrapMode  yang menentukan bagaimana isian yang digambar dengan  PathGradientBrush  ini ditata secara ubin. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Sebuah array struktur Aspose.Imaging.Point yang mewakili titik-titik yang membentuk simpul-simpul jalur. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan titik-titik yang ditentukan dan mode pembungkus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Sebuah array struktur Aspose.Imaging.Point yang mewakili titik-titik yang membentuk simpul-simpul jalur. |
| wrapMode | int | Sebuah  Aspose.Imaging.WrapMode  yang menentukan bagaimana isian yang digambar dengan  PathGradientBrush  ini ditata secara ubin. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Menginisialisasi instance baru dari kelas  PathGradientBrush  dengan jalur yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GraphicsPath yang mendefinisikan area yang diisi oleh  PathGradientBrush  ini. |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Mendapatkan sebuah  Aspose.Imaging.Blend  yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Mendapatkan warna di pusat gradien jalur.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Mendapatkan atau mengatur titik pusat gradien jalur.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Mendapatkan titik fokus untuk penurunan gradien.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Mendapatkan jalur grafis yang kuas ini dibangun di atasnya.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Mendapatkan com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Mendapatkan opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus.

**Returns:**
float - Nilai opasitas kuas.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Mendapatkan titik-titik jalur yang menjadi dasar kuas ini.

**Returns:**
com.aspose.psd.PointF[] - Titik-titik jalur.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Mendapatkan array warna yang sesuai dengan titik-titik pada jalur yang diisi oleh  PathGradientBrush  ini.

**Returns:**
com.aspose.psd.Color[] - Sebuah array struktur  com.aspose.psd.Color  yang mewakili warna yang terkait dengan setiap titik pada jalur yang diisi oleh  PathGradientBrush  ini.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini.

**Returns:**
int - Sebuah  Aspose.Imaging.WrapMode  yang menentukan bagaimana isian yang digambar dengan  TransformBrush  ini ditata ubin.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+.

Nilai:  True  jika transformasi diubah; jika tidak,  false .

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Mengalikan Aspose.Imaging.Matrix yang mewakili transformasi geometris lokal LinearGradientBrush ini dengan Aspose.Imaging.Matrix yang ditentukan dengan menambahkan Aspose.Imaging.Matrix yang ditentukan di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matriks  Aspose.Imaging.Matrix  yang digunakan untuk mengalikan transformasi geometris. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Mengalikan Aspose.Imaging.Matrix yang mewakili transformasi geometris lokal LinearGradientBrush ini dengan Aspose.Imaging.Matrix yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matriks  Aspose.Imaging.Matrix  yang digunakan untuk mengalikan transformasi geometris. |
| urutan | int | Sebuah  Aspose.Imaging.MatrixOrder  yang menentukan dalam urutan apa dua matriks dikalikan. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Mengatur ulang properti TransformBrush.Transform ke identitas.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Memutar transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |
| urutan | int | Sebuah  Aspose.Imaging.MatrixOrder  yang menentukan apakah menambahkan atau menempatkan di depan matriks rotasi. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Menskala transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menyisipkan matriks skala ke transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah skala transformasi pada arah sumbu x. |
| sy | float | Jumlah skala transformasi pada arah sumbu y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah skala transformasi pada arah sumbu x. |
| sy | float | Jumlah skala transformasi pada arah sumbu y. |
| urutan | int | Sebuah Aspose.Imaging.MatrixOrder yang menentukan apakah matriks skala harus ditambahkan di akhir atau di awal. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Mengatur sebuah  Aspose.Imaging.Blend  yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Sebuah  Aspose.Imaging.Blend  yang mewakili penurunan kustom untuk gradien. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Membuat gradien dengan warna pusat dan penurunan linear ke satu warna di sekitarnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Membuat gradien dengan warna pusat dan penurunan linear ke setiap warna di sekitarnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |
| skala | float | Nilai dari 0 hingga 1 yang menentukan intensitas maksimum warna pusat yang dicampur dengan warna batas. Nilai 1 menghasilkan intensitas tertinggi yang mungkin dari warna pusat, dan merupakan nilai default. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Mengatur warna di pusat gradien jalur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Sebuah  com.aspose.psd.Color  yang mewakili warna di pusat gradien jalur. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Mendapatkan atau mengatur titik pusat gradien jalur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Sebuah Aspose.Imaging.PointF yang mewakili titik pusat gradien jalur. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Mendapatkan atau mengatur titik fokus untuk penurunan gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Sebuah Aspose.Imaging.PointF yang mewakili titik fokus untuk penurunan gradien. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Mengatur com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Sebuah com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus pandang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai opasitas kuas. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |
| skala | float | Nilai dari 0 hingga 1 yang menentukan intensitas maksimum warna pusat yang dicampur dengan warna batas. Nilai 1 menghasilkan intensitas tertinggi yang mungkin dari warna pusat, dan merupakan nilai default. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Mengatur array warna yang sesuai dengan titik-titik pada jalur yang diisi oleh  PathGradientBrush  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Sebuah array struktur  com.aspose.psd.Color  yang mewakili warna yang terkait dengan setiap titik pada jalur yang diisi oleh  PathGradientBrush  ini. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini.

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
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menyisipkan translasi ke transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| urutan | int | Urutan (menyisipkan di awal atau menambahkan di akhir) penerapan translasi. |

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

