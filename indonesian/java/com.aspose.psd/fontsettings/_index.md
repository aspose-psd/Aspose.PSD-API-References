---
title: "FontSettings"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pengaturan font renderer untuk format vektor imaging umum."
type: docs
weight: 47
url: /id/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Pengaturan font renderer untuk format vektor imaging umum.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Mendapatkan nama font adobe berdasarkan nama keluarga font. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Mendapatkan nama font default. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Mendapatkan folder font default. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Mendapatkan array pengganti font berdasarkan nama font. |
| [getFontsFolders()](#getFontsFolders--) | Mendapatkan salinan array yang berisi daftar folder tempat Aspose.Imaging mencari font TrueType. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Mendapatkan font pengganti yang paling cocok. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Menentukan apakah [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Menghapus file cache font. |
| [reset()](#reset--) | Mengatur ulang folder font dan nama font default ke default sistem. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Membatasi penggunaan font dengan daftar font. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Mengatur nama font default. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Mengatur daftar pengganti font. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Timpa daftar folder font untuk folder. |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Timpa daftar folder font untuk folder. |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Mengatur folder tempat font TrueType dimuat dan menghapus semua font yang dimuat. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Memperbarui cache font untuk file PSD yang berisi lapisan teks. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Mendapatkan nama font adobe berdasarkan nama keluarga font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Nama keluarga font. |

**Returns:**
java.lang.String - Nama font adobe berdasarkan nama keluarga font.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Mendapatkan nama font default.

**Returns:**
java.lang.String - nama font default
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Mendapatkan folder font default.

**Returns:**
java.lang.String[] - Mengembalikan folder sistem
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Mendapatkan array pengganti font berdasarkan nama font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font. |

**Returns:**
java.lang.String[] - Array nama pengganti untuk font yang disediakan
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Mendapatkan salinan array yang berisi daftar folder tempat Aspose.Imaging mencari font TrueType.

Nilai yang dikembalikan adalah salinan data yang digunakan oleh Aspose.Imaging. Jika Anda mengubah entri dalam array yang dikembalikan, itu tidak akan berpengaruh pada perenderan dokumen. Untuk menentukan lokasi font baru gunakan metode setFontsFolders.

**Returns:**
java.lang.String[] - Salinan lokasi font saat ini.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [get alternative font].

Nilai:  true  jika [get alternative font]; selainnya,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Mendapatkan font pengganti yang paling cocok. Jika semua pengganti tidak diizinkan maka akan mengembalikan font pertama yang diizinkan dan tersedia. Jika tidak ada font yang tersedia maka akan mengembalikan font dari argumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font. |

**Returns:**
java.lang.String - Nama font yang diganti
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


Menentukan apakah [is font allowed] [the specified font name].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font. |

**Returns:**
boolean -  true  jika [is font allowed] [nama font yang ditentukan]; selainnya,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


Menghapus file cache font.

### reset() {#reset--}
```
public static void reset()
```


Mengatur ulang folder font dan nama font default ke default sistem.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Membatasi penggunaan font dengan daftar font. Harap periksa nama font yang sebenarnya sebelum pembatasan. Set Allowed font list ke Null untuk menghapus pembatasan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontList | java.lang.String[] | Daftar font. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Mengatur nama font default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama default font. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Menetapkan daftar pengganti font. Jika font tidak diizinkan maka akan mencari pengganti. Font pertama dalam daftar akan digunakan pertama. Jika juga dibatasi, maka akan dipilih font berikutnya dari daftar. Jika font tidak memiliki pengganti atau semua pengganti tidak diizinkan maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diizinkan dan tersedia maka perpustakaan akan mencoba menggunakan font default sistem meskipun tidak diizinkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontToReplace | java.lang.String | Font yang akan diganti. |
| fontNames | java.lang.String[] | Nama font pengganti dalam urutan kemiripan. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Timpa daftar folder font untuk folder.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folder | java.lang.String | Folder dengan font TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Timpa daftar folder font untuk folder.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folders | java.lang.String[] | Array folder |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Menetapkan folder tempat font TrueType dimuat dan membersihkan semua font yang dimuat. Tidak ada pemeriksaan yang dilakukan pada folder font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folders | java.lang.String[] | Folder font. |
| recursive | boolean | jika disetel ke  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [get alternative font].

Nilai:  true  jika [get alternative font]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Memperbarui cache font untuk file PSD yang berisi lapisan teks. Metode ini menjamin bahwa font dari folder fontsFolder yang menggunakan metode FontSettings.setFontsFolder(fontsFolder) atau setelah mereset font menggunakan FontSettings.reset() akan dipertimbangkan saat memproses file PSD. Harap gunakan metode ini setiap kali FontSettings.setFontsFolder(fontsFolder) atau FontSettings.reset() dipanggil untuk gambar PSD. Tanpa memanggil Method ini tidak ada jaminan bahwa font akan diperbarui.

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

