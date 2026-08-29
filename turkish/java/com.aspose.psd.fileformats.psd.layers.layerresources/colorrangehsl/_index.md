---
title: "ColorRangeHsl"
second_title: "Java için Aspose.PSD API Referansı"
description: "HSV parametrelerini değiştirebileceğiniz 6 renk aralığı vardır."
type: docs
weight: 22
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Yeni bir [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) sınıfının örneğini başlatır. |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Yeni bir [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Alır veya ayarlar hue. |
| [getLeftBorder()](#getLeftBorder--) | Sol kenarı alır veya ayarlar. |
| [getLightness()](#getLightness--) | Alır veya ayarlar lightness. |
| [getMostLeftBorder()](#getMostLeftBorder--) | En sol kenarı alır veya ayarlar. |
| [getMostRightBorder()](#getMostRightBorder--) | En sağ kenarı alır veya ayarlar. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Aralık katsayısını alır. |
| [getRightBorder()](#getRightBorder--) | Sağ kenarı alır veya ayarlar. |
| [getSaturation()](#getSaturation--) | Doygunluğu alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Renk tonunun büyük aralıkta olup olmadığını belirler. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Renk tonunun küçük aralıkta olup olmadığını belirler. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Veriyi belirtilen akış konteynerine kaydeder. |
| [setHue(short value)](#setHue-short-) | Alır veya ayarlar hue. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Sol kenarı alır veya ayarlar. |
| [setLightness(short value)](#setLightness-short-) | Alır veya ayarlar lightness. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | En sol kenarı alır veya ayarlar. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | En sağ kenarı alır veya ayarlar. |
| [setRightBorder(short value)](#setRightBorder-short-) | Sağ kenarı alır veya ayarlar. |
| [setSaturation(short value)](#setSaturation-short-) | Doygunluğu alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Yeni bir [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) sınıfının örneğini başlatır.

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Yeni bir [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Renk aralığı verileri. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getHue() {#getHue--}
```
public final short getHue()
```


Alır veya ayarlar hue.

Değer: Renk tonu.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Sol kenarı alır veya ayarlar.

Değer: Sol kenar.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Alır veya ayarlar lightness.

Değer: Açıklık.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


En sol kenarı alır veya ayarlar.

Değer: En sol kenar.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


En sağ kenarı alır veya ayarlar.

Değer: En sağ kenar.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Aralık katsayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | double | Renk tonu değeri. |

**Returns:**
double - Doygunluk aralığı katsayısı.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Sağ kenarı alır veya ayarlar.

Değer: Sağ kenar.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Doygunluğu alır veya ayarlar.

Değer: Doygunluk.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


Renk tonunun büyük aralıkta olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | double | Renk tonu değeri. |

**Returns:**
boolean -  true  eğer hue büyük aralıkta; aksi takdirde,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Renk tonunun küçük aralıkta olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | double | Renk tonu değeri. |

**Returns:**
boolean -  true  eğer hue küçük aralıkta; aksi takdirde,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Veriyi belirtilen akış konteynerine kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Alır veya ayarlar hue.

Değer: Renk tonu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Sol kenarı alır veya ayarlar.

Değer: Sol kenar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Alır veya ayarlar lightness.

Değer: Açıklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


En sol kenarı alır veya ayarlar.

Değer: En sol kenar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


En sağ kenarı alır veya ayarlar.

Değer: En sağ kenar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Sağ kenarı alır veya ayarlar.

Değer: Sağ kenar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Doygunluğu alır veya ayarlar.

Değer: Doygunluk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

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

