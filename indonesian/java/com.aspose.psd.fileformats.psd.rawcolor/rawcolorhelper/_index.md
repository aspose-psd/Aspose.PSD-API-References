---
title: "RawColorHelper"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas Raw Color Helper membantu membuat RawColor lebih cepat menggunakan metadata saluran yang telah ditentukan sebelumnya"
type: docs
weight: 12
url: /id/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Kelas Pembantu Raw Color membantu membuat RawColor lebih cepat, menggunakan metadata kanal yang telah ditentukan
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Membuat warna ARGB 16-bit per saluran. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Membuat warna ARGB 8-bit per saluran. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Membuat warna ARGB 8-bit per saluran dari Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Membuat warna CMYK 16-bit per saluran. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Membuat warna CMYK 8-bit per saluran. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


Membuat warna ARGB 16-bit per saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | int | Nilai komponen alfa (0-65535). |
| r | int | Nilai komponen merah (0-65535). |
| g | int | Nilai komponen hijau (0-65535). |
|  | b | int | Nilai komponen biru (0-65535). |

--------------------

Komponen warna dikemas ke dalam integer 64-bit dengan urutan: alfa (bit 48-63), merah (bit 32-47), hijau (bit 16-31), dan biru (bit 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Membuat warna ARGB 8-bit per saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | byte | Nilai komponen alfa (0-255). |
| r | byte | Nilai komponen merah (0-255). |
| g | byte | Nilai komponen hijau (0-255). |
|  | b | byte | Nilai komponen biru (0-255). |

--------------------

Komponen warna dikemas ke dalam integer 32-bit dengan urutan: alfa (bit 24-31), merah (bit 16-23), hijau (bit 8-15), dan biru (bit 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Membuat warna ARGB 8-bit per saluran dari Drawing.Color

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | Warna System.Drawing |

--------------------

Komponen warna dikemas ke dalam integer 32-bit dengan urutan: alfa (bit 24-31), merah (bit 16-23), hijau (bit 8-15), dan biru (bit 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Membuat warna CMYK 16-bit per saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | int | Nilai komponen cyan (0-65535). |
| m | int | Nilai komponen magenta (0-65535). |
| y | int | Nilai komponen kuning (0-65535). |
|  | k | int | Nilai komponen kunci (hitam) (0-65535). |

--------------------

Komponen warna dikemas ke dalam integer 64-bit dengan urutan: cyan (bits 48-63), magenta (bits 32-47), yellow (bits 16-31), dan key/black (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Membuat warna CMYK 8-bit per saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | byte | Nilai komponen cyan (0-255). |
| m | byte | Nilai komponen magenta (0-255). |
| y | byte | Nilai komponen kuning (0-255). |
|  | k | byte | Nilai komponen kunci (hitam) (0-255). |

--------------------

Komponen warna dikemas ke dalam integer 32-bit dengan urutan: cyan (bits 24-31), magenta (bits 16-23), yellow (bits 8-15), dan key/black (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

