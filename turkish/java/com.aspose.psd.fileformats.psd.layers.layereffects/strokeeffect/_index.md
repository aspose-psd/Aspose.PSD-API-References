---
title: "StrokeEffect"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD katmanı için Adobe Photoshop çizgi efekti."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

PSD katmanı için Adobe® Photoshop® stroke efekti.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Karışım modunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Varlığı alır |
| [getEffectType()](#getEffectType--) | Bir efekt türünü alır |
| [getFillSettings()](#getFillSettings--) | Dolgu ayarlarını alır veya ayarlar. |
| [getOpacity()](#getOpacity--) | Opaklığı alır veya ayarlar. |
| [getOverprint()](#getOverprint--) | Bu [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) öğesinin, çizgiyi mevcut katman içeriğine karıştırıp karıştırmayacağını gösteren bir değeri alır veya ayarlar. |
| [getPosition()](#getPosition--) | Çizgi efektinin konumunu alır veya ayarlar; böylece çizginizin PSD katmanı içeriğine hizalanmasını kontrol eder. |
| [getSize()](#getSize--) | Çizgi efektinin genişliğini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Belirli indeksteki katman etkisini kaldırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Karışım modunu alır veya ayarlar. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Dolgu ayarlarını alır veya ayarlar. |
| [setOpacity(byte value)](#setOpacity-byte-) | Opaklığı alır veya ayarlar. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Bu [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) öğesinin, çizgiyi mevcut katman içeriğine karıştırıp karıştırmayacağını gösteren bir değeri alır veya ayarlar. |
| [setPosition(short value)](#setPosition-short-) | Çizgi efektinin konumunu alır veya ayarlar; böylece çizginizin PSD katmanı içeriğine hizalanmasını kontrol eder. |
| [setSize(int value)](#setSize-int-) | Çizgi efektinin genişliğini alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Belirli indeksteki katman etkisini kaldırır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Karışım modunu alır veya ayarlar.

Değer: Karışım modu.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Katman piksel sınırları. |
| globalAngle | int | Genel ışık açısını hesaplamak için genel açı. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Varlığı alır

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Bir efekt türünü alır

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Dolgu ayarlarını alır veya ayarlar.

Değer: Dolgu ayarları.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Opaklığı alır veya ayarlar.

Değer: Opaklık.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Bu [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) öğesinin, çizgiyi mevcut katman içeriğine karıştırıp karıştırmayacağını gösteren bir değeri alır veya ayarlar.

Değer:  true  çizgi mevcut katman içeriğine karıştırılmalıysa; aksi takdirde,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Çizgi efektinin konumunu alır veya ayarlar; böylece çizginizin PSD katmanı içeriğine hizalanmasını kontrol eder. Değer, PSD katmanı içeriği içinde çizgi çizmek için [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside), PSD katmanı içeriği etrafında çizgi çizmek için [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) veya hem içinde hem dışında çizgi çizmek için [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) olabilir.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Çizgi efektinin genişliğini alır veya ayarlar.

Değer: Çizgi efektinin genişliği.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Belirli indeksteki katman etkisini kaldırır.

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Karışım modunu alır veya ayarlar.

Değer: Karışım modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Dolgu ayarlarını alır veya ayarlar.

Değer: Dolgu ayarları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Opaklığı alır veya ayarlar.

Değer: Opaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Bu [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) öğesinin, çizgiyi mevcut katman içeriğine karıştırıp karıştırmayacağını gösteren bir değeri alır veya ayarlar.

Değer:  true  çizgi mevcut katman içeriğine karıştırılmalıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Çizgi efektinin konumunu alır veya ayarlar; böylece çizginizin PSD katmanı içeriğine hizalanmasını kontrol eder. Değer, PSD katmanı içeriği içinde çizgi çizmek için [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside), PSD katmanı içeriği etrafında çizgi çizmek için [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) veya hem içinde hem dışında çizgi çizmek için [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Çizgi efektinin genişliğini alır veya ayarlar.

Değer: Çizgi efektinin genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Belirli indeksteki katman etkisini kaldırır.

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

