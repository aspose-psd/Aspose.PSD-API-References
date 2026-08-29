---
title: "CmykColor"
second_title: "Java용 Aspose.PSD API 참조"
description: "픽셀의 CMYK 색상."
type: docs
weight: 17
url: /ko/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

픽셀의 CMYK 색상.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | 32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여  CmykColor  구조를 생성합니다. |
| [getC()](#getC--) | 이  com.aspose.psd.Color  구조의 시안 구성 요소 값을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 비어 있는 값을 가져옵니다. |
| [getK()](#getK--) | 이  com.aspose.psd.Color  구조의 블랙 구성 요소 값을 가져옵니다. |
| [getM()](#getM--) | 이  com.aspose.psd.Color  구조의 마젠타 구성 요소 값을 가져옵니다. |
| [getY()](#getY--) | 이  com.aspose.psd.Color  구조의 옐로우 구성 요소 값을 가져옵니다. |
| [hashCode()](#hashCode--) | 해시 코드를 가져옵니다. |
| [isEmpty()](#isEmpty--) | 이  com.aspose.psd.Color  구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 32비트 ARGB Color로 변환합니다. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 32비트 ARGB에서 CMYKColor로 변환합니다. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 32비트 ARGB 색상에서 CMYKColor로 변환합니다. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | CMYKColor에서 Color로 변환합니다. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 Color로 변환합니다. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 Color로 변환합니다. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | ICC 변환을 사용하여 CMYKColor에서 Color로 변환합니다. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 Color로 변환합니다. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | ICC 변환을 사용하여 CMYKColor에서 Color로 변환합니다. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | ICC 변환을 사용하여 CMYKColor에서 Color로 변환합니다. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | ICC 변환을 사용하여 CMYKColor에서 Color로 변환합니다. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | 값으로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여  CmykColor  구조를 생성합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 CmykColorHelper\#fromComponents(int, int, int, int)을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시안 | int | 시안 구성 요소. 유효 값은 0부터 255까지입니다. |
| 마젠타 | int | 마젠타 구성 요소. 유효 값은 0부터 255까지입니다. |
| 노란색 | int | 노란색 구성 요소. 유효 값은 0부터 255까지입니다. |
| 검정색 | int | 검은색 구성 요소. 유효 값은 0부터 255까지입니다. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


이  com.aspose.psd.Color  구조의 시안 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이  com.aspose.psd.Color  의 시안 구성 요소 값.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


비어 있는 값을 가져옵니다.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


이  com.aspose.psd.Color  구조의 블랙 구성 요소 값을 가져옵니다.

Value: 이  com.aspose.psd.Color  의 블랙 구성 요소 값.

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


이  com.aspose.psd.Color  구조의 마젠타 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이  com.aspose.psd.Color  의 마젠타 구성 요소 값.
### getY() {#getY--}
```
public byte getY()
```


이  com.aspose.psd.Color  구조의 옐로우 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이  com.aspose.psd.Color  의 옐로우 구성 요소 값.
### hashCode() {#hashCode--}
```
public int hashCode()
```


해시 코드를 가져옵니다.

**Returns:**
int - 정수.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이  com.aspose.psd.Color  구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 속성은 색상이 초기화되지 않은 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.psd.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 32비트 ARGB Color로 변환합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toArgb32(int[]) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀. |

**Returns:**
int[] - 32비트 ARGB 색상의 배열.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


32비트 ARGB에서 CMYKColor로 변환합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toCmyk(int) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argbPixel | int | 32비트 ARGB 형식의 픽셀. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


32비트 ARGB 색상에서 CMYKColor 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toCmyk(int[]) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argbPixels | int[] | 32비트 ARGB 형식의 픽셀들. |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[].
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


CMYKColor에서 Color 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toArgb(int) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


기본 프로파일을 사용한 ICC 변환을 통해 CMYKColor에서 Color 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toArgb(int[]) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀. |

**Returns:**
com.aspose.psd.Color[] - ARGB 색상의 배열입니다.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


기본 프로파일을 사용한 ICC 변환을 통해 CMYKColor에서 Color 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toArgbIcc(int) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


ICC 변환을 통해 CMYKColor에서 Color 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toArgbIcc(int, Stream, Stream) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |
| cmykIccStream | java.io.InputStream | icc cmyk 프로파일을 포함하는 스트림입니다. |
| rgbIccStream | java.io.InputStream | icc rgb 프로파일을 포함하는 스트림입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


기본 프로파일을 사용한 ICC 변환을 통해 CMYKColor에서 Color 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인 CmykColorHelper\#toArgbIcc(int[]) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀. |

**Returns:**
com.aspose.psd.Color[] - com.aspose.psd.Color[] 입니다.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


ICC 변환을 통해 CMYKColor에서 Color 로의 변환입니다. 이 메서드는 사용되지 않습니다. 보다 효율적인  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) 을 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀. |
| cmykIccStream | java.io.InputStream | icc cmyk 프로파일을 포함하는 스트림입니다. |
| rgbIccStream | java.io.InputStream | icc rgb 프로파일을 포함하는 스트림입니다. |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[] 입니다.
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


ICC 변환을 사용하여 CMYKColor에서 Color로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk 프로파일을 포함하는 스트림입니다. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb 프로파일을 포함하는 스트림입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


ICC 변환을 사용하여 CMYKColor에서 Color로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk 프로파일을 포함하는 스트림입니다. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb 프로파일을 포함하는 스트림입니다. |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[] 입니다.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toValue() {#toValue--}
```
public long toValue()
```


값으로 변환합니다.

**Returns:**
long - long 입니다.
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

