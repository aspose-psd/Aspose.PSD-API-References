---
title: "RawColorHelper"
second_title: "Java용 Aspose.PSD API 참조"
description: "Raw Color Helper Class는 미리 정의된 채널 메타데이터를 사용하여 RawColor를 더 빠르게 생성하도록 도와줍니다."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class는 미리 정의된 채널 메타데이터를 사용하여 RawColor를 더 빠르게 생성하도록 도와줍니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | 채널당 16비트 ARGB 색을 생성합니다. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | 채널당 8비트 ARGB 색을 생성합니다. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Drawing.Color에서 채널당 8비트 ARGB 색을 생성합니다. |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | 채널당 16비트 CMYK 색을 생성합니다. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | 채널당 8비트 CMYK 색상을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


채널당 16비트 ARGB 색을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | int | 알파 구성 요소 값 (0-65535). |
| r | int | 빨간색 구성 요소 값 (0-65535). |
| g | int | 녹색 구성 요소 값 (0-65535). |
|  | b | int | 파란색 구성 요소 값 (0-65535). |

--------------------

색상 구성 요소는 64비트 정수에 다음 순서로 패킹됩니다: 알파 (비트 48-63), 빨간색 (비트 32-47), 녹색 (비트 16-31), 그리고 파란색 (비트 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


채널당 8비트 ARGB 색을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | byte | 알파 구성 요소 값 (0-255). |
| r | byte | 빨간색 구성 요소 값 (0-255). |
| g | byte | 녹색 구성 요소 값 (0-255). |
|  | b | byte | 파란색 구성 요소 값 (0-255). |

--------------------

색상 구성 요소는 32비트 정수에 다음 순서로 패킹됩니다: 알파 (비트 24-31), 빨간색 (비트 16-23), 녹색 (비트 8-15), 그리고 파란색 (비트 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Drawing.Color에서 채널당 8비트 ARGB 색을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | System.Drawing 색상 |

--------------------

색상 구성 요소는 32비트 정수에 다음 순서로 패킹됩니다: 알파 (비트 24-31), 빨간색 (비트 16-23), 녹색 (비트 8-15), 그리고 파란색 (비트 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


채널당 16비트 CMYK 색을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | int | 시안 구성 요소 값 (0-65535). |
| m | int | 마젠타 구성 요소 값 (0-65535). |
| y | int | 노란색 구성 요소 값 (0-65535). |
|  | k | int | 키(검정) 구성 요소 값 (0-65535). |

--------------------

색상 구성 요소는 64비트 정수에 다음 순서로 패킹됩니다: 시안 (비트 48-63), 마젠타 (비트 32-47), 노란색 (비트 16-31), 그리고 키/검정 (비트 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


채널당 8비트 CMYK 색상을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | byte | 시안 구성 요소 값 (0-255). |
| m | byte | 마젠타 구성 요소 값 (0-255). |
| y | byte | 노란색 구성 요소 값 (0-255). |
|  | k | byte | 키(검정) 구성 요소 값 (0-255). |

--------------------

색 구성 요소는 32비트 정수에 다음 순서로 패킹됩니다: cyan (bits 24-31), magenta (bits 16-23), yellow (bits 8-15), 및 key/black (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

