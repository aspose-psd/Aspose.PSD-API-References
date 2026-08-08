---
title: "NoiseGradientFillSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "노이즈 그라디언트 정의 클래스."
type: docs
weight: 18
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

노이즈 그라디언트 정의 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | 새 인스턴스를 초기화합니다 [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) 클래스. |
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
| [getColorModel()](#getColorModel--) | 색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다. |
| [getExpansionCount()](#getExpansionCount--) | 확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2). |
| [getFillType()](#getFillType--) | 채우기 유형. |
| [getGradientMode()](#getGradientMode--) | 이 그라디언트의 모드를 가져옵니다. |
| [getGradientName()](#getGradientName--) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [getGradientType()](#getGradientType--) | 그라디언트 유형을 가져오거나 설정합니다. |
| [getHorizontalOffset()](#getHorizontalOffset--) | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat의 최대 색상을 가져오거나 설정합니다. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat의 최소 색상을 가져오거나 설정합니다. |
| [getReverse()](#getReverse--) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getRndNumberSeed()](#getRndNumberSeed--) | 노이즈 그라디언트에 대한 색상을 생성하는 데 사용되는 난수 시드를 가져오거나 설정합니다 |
| [getRoughness()](#getRoughness--) | 거칠기 계수를 가져오거나 설정합니다. |
| [getScale()](#getScale--) | 스케일을 가져오거나 설정합니다. |
| [getShowTransparency()](#getShowTransparency--) | 투명도 표시 플래그를 가져오거나 설정합니다. |
| [getUseVectorColor()](#getUseVectorColor--) | 벡터 색상 사용 플래그를 가져오거나 설정합니다. |
| [getVerticalOffset()](#getVerticalOffset--) | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 값 변경을 발생시킵니다. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] 여부를 가져오거나 설정합니다. |
| [setAngle(double value)](#setAngle-double-) | 각도 값을 가져오거나 설정합니다. |
| [setColorModel(short value)](#setColorModel-short-) | 색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | 이 그라디언트의 모드를 가져옵니다. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [setGradientType(int value)](#setGradientType-int-) | 그라디언트 유형을 가져오거나 설정합니다. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat의 최대 색상을 가져오거나 설정합니다. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat의 최소 색상을 가져오거나 설정합니다. |
| [setReverse(boolean value)](#setReverse-boolean-) | 이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 노이즈 그라디언트에 대한 색상을 생성하는 데 사용되는 난수 시드를 가져오거나 설정합니다 |
| [setRoughness(int value)](#setRoughness-int-) | 거칠기 계수를 가져오거나 설정합니다. |
| [setScale(int value)](#setScale-int-) | 스케일을 가져오거나 설정합니다. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 투명도 표시 플래그를 가져오거나 설정합니다. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | 벡터 색상 사용 플래그를 가져오거나 설정합니다. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


새 인스턴스를 초기화합니다 [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) 클래스.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 디더링되는지 여부를 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2).

**Returns:**
short
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat의 최대 색상을 가져오거나 설정합니다.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat의 최소 색상을 가져오거나 설정합니다.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


이 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


노이즈 그라디언트에 대한 색상을 생성하는 데 사용되는 난수 시드를 가져오거나 설정합니다

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


거칠기 계수를 가져오거나 설정합니다.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


스케일을 가져오거나 설정합니다.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


투명도 표시 플래그를 가져오거나 설정합니다.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


벡터 색상 사용 플래그를 가져오거나 설정합니다.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat의 최대 색상을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat의 최소 색상을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


노이즈 그라디언트에 대한 색상을 생성하는 데 사용되는 난수 시드를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


거칠기 계수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


스케일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


투명도 표시 플래그를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


벡터 색상 사용 플래그를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

