---
title: "GraphicsPath"
second_title: "Java용 Aspose.PSD API 참조"
description: "연결된 선과 곡선의 시리즈를 나타냅니다."
type: docs
weight: 50
url: /ko/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

연결된 선과 곡선의 연속을 나타냅니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | GraphicsPath 클래스의 새 인스턴스를 초기화합니다. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | GraphicsPath 클래스의 새 인스턴스를 초기화합니다. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | GraphicsPath 클래스의 새 인스턴스를 초기화합니다. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | GraphicsPath 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | 새 도형을 추가합니다. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | 새 도형들을 추가합니다. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | 지정된 com.aspose.psd.GraphicsPath 를 이 경로에 추가합니다. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | 지정된 com.aspose.psd.GraphicsPath 를 이 경로에 추가합니다. |
| [deepClone()](#deepClone--) | 이 그래픽 경로를 깊은 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | 이 경로의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | 지정된 변환을 적용한 다음, 이 com.aspose.psd.GraphicsPath 의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | 이 com.aspose.psd.GraphicsPath 의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [getBounds()](#getBounds--) | 객체의 경계를 가져오거나 설정합니다. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 객체의 경계를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | 경로 도형을 가져옵니다. |
| [getFillMode()](#getFillMode--) | 이 com.aspose.psd.GraphicsPath 에 있는 도형 내부가 어떻게 채워지는지를 결정하는 com.aspose.psd.FillMode 열거형을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | 지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | 지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | 지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | 지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | 지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | 지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | 지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | 지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(float x, float y)](#isVisible-float-float-) | 지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.graphics의 가시 클립 영역 내에서 이 com.aspose.psd.GraphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(int x, int y)](#isVisible-int-int-) | 지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | 지정된 com.aspose.psd.graphics를 사용하여 이 com.aspose.psd.GraphicsPath 안에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | 도형을 제거합니다. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | 도형들을 제거합니다. |
| [reset()](#reset--) | 그래픽 경로를 비우고 com.aspose.psd.FillMode을 F:com.aspose.psd.fillMode.alternate 로 설정합니다. |
| [reverse()](#reverse--) | 이 com.aspose.psd.graphicsPath의 각 형태에서 도형, 쉐이프 및 포인트의 순서를 반전시킵니다. |
| [setFillMode(int value)](#setFillMode-int-) | 이 com.aspose.psd.GraphicsPath의 도형 내부가 채워지는 방식을 결정하는 com.aspose.psd.FillMode 열거형을 설정합니다. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 지정된 변환을 모양에 적용합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | 사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | 사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | 사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | 사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다. |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | 경로에 추가 외곽선을 추가합니다. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | com.aspose.psd.graphicsPath에 추가 외곽선을 추가합니다. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | 지정된 펜으로 이 경로를 그릴 때 채워지는 영역을 둘러싸는 곡선으로 이 com.aspose.psd.GraphicsPath를 교체합니다. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


GraphicsPath 클래스의 새 인스턴스를 초기화합니다.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


GraphicsPath 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 초기화할 도형들. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


GraphicsPath 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 초기화할 도형들. |
| fillMode | int | 채우기 모드. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


GraphicsPath 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillMode | int | 채우기 모드. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


새 도형을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | 추가할 도형. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


새 도형들을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 추가할 도형들. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


지정된 com.aspose.psd.GraphicsPath 를 이 경로에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 추가할 com.aspose.psd.GraphicsPath. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


지정된 com.aspose.psd.GraphicsPath 를 이 경로에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 추가할 com.aspose.psd.GraphicsPath. |
| connect | boolean | 추가된 경로의 첫 번째 도형이 이 경로의 마지막 도형의 일부인지 여부를 지정하는 부울 값입니다. true 값은 추가된 경로의 첫 번째 도형이 이 경로의 마지막 도형의 일부임을 지정합니다. false 값은 추가된 경로의 첫 번째 도형이 이 경로의 마지막 도형과 별개임을 지정합니다. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


이 그래픽 경로를 깊은 복제합니다.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


이 경로의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


지정된 변환을 적용한 다음, 이 com.aspose.psd.GraphicsPath 의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 평탄화하기 전에 이 com.aspose.psd.GraphicsPath를 변환할 com.aspose.psd.Matrix. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


이 com.aspose.psd.GraphicsPath 의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 평탄화하기 전에 이 com.aspose.psd.GraphicsPath를 변환할 com.aspose.psd.Matrix. |
| flatness | float | 곡선과 평탄화된 근사값 사이의 허용 가능한 최대 오차를 지정합니다. 기본값은 0.25입니다. flatness 값을 낮추면 근사값에서 선분 수가 증가합니다. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


객체의 경계를 가져오거나 설정합니다.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


객체의 경계를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경계가 계산되기 전에 적용할 행렬입니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


객체의 경계를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경계가 계산되기 전에 적용할 행렬입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 객체에 사용할 펜입니다. 이는 객체의 경계 크기에 영향을 줄 수 있습니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


경로 도형을 가져옵니다.

**Returns:**
com.aspose.psd.Figure[] - 경로 도형들.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


이 com.aspose.psd.GraphicsPath 에 있는 도형 내부가 어떻게 채워지는지를 결정하는 com.aspose.psd.FillMode 열거형을 가져옵니다.

**Returns:**
int - 채우기 모드. 이 com.aspose.psd.GraphicsPath 내 도형들의 내부가 어떻게 채워지는지를 지정하는 com.aspose.psd.FillMode 열거형.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 테스트할 위치를 지정하는 com.aspose.psd.Point. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | 테스트할 위치를 지정하는 com.aspose.psd.Point. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 테스트할 위치를 지정하는 com.aspose.psd.PointF. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | 테스트할 위치를 지정하는 com.aspose.psd.PointF. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선(아래)에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선(아래)에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


지정된 점이 지정된 com.aspose.psd.pen으로 그렸을 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


지정된 점이 지정된 com.aspose.psd.Pen으로 그리고 지정된 com.aspose.psd.graphics를 사용할 때 이 com.aspose.psd.GraphicsPath의 외곽선 안(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 테스트할 com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 지정된 com.aspose.psd.Pen 으로 그린 이 com.aspose.psd.GraphicsPath 의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 테스트할 점을 나타내는 com.aspose.psd.Point. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | 테스트할 점을 나타내는 com.aspose.psd.Point. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 테스트할 점을 나타내는 com.aspose.psd.PointF. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | 테스트할 점을 나타내는 com.aspose.psd.PointF. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 이 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


지정된 점이 지정된 com.aspose.psd.graphics의 가시 클립 영역 내에서 이 com.aspose.psd.GraphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


지정된 점이 이 com.aspose.psd.graphicsPath 안에 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


지정된 com.aspose.psd.graphics를 사용하여 이 com.aspose.psd.GraphicsPath 안에 지정된 점이 포함되는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 가시성을 테스트할 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.GraphicsPath 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


도형을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | 제거할 도형. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


도형들을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 제거할 도형들. |

### reset() {#reset--}
```
public void reset()
```


그래픽 경로를 비우고 com.aspose.psd.FillMode을 F:com.aspose.psd.fillMode.alternate 로 설정합니다.

### reverse() {#reverse--}
```
public void reverse()
```


이 com.aspose.psd.graphicsPath의 각 형태에서 도형, 쉐이프 및 포인트의 순서를 반전시킵니다.

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


이 com.aspose.psd.GraphicsPath의 도형 내부가 채워지는 방식을 결정하는 com.aspose.psd.FillMode 열거형을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 채우기 모드. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


지정된 변환을 모양에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 적용할 변환. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect 로 정의된 사각형이 변환되는 평행사변형을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면, 평행사변형의 오른쪽 아래 모서리는 첫 세 점에 의해 암시됩니다. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints 로 정의된 평행사변형으로 변환되는 사각형을 나타내는 com.aspose.psd.RectangleF. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect 로 정의된 사각형이 변환되는 평행사변형을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면, 평행사변형의 오른쪽 아래 모서리는 첫 세 점에 의해 암시됩니다. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints 로 정의된 평행사변형으로 변환되는 사각형을 나타내는 com.aspose.psd.RectangleF. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경로에 적용할 기하학적 변환을 지정하는 com.aspose.psd.Matrix. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect 로 정의된 사각형이 변환되는 평행사변형을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면, 평행사변형의 오른쪽 아래 모서리는 첫 세 점에 의해 암시됩니다. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints 로 정의된 평행사변형으로 변환되는 사각형을 나타내는 com.aspose.psd.RectangleF. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경로에 적용할 기하학적 변환을 지정하는 com.aspose.psd.Matrix. |
| warpMode | int | 이 워프 작업이 원근법 또는 이중선형 모드를 사용하는지를 지정하는 com.aspose.psd.WarpMode 열거형. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


사각형과 평행사변형으로 정의된 워프 변환을 이 com.aspose.psd.graphicsPath에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect 로 정의된 사각형이 변환되는 평행사변형을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면, 평행사변형의 오른쪽 아래 모서리는 첫 세 점에 의해 암시됩니다. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints 로 정의된 평행사변형으로 변환되는 사각형을 나타내는 com.aspose.psd.RectangleF. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경로에 적용할 기하학적 변환을 지정하는 com.aspose.psd.Matrix. |
| warpMode | int | 이 워프 작업이 원근법 또는 이중선형 모드를 사용하는지를 지정하는 com.aspose.psd.WarpMode 열거형. |
| flatness | float | 결과 경로가 얼마나 평평한지를 지정하는 0부터 1까지의 값입니다. 자세한 내용은 com.aspose.psd.GraphicsPath.flatten 메서드를 참조하십시오. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


경로에 추가 외곽선을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 이 메서드가 생성하는 새 외곽선과 원래 경로 외곽선 사이의 너비를 지정하는 com.aspose.psd.Pen. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


com.aspose.psd.graphicsPath에 추가 외곽선을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 이 메서드가 생성하는 새 외곽선과 원래 경로 외곽선 사이의 너비를 지정하는 com.aspose.psd.Pen. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 넓히기 전에 경로에 적용할 변환을 지정하는 com.aspose.psd.Matrix. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


지정된 펜으로 이 경로를 그릴 때 채워지는 영역을 둘러싸는 곡선으로 이 com.aspose.psd.GraphicsPath를 교체합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 이 메서드가 생성하는 새 외곽선과 원래 경로 외곽선 사이의 너비를 지정하는 com.aspose.psd.Pen. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 넓히기 전에 경로에 적용할 변환을 지정하는 com.aspose.psd.Matrix. |
| flatness | float | 곡선의 평탄도를 지정하는 값. |

