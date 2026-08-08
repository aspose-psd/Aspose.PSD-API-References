---
title: "ColorantLab"
second_title: "Java용 Aspose.PSD API 참조"
description: "LAB 컬러런트를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.xmp.types.complex.colorant/colorantlab/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantLab extends ColorantBase
```

LAB 컬러런트를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorantLab()](#ColorantLab--) | ColorantLab 클래스의 새 인스턴스를 초기화합니다. |
| [ColorantLab(int a, int b, float l)](#ColorantLab-int-int-float-) | ColorantLab 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [MaxA](#MaxA) | 최대 A 구성 요소 값 |
| [MaxB](#MaxB) | 최대 A 구성 요소 값 |
| [MaxL](#MaxL) | 최대 A 구성 요소 값 |
| [MinA](#MinA) | 최소 A 구성 요소 값 |
| [MinB](#MinB) | 최소 B 구성 요소 값 |
| [MinL](#MinL) | 최소 L 구성 요소 값 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 지정된 키를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | A 구성 요소를 가져오거나 설정합니다. |
| [getB()](#getB--) | B 구성 요소를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 색상의 유형을 가져오거나 설정합니다. |
| [getL()](#getL--) | L 구성 요소를 가져오거나 설정합니다. |
| [getMode()](#getMode--) | 가져옵니다  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | 기본 네임스페이스 URI를 가져옵니다. |
| [getPrefix()](#getPrefix--) | 접두사를 가져옵니다. |
| [getSwatchName()](#getSwatchName--) | 스와치 이름을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(int value)](#setA-int-) | A 구성 요소를 가져오거나 설정합니다. |
| [setB(int value)](#setB-int-) | B 구성 요소를 가져오거나 설정합니다. |
| [setColorType(int value)](#setColorType-int-) | 색상의 유형을 가져오거나 설정합니다. |
| [setL(float value)](#setL-float-) | L 구성 요소를 가져오거나 설정합니다. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | 스와치 이름을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantLab() {#ColorantLab--}
```
public ColorantLab()
```


ColorantLab 클래스의 새 인스턴스를 초기화합니다.

### ColorantLab(int a, int b, float l) {#ColorantLab-int-int-float-}
```
public ColorantLab(int a, int b, float l)
```


ColorantLab 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | int | A 구성 요소. |
| b | int | B 구성 요소. |
| l | float | L 구성 요소. |

### MaxA {#MaxA}
```
public static final int MaxA
```


최대 A 구성 요소 값

### MaxB {#MaxB}
```
public static final int MaxB
```


최대 A 구성 요소 값

### MaxL {#MaxL}
```
public static final float MaxL
```


최대 A 구성 요소 값

### MinA {#MinA}
```
public static final int MinA
```


최소 A 구성 요소 값

### MinB {#MinB}
```
public static final int MinB
```


최소 B 구성 요소 값

### MinL {#MinL}
```
public static final float MinL
```


최소 L 구성 요소 값

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
### getA() {#getA--}
```
public int getA()
```


A 구성 요소를 가져오거나 설정합니다.

값: A 구성 요소.

**Returns:**
int
### getB() {#getB--}
```
public int getB()
```


B 구성 요소를 가져오거나 설정합니다.

값: B 구성 요소.

**Returns:**
int
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
### getL() {#getL--}
```
public float getL()
```


L 구성 요소를 가져오거나 설정합니다.

값: L 구성 요소.

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




### setA(int value) {#setA-int-}
```
public void setA(int value)
```


A 구성 요소를 가져오거나 설정합니다.

값: A 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setB(int value) {#setB-int-}
```
public void setB(int value)
```


B 구성 요소를 가져오거나 설정합니다.

값: B 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setL(float value) {#setL-float-}
```
public void setL(float value)
```


L 구성 요소를 가져오거나 설정합니다.

값: L 구성 요소.

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

