---
title: "SolidBrush"
second_title: "Java용 Aspose.PSD API 참조"
description: "솔리드 브러시는 특정 색상으로 지속적으로 그리기 위해 설계되었습니다."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.brushes/solidbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class SolidBrush extends Brush
```

Solid brush는 특정 색상으로 지속적으로 그리기 위해 설계되었습니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | SolidBrush 클래스의 새 인스턴스를 초기화합니다. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.psd.Color-) | SolidBrush 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 현재 Brush 의 새로운 깊은 복제본을 생성합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 브러시 색상을 가져오거나 설정합니다. |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getOpacity()](#getOpacity--) | Brush 불투명도를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 브러시 색상을 가져오거나 설정합니다. |
| [setOpacity(float value)](#setOpacity-float-) | 브러시 불투명도를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


SolidBrush 클래스의 새 인스턴스를 초기화합니다.

### SolidBrush(Color color) {#SolidBrush-com.aspose.psd.Color-}
```
public SolidBrush(Color color)
```


SolidBrush 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 솔리드 브러시 색상. |

### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


현재 Brush 의 새로운 깊은 복제본을 생성합니다.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

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
### getColor() {#getColor--}
```
public Color getColor()
```


브러시 색상을 가져오거나 설정합니다.

값: 브러시 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


브러시 불투명도를 가져옵니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다.

**Returns:**
float - 브러시 불투명도 값.
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




### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


브러시 색상을 가져오거나 설정합니다.

값: 브러시 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


브러시 불투명도를 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 브러시 불투명도 값. |

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

