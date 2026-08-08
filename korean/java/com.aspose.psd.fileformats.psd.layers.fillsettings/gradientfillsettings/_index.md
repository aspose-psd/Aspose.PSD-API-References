---
title: "GradientFillSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "그라디언트 채우기 효과 설정."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

그라디언트 채우기 효과 설정.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | 새로운 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | [align with layer] 여부를 가져오거나 설정합니다. |
| [getAngle()](#getAngle--) | 각도 값을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | 그라디언트 위치를 올바르게 계산하기 위해 레이어 컨테이너의 경계를 가져오거나 설정합니다. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | 현재 Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) 값에 해당하는  **denormalized**  그라디언트 스케일(UI Scale)을 계산하고 반환합니다. |
| [getDither()](#getDither--) | 이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getFillType()](#getFillType--) | 채우기 유형. |
| [getGradient()](#getGradient--) | 특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다. |
| [getGradientType()](#getGradientType--) | 그라디언트 유형을 가져오거나 설정합니다. |
| [getHorizontalOffset()](#getHorizontalOffset--) | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| [getInterpolationMethod()](#getInterpolationMethod--) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [getReverse()](#getReverse--) | 이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getScale()](#getScale--) |  **normalized**  그라디언트 스케일(백분율)을 가져오거나 설정합니다. |
| [getVerticalOffset()](#getVerticalOffset--) | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 값 변경을 발생시킵니다. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] 여부를 가져오거나 설정합니다. |
| [setAngle(double value)](#setAngle-double-) | 각도 값을 가져오거나 설정합니다. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | 그라디언트 위치를 올바르게 계산하기 위해 레이어 컨테이너의 경계를 가져오거나 설정합니다. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | 지정된 비정규화된 스케일(UI) 값을 **normalized** 등가물로 변환하고 Scale에 할당합니다 ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | 이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | 특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다. |
| [setGradientType(int value)](#setGradientType-int-) | 그라디언트 유형을 가져오거나 설정합니다. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [setReverse(boolean value)](#setReverse-boolean-) | 이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setScale(int value)](#setScale-int-) |  **normalized**  그라디언트 스케일(백분율)을 가져오거나 설정합니다. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


새로운 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 클래스 인스턴스를 초기화합니다.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


[align with layer] 여부를 가져오거나 설정합니다.

값:  true  인 경우 [align with layer]; 그렇지 않으면,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


각도 값을 가져오거나 설정합니다.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


그라디언트 위치를 올바르게 계산하기 위해 레이어 컨테이너의 경계를 가져오거나 설정합니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


현재 Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) 값에 해당하는  **denormalized**  그라디언트 스케일(UI Scale)을 계산하고 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | 그라디언트의 경계. |

**Returns:**
int - Photoshop에 표시되는 비정규화된(UI) 스케일(백분율).
### getDither() {#getDither--}
```
public final boolean getDither()
```


이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


채우기 유형.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다.

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


그라디언트 유형을 가져오거나 설정합니다.

값: 그라디언트 유형.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


수평 오프셋을 백분율로 가져오거나 설정합니다.

값: 수평 오프셋.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


 **normalized**  그라디언트 스케일(백분율)을 가져오거나 설정합니다.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


수직 오프셋을 백분율로 가져오거나 설정합니다.

값: 수직 오프셋.

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


값 변경을 발생시킵니다.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


[align with layer] 여부를 가져오거나 설정합니다.

값:  true  인 경우 [align with layer]; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


각도 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


그라디언트 위치를 올바르게 계산하기 위해 레이어 컨테이너의 경계를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


지정된 비정규화된 스케일(UI) 값을 **normalized** 등가물로 변환하고 Scale에 할당합니다 ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). 변환은 그라디언트의 현재 Angle([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-))와 제공된 fillArea를 적용하여 정규화 계수를 계산합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | Photoshop에 표시되는 비정규화된 스케일, UI Scale(백분율); |
| fillArea | [Size](../../com.aspose.psd/size) | 그라디언트의 경계. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


그라디언트 유형을 가져오거나 설정합니다.

값: 그라디언트 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


수평 오프셋을 백분율로 가져오거나 설정합니다.

값: 수평 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


이 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


 **normalized**  그라디언트 스케일(백분율)을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


수직 오프셋을 백분율로 가져오거나 설정합니다.

값: 수직 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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

