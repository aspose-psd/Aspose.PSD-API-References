---
title: "ILayerEffect"
second_title: "Java için Aspose.PSD API Referansı"
description: "Katman Efektleri için arayüz"
type: docs
weight: 20
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Katman Efektleri için arayüz
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Karışım modunu alır veya ayarlar. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır. |
| [getEffectType()](#getEffectType--) | Bir efekt türünü alır |
| [getOpacity()](#getOpacity--) | Opaklığı alır veya ayarlar, burada 255 = %100 |
| [isVisible()](#isVisible--) | Belirli indeksteki katman etkisini kaldırır. |
| [setBlendMode(long value)](#setBlendMode-long-) | Karışım modunu alır veya ayarlar. |
| [setOpacity(byte value)](#setOpacity-byte-) | Opaklığı alır veya ayarlar, burada 255 = %100 |
| [setVisible(boolean value)](#setVisible-boolean-) | Belirli indeksteki katman etkisini kaldırır. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Karışım modunu alır veya ayarlar.

Değer: Karışım modu.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Katman piksel sınırları. |
| globalAngle | int | Genel ışık açısını hesaplamak için genel açı. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Bir efekt türünü alır

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Opaklığı alır veya ayarlar, burada 255 = %100

Değer: Opaklık.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Belirli indeksteki katman etkisini kaldırır.

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Karışım modunu alır veya ayarlar.

Değer: Karışım modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Opaklığı alır veya ayarlar, burada 255 = %100

Değer: Opaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Belirli indeksteki katman etkisini kaldırır.

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

