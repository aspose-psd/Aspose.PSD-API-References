---
title: "ColorTranslator"
second_title: "Java용 Aspose.PSD API 참조"
description: "색상을 GDI Color 구조체로 변환하고 그 반대로 변환합니다."
type: docs
weight: 30
url: /ko/java/com.aspose.psd/colortranslator/
---

**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

색상을 GDI+ Color 구조체로 변환하고 그 반대로 변환합니다. 이 클래스는 상속할 수 없습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | HTML 색상에서 색상을 가져옵니다. |
| [fromOle(int oleColor)](#fromOle-int-) | OLE 색상에서 색상을 가져옵니다. |
| [fromWin32(int win32Color)](#fromWin32-int-) | HTML 색상에서 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toHtml(Color c)](#toHtml-com.aspose.psd.Color-) | 색상에서 HTML 색상을 생성합니다. |
| [toOle(Color c)](#toOle-com.aspose.psd.Color-) | OLE 색상을 색상으로 변환합니다. |
| [toString()](#toString--) |  |
| [toWin32(Color c)](#toWin32-com.aspose.psd.Color-) | 색상을 Win32 색상으로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


HTML 색상에서 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML 색상. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


OLE 색상에서 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oleColor | int | OLE 색상. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


HTML 색상에서 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| win32Color | int | Win32 색상. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color.
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




### toHtml(Color c) {#toHtml-com.aspose.psd.Color-}
```
public static String toHtml(Color c)
```


색상에서 HTML 색상을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | [Color](../../com.aspose.psd/color) | 색상 클래스. |

**Returns:**
java.lang.String - HTML 문자열 색상.
### toOle(Color c) {#toOle-com.aspose.psd.Color-}
```
public static int toOle(Color c)
```


OLE 색상을 색상으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | [Color](../../com.aspose.psd/color) | 색상. |

**Returns:**
int - OLE 색상.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toWin32(Color c) {#toWin32-com.aspose.psd.Color-}
```
public static int toWin32(Color c)
```


색상을 Win32 색상으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | [Color](../../com.aspose.psd/color) | 색상. |

**Returns:**
int - Win32 색상.
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

