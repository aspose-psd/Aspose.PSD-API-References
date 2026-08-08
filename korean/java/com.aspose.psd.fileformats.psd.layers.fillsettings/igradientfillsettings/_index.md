---
title: "IGradientFillSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "그라디언트 채우기 설정에 대한 기본 인터페이스."
type: docs
weight: 23
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

그라디언트 채우기 설정에 대한 기본 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | [align with layer] 여부를 가져오거나 설정합니다. |
| [getAngle()](#getAngle--) | 각도 값을 가져오거나 설정합니다. |
| [getDither()](#getDither--) | 이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getGradient()](#getGradient--) | 특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다. |
| [getGradientType()](#getGradientType--) | 그라디언트 유형을 가져오거나 설정합니다. |
| [getHorizontalOffset()](#getHorizontalOffset--) | 수평 오프셋 값을 가져오거나 설정합니다. |
| [getInterpolationMethod()](#getInterpolationMethod--) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [getReverse()](#getReverse--) | 이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getScale()](#getScale--) | **정규화된** gradient scale (in percent)를 가져오거나 설정합니다. |
| [getVerticalOffset()](#getVerticalOffset--) | 수직 오프셋 값을 가져오거나 설정합니다. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] 여부를 가져오거나 설정합니다. |
| [setAngle(double value)](#setAngle-double-) | 각도 값을 가져오거나 설정합니다. |
| [setDither(boolean value)](#setDither-boolean-) | 이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | 특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다. |
| [setGradientType(int value)](#setGradientType-int-) | 그라디언트 유형을 가져오거나 설정합니다. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 수평 오프셋 값을 가져오거나 설정합니다. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [setReverse(boolean value)](#setReverse-boolean-) | 이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setScale(int value)](#setScale-int-) | **정규화된** gradient scale (in percent)를 가져오거나 설정합니다. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 수직 오프셋 값을 가져오거나 설정합니다. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


[align with layer] 여부를 가져오거나 설정합니다.

값:  true  인 경우 [align with layer]; 그렇지 않으면,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


각도 값을 가져오거나 설정합니다.

값: 각도.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다.

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


그라디언트 유형을 가져오거나 설정합니다.

값: 그라디언트 유형.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


수평 오프셋 값을 가져오거나 설정합니다.

값: 수평 오프셋.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


**정규화된** gradient scale (in percent)를 가져오거나 설정합니다.

값: 스케일.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


수직 오프셋 값을 가져오거나 설정합니다.

값: 수직 오프셋.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


[align with layer] 여부를 가져오거나 설정합니다.

값:  true  인 경우 [align with layer]; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


각도 값을 가져오거나 설정합니다.

값: 각도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


그라디언트 유형을 가져오거나 설정합니다.

값: 그라디언트 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


수평 오프셋 값을 가져오거나 설정합니다.

값: 수평 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


이 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


**정규화된** gradient scale (in percent)를 가져오거나 설정합니다.

값: 스케일.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


수직 오프셋 값을 가져오거나 설정합니다.

값: 수직 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

