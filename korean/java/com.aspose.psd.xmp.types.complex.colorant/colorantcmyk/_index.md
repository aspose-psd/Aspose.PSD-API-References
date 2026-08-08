---
title: "ColorantCmyk"
second_title: "Java용 Aspose.PSD API 참조"
description: "CMYK 컬러런트를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

CMYK 컬러런트를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | 새 인스턴스를 초기화합니다  ColorantCmyk  클래스의. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | 새 인스턴스를 초기화합니다  ColorantCmyk  클래스의. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | CMYK 색소에서 색상 최대값. |
| [ColorValueMin](#ColorValueMin) | CMYK 색소에서 색상 최소값. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 지정된 키를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | 검은색 구성 요소 값을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 색상의 유형을 가져오거나 설정합니다. |
| [getCyan()](#getCyan--) | 시안 구성 요소 값을 가져오거나 설정합니다. |
| [getMagenta()](#getMagenta--) | 마젠타 구성 요소 값을 가져오거나 설정합니다. |
| [getMode()](#getMode--) | 가져옵니다  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | 기본 네임스페이스 URI를 가져옵니다. |
| [getPrefix()](#getPrefix--) | 접두사를 가져옵니다. |
| [getSwatchName()](#getSwatchName--) | 스와치 이름을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [getYellow()](#getYellow--) | 노란색 구성 요소 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | 검은색 구성 요소 값을 가져오거나 설정합니다. |
| [setColorType(int value)](#setColorType-int-) | 색상의 유형을 가져오거나 설정합니다. |
| [setCyan(float value)](#setCyan-float-) | 시안 구성 요소 값을 가져오거나 설정합니다. |
| [setMagenta(float value)](#setMagenta-float-) | 마젠타 구성 요소 값을 가져오거나 설정합니다. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | 스와치 이름을 가져오거나 설정합니다. |
| [setYellow(float value)](#setYellow-float-) | 노란색 구성 요소 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


새 인스턴스를 초기화합니다  ColorantCmyk  클래스의.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


새 인스턴스를 초기화합니다  ColorantCmyk  클래스의.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 검정색 | float | 검정색 구성 요소 값. |
| 시안 | float | 시안 색 구성 요소 값. |
| 마젠타 | float | 마젠타 구성 요소 값. |
| 노란색 | float | 노란색 구성 요소 값. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


CMYK 색소에서 색상 최대값.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


CMYK 색소에서 색상 최소값.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


지정된 키를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 추가된 값과 식별되는 키의 문자열 표현. |
| 값 | java.lang.Object | 추가할 값. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


검은색 구성 요소 값을 가져오거나 설정합니다.

값: 검정색 구성 요소 값.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


색상의 유형을 가져오거나 설정합니다.

값: 색상의 유형.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


시안 구성 요소 값을 가져오거나 설정합니다.

값: 시안 구성 요소 값.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


마젠타 구성 요소 값을 가져오거나 설정합니다.

값: 마젠타 구성 요소 값.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


가져옵니다  ColorMode .

값: 색상 모드.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


기본 네임스페이스 URI를 가져옵니다.

**Returns:**
java.lang.String - 기본 네임스페이스 URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


접두사를 가져옵니다.

**Returns:**
java.lang.String - 접두사.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


스와치 이름을 가져오거나 설정합니다.

값: 스와치 이름.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 형식의 문자열 포함 값을 가져옵니다.

**Returns:**
java.lang.String - XMP 형식의 문자열 포함 값을 반환합니다.
### getYellow() {#getYellow--}
```
public float getYellow()
```


노란색 구성 요소 값을 가져오거나 설정합니다.

값: 노란색 구성 요소 값.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


검은색 구성 요소 값을 가져오거나 설정합니다.

값: 검정색 구성 요소 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


색상의 유형을 가져오거나 설정합니다.

값: 색상의 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


시안 구성 요소 값을 가져오거나 설정합니다.

값: 시안 구성 요소 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


마젠타 구성 요소 값을 가져오거나 설정합니다.

값: 마젠타 구성 요소 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


스와치 이름을 가져오거나 설정합니다.

값: 스와치 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


노란색 구성 요소 값을 가져오거나 설정합니다.

값: 노란색 구성 요소 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

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

