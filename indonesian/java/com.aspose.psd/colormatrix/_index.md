---
title: "ColorMatrix"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan matriks 5 x 5 yang berisi koordinat untuk ruang RGBA."
type: docs
weight: 25
url: /id/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Mendefinisikan matriks 5 x 5 yang berisi koordinat untuk ruang RGBA. Beberapa metode dari kelas  com.aspose.psd.ImageAttributes  menyesuaikan warna gambar dengan menggunakan matriks warna. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Menginisialisasi instance baru dari kelas  Aspose.Imaging.ColorMatrix  . |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Menginisialisasi instance baru dari kelas  Aspose.Imaging.ColorMatrix  menggunakan elemen-elemen dalam matriks  newColorMatrix . |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Jumlah elemen dalam dimensi matriks. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Jumlah dimensi matriks. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Jumlah total elemen dalam matriks. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Mendapatkan nilai-nilai matriks. |
| [getMatrix00()](#getMatrix00--) | Mendapatkan elemen pada baris 0 (nol) dan kolom 0 dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix01()](#getMatrix01--) | Mendapatkan elemen pada baris 0 (nol) dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix02()](#getMatrix02--) | Mendapatkan elemen pada baris 0 (nol) dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix03()](#getMatrix03--) | Mendapatkan elemen pada baris 0 (nol) dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix04()](#getMatrix04--) | Mendapatkan elemen pada baris 0 (nol) dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix10()](#getMatrix10--) | Mendapatkan elemen pada baris pertama dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix11()](#getMatrix11--) | Mendapatkan elemen pada baris pertama dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix12()](#getMatrix12--) | Mendapatkan elemen pada baris pertama dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix13()](#getMatrix13--) | Mendapatkan elemen pada baris pertama dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix14()](#getMatrix14--) | Mendapatkan elemen pada baris pertama dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix20()](#getMatrix20--) | Mendapatkan elemen pada baris kedua dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix21()](#getMatrix21--) | Mendapatkan elemen pada baris kedua dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix22()](#getMatrix22--) | Mendapatkan elemen pada baris kedua dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix23()](#getMatrix23--) | Mendapatkan elemen pada baris kedua dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix24()](#getMatrix24--) | Mendapatkan elemen pada baris kedua dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix30()](#getMatrix30--) | Mendapatkan elemen pada baris ketiga dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix31()](#getMatrix31--) | Mendapatkan elemen pada baris ketiga dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix32()](#getMatrix32--) | Mendapatkan elemen pada baris ketiga dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix33()](#getMatrix33--) | Mendapatkan elemen pada baris ketiga dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix34()](#getMatrix34--) | Mendapatkan elemen pada baris ketiga dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix40()](#getMatrix40--) | Mendapatkan elemen pada baris keempat dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix41()](#getMatrix41--) | Mendapatkan elemen pada baris keempat dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |
| [getMatrix42()](#getMatrix42--) | Mendapatkan elemen pada baris keempat dan kolom kedua dari Aspose.Imaging.ColorMatrix . |
| [getMatrix43()](#getMatrix43--) | Mendapatkan elemen pada baris keempat dan kolom ketiga dari Aspose.Imaging.ColorMatrix . |
| [getMatrix44()](#getMatrix44--) | Mendapatkan elemen pada baris keempat dan kolom keempat dari Aspose.Imaging.ColorMatrix . |
| [get_Item(int row, int column)](#get-Item-int-int-) | Mendapatkan elemen pada baris dan kolom yang ditentukan di Aspose.Imaging.ColorMatrix . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Mengatur elemen pada baris 0 (nol) dan kolom 0 dari Aspose.Imaging.ColorMatrix . |
| [setMatrix01(float value)](#setMatrix01-float-) | Mengatur elemen pada baris 0 (nol) dan kolom pertama dari Aspose.Imaging.ColorMatrix . |
| [setMatrix02(float value)](#setMatrix02-float-) | Mengatur elemen pada baris 0 (nol) dan kolom kedua dari Aspose.Imaging.ColorMatrix . |
| [setMatrix03(float value)](#setMatrix03-float-) | Mengatur elemen pada baris 0 (nol) dan kolom ketiga dari Aspose.Imaging.ColorMatrix . |
| [setMatrix04(float value)](#setMatrix04-float-) | Mengatur elemen pada baris 0 (nol) dan kolom keempat dari Aspose.Imaging.ColorMatrix . |
| [setMatrix10(float value)](#setMatrix10-float-) | Mengatur elemen pada baris pertama dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix . |
| [setMatrix11(float value)](#setMatrix11-float-) | Mengatur elemen pada baris pertama dan kolom pertama dari Aspose.Imaging.ColorMatrix . |
| [setMatrix12(float value)](#setMatrix12-float-) | Mengatur elemen pada baris pertama dan kolom kedua dari Aspose.Imaging.ColorMatrix . |
| [setMatrix13(float value)](#setMatrix13-float-) | Mengatur elemen pada baris pertama dan kolom ketiga dari Aspose.Imaging.ColorMatrix . |
| [setMatrix14(float value)](#setMatrix14-float-) | Mengatur elemen pada baris pertama dan kolom keempat dari Aspose.Imaging.ColorMatrix . |
| [setMatrix20(float value)](#setMatrix20-float-) | Mengatur elemen pada baris kedua dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix . |
| [setMatrix21(float value)](#setMatrix21-float-) | Mengatur elemen pada baris kedua dan kolom pertama dari Aspose.Imaging.ColorMatrix . |
| [setMatrix22(float value)](#setMatrix22-float-) | Mengatur elemen pada baris kedua dan kolom kedua dari Aspose.Imaging.ColorMatrix . |
| [setMatrix23(float value)](#setMatrix23-float-) | Mengatur elemen pada baris kedua dan kolom ketiga dari Aspose.Imaging.ColorMatrix . |
| [setMatrix24(float value)](#setMatrix24-float-) | Mengatur elemen pada baris kedua dan kolom keempat dari Aspose.Imaging.ColorMatrix . |
| [setMatrix30(float value)](#setMatrix30-float-) | Mengatur elemen pada baris ketiga dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix . |
| [setMatrix31(float value)](#setMatrix31-float-) | Mengatur elemen pada baris ketiga dan kolom pertama dari Aspose.Imaging.ColorMatrix . |
| [setMatrix32(float value)](#setMatrix32-float-) | Mengatur elemen pada baris ketiga dan kolom kedua dari Aspose.Imaging.ColorMatrix . |
| [setMatrix33(float value)](#setMatrix33-float-) | Mengatur elemen pada baris ketiga dan kolom ketiga dari Aspose.Imaging.ColorMatrix . |
| [setMatrix34(float value)](#setMatrix34-float-) | Mengatur elemen pada baris ketiga dan kolom keempat dari Aspose.Imaging.ColorMatrix . |
| [setMatrix40(float value)](#setMatrix40-float-) | Mengatur elemen pada baris keempat dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix . |
| [setMatrix41(float value)](#setMatrix41-float-) | Mengatur elemen pada baris keempat dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |
| [setMatrix42(float value)](#setMatrix42-float-) | Mengatur elemen pada baris keempat dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |
| [setMatrix43(float value)](#setMatrix43-float-) | Mengatur elemen pada baris keempat dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |
| [setMatrix44(float value)](#setMatrix44-float-) | Mengatur elemen pada baris keempat dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Mengatur elemen pada baris dan kolom yang ditentukan dalam Aspose.Imaging.ColorMatrix. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Menginisialisasi instance baru dari kelas  Aspose.Imaging.ColorMatrix  .

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Menginisialisasi instance baru dari kelas  Aspose.Imaging.ColorMatrix  menggunakan elemen-elemen dalam matriks  newColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | float[][] | Nilai-nilai elemen untuk Aspose.Imaging.ColorMatrix baru. |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Jumlah elemen dalam dimensi matriks.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Jumlah dimensi matriks.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Jumlah total elemen dalam matriks.

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
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Mendapatkan nilai-nilai matriks.

**Returns:**
float[][] - Array nilai matriks.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom 0 dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris 0 dan kolom 0 dari Aspose.Imaging.ColorMatrix ini.
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris 0 dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris 0 dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris 0 dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris 0 dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Mendapatkan elemen pada baris pertama dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris pertama dan kolom 0 dari Aspose.Imaging.ColorMatrix ini.
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Mendapatkan elemen pada baris pertama dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris pertama dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Mendapatkan elemen pada baris pertama dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris pertama dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Mendapatkan elemen pada baris pertama dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris pertama dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Mendapatkan elemen pada baris pertama dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris pertama dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Mendapatkan elemen pada baris kedua dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris kedua dan kolom 0 dari Aspose.Imaging.ColorMatrix ini.
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Mendapatkan elemen pada baris kedua dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris kedua dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Mendapatkan elemen pada baris kedua dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris kedua dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Mendapatkan elemen pada baris kedua dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris kedua dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Mendapatkan elemen pada baris kedua dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris kedua dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Mendapatkan elemen pada baris ketiga dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris ketiga dan kolom 0 dari Aspose.Imaging.ColorMatrix ini.
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Mendapatkan elemen pada baris ketiga dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris ketiga dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Mendapatkan elemen pada baris ketiga dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris ketiga dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Mendapatkan elemen pada baris ketiga dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris ketiga dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Mendapatkan elemen pada baris ketiga dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris ketiga dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Mendapatkan elemen pada baris keempat dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris keempat dan kolom 0 dari Aspose.Imaging.ColorMatrix ini.
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Mendapatkan elemen pada baris keempat dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.

**Returns:**
float - Elemen pada baris keempat dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Mendapatkan elemen pada baris keempat dan kolom kedua dari Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elemen pada baris keempat dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Mendapatkan elemen pada baris keempat dan kolom ketiga dari Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elemen pada baris keempat dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Mendapatkan elemen pada baris keempat dan kolom keempat dari Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elemen pada baris keempat dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Mendapatkan elemen pada baris dan kolom yang ditentukan di Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baris | int | Nomor baris. |
| kolom | int | Nomor kolom. |

**Returns:**
float - Elemen pada baris dan kolom yang ditentukan.
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




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom 0 dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris 0 dan kolom 0 dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom pertama dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris 0 dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom kedua dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris 0 dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom ketiga dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris 0 dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom keempat dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris 0 dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Mengatur elemen pada baris pertama dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris pertama dan kolom 0 dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Mengatur elemen pada baris pertama dan kolom pertama dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris pertama dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Mengatur elemen pada baris pertama dan kolom kedua dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris pertama dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Mengatur elemen pada baris pertama dan kolom ketiga dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris pertama dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Mengatur elemen pada baris pertama dan kolom keempat dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris pertama dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Mengatur elemen pada baris kedua dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris kedua dan kolom 0 dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Mengatur elemen pada baris kedua dan kolom pertama dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris kedua dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Mengatur elemen pada baris kedua dan kolom kedua dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris kedua dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Mengatur elemen pada baris kedua dan kolom ketiga dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris kedua dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Mengatur elemen pada baris kedua dan kolom keempat dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris kedua dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Mengatur elemen pada baris ketiga dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris ketiga dan kolom 0 dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Mengatur elemen pada baris ketiga dan kolom pertama dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris ketiga dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Mengatur elemen pada baris ketiga dan kolom kedua dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris ketiga dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Mengatur elemen pada baris ketiga dan kolom ketiga dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris ketiga dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Mengatur elemen pada baris ketiga dan kolom keempat dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris ketiga dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Mengatur elemen pada baris keempat dan kolom 0 (nol) dari Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris keempat dan kolom 0 dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Mengatur elemen pada baris keempat dan kolom pertama dari Aspose.Imaging.ColorMatrix ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris keempat dan kolom pertama dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Mengatur elemen pada baris keempat dan kolom kedua dari Aspose.Imaging.ColorMatrix ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris keempat dan kolom kedua dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Mengatur elemen pada baris keempat dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris keempat dan kolom ketiga dari Aspose.Imaging.ColorMatrix ini. |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Mengatur elemen pada baris keempat dan kolom keempat dari Aspose.Imaging.ColorMatrix ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Elemen pada baris keempat dan kolom keempat dari Aspose.Imaging.ColorMatrix ini. |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Mengatur elemen pada baris dan kolom yang ditentukan dalam Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baris | int | Nomor baris. |
| kolom | int | Nomor kolom. |
| nilai | float | Nilai |

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

