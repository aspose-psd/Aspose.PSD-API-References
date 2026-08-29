---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili Brush dengan gradien linier yang didefinisikan oleh beberapa warna dan posisi yang sesuai."
type: docs
weight: 13
url: /id/java/com.aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Mewakili Brush dengan gradien linier yang didefinisikan oleh beberapa warna dan posisi yang sesuai. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush dengan parameter default. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush dengan titik-titik yang ditentukan. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush dengan titik-titik yang ditentukan. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-) | Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Membuat klon mendalam baru dari Brush saat ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Mendapatkan sudut gradien. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getGammaCorrection()](#getGammaCorrection--) | Mendapatkan nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk LinearGradientBrushBase ini. |
| [getInterpolationColors()](#getInterpolationColors--) | Mendapatkan com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna. |
| [getOpacity()](#getOpacity--) | Mendapatkan opasitas kuas. |
| [getRectangle()](#getRectangle--) | Mendapatkan wilayah persegi panjang yang mendefinisikan titik awal dan akhir gradien. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini. |
| [getWrapMode()](#getWrapMode--) | Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Mendapatkan nilai yang menunjukkan apakah LinearGradientBrushBase.Angle diubah selama transformasi dengan LinearGradientBrushBase ini. |
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
| [setAngle(float value)](#setAngle-float-) | Mengatur sudut gradien. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Mengatur nilai yang menunjukkan apakah LinearGradientBrushBase.Angle diubah selama transformasi dengan LinearGradientBrushBase ini. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk LinearGradientBrushBase ini. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Mengatur com.aspose.psd.ColorBlend yang mendefinisikan gradien linear multiwarna. |
| [setOpacity(float value)](#setOpacity-float-) | Mengatur opasitas kuas. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Mengatur wilayah persegi panjang yang mendefinisikan titik awal dan akhir gradien. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini. |
| [setWrapMode(int value)](#setWrapMode-int-) | Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Menginisialisasi instance baru dari kelas  LinearMulticolorGradientBrush  dengan parameter default. Warna awal adalah hitam, warna akhir adalah putih, sudutnya 45 derajat dan persegi panjang berada di (0,0) dengan ukuran (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush dengan titik-titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Sebuah struktur  Aspose.Imaging.Point  yang mewakili titik awal gradien linier. |
| point2 | [Point](../../com.aspose.psd/point) | Sebuah struktur  Aspose.Imaging.Point  yang mewakili titik akhir gradien linier. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush dengan titik-titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Sebuah struktur  Aspose.Imaging.PointF  yang mewakili titik awal gradien linier. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Sebuah struktur  Aspose.Imaging.PointF  yang mewakili titik akhir gradien linier. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Sebuah struktur  Aspose.Imaging.RectangleF  yang menentukan batas gradien linier. |
| angle | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah struktur  Aspose.Imaging.RectangleF  yang menentukan batas gradien linier. |
| angle | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Sebuah struktur  Aspose.Imaging.RectangleF  yang menentukan batas gradien linier. |
| angle | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |
| isAngleScalable | boolean | jika disetel ke  true  sudut akan berubah selama transformasi dengan  LinearMulticolorGradientBrush  ini. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Menginisialisasi instance baru dari kelas LinearMulticolorGradientBrush berdasarkan sebuah persegi panjang dan sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah struktur  Aspose.Imaging.RectangleF  yang menentukan batas gradien linier. |
| angle | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |
| isAngleScalable | boolean | jika disetel ke  true  sudut akan berubah selama transformasi dengan  LinearMulticolorGradientBrush  ini. |

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Mendapatkan sudut gradien.

**Returns:**
float - Sudut gradien.
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
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Mendapatkan nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk LinearGradientBrushBase ini.

**Returns:**
boolean - Nilainya true jika koreksi gamma diaktifkan untuk  LinearGradientBrushBase  ini; jika tidak, false.
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
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Mendapatkan wilayah persegi panjang yang mendefinisikan titik awal dan akhir gradien.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
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
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Mendapatkan nilai yang menunjukkan apakah LinearGradientBrushBase.Angle diubah selama transformasi dengan LinearGradientBrushBase ini.

**Returns:**
boolean -  true  jika  LinearGradientBrushBase.Angle  berubah selama transformasi dengan  LinearGradientBrushBase  ini; jika tidak,  false .
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

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Mengatur sudut gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Sudut gradien. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Mengatur nilai yang menunjukkan apakah LinearGradientBrushBase.Angle diubah selama transformasi dengan LinearGradientBrushBase ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true jika LinearGradientBrushBase.Angle diubah selama transformasi dengan LinearGradientBrushBase ini; selainnya, false. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk LinearGradientBrushBase ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilainya true jika koreksi gamma diaktifkan untuk LinearGradientBrushBase ini; selainnya, false. |

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

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Mengatur wilayah persegi panjang yang mendefinisikan titik awal dan akhir gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah struktur com.aspose.psd.RectangleF yang menentukan titik awal dan akhir gradien. |

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

