---
title: "ColorComponent"
second_title: "Java용 Aspose.PSD API 참조"
description: "컬러 컴포넌트는 Channel Value와 Channel Value에 대한 추상화입니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Color component는 Channel Value와 Channel Value에 대한 추상화입니다. 모든 색은 ColorComponent 배열로 구성됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Color Component/Channel의 비트 깊이를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Color Component의 설명을 가져옵니다. |
| [getFullName()](#getFullName--) | 이름과 공백으로 구분된 설명을 포함한 색 구성 요소의 전체 이름을 가져옵니다. |
| [getName()](#getName--) | 색 구성 요소의 이름을 가져옵니다. |
| [getPermittedFullNames()](#getPermittedFullNames--) | 허용된 전체 이름을 가져옵니다. |
| [getValue()](#getValue--) | 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


[ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) 클래스의 새 인스턴스를 초기화합니다. 확인하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitDepth | byte | 비트 깊이. |
| fullName | java.lang.String | 전체 이름입니다. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Color Component/Channel의 비트 깊이를 가져옵니다.

Value: 비트 깊이.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Color Component의 설명을 가져옵니다.

값: 설명.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


이름과 공백으로 구분된 설명을 포함한 색 구성 요소의 전체 이름을 가져옵니다.

Value: 전체 이름.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


색 구성 요소의 이름을 가져옵니다.

Value: 이름.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


허용된 전체 이름을 가져옵니다.

Value: 허용된 전체 이름.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


값을 가져오거나 설정합니다. 현재 비트 깊이에 저장할 수 있는 것보다 큰 값을 설정하려고 하면 예외가 발생한다는 점에 유의하십시오.

값: 해당 값입니다.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


값을 가져오거나 설정합니다. 현재 비트 깊이에 저장할 수 있는 것보다 큰 값을 설정하려고 하면 예외가 발생한다는 점에 유의하십시오.

값: 해당 값입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

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

