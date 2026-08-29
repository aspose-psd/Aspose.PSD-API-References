---
title: "NoiseGradient"
second_title: "Java용 Aspose.PSD API 참조"
description: "노이즈 그라디언트 정의 클래스."
type: docs
weight: 19
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class NoiseGradient extends BaseGradient
```

노이즈 그라디언트 정의 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NoiseGradient()](#NoiseGradient--) | 새 인스턴스를 초기화합니다 [NoiseGradient](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | 색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6). |
| [getExpansionCount()](#getExpansionCount--) | 확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2). |
| [getGradientMode()](#getGradientMode--) | 이 그라디언트의 모드를 가져옵니다. |
| [getGradientName()](#getGradientName--) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat의 최대 색상을 가져오거나 설정합니다. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat의 최소 색상을 가져오거나 설정합니다. |
| [getRndNumberSeed()](#getRndNumberSeed--) | 노이즈 그라디언트에 대한 색상을 생성하는 데 사용되는 난수 시드를 가져오거나 설정합니다 |
| [getRoughness()](#getRoughness--) | 거칠기 계수를 가져오거나 설정합니다. |
| [getShowTransparency()](#getShowTransparency--) | 투명도 표시 플래그를 가져오거나 설정합니다. |
| [getUseVectorColor()](#getUseVectorColor--) | 벡터 색상 사용 플래그를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorModel(short value)](#setColorModel-short-) | 색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6). |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat의 최대 색상을 가져오거나 설정합니다. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat의 최소 색상을 가져오거나 설정합니다. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 노이즈 그라디언트에 대한 색상을 생성하는 데 사용되는 난수 시드를 가져오거나 설정합니다 |
| [setRoughness(int value)](#setRoughness-int-) | 거칠기 계수를 가져오거나 설정합니다. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 투명도 표시 플래그를 가져오거나 설정합니다. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | 벡터 색상 사용 플래그를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradient() {#NoiseGradient--}
```
public NoiseGradient()
```


새 인스턴스를 초기화합니다 [NoiseGradient](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient) 클래스.

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
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2).

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
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




### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


색상 모델을 가져오거나 설정합니다 - RGB/HSB/LAB (3/4/6).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


확장 개수를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

