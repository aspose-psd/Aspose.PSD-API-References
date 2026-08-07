---
title: "ImageAttributes"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Sebuah objek com.aspose.psd.ImageAttributes berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama proses rendering."
type: docs
weight: 55
url: /id/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Sebuah objek com.aspose.psd.ImageAttributes berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama proses rendering. Sebuah objek com.aspose.psd.ImageAttributes mempertahankan beberapa pengaturan penyesuaian warna, termasuk matriks penyesuaian warna, matriks penyesuaian skala abu-abu, nilai koreksi gamma, tabel peta warna, dan nilai ambang warna. Selama rendering, warna dapat dikoreksi, diperdalam, diterangkan, dan dihapus. Untuk menerapkan manipulasi tersebut, inisialisasikan sebuah objek com.aspose.psd.ImageAttributes dan berikan jalur objek com.aspose.psd.ImageAttributes tersebut (bersama dengan jalur sebuah [Image](../../com.aspose.psd/image)) ke metode drawImage.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Menginisialisasi sebuah instance baru dari kelas com.aspose.psd.ImageAttributes. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | Atribut gambar GDI. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Menghapus tabel pemetaan ulang warna kuas dari objek com.aspose.psd.ImageAttributes ini. |
| [clearColorKey()](#clearColorKey--) | Menghapus kunci warna (rentang transparansi) untuk kategori default. |
| [clearColorKey(int type)](#clearColorKey-int-) | Menghapus kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [clearColorMatrix()](#clearColorMatrix--) | Menghapus matriks penyesuaian warna untuk kategori default. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Menghapus matriks penyesuaian warna untuk kategori yang ditentukan. |
| [clearGamma()](#clearGamma--) | Menonaktifkan koreksi gamma untuk kategori default. |
| [clearGamma(int type)](#clearGamma-int-) | Menonaktifkan koreksi gamma untuk kategori yang ditentukan. |
| [clearNoOp()](#clearNoOp--) | Menghapus pengaturan NoOp untuk kategori default. |
| [clearNoOp(int type)](#clearNoOp-int-) | Menghapus pengaturan NoOp untuk kategori yang ditentukan. |
| [clearOutputChannel()](#clearOutputChannel--) | Menghapus pengaturan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Menghapus pengaturan saluran output (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Menghapus pengaturan profil warna saluran output untuk kategori default. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Menghapus pengaturan profil warna saluran output untuk kategori yang ditentukan. |
| [clearRemapTable()](#clearRemapTable--) | Menghapus tabel pemetaan ulang warna untuk kategori default. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Menghapus tabel pemetaan ulang warna untuk kategori yang ditentukan. |
| [clearThreshold()](#clearThreshold--) | Menghapus nilai ambang untuk kategori default. |
| [clearThreshold(int type)](#clearThreshold-int-) | Menghapus nilai ambang batas untuk kategori yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Mengatur tabel pemetaan ulang warna untuk kategori kuas. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Mengatur kunci warna untuk kategori default. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Mengatur kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Mengatur matriks penyesuaian warna untuk kategori yang ditentukan. |
| [setGamma(float gamma)](#setGamma-float-) | Mengatur nilai gamma untuk kategori default. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Mengatur nilai gamma untuk kategori yang ditentukan. |
| [setNoOp()](#setNoOp--) | Menonaktifkan penyesuaian warna untuk kategori default. |
| [setNoOp(int type)](#setNoOp-int-) | Menonaktifkan penyesuaian warna untuk kategori yang ditentukan. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Mengatur berkas profil warna saluran output untuk kategori default. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Mengatur berkas profil warna saluran output untuk kategori yang ditentukan. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Mengatur tabel pemetaan ulang warna untuk kategori default. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Mengatur tabel pemetaan ulang warna untuk kategori yang ditentukan. |
| [setThreshold(float threshold)](#setThreshold-float-) | Mengatur ambang batas (rentang transparansi) untuk kategori default. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Mengatur ambang batas (rentang transparansi) untuk kategori yang ditentukan. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Mengatur mode pembungkus yang digunakan untuk menentukan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Menginisialisasi sebuah instance baru dari kelas com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


Atribut gambar GDI.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Menghapus tabel pemetaan ulang warna kuas dari objek com.aspose.psd.ImageAttributes ini.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Menghapus kunci warna (rentang transparansi) untuk kategori default.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Menghapus kunci warna (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari  Aspose.Imaging.ColorAdjustType  yang menentukan kategori di mana kunci warna dihapus. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Menghapus matriks penyesuaian warna untuk kategori default.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Menghapus matriks penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari  Aspose.Imaging.ColorAdjustType  yang menentukan kategori di mana matriks penyesuaian warna dihapus. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Menonaktifkan koreksi gamma untuk kategori default.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Menonaktifkan koreksi gamma untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari  Aspose.Imaging.ColorAdjustType  yang menentukan kategori di mana koreksi gamma dinonaktifkan. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Menghapus pengaturan NoOp untuk kategori default.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Menghapus pengaturan NoOp untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana pengaturan NoOp dibersihkan. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Menghapus pengaturan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Menghapus pengaturan saluran output (cyan-magenta-yellow-black) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana pengaturan saluran output dibersihkan. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Menghapus pengaturan profil warna saluran output untuk kategori default.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Menghapus pengaturan profil warna saluran output untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana pengaturan profil saluran output dibersihkan. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Menghapus tabel pemetaan ulang warna untuk kategori default.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Menghapus tabel pemetaan ulang warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana tabel remap dibersihkan. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Menghapus nilai ambang untuk kategori default.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Menghapus nilai ambang batas untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana ambang dibersihkan. |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Mengatur tabel pemetaan ulang warna untuk kategori kuas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Array dari objek com.aspose.psd.ColorMap. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Mengatur kunci warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Nilai kunci warna rendah. |
| colorHigh | [Color](../../com.aspose.psd/color) | Nilai kunci warna tinggi. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Mengatur kunci warna (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Nilai kunci warna rendah. |
| colorHigh | [Color](../../com.aspose.psd/color) | Nilai kunci warna tinggi. |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana kunci warna diatur. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian warna. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian skala abu-abu. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian warna. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian skala abu-abu. |
| bendera | int | Elemen dari Aspose.Imaging.ColorMatrixFlag yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna dan penyesuaian skala abu-abu. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian warna. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian skala abu-abu. |
| mode | int | Elemen dari Aspose.Imaging.ColorMatrixFlag yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna dan penyesuaian skala abu-abu. |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana matriks penyesuaian warna dan penyesuaian skala abu-abu diatur. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Mengatur matriks penyesuaian warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian warna. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Mengatur matriks penyesuaian warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian warna. |
| bendera | int | Elemen dari Aspose.Imaging.ColorMatrixFlag yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Mengatur matriks penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Matriks penyesuaian warna. |
| mode | int | Elemen dari Aspose.Imaging.ColorMatrixFlag yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna. |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana matriks penyesuaian warna diatur. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Mengatur nilai gamma untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gamma | float | Nilai koreksi gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Mengatur nilai gamma untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gamma | float | Nilai koreksi gamma. |
| type | int | Elemen dari enumerasi Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana nilai gamma diatur. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Menonaktifkan penyesuaian warna untuk kategori default.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Menonaktifkan penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana koreksi warna dimatikan. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bendera | int | Elemen dari Aspose.Imaging.ColorChannelFlag yang menentukan saluran output. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bendera | int | Elemen dari Aspose.Imaging.ColorChannelFlag yang menentukan saluran output. |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana saluran output diatur. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Mengatur berkas profil warna saluran output untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Nama jalur file profil warna. Jika file profil warna berada di direktori %SystemRoot%\\System32\\Spool\\Drivers\\Color, parameter ini dapat berupa nama file. Jika tidak, parameter ini harus berupa nama jalur lengkap. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Mengatur berkas profil warna saluran output untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Nama jalur file profil warna. Jika file profil warna berada di direktori %SystemRoot%\\System32\\Spool\\Drivers\\Color, parameter ini dapat berupa nama file. Jika tidak, parameter ini harus berupa nama jalur lengkap. |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana file profil warna saluran output diatur. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Mengatur tabel pemetaan ulang warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Array dari pasangan warna tipe com.aspose.psd.ColorMap. Setiap pasangan warna berisi warna yang ada (nilai pertama) dan warna yang akan dipetakan kepadanya (nilai kedua). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Mengatur tabel pemetaan ulang warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Array dari pasangan warna tipe com.aspose.psd.ColorMap. Setiap pasangan warna berisi warna yang ada (nilai pertama) dan warna yang akan dipetakan kepadanya (nilai kedua). |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana tabel pemetaan ulang warna diatur. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Mengatur ambang batas (rentang transparansi) untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | float | Bilangan riil yang menentukan nilai ambang. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Mengatur ambang batas (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | float | Nilai ambang dari 0.0 hingga 1.0 yang digunakan sebagai titik pemisah untuk mengurutkan warna yang akan dipetakan ke nilai maksimum atau minimum. |
| type | int | Elemen dari Aspose.Imaging.ColorAdjustType yang menentukan kategori di mana ambang warna diatur. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Mengatur mode pembungkus yang digunakan untuk menentukan cara menata tekstur pada sebuah bentuk, atau pada batas bentuk. Tekstur ditata pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Elemen dari Aspose.Imaging.WrapMode yang menentukan bagaimana salinan berulang dari sebuah gambar digunakan untuk menata area. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menata tekstur pada sebuah bentuk, atau pada batas bentuk. Tekstur ditata pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Elemen dari Aspose.Imaging.WrapMode yang menentukan bagaimana salinan berulang dari sebuah gambar digunakan untuk menata area. |
| color | [Color](../../com.aspose.psd/color) | Objek com.aspose.psd.ImageAttributes yang menentukan warna piksel di luar gambar yang dirender. Warna ini terlihat jika parameter mode diatur ke WrapMode.Clamp dan persegi panjang sumber yang diberikan ke DrawImage lebih besar daripada gambar itu sendiri. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menata tekstur pada sebuah bentuk, atau pada batas bentuk. Tekstur ditata pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Elemen dari Aspose.Imaging.WrapMode yang menentukan bagaimana salinan berulang dari sebuah gambar digunakan untuk menata area. |
| color | [Color](../../com.aspose.psd/color) | Objek warna yang menentukan warna piksel di luar gambar yang dirender. Warna ini terlihat jika parameter mode diatur ke WrapMode.Clamp dan persegi panjang sumber yang diberikan ke DrawImage lebih besar daripada gambar itu sendiri. |
| clamp | boolean | Parameter ini tidak berpengaruh. Atur menjadi false. |

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

