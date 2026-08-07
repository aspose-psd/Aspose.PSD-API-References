---
title: "TextureBrush"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Setiap properti dari kelas Aspose.Imaging.Brushes.TextureBrush adalah objek Aspose.Imaging.Brush yang menggunakan gambar untuk mengisi bagian dalam suatu bentuk."
type: docs
weight: 18
url: /id/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Setiap properti dari kelas Aspose.Imaging.Brushes.TextureBrush adalah objek Aspose.Imaging.Brush yang menggunakan gambar untuk mengisi bagian dalam suatu bentuk. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | Menginisialisasi instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | Menginisialisasi instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar dan mode pembungkus yang ditentukan. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Membuat klon mendalam baru dari Brush saat ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getImage()](#getImage--) | Mendapatkan objek com.aspose.psd.Image yang terkait dengan objek com.aspose.psd.brushes.TextureBrush ini. |
| [getImageAttributes()](#getImageAttributes--) | Mendapatkan ImageAttributes yang terkait dengan TextureBrush ini. |
| [getImageRectangle()](#getImageRectangle--) | Mendapatkan Rectangle yang terkait dengan TextureBrush ini. |
| [getOpacity()](#getOpacity--) | Mendapatkan opasitas kuas. |
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
| [setOpacity(float value)](#setOpacity-float-) | Mengatur opasitas kuas. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Mendapatkan atau mengatur salinan Aspose.Imaging.Matrix yang mendefinisikan transformasi geometris lokal untuk TransformBrush ini. |
| [setWrapMode(int value)](#setWrapMode-int-) | Mendapatkan atau mengatur enumerasi Aspose.Imaging.WrapMode yang menunjukkan mode pembungkus untuk TransformBrush ini. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


Menginisialisasi instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Menginisialisasi instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar dan mode pembungkus yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| wrapMode | int | Enumerasi Aspose.Imaging.WrapMode yang menentukan bagaimana objek Aspose.Imaging.Brushes.TextureBrush ini ditata ubin. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| wrapMode | int | Enumerasi Aspose.Imaging.WrapMode yang menentukan bagaimana objek Aspose.Imaging.Brushes.TextureBrush ini ditata ubin. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur Aspose.Imaging.RectangleF yang merepresentasikan persegi panjang pembatas untuk objek Aspose.Imaging.Brushes.TextureBrush ini. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| wrapMode | int | Enumerasi Aspose.Imaging.WrapMode yang menentukan bagaimana objek Aspose.Imaging.Brushes.TextureBrush ini ditata ubin. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Aspose.Imaging.Rectangle yang merepresentasikan persegi panjang pembatas untuk objek Aspose.Imaging.Brushes.TextureBrush ini. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan dan persegi panjang pembatas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur Aspose.Imaging.RectangleF yang merepresentasikan persegi panjang pembatas untuk objek Aspose.Imaging.Brushes.TextureBrush ini. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur Aspose.Imaging.RectangleF yang merepresentasikan persegi panjang pembatas untuk objek Aspose.Imaging.Brushes.TextureBrush ini. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Objek com.aspose.psd.ImageAttributes yang berisi informasi tambahan tentang gambar yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan dan persegi panjang pembatas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Aspose.Imaging.Rectangle yang merepresentasikan persegi panjang pembatas untuk objek Aspose.Imaging.Brushes.TextureBrush ini. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Menginisialisasi sebuah instance baru dari kelas Aspose.Imaging.Brushes.TextureBrush yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Objek Aspose.Imaging.Image yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini untuk mengisi interior. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Aspose.Imaging.Rectangle yang merepresentasikan persegi panjang pembatas untuk objek Aspose.Imaging.Brushes.TextureBrush ini. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Objek com.aspose.psd.ImageAttributes yang berisi informasi tambahan tentang gambar yang digunakan oleh objek Aspose.Imaging.Brushes.TextureBrush ini. |

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
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getImage() {#getImage--}
```
public Image getImage()
```


Mendapatkan objek com.aspose.psd.Image yang terkait dengan objek com.aspose.psd.brushes.TextureBrush ini.

Nilai: Objek com.aspose.psd.Image yang merepresentasikan gambar yang digunakan oleh objek com.aspose.psd.brushes.TextureBrush ini untuk mengisi bentuk.

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Mendapatkan ImageAttributes yang terkait dengan TextureBrush ini.

Nilai: ImageAttributes.

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Mendapatkan Rectangle yang terkait dengan TextureBrush ini.

Nilai: Rectangle.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Mendapatkan opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus.

**Returns:**
float - Nilai opasitas kuas.
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

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus pandang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai opasitas kuas. |

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

