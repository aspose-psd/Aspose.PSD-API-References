---
title: "Renk bindirme etkisini ekler."
second_title: "Java için Aspose.PSD API Referansı"
description: "Katman durumu efektleri."
type: docs
weight: 13
url: /tr/java/com.aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Inheritance:**
java.lang.Object
```
public class LayerStateEffects
```

Katman durumu efektleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | Gölge düşürme etkisini ekler. |
| [addDropShadow()](#addDropShadow--) | Gradyan bindirme etkisini ekler. |
| [addGradientOverlay()](#addGradientOverlay--) | İç gölge etkisini ekler. |
| [addInnerShadow()](#addInnerShadow--) | Dış parıltı etkisini ekler. |
| [addOuterGlow()](#addOuterGlow--) | Desen bindirme etkisini ekler. |
| [addPatternOverlay()](#addPatternOverlay--) | Çizgi etkisini ekler. |
| [addStroke(int fillType)](#addStroke-int-) | Tüm katman stil etkilerini temizler. |
| [clearLayerStyle()](#clearLayerStyle--) | Katman etkilerini alır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | Katman stil etkileri modelini alır veya ayarlar. |
| [getLayerStyleFX()](#getLayerStyleFX--) | Ölçek değerini alır veya ayarlar. |
| [getScale()](#getScale--) | Bu örneğin görünür olup olmadığını gösteren değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Belirli indeksteki katman etkisini kaldırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeEffectAt(int index)](#removeEffectAt-int-) | Katman stilini ayarlar ve etkiler listesini günceller. |
| [setLayerStyleFX_internalized(LayerStyleFX value)](#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | Ölçek değerini alır veya ayarlar. |
| [setLayerStyle_internalized(LayerStyleFX layerStyle)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | stroke doldurma tipi. |
| [setScale(double value)](#setScale-double-) | Bu örneğin görünür olup olmadığını gösteren değeri alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Belirli indeksteki katman etkisini kaldırır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addColorOverlay() {#addColorOverlay--}
```
public final ColorOverlayEffect addColorOverlay()
```


Gölge düşürme etkisini ekler.

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - The new instance of the [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) class.
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


Gradyan bindirme etkisini ekler.

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - The new instance of the [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) class.
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


İç gölge etkisini ekler.

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - The new instance of the [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) class.
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


Dış parıltı etkisini ekler.

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - The new instance of the [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) class.
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


Desen bindirme etkisini ekler.

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - The new instance of the [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) class.
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


Çizgi etkisini ekler.

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - The new instance of the [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) class.
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


Tüm katman stil etkilerini temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillType | int | com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect[] |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - The new instance of the [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) class.
### clearLayerStyle() {#clearLayerStyle--}
```
public final void clearLayerStyle()
```


Katman etkilerini alır.

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
### getEffects() {#getEffects--}
```
public final ILayerEffect[] getEffects()
```


Katman stil etkileri modelini alır veya ayarlar.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
### getLayerStyleFX() {#getLayerStyleFX--}
```
public final LayerStyleFX getLayerStyleFX()
```


Ölçek değerini alır veya ayarlar.

**Returns:**
Katman etkisinin indeksi.
### getScale() {#getScale--}
```
public final double getScale()
```


Bu örneğin görünür olup olmadığını gösteren değeri alır veya ayarlar.

**Returns:**
double
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




### removeEffectAt(int index) {#removeEffectAt-int-}
```
public final void removeEffectAt(int index)
```


Katman stilini ayarlar ve etkiler listesini günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | layerStyle |

### setLayerStyleFX_internalized(LayerStyleFX value) {#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyleFX_internalized(LayerStyleFX value)
```


Ölçek değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Katman etkisinin indeksi. |  |

### setLayerStyle_internalized(LayerStyleFX layerStyle) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX layerStyle)
```


stroke doldurma tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerStyle | Katman etkisinin indeksi. | Katman stili. |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Bu örneğin görünür olup olmadığını gösteren değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

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

