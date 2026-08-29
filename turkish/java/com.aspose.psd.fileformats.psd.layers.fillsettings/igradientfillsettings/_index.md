---
title: "IGradientFillSettings"
second_title: "Java için Aspose.PSD API Referansı"
description: "Gradyan doldurma ayarları için temel arayüz."
type: docs
weight: 23
url: /tr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Gradyan doldurma ayarları için temel arayüz.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAngle()](#getAngle--) | Açıyı alır veya ayarlar. |
| [getDither()](#getDither--) | Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin dithering yapıp yapmadığını gösteren bir değeri alır veya ayarlar. |
| [getGradient()](#getGradient--) | Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Gradyanın türünü alır veya ayarlar. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Yatay ofseti alır veya ayarlar. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [getReverse()](#getReverse--) | Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getScale()](#getScale--) | **normalized** gradient ölçeğini (yüzde olarak) alır veya ayarlar. |
| [getVerticalOffset()](#getVerticalOffset--) | Dikey ofseti alır veya ayarlar. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) | Açıyı alır veya ayarlar. |
| [setDither(boolean value)](#setDither-boolean-) | Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin dithering yapıp yapmadığını gösteren bir değeri alır veya ayarlar. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Gradyanın türünü alır veya ayarlar. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Yatay ofseti alır veya ayarlar. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [setReverse(boolean value)](#setReverse-boolean-) | Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setScale(int value)](#setScale-int-) | **normalized** gradient ölçeğini (yüzde olarak) alır veya ayarlar. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Dikey ofseti alır veya ayarlar. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Açıyı alır veya ayarlar.

Değer: Açı.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin dithering yapıp yapmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Gradyanın türünü alır veya ayarlar.

Değer: Gradyanın türü.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Gradient için ara değerleme yöntemini alır veya ayarlar.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


**normalized** gradient ölçeğini (yüzde olarak) alır veya ayarlar.

Değer: Ölçek.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Açıyı alır veya ayarlar.

Değer: Açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin dithering yapıp yapmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Gradyanın türünü alır veya ayarlar.

Değer: Gradyanın türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Gradient için ara değerleme yöntemini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Bu [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


**normalized** gradient ölçeğini (yüzde olarak) alır veya ayarlar.

Değer: Ölçek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

