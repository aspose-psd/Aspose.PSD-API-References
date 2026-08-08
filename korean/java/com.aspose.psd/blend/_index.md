---
title: "Blend"
second_title: "Java용 Aspose.PSD API 참조"
description: "블렌드 패턴을 정의합니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

블렌드 패턴을 정의합니다. 이 클래스는 상속될 수 없습니다.

일반적인 Blend 클래스 사용 방법은 브러시용 블렌드 패턴을 정의하는 것입니다. 따라서 블렌드 속성은 신중하게 초기화해야 합니다. null 배열은 허용되지 않습니다. 블렌드 팩터 또는 위치 배열이 비어 있거나 길이가 동일하지 않을 경우 브러시는 적절한 예외를 발생시킵니다. 위치 배열에 두 개 이상의 요소가 있는 경우 첫 번째 요소는 0이어야 하고 마지막 요소는 1이어야 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Blend()](#Blend--) | Blend 클래스의 새 인스턴스를 초기화합니다. |
| [Blend(int count)](#Blend-int-) | 지정된 팩터와 위치 수를 사용하여 Blend 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 com.aspose.psd.Blend 클래스이며 이 com.aspose.psd.Blend 클래스와 동등한지 테스트합니다. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | 그라디언트에 대한 블렌드 팩터 배열을 가져옵니다. |
| [getPositions()](#getPositions--) | 그라디언트에 대한 블렌드 위치 배열을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | 그라디언트에 대한 블렌드 팩터 배열을 설정합니다. |
| [setPositions(float[] value)](#setPositions-float---) | 그라디언트에 대한 블렌드 위치 배열을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Blend 클래스의 새 인스턴스를 초기화합니다. 팩터와 블렌드 배열의 요소 수는 1과 같습니다.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


지정된 팩터와 위치 수를 사용하여 Blend 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| count | int | 팩터 및 위치 배열의 요소 수. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 com.aspose.psd.Blend 클래스이며 이 com.aspose.psd.Blend 클래스와 동등한지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체입니다. |

**Returns:**
boolean - obj가 이 com.aspose.psd.Blend 클래스와 동등한 com.aspose.psd.Blend 클래스인 경우 true; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


그라디언트에 대한 블렌드 팩터 배열을 가져옵니다.

**Returns:**
float[] - 해당 위치에서 사용되는 시작 색상과 끝 색상의 비율을 지정하는 블렌드 팩터 배열.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


그라디언트에 대한 블렌드 위치 배열을 가져옵니다.

**Returns:**
float[] - 그라디언트 라인상의 거리 비율을 지정하는 블렌드 위치 배열.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


그라디언트에 대한 블렌드 팩터 배열을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float[] | 해당 위치에서 사용되는 시작 색상과 끝 색상의 비율을 지정하는 블렌드 팩터 배열. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


그라디언트에 대한 블렌드 위치 배열을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float[] | 그라디언트 라인상의 거리 비율을 지정하는 블렌드 위치 배열. |

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

