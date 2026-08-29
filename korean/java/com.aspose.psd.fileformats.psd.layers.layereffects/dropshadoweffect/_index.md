---
title: "DropShadowEffect"
second_title: "Java용 Aspose.PSD API 참조"
description: "드롭 섀도우 레이어 효과"
type: docs
weight: 12
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

드롭 섀도우 레이어 효과
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | 각도를 도 단위로 가져오거나 설정합니다. |
| [getBlendMode()](#getBlendMode--) | 블렌드 모드를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 색상을 가져오거나 설정합니다. |
| [getDistance()](#getDistance--) | 거리를 픽셀 단위로 가져오거나 설정합니다. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | 엔터티를 가져옵니다. |
| [getEffectType()](#getEffectType--) | 효과 유형을 가져옵니다. |
| [getKnocksOut()](#getKnocksOut--) | 값이 [knocks out]인지 여부를 가져오거나 설정합니다. |
| [getNoise()](#getNoise--) | 노이즈를 가져오거나 설정합니다. |
| [getOpacity()](#getOpacity--) | 불투명도를 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 블러 값을 픽셀 단위로 가져오거나 설정합니다. |
| [getSpread()](#getSpread--) | 강도를 백분율로 가져오거나 설정합니다. |
| [getUseGlobalLight()](#getUseGlobalLight--) | 이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | 각도를 도 단위로 가져오거나 설정합니다. |
| [setBlendMode(long value)](#setBlendMode-long-) | 블렌드 모드를 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 색상을 가져오거나 설정합니다. |
| [setDistance(int value)](#setDistance-int-) | 거리를 픽셀 단위로 가져오거나 설정합니다. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | 값이 [knocks out]인지 여부를 가져오거나 설정합니다. |
| [setNoise(int value)](#setNoise-int-) | 노이즈를 가져오거나 설정합니다. |
| [setOpacity(byte value)](#setOpacity-byte-) | 불투명도를 가져오거나 설정합니다. |
| [setSize(int value)](#setSize-int-) | 블러 값을 픽셀 단위로 가져오거나 설정합니다. |
| [setSpread(int value)](#setSpread-int-) | 강도를 백분율로 가져오거나 설정합니다. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | 이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects]. |
| [setVisible(boolean value)](#setVisible-boolean-) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


각도를 도 단위로 가져오거나 설정합니다.

값: 각도.

**Returns:**
int
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
### getColor() {#getColor--}
```
public final Color getColor()
```


색상을 가져오거나 설정합니다.

값: 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


거리를 픽셀 단위로 가져오거나 설정합니다.

값: 거리.

**Returns:**
int
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
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


값이 [knocks out]인지 여부를 가져오거나 설정합니다.

값:  true  if [knocks out]; otherwise,  false .

**Returns:**
boolean
### getNoise() {#getNoise--}
```
public final int getNoise()
```


노이즈를 가져오거나 설정합니다.

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
### getSize() {#getSize--}
```
public final int getSize()
```


블러 값을 픽셀 단위로 가져오거나 설정합니다.

값: 크기.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


강도를 백분율로 가져오거나 설정합니다.

값: 퍼짐.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects].

값: [use global light]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


각도를 도 단위로 가져오거나 설정합니다.

값: 각도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


색상을 가져오거나 설정합니다.

값: 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


거리를 픽셀 단위로 가져오거나 설정합니다.

값: 거리.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


값이 [knocks out]인지 여부를 가져오거나 설정합니다.

값:  true  if [knocks out]; otherwise,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


노이즈를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


블러 값을 픽셀 단위로 가져오거나 설정합니다.

값: 크기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


강도를 백분율로 가져오거나 설정합니다.

값: 퍼짐.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects].

값: [use global light]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

