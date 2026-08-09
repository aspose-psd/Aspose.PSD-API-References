---
title: "SolidGradient"
second_title: "Java için Aspose.PSD API Referansı"
description: "Degrade doldurma efekt ayarları."
type: docs
weight: 13
url: /tr/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Degrade doldurma efekt ayarları.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Yeni bir [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Renk noktasını ekler. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Renk noktasını ekler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | LFX2 kaynak düğümlerini oluşturur. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Renk noktalarını alır veya ayarlar. |
| [getGradientMode()](#getGradientMode--) | Bu gradyan için modu alır. |
| [getGradientName()](#getGradientName--) | Gradyanın adını alır veya ayarlar. |
| [getInterpolation()](#getInterpolation--) | Interpolation'ı alır veya ayarlar. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Şeffaflık noktalarını alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Renk noktasını kaldırır. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Şeffaflık noktasını kaldırır. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Renk noktalarını alır veya ayarlar. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gradyanın adını alır veya ayarlar. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolation'ı alır veya ayarlar. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Şeffaflık noktalarını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Yeni bir [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) sınıfı örneği başlatır.

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Renk noktasını ekler.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Renk noktasını ekler.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


LFX2 kaynak düğümlerini oluşturur.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Oluşturulan [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) Listesi
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Renk noktalarını alır veya ayarlar.

Değer: Renk noktaları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
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
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolasyonu alır veya ayarlar. 'Gradient Type' = 'Solid' olduğunda Pürüzsüzlüğü belirler. Değer aralığı: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Şeffaflık noktalarını alır veya ayarlar.

Değer: Şeffaflık noktaları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


Renk noktasını kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Nokta. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Şeffaflık noktasını kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Nokta. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Renk noktalarını alır veya ayarlar.

Değer: Renk noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolasyonu alır veya ayarlar. 'Gradient Type' = 'Solid' olduğunda Pürüzsüzlüğü belirler. Değer aralığı: 0-4096.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Şeffaflık noktalarını alır veya ayarlar.

Değer: Şeffaflık noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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

