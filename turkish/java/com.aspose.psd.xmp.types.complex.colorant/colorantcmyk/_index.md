---
title: "ColorantCmyk"
second_title: "Java için Aspose.PSD API Referansı"
description: "CMYK Renkörneği temsil eder."
type: docs
weight: 13
url: /tr/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

CMYK Renkörneği temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | ColorantCmyk sınıfının yeni bir örneğini başlatır. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | ColorantCmyk sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | CMYK renk maddesindeki maksimum renk değeri. |
| [ColorValueMin](#ColorValueMin) | CMYK renk maddesindeki minimum renk değeri. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Belirtilen anahtarı ekler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Siyah bileşen değerini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Rengin türünü alır veya ayarlar. |
| [getCyan()](#getCyan--) | Camgöbeği bileşen değerini alır veya ayarlar. |
| [getMagenta()](#getMagenta--) | Macenta bileşen değerini alır veya ayarlar. |
| [getMode()](#getMode--) | ColorMode değerini alır. |
| [getNamespaceUri()](#getNamespaceUri--) | Varsayılan ad alanı URI'sını alır. |
| [getPrefix()](#getPrefix--) | Ön eki alır. |
| [getSwatchName()](#getSwatchName--) | Örnek rengin adını alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
| [getYellow()](#getYellow--) | Sarı bileşen değerini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Siyah bileşen değerini alır veya ayarlar. |
| [setColorType(int value)](#setColorType-int-) | Rengin türünü alır veya ayarlar. |
| [setCyan(float value)](#setCyan-float-) | Camgöbeği bileşen değerini alır veya ayarlar. |
| [setMagenta(float value)](#setMagenta-float-) | Macenta bileşen değerini alır veya ayarlar. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Örnek rengin adını alır veya ayarlar. |
| [setYellow(float value)](#setYellow-float-) | Sarı bileşen değerini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


ColorantCmyk sınıfının yeni bir örneğini başlatır.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


ColorantCmyk sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| siyah | float | Siyah bileşen değeri. |
| camgöbeği | float | Camgöbeği renk bileşen değeri. |
| macenta | float | Macenta bileşen değeri. |
| sarı | float | Sarı bileşen değeri. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


CMYK renk maddesindeki maksimum renk değeri.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


CMYK renk maddesindeki minimum renk değeri.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Belirtilen anahtarı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.Object | Eklenecek değer. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Siyah bileşen değerini alır veya ayarlar.

Değer: Siyah bileşen değeri.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Rengin türünü alır veya ayarlar.

Değer: Renk türü.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Camgöbeği bileşen değerini alır veya ayarlar.

Değer: Camgöbeği bileşen değeri.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Macenta bileşen değerini alır veya ayarlar.

Değer: Macenta bileşen değeri.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


ColorMode değerini alır.

Değer: Renk modu.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Varsayılan ad alanı URI'sını alır.

**Returns:**
java.lang.String - Varsayılan ad alanı URI'si.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ön eki alır.

**Returns:**
java.lang.String - Önek.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Örnek rengin adını alır veya ayarlar.

Değer: Renk örneği adı.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içerilen dize değerini alır.

**Returns:**
java.lang.String - XMP formatında içerilen dize değerini döndürür.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Sarı bileşen değerini alır veya ayarlar.

Değer: Sarı bileşen değeri.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Siyah bileşen değerini alır veya ayarlar.

Değer: Siyah bileşen değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Rengin türünü alır veya ayarlar.

Değer: Renk türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Camgöbeği bileşen değerini alır veya ayarlar.

Değer: Camgöbeği bileşen değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Macenta bileşen değerini alır veya ayarlar.

Değer: Macenta bileşen değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Örnek rengin adını alır veya ayarlar.

Değer: Renk örneği adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Sarı bileşen değerini alır veya ayarlar.

Değer: Sarı bileşen değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

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

