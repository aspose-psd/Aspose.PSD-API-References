---
title: "PathGradientBrushBase"
second_title: "Java용 Aspose.PSD API 참조"
description: "기본 경로 그라디언트 기능을 갖는 브러시를 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.aspose.psd.brushes/pathgradientbrushbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

기본 경로 그라디언트 기능을 가진  Brush  를 나타냅니다.

PathGradientBrushBase 클래스를 생성할 때 최소 2개의 점으로 초기화해야 함을 유의하십시오. 내부에 생성된 경로는 항상 닫힌 도형이며, 마지막 점이 첫 번째 점과 연결됩니다. 이 형태는 해당 PathGradientBrushBase 로 채워집니다. GDI+ 구현은 빈 배열이나 동일한 좌표를 가진 점 집합을 전달하면 OutOfMemoryError 를 발생시킵니다. 점 배열에 2개 미만의 점이 포함된 경우 PathGradientBrushBase 가 예외를 발생시키며, 이때 ArgumentException 이 OutOfMemoryError 대신 발생합니다. 중심점은 기본적으로 전달된 점들의 질량 중심으로 계산됩니다. 사용자는 나중에 이 점을 변경할 수 있습니다. 포커스 스케일은 기본적으로 빈 점 (0.0, 0.0) 입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 현재 Brush 의 새로운 깊은 복제본을 생성합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getFocusScales()](#getFocusScales--) | 그라디언트 감소에 대한 초점점을 가져옵니다. |
| [getGraphicsPath()](#getGraphicsPath--) | 이 브러시가 기반으로 하는 그래픽 경로를 가져옵니다. |
| [getOpacity()](#getOpacity--) | Brush 불투명도를 가져옵니다. |
| [getPathPoints()](#getPathPoints--) | 이 브러시가 기반으로 하는 경로 점들을 가져옵니다. |
| [getTransform()](#getTransform--) | 이 TransformBrush 에 대한 로컬 기하학 변환을 정의하는 Aspose.Imaging.Matrix 복사본을 가져오거나 설정합니다. |
| [getWrapMode()](#getWrapMode--) | 이 TransformBrush 에 대한 랩 모드를 나타내는 Aspose.Imaging.WrapMode 열거형을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | 변환이 어떤 방식으로든 변경되었는지 여부를 나타내는 값을 가져옵니다. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | 지정된 Aspose.Imaging.Matrix 를 앞에 추가하여 이 LinearGradientBrush 의 로컬 기하학 변환을 나타내는 Aspose.Imaging.Matrix 를 지정된 Aspose.Imaging.Matrix 로 곱합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | 지정된 순서대로 지정된 Aspose.Imaging.Matrix 로 이 LinearGradientBrush 의 로컬 기하학 변환을 나타내는 Aspose.Imaging.Matrix 를 곱합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | TransformBrush.Transform 속성을 단위 행렬로 재설정합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 양만큼 로컬 기하학 변환을 회전시킵니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 회전시킵니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 양만큼 로컬 기하학 변환을 스케일링합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 스케일링합니다. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | 그라디언트 감소에 대한 초점점을 가져오거나 설정합니다. |
| [setOpacity(float value)](#setOpacity-float-) | 브러시 불투명도를 설정합니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 이 TransformBrush 에 대한 로컬 기하학 변환을 정의하는 Aspose.Imaging.Matrix 복사본을 가져오거나 설정합니다. |
| [setWrapMode(int value)](#setWrapMode-int-) | 이 TransformBrush 에 대한 랩 모드를 나타내는 Aspose.Imaging.WrapMode 열거형을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


경로 그라디언트의 중심점을 가져오거나 설정합니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


그라디언트 감소에 대한 초점점을 가져옵니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


이 브러시가 기반으로 하는 그래픽 경로를 가져옵니다.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


브러시 불투명도를 가져옵니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다.

**Returns:**
float - 브러시 불투명도 값.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


이 브러시가 기반으로 하는 경로 점들을 가져옵니다.

**Returns:**
com.aspose.psd.PointF[] - 경로 점들.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


이 TransformBrush 에 대한 로컬 기하학 변환을 정의하는 Aspose.Imaging.Matrix 복사본을 가져오거나 설정합니다.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


이 TransformBrush 에 대한 랩 모드를 나타내는 Aspose.Imaging.WrapMode 열거형을 가져오거나 설정합니다.

**Returns:**
int - 이 TransformBrush로 그린 채우기가 타일링되는 방식을 지정하는 Aspose.Imaging.WrapMode입니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


변환이 어떤 방식으로든 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 이전 호환성을 위해 도입되었습니다.

값: 변환이 변경된 경우 `True`, 그렇지 않으면 `false`.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


지정된 Aspose.Imaging.Matrix 를 앞에 추가하여 이 LinearGradientBrush 의 로컬 기하학 변환을 나타내는 Aspose.Imaging.Matrix 를 지정된 Aspose.Imaging.Matrix 로 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 기하 변환에 곱할 Aspose.Imaging.Matrix입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


지정된 순서대로 지정된 Aspose.Imaging.Matrix 로 이 LinearGradientBrush 의 로컬 기하학 변환을 나타내는 Aspose.Imaging.Matrix 를 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 기하 변환에 곱할 Aspose.Imaging.Matrix입니다. |
| order | int | 두 행렬을 곱할 순서를 지정하는 Aspose.Imaging.MatrixOrder입니다. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


TransformBrush.Transform 속성을 단위 행렬로 재설정합니다.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


지정된 양만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 회전시킵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |
| order | int | 회전 행렬을 추가하거나 앞에 삽입할지 지정하는  Aspose.Imaging.MatrixOrder  입니다. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


지정된 양만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링하는 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링하는 양입니다. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 스케일링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링하는 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링하는 양입니다. |
| order | int | 스케일링 행렬을 추가하거나 앞에 삽입할지 지정하는  Aspose.Imaging.MatrixOrder  입니다. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


경로 그라디언트의 중심점을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | 경로 그라디언트의 중심점을 나타내는 Aspose.Imaging.PointF. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


그라디언트 감소에 대한 초점점을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | 그라디언트 감소에 대한 초점점을 나타내는 Aspose.Imaging.PointF. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


브러시 불투명도를 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 브러시 불투명도 값. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


이 TransformBrush 에 대한 로컬 기하학 변환을 정의하는 Aspose.Imaging.Matrix 복사본을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


이 TransformBrush 에 대한 랩 모드를 나타내는 Aspose.Imaging.WrapMode 열거형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 변환 앞에 평행 이동 행렬을 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |
| order | int | 평행 이동을 적용할 순서(앞에 삽입 또는 뒤에 추가)입니다. |

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

