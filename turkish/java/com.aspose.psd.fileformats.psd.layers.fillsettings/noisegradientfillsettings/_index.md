---
title: "NoiseGradientFillSettings"
second_title: "Java için Aspose.PSD API Referansı"
description: "Gürültü gradyanı tanım sınıfı."
type: docs
weight: 18
url: /tr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Gürültü gradyanı tanım sınıfı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAngle()](#getAngle--) | Açıyı alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Renk Modelini alır veya ayarlar - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getExpansionCount()](#getExpansionCount--) | Genişleme sayısını alır veya ayarlar ( = 2 Photoshop 6.0 için). |
| [getFillType()](#getFillType--) | Dolgu türü. |
| [getGradientMode()](#getGradientMode--) | Bu gradyan için modu alır. |
| [getGradientName()](#getGradientName--) | Gradyanın adını alır veya ayarlar. |
| [getGradientType()](#getGradientType--) | Gradyanın türünü alır veya ayarlar. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat'ın Azami rengini alır veya ayarlar. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat'ın Minimum rengini alır veya ayarlar. |
| [getReverse()](#getReverse--) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Gürültü gradyanı için renk üretmekte kullanılan rastgele sayı tohumunu alır veya ayarlar. |
| [getRoughness()](#getRoughness--) | Pürüzlülük faktörünü alır veya ayarlar. |
| [getScale()](#getScale--) | Ölçeği alır veya ayarlar. |
| [getShowTransparency()](#getShowTransparency--) | Şeffaflığı gösterme bayrağını alır veya ayarlar. |
| [getUseVectorColor()](#getUseVectorColor--) | Vektör rengini kullanma bayrağını alır veya ayarlar. |
| [getVerticalOffset()](#getVerticalOffset--) | Yüzde olarak dikey ofseti alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Değer değiştiğinde tetikler. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) | Açıyı alır veya ayarlar. |
| [setColorModel(short value)](#setColorModel-short-) | Renk Modelini alır veya ayarlar - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Genişleme sayısını alır veya ayarlar ( = 2 Photoshop 6.0 için). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Bu gradyan için modu alır. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gradyanın adını alır veya ayarlar. |
| [setGradientType(int value)](#setGradientType-int-) | Gradyanın türünü alır veya ayarlar. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat'ın Azami rengini alır veya ayarlar. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat'ın Minimum rengini alır veya ayarlar. |
| [setReverse(boolean value)](#setReverse-boolean-) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Gürültü gradyanı için renk üretmekte kullanılan rastgele sayı tohumunu alır veya ayarlar. |
| [setRoughness(int value)](#setRoughness-int-) | Pürüzlülük faktörünü alır veya ayarlar. |
| [setScale(int value)](#setScale-int-) | Ölçeği alır veya ayarlar. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Şeffaflığı gösterme bayrağını alır veya ayarlar. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Vektör rengini kullanma bayrağını alır veya ayarlar. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Yüzde olarak dikey ofseti alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


[NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) sınıfının yeni bir örneğini başlatır.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Açıyı alır veya ayarlar.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Renk Modelini alır veya ayarlar - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Genişleme sayısını alır veya ayarlar ( = 2 Photoshop 6.0 için).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


Dolgu türü.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Bu gradyanın kipini alır. 'Gradient Type' = 'Solid/Noise' (0/1) belirler.

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Gradyanın adını alır veya ayarlar.

Değer: Gradyanın adı.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Gradyanın türünü alır veya ayarlar.

Değer: Gradyanın türü.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Yüzde olarak yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Returns:**
double
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat'ın Azami rengini alır veya ayarlar.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat'ın Minimum rengini alır veya ayarlar.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Gürültü gradyanı için renk üretmekte kullanılan rastgele sayı tohumunu alır veya ayarlar.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Pürüzlülük faktörünü alır veya ayarlar.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Ölçeği alır veya ayarlar.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Şeffaflığı gösterme bayrağını alır veya ayarlar.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Vektör rengini kullanma bayrağını alır veya ayarlar.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Yüzde olarak dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Değer değiştiğinde tetikler.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Açıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Renk Modelini alır veya ayarlar - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Genişleme sayısını alır veya ayarlar ( = 2 Photoshop 6.0 için).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Bu gradyanın kipini alır. 'Gradient Type' = 'Solid/Noise' (0/1) belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Gradyanın adını alır veya ayarlar.

Değer: Gradyanın adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Gradyanın türünü alır veya ayarlar.

Değer: Gradyanın türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Yüzde olarak yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat'ın Azami rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat'ın Minimum rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Gürültü gradyanı için renk üretmekte kullanılan rastgele sayı tohumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Pürüzlülük faktörünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Ölçeği alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Şeffaflığı gösterme bayrağını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Vektör rengini kullanma bayrağını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Yüzde olarak dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

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

