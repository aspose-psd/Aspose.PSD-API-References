---
title: "Font"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan format tertentu untuk teks termasuk atribut ukuran jenis huruf dan gaya."
type: docs
weight: 46
url: /id/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Mendefinisikan format tertentu untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Menginisialisasi sebuah  com.aspose.psd.Font  baru yang menggunakan  com.aspose.psd.Font  yang ada dan enumerasi  com.aspose.psd.FontStyle  yang ditentukan. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran yang ditentukan. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran dan gaya yang ditentukan. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran, gaya, satuan, dan set karakter yang ditentukan. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran, gaya, dan satuan yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan dalam yang tepat dari  Font  ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menunjukkan apakah objek yang ditentukan adalah  com.aspose.psd.Font  dan memiliki nilai properti yang sama dengan  com.aspose.psd.Font  ini. |
| [getBold()](#getBold--) | Mendapatkan nilai yang menunjukkan apakah  Font  ini tebal. |
| [getCharacterSet()](#getCharacterSet--) | Mendapatkan nilai byte yang menentukan set karakter yang digunakan oleh  Font  ini. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Mendapatkan nilai yang menunjukkan apakah  Font  ini miring. |
| [getName()](#getName--) | Mendapatkan nama jenis huruf dari  Font  ini. |
| [getSize()](#getSize--) | Mendapatkan ukuran em dari  Font  ini yang diukur dalam satuan yang ditentukan oleh properti  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Mendapatkan nilai yang menunjukkan apakah  Font  ini memiliki garis horizontal melalui huruf. |
| [getStyle()](#getStyle--) | Mendapatkan informasi gaya untuk  Font  ini. |
| [getUnderline()](#getUnderline--) | Mendapatkan nilai yang menunjukkan apakah  Font  ini bergaris bawah. |
| [getUnit()](#getUnit--) | Mendapatkan satuan ukuran untuk  Font  ini. |
| [hashCode()](#hashCode--) | Mendapatkan kode hash untuk  com.aspose.psd.Font  ini. |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran dan satuan yang ditentukan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari  com.aspose.psd.Font  ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Menginisialisasi sebuah  com.aspose.psd.Font  baru yang menggunakan  com.aspose.psd.Font  yang ada dan enumerasi  com.aspose.psd.FontStyle  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Font  com.aspose.psd.Font  yang ada dari mana akan dibuat Font  com.aspose.psd.Font  baru. |
| newStyle | int | FontStyle  com.aspose.psd.FontStyle  yang akan diterapkan pada Font  com.aspose.psd.Font  baru. Beberapa nilai dari enumerasi  com.aspose.psd.FontStyle  dapat digabungkan dengan operator OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Menginisialisasi sebuah  com.aspose.psd.Font  baru menggunakan ukuran yang ditentukan. Set karakter diatur ke  F:Aspose.Imaging.CharacterSet.Default , unit grafik ke  F:Aspose.Imaging.GraphicsUnit.Point , gaya font ke  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Representasi string dari nama  com.aspose.psd.Font . |
| emSize | float | Ukuran em, dalam poin, dari font baru. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Menginisialisasi sebuah  com.aspose.psd.Font  baru menggunakan ukuran dan gaya yang ditentukan. Set karakter diatur ke  F:Aspose.Imaging.CharacterSet.Default , unit grafik ke  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Representasi string dari nama  com.aspose.psd.Font . |
| emSize | float | Ukuran em, dalam poin, dari font baru. |
| style | int | Gaya  com.aspose.psd.FontStyle  dari font baru. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran, gaya, satuan, dan set karakter yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Representasi string dari nama  com.aspose.psd.Font . |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter  unit . |
| style | int | Gaya  com.aspose.psd.FontStyle  dari font baru. |
| unit | int | Unit  com.aspose.psd.GraphicsUnit  dari font baru. |
| characterSet | int | Set karakter yang digunakan untuk font ini. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Menginisialisasi sebuah  com.aspose.psd.Font  baru dengan ukuran, gaya, dan satuan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Representasi string dari nama  com.aspose.psd.Font . |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter  unit . |
| style | int | Gaya  com.aspose.psd.FontStyle  dari font baru. |
| unit | int | Unit  com.aspose.psd.GraphicsUnit  dari font baru. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Membuat salinan dalam yang tepat dari  Font  ini.

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menunjukkan apakah objek yang ditentukan adalah  com.aspose.psd.Font  dan memiliki nilai properti yang sama dengan  com.aspose.psd.Font  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - True jika parameter  obj  adalah sebuah  com.aspose.psd.Font  dan memiliki nilai properti yang sama dengan  com.aspose.psd.Font  ini; jika tidak, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Mendapatkan nilai yang menunjukkan apakah  Font  ini tebal.

**Returns:**
boolean - True jika  Font  ini tebal; jika tidak, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Mendapatkan nilai byte yang menentukan set karakter yang digunakan oleh  Font  ini.

**Returns:**
int - Set karakter yang digunakan oleh  Font  ini.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Mendapatkan nilai yang menunjukkan apakah  Font  ini miring.

**Returns:**
boolean - True jika  Font  ini miring; jika tidak, false.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama jenis huruf dari  Font  ini.

**Returns:**
java.lang.String - Representasi string dari nama wajah (face name) dari  Font  ini.
### getSize() {#getSize--}
```
public float getSize()
```


Mendapatkan ukuran em dari  Font  ini yang diukur dalam satuan yang ditentukan oleh properti  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - Ukuran em dari  Font  ini.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Mendapatkan nilai yang menunjukkan apakah  Font  ini memiliki garis horizontal melalui huruf.

**Returns:**
boolean - True jika  Font  ini memiliki garis horizontal melaluinya; jika tidak, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Mendapatkan informasi gaya untuk  Font  ini.

**Returns:**
int - Sebuah enumerasi  FontStyle  yang berisi informasi gaya untuk  Font  ini.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Mendapatkan nilai yang menunjukkan apakah  Font  ini bergaris bawah.

**Returns:**
boolean - True jika  Font  ini digarisbawahi; jika tidak, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Mendapatkan satuan ukuran untuk  Font  ini.

**Returns:**
int - Sebuah  GraphicsUnit  yang mewakili satuan ukuran untuk  Font  ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash untuk  com.aspose.psd.Font  ini.

**Returns:**
int - Kode hash untuk  com.aspose.psd.Font  ini.
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Menginisialisasi sebuah  com.aspose.psd.Font  baru menggunakan ukuran dan satuan yang ditentukan. Set karakter diatur ke  F:Aspose.Imaging.CharacterSet.Default , gaya diatur ke  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Representasi string dari nama  com.aspose.psd.Font . |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter  unit . |
| unit | int | Unit  com.aspose.psd.GraphicsUnit  dari font baru. |

**Returns:**
[Font](../../com.aspose.psd/font)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari  com.aspose.psd.Font  ini.

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan  com.aspose.psd.Font  ini.
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

