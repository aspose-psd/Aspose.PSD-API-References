---
title: "BaseGradientFillSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "기본 그라디언트 정의 클래스."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Base gradient definition class. 두 종류의 그라디언트(Solid 및 Noise)에 대한 공통 속성을 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 클래스의 새 인스턴스를 초기화합니다. |
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
| [getDither()](#getDither--) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다. |
| [getFillType()](#getFillType--) | 채우기 유형. |
| [getGradientMode()](#getGradientMode--) | 이 그라디언트의 모드를 가져옵니다. |
| [getGradientName()](#getGradientName--) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [getGradientType()](#getGradientType--) | 그라디언트 유형을 가져오거나 설정합니다. |
| [getHorizontalOffset()](#getHorizontalOffset--) | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| [getReverse()](#getReverse--) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getScale()](#getScale--) | 스케일을 가져오거나 설정합니다. |
| [getVerticalOffset()](#getVerticalOffset--) | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 값 변경을 발생시킵니다. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] 여부를 가져오거나 설정합니다. |
| [setAngle(double value)](#setAngle-double-) | 각도 값을 가져오거나 설정합니다. |
| [setDither(boolean value)](#setDither-boolean-) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | 이 그라디언트의 모드를 가져옵니다. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [setGradientType(int value)](#setGradientType-int-) | 그라디언트 유형을 가져오거나 설정합니다. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| [setReverse(boolean value)](#setReverse-boolean-) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setScale(int value)](#setScale-int-) | 스케일을 가져오거나 설정합니다. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


[BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 클래스의 새 인스턴스를 초기화합니다.

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
### getDither() {#getDither--}
```
public final boolean getDither()
```


이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다.

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
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


이 그라디언트의 모드를 가져옵니다. 'Gradient Type'을 'Solid/Noise'(0/1)으로 결정합니다.

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


그라디언트의 이름을 가져오거나 설정합니다.

값: 그라디언트의 이름.

**Returns:**
java.lang.String
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


스케일을 가져오거나 설정합니다.

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

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


이 그라디언트의 모드를 가져옵니다. 'Gradient Type'을 'Solid/Noise'(0/1)으로 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


그라디언트의 이름을 가져오거나 설정합니다.

값: 그라디언트의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


스케일을 가져오거나 설정합니다.

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

