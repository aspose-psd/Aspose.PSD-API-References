---
title: "CmykColorHelper"
second_title: "Java용 Aspose.PSD API 참조"
description: "부호 있는 32비트 정수 값으로 표현된 CMYK 색상을 다루는 도우미 메서드입니다."
type: docs
weight: 18
url: /ko/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

CMYK 색상을 부호 있는 32비트 정수 값으로 표현하는 데 사용되는 도우미 메서드입니다. com.aspose.psd.CmykColor 구조체와 유사한 API를 제공합니다. CMYK 색상이 내부 필드가 있는 구조체가 아니라 Int32로만 표현되기 때문에 더 가볍습니다. 가능한 경우에는 더 이상 사용되지 않는 com.aspose.psd.CmykColor 구조체 대신 이 클래스의 정적 메서드를 사용하는 것이 좋습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여 CMYK를 생성합니다. |
| [getC(int cmyk)](#getC-int-) | 시안 구성 요소 값을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | 블랙 구성 요소 값을 가져옵니다. |
| [getM(int cmyk)](#getM-int-) | 마젠타 구성 요소 값을 가져옵니다. |
| [getY(int cmyk)](#getY-int-) | 노란색 구성 요소 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | CMYK 색상에서 ARGB 색상으로의 변환. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | CMYK 색상에서 ARGB 색상으로의 변환. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | CMYK 색상에서 ARGB 색상으로의 변환. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | 기본 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | 사용자 정의 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | 기본 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | 사용자 정의 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | RGB를 CMYK로 변환합니다. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | 기본 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | 사용자 정의 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | 기본 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | 사용자 정의 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | 사용자 정의 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다. |
| [toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
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
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여 CMYK를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시안 | int | 시안 구성 요소. 유효 값은 0부터 255까지입니다. |
| 마젠타 | int | 마젠타 구성 요소. 유효 값은 0부터 255까지입니다. |
| 노란색 | int | 노란색 구성 요소. 유효 값은 0부터 255까지입니다. |
| 검정색 | int | 검은색 구성 요소. 유효 값은 0부터 255까지입니다. |

**Returns:**
int - 32비트 정수 값으로 표시된 CMYK 색상.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


시안 구성 요소 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상. |

**Returns:**
int - 시안 구성 요소 값.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


블랙 구성 요소 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상. |

**Returns:**
int - 검은색 구성 요소 값.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


마젠타 구성 요소 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상. |

**Returns:**
int - 마젠타 구성 요소 값.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


노란색 구성 요소 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상. |

**Returns:**
int - 노란색 구성 요소 값.
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




### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | int | 32비트 정수 값으로 표시된 CMYK 색상. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | int[] | CMYK 색상이 32비트 정수 값으로 표시됩니다. |

**Returns:**
com.aspose.psd.Color[] - ARGB 색상.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | int[] | CMYK 색상이 32비트 정수 값으로 표시됩니다. |

**Returns:**
int[] - ARGB 색상이 32비트 정수 값으로 표시됩니다.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


기본 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | int | 32비트 정수 값으로 표시된 CMYK 색상. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


사용자 정의 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixel | int | 32비트 정수 값으로 표시된 CMYK 색상. |
| cmykIccStream | java.io.InputStream | CMYK Icc 프로파일을 포함하는 스트림. |
| rgbIccStream | java.io.InputStream | RGB Icc 프로파일을 포함하는 스트림. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


기본 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | int[] | CMYK 픽셀이 32비트 정수 값으로 표시됩니다. |

**Returns:**
com.aspose.psd.Color[] - ARGB 색상.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


사용자 정의 프로파일을 사용한 ICC 변환으로 CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cmykPixels | int[] | CMYK 색상이 32비트 정수 값으로 표시됩니다. |
| cmykIccStream | java.io.InputStream | CMYK Icc 프로파일을 포함하는 스트림. |
| rgbIccStream | java.io.InputStream | RGB Icc 프로파일을 포함하는 스트림. |

**Returns:**
com.aspose.psd.Color[] - ARGB 색상.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB 색상. |

**Returns:**
int - 32비트 정수 값으로 표시된 CMYK 색상.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB 색상들. |

**Returns:**
int[] - CMYK 색상이 32비트 정수 값으로 표시됩니다.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argbPixel | int | ARGB 색상이 32비트 정수 값으로 표시됩니다. |

**Returns:**
int - 32비트 정수 값으로 표시된 CMYK 색상.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argbPixels | int[] | ARGB 색상이 32비트 정수 값으로 표시됩니다. |

**Returns:**
int[] - CMYK 색상이 32비트 정수 값으로 표시됩니다.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


RGB를 CMYK로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argbPixels | int[] | RGB 색상이 32비트 정수 값으로 표시됩니다. |
| startIndex | int | RGB 색상의 시작 인덱스. |
| length | int | 변환할 RGB 픽셀 수. |

**Returns:**
byte[] - CMYK 색상이 바이트 배열로 표시됩니다.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


기본 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB 색상. |

**Returns:**
int - 32비트 정수 값으로 표시된 CMYK 색상.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


사용자 정의 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB 색상. |
| rgbIccStream | java.io.InputStream | RGB Icc 프로파일을 포함하는 스트림. |
| cmykIccStream | java.io.InputStream | CMYK Icc 프로파일을 포함하는 스트림. |

**Returns:**
int - 32비트 정수 값으로 표시된 CMYK 색상.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


기본 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB 색상들. |

**Returns:**
int[] - CMYK 색상이 32비트 정수 값으로 표시됩니다.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


사용자 정의 프로파일을 사용한 ICC 변환으로 ARGB 색상에서 CMYK 색상으로의 변환.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB 색상들. |
| rgbIccStream | java.io.InputStream | RGB Icc 프로파일을 포함하는 스트림. |
| cmykIccStream | java.io.InputStream | CMYK Icc 프로파일을 포함하는 스트림. |

**Returns:**
int[] - CMYK 색상이 32비트 정수 값으로 표시됩니다.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


사용자 정의 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] | RGB 색상이 32비트 정수 값으로 표시됩니다. |
| startIndex | int | RGB 색상의 시작 인덱스. |
| length | int | 변환할 RGB 픽셀 수. |
| rgbIccStream | java.io.InputStream | RGB 프로파일 스트림. |
| cmykIccStream | java.io.InputStream | CMYK 프로파일 스트림. |

**Returns:**
byte[] - CMYK 색상이 바이트 배열로 표시됩니다.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] |  |
| startIndex | int |  |
| length | int |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
byte[]
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

