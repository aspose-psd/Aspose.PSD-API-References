---
title: "ColorRangeHsl"
second_title: "Java용 Aspose.PSD API 참조"
description: "HSV 매개변수를 변경할 수 있는 6개의 색상 범위가 있습니다."
type: docs
weight: 22
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | 새 인스턴스를 초기화합니다 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 클래스. |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | 새 인스턴스를 초기화합니다 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | 색조를 가져오거나 설정합니다. |
| [getLeftBorder()](#getLeftBorder--) | 왼쪽 경계를 가져오거나 설정합니다. |
| [getLightness()](#getLightness--) | 명도를 가져오거나 설정합니다. |
| [getMostLeftBorder()](#getMostLeftBorder--) | 가장 왼쪽 경계를 가져오거나 설정합니다. |
| [getMostRightBorder()](#getMostRightBorder--) | 가장 오른쪽 경계를 가져오거나 설정합니다. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | 범위 계수를 가져옵니다. |
| [getRightBorder()](#getRightBorder--) | 오른쪽 경계를 가져오거나 설정합니다. |
| [getSaturation()](#getSaturation--) | 채도를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | 색조가 큰 범위에 있는지 여부를 결정합니다. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | 색조가 작은 범위에 있는지 여부를 결정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | 데이터를 지정된 스트림 컨테이너에 저장합니다. |
| [setHue(short value)](#setHue-short-) | 색조를 가져오거나 설정합니다. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | 왼쪽 경계를 가져오거나 설정합니다. |
| [setLightness(short value)](#setLightness-short-) | 명도를 가져오거나 설정합니다. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | 가장 왼쪽 경계를 가져오거나 설정합니다. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | 가장 오른쪽 경계를 가져오거나 설정합니다. |
| [setRightBorder(short value)](#setRightBorder-short-) | 오른쪽 경계를 가져오거나 설정합니다. |
| [setSaturation(short value)](#setSaturation-short-) | 채도를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


새 인스턴스를 초기화합니다 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 클래스.

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


새 인스턴스를 초기화합니다 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 색상 범위 데이터입니다. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getHue() {#getHue--}
```
public final short getHue()
```


색조를 가져오거나 설정합니다.

값: 색조.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


왼쪽 경계를 가져오거나 설정합니다.

값: 왼쪽 경계.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


명도를 가져오거나 설정합니다.

값: 밝기.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


가장 왼쪽 경계를 가져오거나 설정합니다.

값: 가장 왼쪽 경계.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


가장 오른쪽 경계를 가져오거나 설정합니다.

값: 가장 오른쪽 경계.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


범위 계수를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hue | double | 색조 값입니다. |

**Returns:**
double - 채도 범위 계수.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


오른쪽 경계를 가져오거나 설정합니다.

값: 오른쪽 경계.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


채도를 가져오거나 설정합니다.

값: 채도.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


색조가 큰 범위에 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hue | double | 색조 값입니다. |

**Returns:**
boolean -  true  색조가 큰 범위에 있으면; 그렇지 않으면  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


색조가 작은 범위에 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hue | double | 색조 값입니다. |

**Returns:**
boolean -  true  색조가 작은 범위에 있으면; 그렇지 않으면  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


데이터를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


색조를 가져오거나 설정합니다.

값: 색조.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


왼쪽 경계를 가져오거나 설정합니다.

값: 왼쪽 경계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


명도를 가져오거나 설정합니다.

값: 밝기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


가장 왼쪽 경계를 가져오거나 설정합니다.

값: 가장 왼쪽 경계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


가장 오른쪽 경계를 가져오거나 설정합니다.

값: 가장 오른쪽 경계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


오른쪽 경계를 가져오거나 설정합니다.

값: 오른쪽 경계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


채도를 가져오거나 설정합니다.

값: 채도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

