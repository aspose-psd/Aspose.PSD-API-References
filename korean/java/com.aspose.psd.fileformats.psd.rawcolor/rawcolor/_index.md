---
title: "RawColor"
second_title: "Java용 Aspose.PSD API 참조"
description: "Raw Color Class는 채널 수, 색상 모드 및 비트 깊이에 관계없이 색상을 저장하는 데 도움이 됩니다. 일부 내부 클래스는 RawColor를 기본 형식으로 변환하는 데 문제가 있을 수 있으므로 API가 CMYK 색상을 제공하는 경우 제공된 형식을 사용하는 것이 더 신뢰할 수 있습니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color Class는 채널 수, 색상 모드 및 비트 깊이에 관계없이 색상을 저장하는 데 도움이 됩니다. 참고로, 일부 내부 클래스는 RawColor를 해당 기본 형식으로 변환하는 데 문제가 있을 수 있으므로 API가 CMYK 색상을 제공하는 경우 제공된 형식을 사용하는 것이 더 신뢰할 수 있습니다. 또한 Raw Color가 변환될 수 있는 경우도 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 클래스의 새 인스턴스를 초기화합니다. |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | 미리 정의된 색상 모드를 사용하여 픽셀 데이터 형식에서 [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 이 인스턴스와 같은지 확인합니다. |
| [getAsInt()](#getAsInt--) | 가능한 경우 색상을 int 형식으로 가져옵니다. |
| [getAsLong()](#getAsLong--) | 가능한 경우 색상을 long 형식으로 가져옵니다. |
| [getBitDepth()](#getBitDepth--) | Raw Color의 비트 깊이를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 색상이 따라야 할 모드. |
| [getColorModeName()](#getColorModeName--) | 색상 모드의 이름을 가져옵니다. |
| [getComponents()](#getComponents--) | 색상의 구성 요소를 가져옵니다. |
| [hashCode()](#hashCode--) | 현재 객체의 해시 코드를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 연산자 ==를 구현합니다. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 연산자 !=를 구현합니다. |
| [setAsInt(int value)](#setAsInt-int-) | 가능한 경우 int 인수를 사용하여 모든 채널에 데이터를 설정합니다. |
| [setAsLong(long value)](#setAsLong-long-) | 가능한 경우 int 인수를 사용하여 모든 채널에 데이터를 설정합니다. |
| [setColorMode(short value)](#setColorMode-short-) | 색상이 따라야 할 모드. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | 사용자 정의 색상 구성 요소입니다. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


미리 정의된 색상 모드를 사용하여 픽셀 데이터 형식에서 [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 픽셀 데이터 형식. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 이 인스턴스와 같은지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 Object입니다. |

**Returns:**
boolean - 지정된 Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


가능한 경우 색상을 int 형식으로 가져옵니다.

**Returns:**
int - 채널 데이터가 Int에 저장됩니다
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


가능한 경우 색상을 long 형식으로 가져옵니다.

**Returns:**
long - 채널 데이터가 Int에 저장됩니다
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Raw Color의 비트 깊이를 가져옵니다. 예를 들어, 채널당 8비트인 ARGB 색상의 경우 전체 ARGB 색상의 비트 깊이는 32비트이며, 채널당 16비트인 경우 64비트입니다. 비트 깊이는 각 채널 비트 깊이의 합계로 누적됩니다. 채널마다 비트 깊이가 다를 수도 있습니다.

**Returns:**
int - 모든 채널 비트 깊이의 합계
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


색상이 따라야 할 모드.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


색상 모드의 이름을 가져옵니다. 색상 모드 이름은 채널/구성 요소 이름에서 누적됩니다.

**Returns:**
java.lang.String - 색상 모드 이름을 포함하는 문자열
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


색상의 구성 요소를 가져옵니다. 각 구성 요소는 별개의 채널이며, 일반적이지 않은 색상 체계를 사용하는 경우 각 채널을 별도로 작업하는 것이 좋습니다.

값: 색상의 구성 요소

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


현재 객체의 해시 코드를 가져옵니다.

**Returns:**
int - 해시 코드.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


연산자 ==를 구현합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 첫 번째 RawColor입니다. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 두 번째 RawColor. |

**Returns:**
boolean - 연산자의 결과.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


연산자 !=를 구현합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 첫 번째 RawColor입니다. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 두 번째 RawColor. |

**Returns:**
boolean - 연산자의 결과.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


가능한 경우 int 인수를 사용하여 모든 채널에 데이터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 구성 요소 데이터를 포함하는 int 값 |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


가능한 경우 int 인수를 사용하여 모든 채널에 데이터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 구성 요소 데이터를 포함하는 int 값 |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


색상이 따라야 할 모드.

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

