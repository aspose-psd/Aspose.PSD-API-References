---
title: "RawColorHelper"
second_title: "Java için Aspose.PSD API Referansı"
description: "Raw Color Helper Sınıfı, önceden tanımlı kanal meta verilerini kullanarak RawColor'ı daha hızlı oluşturur."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class, önceden tanımlı kanal meta verilerini kullanarak RawColor'ı daha hızlı oluşturmanıza yardımcı olur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Her kanal için 16 bit ARGB renk oluşturur. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Her kanal için 8 bit ARGB renk oluşturur. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Drawing.Color'dan her kanal için 8 bit ARGB renk oluşturur. |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Her kanal için 16 bit CMYK renk oluşturur. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Her kanal için 8 bit CMYK renk oluşturur. |
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


Her kanal için 16 bit ARGB renk oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | int | Alfa bileşen değeri (0-65535). |
| r | int | Kırmızı bileşen değeri (0-65535). |
| g | int | Yeşil bileşen değeri (0-65535). |
|  | b | int | Mavi bileşen değeri (0-65535). |

--------------------

Renk bileşenleri, aşağıdaki sırayla 64 bit tamsayı içinde paketlenir: alfa (bitler 48-63), kırmızı (bitler 32-47), yeşil (bitler 16-31) ve mavi (bitler 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Her kanal için 8 bit ARGB renk oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | byte | Alfa bileşen değeri (0-255). |
| r | byte | Kırmızı bileşen değeri (0-255). |
| g | byte | Yeşil bileşen değeri (0-255). |
|  | b | byte | Mavi bileşen değeri (0-255). |

--------------------

Renk bileşenleri, aşağıdaki sırayla 32 bit tamsayı içinde paketlenir: alfa (bitler 24-31), kırmızı (bitler 16-23), yeşil (bitler 8-15) ve mavi (bitler 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Drawing.Color'dan her kanal için 8 bit ARGB renk oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | System.Drawing Rengi |

--------------------

Renk bileşenleri, aşağıdaki sırayla 32 bit tamsayı içinde paketlenir: alfa (bitler 24-31), kırmızı (bitler 16-23), yeşil (bitler 8-15) ve mavi (bitler 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Her kanal için 16 bit CMYK renk oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | int | Camgöbeği bileşen değeri (0-65535). |
| m | int | Macenta bileşen değeri (0-65535). |
| y | int | Sarı bileşen değeri (0-65535). |
|  | k | int | Anahtar (siyah) bileşen değeri (0-65535). |

--------------------

Renk bileşenleri, şu sırayla 64-bit tamsayıya paketlenir: camgöbeği (bitler 48-63), macenta (bitler 32-47), sarı (bitler 16-31) ve anahtar/siyah (bitler 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Her kanal için 8 bit CMYK renk oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | byte | Camgöbeği bileşen değeri (0-255). |
| m | byte | Macenta bileşen değeri (0-255). |
| y | byte | Sarı bileşen değeri (0-255). |
|  | k | byte | Anahtar (siyah) bileşen değeri (0-255). |

--------------------

Renk bileşenleri, şu sırayla 32-bit tamsayıya paketlenir: camgöbeği (bitler 24-31), macenta (bitler 16-23), sarı (bitler 8-15) ve anahtar/siyah (bitler 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

