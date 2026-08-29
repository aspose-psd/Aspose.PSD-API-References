---
title: "AutoMaskingArgs"
second_title: "Java용 Aspose.PSD API 참조"
description: "자동 마스킹 메서드에 지정된 인수를 나타냅니다"
type: docs
weight: 11
url: /ko/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

자동 마스킹 메서드에 지정된 인수를 나타냅니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | 반복 횟수의 최대값을 가져옵니다. |
| [getNumberOfObjects()](#getNumberOfObjects--) | 초기 이미지를 분리할 객체 수를 가져옵니다 (옵션), 기본값은 2 (객체와 배경)입니다. |
| [getObjectsPoints()](#getObjectsPoints--) | 분리된 객체에 속하는 점들을 가져옵니다 (옵션) NumberOfObjects 좌표는 초기 이미지의 NumberOfObjects 객체에 속합니다. |
| [getObjectsRectangles()](#getObjectsRectangles--) | 분리된 객체에 속하는 객체 사각형을 가져옵니다 (옵션). |
| [getOrphanedPoints()](#getOrphanedPoints--) | 더 이상 어떤 객체에도 속하지 않는 점들을 가져옵니다 (옵션). |
| [getPrecision()](#getPrecision--) | 분할 방법의 정밀도를 가져옵니다 (옵션). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | 최대 반복 횟수를 설정합니다. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | 초기 이미지를 분리할 객체 수를 설정합니다 (옵션), 기본값은 2 (객체와 배경)입니다. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | 분리된 객체에 속하는 점들을 설정합니다 (옵션) NumberOfObjects 좌표는 초기 이미지의 NumberOfObjects 객체에 속합니다. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | 분리된 객체에 속하는 객체 사각형을 설정합니다 (옵션). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | 더 이상 어떤 객체에도 속하지 않는 점들을 설정합니다 (옵션). |
| [setPrecision(double value)](#setPrecision-double-) | 분할 방법의 정밀도를 설정합니다 (옵션). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


반복 횟수의 최대값을 가져옵니다.

값: 최대 반복 횟수입니다.

**Returns:**
int - 최대 반복 횟수입니다.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


초기 이미지를 분리할 객체 수를 가져옵니다 (옵션), 기본값은 2 (객체와 배경)입니다.

값: 객체 수입니다.

**Returns:**
int - 초기 이미지를 분리할 객체 수 (옵션), 기본값은 2 (객체와 배경)입니다.
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


분리된 객체에 속하는 점들을 가져옵니다 (옵션) NumberOfObjects 좌표는 초기 이미지의 NumberOfObjects 객체에 속합니다. 이 매개변수는 분할 방법의 정밀도를 높이는 데 사용됩니다.

값: 객체 점들입니다.

**Returns:**
com.aspose.psd.Point[][] - 분리된 객체에 속하는 점들 (옵션) NumberOfObjects 좌표는 초기 이미지의 NumberOfObjects 객체에 속합니다.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


분리된 객체에 속하는 객체 사각형을 가져옵니다 (옵션). 이 매개변수는 분할 방법의 정밀도를 높이는 데 사용됩니다.

값: 객체 사각형입니다.

**Returns:**
com.aspose.psd.Rectangle[] - 분리된 객체에 속하는 객체 사각형 (옵션).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


더 이상 어떤 객체에도 속하지 않는 점들을 가져옵니다 (옵션). 이 매개변수는 재분할 경우에만 사용됩니다.

값: 고아 점들입니다.

**Returns:**
com.aspose.psd.Point[] - 더 이상 어떤 객체에도 속하지 않는 점들 (옵션).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


분할 방법의 정밀도를 가져옵니다 (옵션).

값: 분할 방법의 정밀도 (옵션).

**Returns:**
double - 분할 방법의 정밀도 (옵션).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


최대 반복 횟수를 설정합니다.

값: 최대 반복 횟수입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 최대 반복 횟수. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


초기 이미지를 분리할 객체 수를 설정합니다 (옵션), 기본값은 2 (객체와 배경)입니다.

값: 객체 수입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 초기 이미지를 분리할 객체 수 (옵션), 기본값은 2 (객체와 배경)입니다. |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


분리된 객체에 속하는 점을 설정합니다 (옵션) NumberOfObjects 좌표는 초기 이미지의 NumberOfObjects 객체에 속합니다. 이 매개변수는 세분화 방법의 정밀도를 높이는 데 사용됩니다.

값: 객체 점들입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 분리된 객체에 속하는 점 (옵션) NumberOfObjects 좌표는 초기 이미지의 NumberOfObjects 객체에 속합니다. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


분리된 객체에 속하는 객체 사각형을 설정합니다 (옵션). 이 매개변수는 세분화 방법의 정밀도를 높이는 데 사용됩니다.

값: 객체 사각형입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 분리된 객체에 속하는 객체 사각형 (옵션). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


더 이상 어떤 객체에도 속하지 않는 점을 설정합니다 (옵션). 이 매개변수는 재세분화 경우에만 사용됩니다.

값: 고아 점들입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 더 이상 어떤 객체에도 속하지 않는 점 (옵션). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


분할 방법의 정밀도를 설정합니다 (옵션).

값: 분할 방법의 정밀도 (옵션).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 세분화 방법의 정밀도 (옵션). |

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

