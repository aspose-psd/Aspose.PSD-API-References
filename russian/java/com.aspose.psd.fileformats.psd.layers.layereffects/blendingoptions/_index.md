---
title: "BlendingOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "BlendingOptions."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---

**Inheritance:**
java.lang.Object
```
public class BlendingOptions
```

BlendingOptions. Это оболочка для BaseFxResource, которая предоставляет API для эффектов слоёв
## Поля

| Поле | Описание |
| --- | --- |
| [ResourceChanged_internalized](#ResourceChanged-internalized) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | Добавляет цветовое наложение. |
| [addDropShadow()](#addDropShadow--) | Добавляет эффект отбрасываемой тени. |
| [addGradientOverlay()](#addGradientOverlay--) | Добавляет градиентное наложение. |
| [addInnerShadow()](#addInnerShadow--) | Добавляет эффект внутренней тени. |
| [addOuterGlow()](#addOuterGlow--) | Добавляет эффект внешнего свечения. |
| [addPatternOverlay()](#addPatternOverlay--) | Добавляет шаблонное наложение. |
| [addStroke(int fillType)](#addStroke-int-) | Добавляет эффект обводки. |
| [calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)](#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-) | Вычисляет границы слоя, включая визуальные эффекты. |
| [create_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAreEffectsEnabled()](#getAreEffectsEnabled--) | Получает или задаёт видимость всех эффектов слоя. |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | Получает эффекты. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAreEffectsEnabled(boolean value)](#setAreEffectsEnabled-boolean-) | Получает или задаёт видимость всех эффектов слоя. |
| [setEffects(ILayerEffect[] value)](#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---) | Получает эффекты. |
| [setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)](#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Создаёт новые данные шаблона и устанавливает их в экземпляр [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Обновляет эффекты, если они новее. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceChanged_internalized {#ResourceChanged-internalized}
```
public final Event<System.EventHandler<ResourceChangedEventArgs>> ResourceChanged_internalized
```


### addColorOverlay() {#addColorOverlay--}
```
public final ColorOverlayEffect addColorOverlay()
```


Добавляет цветовое наложение.

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - Created [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) object
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


Добавляет эффект отбрасываемой тени.

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - Created [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) object
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


Добавляет градиентное наложение.

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - Created [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) object
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


Добавляет эффект внутренней тени.

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - Created [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) object
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


Добавляет эффект внешнего свечения.

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - Created [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) object
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


Добавляет шаблонное наложение.

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - Created [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) object
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


Добавляет эффект обводки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillType | int | Тип заливки для заполнения контура. |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - Created [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) object.
### calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle) {#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-}
```
public final Rectangle calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)
```


Вычисляет границы слоя, включая визуальные эффекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Исходные границы слоя. |
| globalAngle | int | Глобальный угол света, используемый для некоторых эффектов. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The calculated bounds including the visual effects.
### create_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static BlendingOptions create_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAreEffectsEnabled() {#getAreEffectsEnabled--}
```
public final boolean getAreEffectsEnabled()
```


Получает или задаёт видимость всех эффектов слоя.

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


Получает эффекты.

Значение: Эффекты.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect[]
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




### setAreEffectsEnabled(boolean value) {#setAreEffectsEnabled-boolean-}
```
public final void setAreEffectsEnabled(boolean value)
```


Получает или задаёт видимость всех эффектов слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setEffects(ILayerEffect[] value) {#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---}
```
public void setEffects(ILayerEffect[] value)
```


Получает эффекты.

Значение: Эффекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILayerEffect\[\]](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect) |  |

### setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings) {#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)
```


Создаёт новые данные шаблона и устанавливает их в экземпляр [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| patternSettings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Настройки заполнения шаблоном. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```


Обновляет эффекты, если они новее.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | Стиль слоя с эффектами. |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | Ресурс patt. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

