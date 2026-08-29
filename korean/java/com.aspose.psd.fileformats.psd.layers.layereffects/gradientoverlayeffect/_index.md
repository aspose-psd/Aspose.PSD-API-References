---
title: "GradientOverlayEffect"
second_title: "Java용 Aspose.PSD API 참조"
description: "그라디언트 레이어 효과"
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class GradientOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

그라디언트 레이어 효과
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | 블렌드 모드를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | 엔터티를 가져옵니다. |
| [getEffectType()](#getEffectType--) | 효과 유형을 가져옵니다. |
| [getOpacity()](#getOpacity--) | 불투명도를 가져오거나 설정합니다. |
| [getSettings()](#getSettings--) | 설정을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | 블렌드 모드를 가져오거나 설정합니다. |
| [setOpacity(byte value)](#setOpacity-byte-) | 불투명도를 가져오거나 설정합니다. |
| [setSettings(GradientFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings-) | 설정을 가져오거나 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static GradientOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


블렌드 모드를 가져오거나 설정합니다.

값: 블렌드 모드.

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


입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 레이어 픽셀 경계. |
| globalAngle | int | 전역 조명을 계산하기 위한 전역 각도입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


엔터티를 가져옵니다.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


효과 유형을 가져옵니다.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


불투명도를 가져오거나 설정합니다.

값: 불투명도.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final GradientFillSettings getSettings()
```


설정을 가져오거나 설정합니다.

값: 설정입니다.

**Returns:**
[GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)
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


이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 보이면; 그렇지 않으면  false .

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


블렌드 모드를 가져오거나 설정합니다.

값: 블렌드 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


불투명도를 가져오거나 설정합니다.

값: 불투명도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setSettings(GradientFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings-}
```
public final void setSettings(GradientFillSettings value)
```


설정을 가져오거나 설정합니다.

값: 설정입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 보이면; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

