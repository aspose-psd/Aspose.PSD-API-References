---
title: "StringFormat"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Menangkap informasi tata letak teks seperti orientasi perataan dan tab stop, serta manipulasi tampilan seperti penyisipan elipsis, substitusi digit nasional, dan fitur OpenType."
type: docs
weight: 106
url: /id/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Menangkap informasi tata letak teks (seperti perataan, orientasi, dan tab stop) serta manipulasi tampilan (seperti penyisipan elipsis dan substitusi digit nasional) dan fitur OpenType. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StringFormat()](#StringFormat--) | Menginisialisasi objek  com.aspose.psd.StringFormat  baru. |
| [StringFormat(int options)](#StringFormat-int-) | Menginisialisasi objek  com.aspose.psd.StringFormat  baru dengan enumerasi  com.aspose.psd.StringFormatFlags  yang ditentukan dan bahasa. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Menginisialisasi objek  com.aspose.psd.StringFormat  baru dari objek  com.aspose.psd.StringFormat  yang ada yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Membuat klon mendalam dari objek  com.aspose.psd.StringFormat  ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Mengambil informasi perataan teks pada bidang vertikal. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Mengambil bahasa yang digunakan ketika digit lokal digantikan dengan digit barat. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Mengambil metode yang akan digunakan untuk substitusi digit. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Mengambil jumlah spasi antara awal baris teks dan tab stop pertama. |
| [getFormatFlags()](#getFormatFlags--) | Mengambil enumerasi  com.aspose.psd.StringFormatFlags  yang berisi informasi pemformatan. |
| [getGenericDefault()](#getGenericDefault--) | Mengambil objek  com.aspose.psd.StringFormat  default generik. |
| [getGenericTypographic()](#getGenericTypographic--) | Mengambil objek  com.aspose.psd.StringFormat  tipografi generik. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Mengambil objek  com.aspose.psd.HotkeyPrefix  untuk objek  com.aspose.psd.StringFormat  ini. |
| [getLineAlignment()](#getLineAlignment--) | Mengambil perataan baris pada bidang horizontal. |
| [getTabStops()](#getTabStops--) | Mengambil array jarak antara tab stop dalam satuan yang ditentukan oleh properti  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | Mengambil enumerasi  com.aspose.psd.StringTrimming  untuk objek  com.aspose.psd.StringFormat  ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Mengatur informasi perataan teks pada bidang vertikal. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Mengatur bahasa yang digunakan ketika digit lokal digantikan dengan digit barat. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Mengatur metode yang akan digunakan untuk substitusi digit. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Mengatur enumerasi  com.aspose.psd.StringFormatFlags  yang berisi informasi pemformatan. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Mengatur objek  com.aspose.psd.HotkeyPrefix  untuk objek  com.aspose.psd.StringFormat  ini. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Mengatur perataan baris pada bidang horizontal. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Mengatur tab stop untuk objek  com.aspose.psd.StringFormat  ini. |
| [setTrimming(int value)](#setTrimming-int-) | Mengatur enumerasi  com.aspose.psd.StringTrimming  untuk objek  com.aspose.psd.StringFormat  ini. |
| [toString()](#toString--) | Mengonversi objek  com.aspose.psd.StringFormat  ini menjadi string yang dapat dibaca manusia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Menginisialisasi objek  com.aspose.psd.StringFormat  baru.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Menginisialisasi objek  com.aspose.psd.StringFormat  baru dengan enumerasi  com.aspose.psd.StringFormatFlags  yang ditentukan dan bahasa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| opsi | int | Enumerasi  com.aspose.psd.StringFormatFlags  untuk objek  com.aspose.psd.StringFormat  baru. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Menginisialisasi objek  com.aspose.psd.StringFormat  baru dari objek  com.aspose.psd.StringFormat  yang ada yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Objek  com.aspose.psd.StringFormat  yang digunakan untuk menginisialisasi objek  com.aspose.psd.StringFormat  baru. |

### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Membuat klon mendalam dari objek  com.aspose.psd.StringFormat  ini.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Mengambil informasi perataan teks pada bidang vertikal.

**Returns:**
int - Sebuah enumerasi  com.aspose.psd.StringAlignment  yang menentukan informasi perataan teks.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Mengambil bahasa yang digunakan ketika digit lokal digantikan dengan digit barat.

**Returns:**
int - Sebuah pengenal bahasa National Language Support (NLS) yang mengidentifikasi bahasa yang akan digunakan ketika digit lokal digantikan dengan digit barat. Anda dapat memberikan properti  P:System.Globalization.CultureInfo.LCID  dari objek  System.Globalization.CultureInfo  sebagai pengenal bahasa NLS. Misalnya, anggap Anda membuat objek  System.Globalization.CultureInfo  dengan memberikan string "ar-EG" ke konstruktor  System.Globalization.CultureInfo . Jika Anda memberikan properti  P:System.Globalization.CultureInfo.LCID  dari objek  System.Globalization.CultureInfo  tersebut bersama dengan  com.aspose.psd.StringDigitSubstitute.Traditional  ke metode  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) , maka digit Arab-Indic akan digantikan dengan digit barat pada saat tampilan.

Setter diperkenalkan untuk metode usang setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Mengambil metode yang akan digunakan untuk substitusi digit.

**Returns:**
int - Sebuah nilai enumerasi  com.aspose.psd.StringDigitSubstitute  yang menentukan cara menggantikan karakter dalam string yang tidak dapat ditampilkan karena tidak didukung oleh font saat ini.

Setter diperkenalkan untuk metode usang SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Mengambil jumlah spasi antara awal baris teks dan tab stop pertama.

**Returns:**
float - Offset tab pertama.

Properti ini diperkenalkan untuk metode yang dihapus GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Mengambil enumerasi  com.aspose.psd.StringFormatFlags  yang berisi informasi pemformatan.

**Returns:**
int - Sebuah enumerasi  com.aspose.psd.StringFormatFlags  yang berisi informasi pemformatan.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Mengambil objek  com.aspose.psd.StringFormat  default generik.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Mengambil objek  com.aspose.psd.StringFormat  tipografi generik.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Mengambil objek  com.aspose.psd.HotkeyPrefix  untuk objek  com.aspose.psd.StringFormat  ini.

**Returns:**
int - Objek  com.aspose.psd.HotkeyPrefix  untuk objek  com.aspose.psd.StringFormat  ini, nilai baku adalah  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Mengambil perataan baris pada bidang horizontal.

**Returns:**
int - Sebuah enumerasi  com.aspose.psd.StringAlignment  yang mewakili perataan baris.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Mengambil array jarak antara tab stop dalam satuan yang ditentukan oleh properti  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] - Tab stop.

Properti ini diperkenalkan untuk metode yang dihapus GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Mengambil enumerasi  com.aspose.psd.StringTrimming  untuk objek  com.aspose.psd.StringFormat  ini.

**Returns:**
int - Sebuah enumerasi  com.aspose.psd.StringTrimming  yang menunjukkan bagaimana teks yang digambar dengan objek  com.aspose.psd.StringFormat  ini dipangkas ketika melebihi tepi persegi panjang tata letak.
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Mengatur informasi perataan teks pada bidang vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Sebuah enumerasi  com.aspose.psd.StringAlignment  yang menentukan informasi perataan teks. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Mengatur bahasa yang digunakan ketika digit lokal digantikan dengan digit barat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Pengenal bahasa National Language Support (NLS) yang mengidentifikasi bahasa yang akan digunakan ketika digit lokal digantikan dengan digit barat. Anda dapat memberikan properti  P:System.Globalization.CultureInfo.LCID  dari objek  System.Globalization.CultureInfo  sebagai pengenal bahasa NLS. Misalnya, anggap Anda membuat objek  System.Globalization.CultureInfo  dengan memberikan string "ar-EG" ke konstruktor  System.Globalization.CultureInfo . Jika Anda memberikan properti  P:System.Globalization.CultureInfo.LCID  dari objek  System.Globalization.CultureInfo  tersebut bersama dengan  com.aspose.psd.StringDigitSubstitute.Traditional  ke metode  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) , maka digit Arab-Indic akan digantikan dengan digit barat pada saat tampilan. |

The setter is introduced for the obsolete method SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Mengatur metode yang akan digunakan untuk substitusi digit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Nilai enumerasi  com.aspose.psd.StringDigitSubstitute  yang menentukan cara menggantikan karakter dalam string yang tidak dapat ditampilkan karena tidak didukung oleh font saat ini. |

The setter is introduced for the obsolete method SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Mengatur enumerasi  com.aspose.psd.StringFormatFlags  yang berisi informasi pemformatan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Enumerasi  com.aspose.psd.StringFormatFlags  yang berisi informasi pemformatan. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Mengatur objek  com.aspose.psd.HotkeyPrefix  untuk objek  com.aspose.psd.StringFormat  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Objek  com.aspose.psd.HotkeyPrefix  untuk objek  com.aspose.psd.StringFormat  ini, nilai defaultnya adalah  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Mengatur perataan baris pada bidang horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Enumerasi  com.aspose.psd.StringAlignment  yang mewakili perataan baris. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Mengatur tab stop untuk objek  com.aspose.psd.StringFormat  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstTabOffset | float | Jumlah spasi antara awal baris teks dan tab stop pertama. |
| tabStops | float[] | Array jarak antara tab stop dalam satuan yang ditentukan oleh properti  com.aspose.psd.Graphics.PageUnit . |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Mengatur enumerasi  com.aspose.psd.StringTrimming  untuk objek  com.aspose.psd.StringFormat  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Enumerasi  com.aspose.psd.StringTrimming  yang menunjukkan bagaimana teks yang digambar dengan objek  com.aspose.psd.StringFormat  ini dipangkas ketika melebihi tepi persegi panjang tata letak. |

### toString() {#toString--}
```
public String toString()
```


Mengonversi objek  com.aspose.psd.StringFormat  ini menjadi string yang dapat dibaca manusia.

**Returns:**
java.lang.String - Representasi string dari objek  com.aspose.psd.StringFormat  ini.
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

