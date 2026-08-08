---
title: "ILayerEffect"
second_title: "Java용 Aspose.PSD API 참조"
description: "레이어 효과에 대한 인터페이스"
type: docs
weight: 20
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

레이어 효과에 대한 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | 블렌드 모드를 가져오거나 설정합니다. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |
| [getEffectType()](#getEffectType--) | 효과 유형을 가져옵니다. |
| [getOpacity()](#getOpacity--) | 불투명도를 가져오거나 설정합니다(255 = 100%). |
| [isVisible()](#isVisible--) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setBlendMode(long value)](#setBlendMode-long-) | 블렌드 모드를 가져오거나 설정합니다. |
| [setOpacity(byte value)](#setOpacity-byte-) | 불투명도를 가져오거나 설정합니다(255 = 100%). |
| [setVisible(boolean value)](#setVisible-boolean-) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


블렌드 모드를 가져오거나 설정합니다.

값: 블렌드 모드.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 레이어 픽셀 경계. |
| globalAngle | int | 전역 조명을 계산하기 위한 전역 각도입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


효과 유형을 가져옵니다.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


불투명도를 가져오거나 설정합니다(255 = 100%).

값: 불투명도.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 보이면; 그렇지 않으면  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


블렌드 모드를 가져오거나 설정합니다.

값: 블렌드 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


불투명도를 가져오거나 설정합니다(255 = 100%).

값: 불투명도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 보이면; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

