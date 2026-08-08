---
title: "BlendingOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "BlendingOptions."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---

**Inheritance:**
java.lang.Object
```
public class BlendingOptions
```

BlendingOptions. 레이어 효과를 위한 API를 제공하는 BaseFxResource의 래퍼입니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ResourceChanged_internalized](#ResourceChanged-internalized) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | 컬러 오버레이를 추가합니다. |
| [addDropShadow()](#addDropShadow--) | 드롭 섀도우 효과를 추가합니다. |
| [addGradientOverlay()](#addGradientOverlay--) | 그라디언트 오버레이를 추가합니다. |
| [addInnerShadow()](#addInnerShadow--) | 내부 섀도우 효과를 추가합니다. |
| [addOuterGlow()](#addOuterGlow--) | 외부 글로우 효과를 추가합니다. |
| [addPatternOverlay()](#addPatternOverlay--) | 패턴 오버레이를 추가합니다. |
| [addStroke(int fillType)](#addStroke-int-) | 스트로크 효과를 추가합니다. |
| [calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)](#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-) | 시각 효과를 포함한 레이어의 경계를 계산합니다. |
| [create_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAreEffectsEnabled()](#getAreEffectsEnabled--) | 모든 레이어 효과의 가시성을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | 효과를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAreEffectsEnabled(boolean value)](#setAreEffectsEnabled-boolean-) | 모든 레이어 효과의 가시성을 가져오거나 설정합니다. |
| [setEffects(ILayerEffect[] value)](#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---) | 효과를 가져옵니다. |
| [setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)](#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | 새 패턴 데이터를 생성하고 이를 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 인스턴스에 설정합니다. |
| [toString()](#toString--) |  |
| [updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | 새로운 경우 효과를 업데이트합니다. |
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


컬러 오버레이를 추가합니다.

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - Created [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) object
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


드롭 섀도우 효과를 추가합니다.

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - Created [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) object
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


그라디언트 오버레이를 추가합니다.

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - Created [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) object
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


내부 섀도우 효과를 추가합니다.

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - Created [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) object
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


외부 글로우 효과를 추가합니다.

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - Created [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) object
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


패턴 오버레이를 추가합니다.

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - Created [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) object
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


스트로크 효과를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillType | int | 스트로크를 채우기 위한 채우기 유형입니다. |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - Created [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) object.
### calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle) {#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-}
```
public final Rectangle calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)
```


시각 효과를 포함한 레이어의 경계를 계산합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 레이어의 원래 경계입니다. |
| globalAngle | int | 특정 효과에 사용되는 전역 조명 각도입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The calculated bounds including the visual effects.
### create_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static BlendingOptions create_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAreEffectsEnabled() {#getAreEffectsEnabled--}
```
public final boolean getAreEffectsEnabled()
```


모든 레이어 효과의 가시성을 가져오거나 설정합니다.

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


효과를 가져옵니다.

값: 효과입니다.

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


모든 레이어 효과의 가시성을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setEffects(ILayerEffect[] value) {#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---}
```
public void setEffects(ILayerEffect[] value)
```


효과를 가져옵니다.

값: 효과입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ILayerEffect\[\]](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect) |  |

### setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings) {#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)
```


새 패턴 데이터를 생성하고 이를 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 인스턴스에 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| patternSettings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | 패턴 채우기 설정입니다. |

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


새로운 경우 효과를 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | 효과가 포함된 레이어 스타일입니다. |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | patt 리소스입니다. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

