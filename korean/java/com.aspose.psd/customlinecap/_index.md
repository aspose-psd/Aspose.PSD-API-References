---
title: "CustomLineCap"
second_title: "Java용 Aspose.PSD API 참조"
description: "사용자 정의 라인 캡을 캡슐화합니다."
type: docs
weight: 34
url: /ko/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

사용자 정의 라인 캡을 캡슐화합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | 새 인스턴스를 초기화합니다  CustomLineCap  class 지정된 윤곽선 및 채우기로. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | 새 인스턴스를 초기화합니다  CustomLineCap  class를 지정된 기존  LineCap  enumeration에서 지정된 윤곽선 및 채우기로. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | 새 인스턴스를 초기화합니다  CustomLineCap  class를 지정된 기존  LineCap  enumeration에서 지정된 윤곽선, 채우기 및 inset로. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | 이  CustomLineCap  가 기반하는  LineCap  enumeration을 가져옵니다. |
| [getBaseInset()](#getBaseInset--) | 캡과 line 사이의 거리를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | custom cap의 채우기를 정의하는 객체를 가져옵니다. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | 이 custom cap을 구성하는 선을 시작하고 끝내는 데 사용되는 caps를 가져옵니다. |
| [getStrokeJoin()](#getStrokeJoin--) | 이  CustomLineCap  객체를 구성하는 선이 결합되는 방식을 결정하는  LineJoin  enumeration을 가져옵니다. |
| [getStrokePath()](#getStrokePath--) | custom cap의 윤곽선을 정의하는 객체를 가져옵니다. |
| [getWidthScale()](#getWidthScale--) | 이  CustomLineCap  Class 객체를  System.Drawing.Pen  객체의 너비에 대해 스케일링하는 양을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | 이  CustomLineCap  가 기반하는  LineCap  enumeration을 설정합니다. |
| [setBaseInset(float value)](#setBaseInset-float-) | 캡과 line 사이의 거리를 설정합니다. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | custom cap의 채우기를 정의하는 객체를 설정합니다. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | 이 custom cap을 구성하는 선을 시작하고 끝내는 데 사용되는 caps를 설정합니다. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | 이  CustomLineCap  객체를 구성하는 선이 결합되는 방식을 결정하는  LineJoin  enumeration을 설정합니다. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | custom cap의 윤곽선을 정의하는 객체를 설정합니다. |
| [setWidthScale(float value)](#setWidthScale-float-) | 이  CustomLineCap  Class 객체를  System.Drawing.Pen  객체의 너비에 대해 스케일링하는 양을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


새 인스턴스를 초기화합니다  CustomLineCap  class 지정된 윤곽선 및 채우기로.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | custom cap의 채우기를 정의하는  GraphicsPath  객체. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 GraphicsPath 객체입니다. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


새 인스턴스를 초기화합니다  CustomLineCap  class를 지정된 기존  LineCap  enumeration에서 지정된 윤곽선 및 채우기로.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | custom cap의 채우기를 정의하는  GraphicsPath  객체. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 GraphicsPath 객체입니다. |
| baseCap | int | 사용자 정의 캡을 만들기 위한 기본 라인 캡입니다. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


새 인스턴스를 초기화합니다  CustomLineCap  class를 지정된 기존  LineCap  enumeration에서 지정된 윤곽선, 채우기 및 inset로.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | custom cap의 채우기를 정의하는  GraphicsPath  객체. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 GraphicsPath 객체입니다. |
| baseCap | int | 사용자 정의 캡을 만들기 위한 기본 라인 캡입니다. |
| baseInset | float | 캡과 선 사이의 거리입니다. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


이  CustomLineCap  가 기반하는  LineCap  enumeration을 가져옵니다.

**Returns:**
int - 이 CustomLineCap이 기반으로 하는 LineCap 열거형입니다.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


캡과 line 사이의 거리를 가져옵니다.

**Returns:**
float - 캡의 시작점과 선의 끝점 사이의 거리입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


custom cap의 채우기를 정의하는 객체를 가져옵니다.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


이 custom cap을 구성하는 선을 시작하고 끝내는 데 사용되는 caps를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startCap | int[] | 이 캡 내에서 선의 시작에 사용되는 LineCap 열거형입니다. |
| endCap | int[] | 이 캡 내에서 선의 끝에 사용되는 LineCap 열거형입니다. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


이  CustomLineCap  객체를 구성하는 선이 결합되는 방식을 결정하는  LineJoin  enumeration을 가져옵니다.

**Returns:**
int - 이 CustomLineCap 객체가 선을 연결하는 데 사용하는 LineJoin 열거형입니다.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


custom cap의 윤곽선을 정의하는 객체를 가져옵니다.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


이  CustomLineCap  Class 객체를  System.Drawing.Pen  객체의 너비에 대해 스케일링하는 양을 가져옵니다.

**Returns:**
float - 캡을 스케일링하는 양입니다.
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


이  CustomLineCap  가 기반하는  LineCap  enumeration을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 CustomLineCap이 기반으로 하는 LineCap 열거형입니다. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


캡과 line 사이의 거리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 캡의 시작점과 선의 끝점 사이의 거리입니다. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


custom cap의 채우기를 정의하는 객체를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | 사용자 정의 캡의 채우기를 정의하는 객체입니다. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


이 custom cap을 구성하는 선을 시작하고 끝내는 데 사용되는 caps를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startCap | int | 이 캡 내에서 선의 시작에 사용되는 LineCap 열거형입니다. |
| endCap | int | 이 캡 내에서 선의 끝에 사용되는 LineCap 열거형입니다. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


이  CustomLineCap  객체를 구성하는 선이 결합되는 방식을 결정하는  LineJoin  enumeration을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 CustomLineCap 객체가 선을 연결하는 데 사용하는 LineJoin 열거형입니다. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


custom cap의 윤곽선을 정의하는 객체를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 객체입니다. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


이  CustomLineCap  Class 객체를  System.Drawing.Pen  객체의 너비에 대해 스케일링하는 양을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 캡을 스케일링하는 양입니다. |

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

