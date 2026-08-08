---
title: "IShadowEffect"
second_title: "Java용 Aspose.PSD API 참조"
description: "그림자 레이어 효과에 대한 인터페이스"
type: docs
weight: 21
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect)
```
public interface IShadowEffect extends ILayerEffect
```

그림자 레이어 효과에 대한 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAngle()](#getAngle--) | 각도를 도 단위로 가져오거나 설정합니다. |
| [getColor()](#getColor--) | 색상을 가져오거나 설정합니다. |
| [getDistance()](#getDistance--) | 거리를 픽셀 단위로 가져오거나 설정합니다. |
| [getNoise()](#getNoise--) | 노이즈를 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 블러 값을 픽셀 단위로 가져오거나 설정합니다. |
| [getSpread()](#getSpread--) | 강도를 백분율로 가져오거나 설정합니다. |
| [getUseGlobalLight()](#getUseGlobalLight--) | 이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects]. |
| [setAngle(int value)](#setAngle-int-) | 각도를 도 단위로 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 색상을 가져오거나 설정합니다. |
| [setDistance(int value)](#setDistance-int-) | 거리를 픽셀 단위로 가져오거나 설정합니다. |
| [setNoise(int value)](#setNoise-int-) | 노이즈를 가져오거나 설정합니다. |
| [setSize(int value)](#setSize-int-) | 블러 값을 픽셀 단위로 가져오거나 설정합니다. |
| [setSpread(int value)](#setSpread-int-) | 강도를 백분율로 가져오거나 설정합니다. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | 이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects]. |
### getAngle() {#getAngle--}
```
public abstract int getAngle()
```


각도를 도 단위로 가져오거나 설정합니다.

값: 각도.

**Returns:**
int
### getColor() {#getColor--}
```
public abstract Color getColor()
```


색상을 가져오거나 설정합니다.

값: 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public abstract int getDistance()
```


거리를 픽셀 단위로 가져오거나 설정합니다.

값: 거리.

**Returns:**
int
### getNoise() {#getNoise--}
```
public abstract int getNoise()
```


노이즈를 가져오거나 설정합니다.

**Returns:**
int
### getSize() {#getSize--}
```
public abstract int getSize()
```


블러 값을 픽셀 단위로 가져오거나 설정합니다.

값: 크기.

**Returns:**
int
### getSpread() {#getSpread--}
```
public abstract int getSpread()
```


강도를 백분율로 가져오거나 설정합니다.

값: 퍼짐.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public abstract boolean getUseGlobalLight()
```


이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects].

값: [use global light]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### setAngle(int value) {#setAngle-int-}
```
public abstract void setAngle(int value)
```


각도를 도 단위로 가져오거나 설정합니다.

값: 각도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public abstract void setColor(Color value)
```


색상을 가져오거나 설정합니다.

값: 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public abstract void setDistance(int value)
```


거리를 픽셀 단위로 가져오거나 설정합니다.

값: 거리.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setNoise(int value) {#setNoise-int-}
```
public abstract void setNoise(int value)
```


노이즈를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```


블러 값을 픽셀 단위로 가져오거나 설정합니다.

값: 크기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSpread(int value) {#setSpread-int-}
```
public abstract void setSpread(int value)
```


강도를 백분율로 가져오거나 설정합니다.

값: 퍼짐.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public abstract void setUseGlobalLight(boolean value)
```


이 각도를 모든 레이어 효과에 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 [use this angle in all of the layer effects].

값: [use global light]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

