---
title: "Region"
second_title: "Java용 Aspose.PSD API 참조"
description: "사각형 및 경로로 구성된 그래픽 모양의 내부를 설명합니다."
type: docs
weight: 90
url: /ko/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

사각형과 경로로 구성된 그래픽 형태의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Region()](#Region--) | 새로운  T:Aspose.Imaging.Region 를 초기화합니다. |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | 지정된  T:Aspose.Imaging.RectangleF  구조에서 새로운  T:Aspose.Imaging.Region  를 초기화합니다. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | 지정된  T:Aspose.Imaging.Rectangle  구조에서 새로운  T:Aspose.Imaging.Region  를 초기화합니다. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | 지정된  T:Aspose.Imaging.GraphicsPath  로 새로운  T:Aspose.Imaging.Region  를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.GraphicsPath와 교차하지 않는 부분을 포함합니다. |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.Rectangle 구조와 교차하지 않는 부분을 포함합니다. |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.RectangleF 구조와 교차하지 않는 부분을 포함합니다. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.Region과 교차하지 않는 부분을 포함합니다. |
| [deepClone()](#deepClone--) | 이 com.aspose.psd.region의 정확한 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.graphicsPath와 교차하지 않는 내부 부분만 포함합니다. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.Rectangle 구조와 교차하지 않는 내부 부분만 포함합니다. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.RectangleF 구조와 교차하지 않는 내부 부분만 포함합니다. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | 이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.region와 교차하지 않는 내부 부분만 포함합니다. |
| [getActions_internalized()](#getActions-internalized--) | region 작업을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | 이 com.aspose.psd.Region을 지정된 com.aspose.psd.graphicsPath와의 교차 영역으로 업데이트합니다. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | 이 com.aspose.psd.Region을 지정된 com.aspose.psd.Rectangle 구조와의 교차 영역으로 업데이트합니다. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | 이 com.aspose.psd.Region을 지정된 com.aspose.psd.RectangleF 구조와의 교차 영역으로 업데이트합니다. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | 이 com.aspose.psd.Region을 지정된 com.aspose.psd.region와의 교차 영역으로 업데이트합니다. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | 지정된 그리기 표면에서 이 com.aspose.psd.Region이 비어 있는 내부를 가지고 있는지 테스트합니다. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | 지정된 그리기 표면에서 지정된 com.aspose.psd.Region이 이 com.aspose.psd.Region과 동일한지 테스트합니다. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | 지정된 그리기 표면에서 이 com.aspose.psd.Region이 무한한 내부를 가지고 있는지 테스트합니다. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | 지정된 com.aspose.psd.Point 구조가 이 com.aspose.psd.region에 포함되는지 테스트합니다. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | 지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.Point 구조가 이 com.aspose.psd.Region에 포함되는지 테스트합니다. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | 지정된 com.aspose.psd.PointF 구조가 이 com.aspose.psd.region에 포함되는지 테스트합니다. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | 지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.PointF 구조가 이 com.aspose.psd.Region에 포함되는지 테스트합니다. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | 지정된 com.aspose.psd.Rectangle 구조의 일부가 이 com.aspose.psd.region에 포함되는지 테스트합니다. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | 지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.Rectangle 구조의 일부가 이 com.aspose.psd.Region에 포함되는지 테스트합니다. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | 지정된 com.aspose.psd.RectangleF 구조의 일부가 이 com.aspose.psd.region에 포함되는지 테스트합니다. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | 지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.RectangleF 구조의 일부가 이 com.aspose.psd.Region에 포함되는지 테스트합니다. |
| [isVisible(float x, float y)](#isVisible-float-float-) | 지정된 점이 이 com.aspose.psd.region 내에 포함되는지 테스트합니다. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.graphics를 사용하여 그린 경우 이 com.aspose.psd.Region 내에 포함되는지 테스트합니다. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 지정된 사각형의 일부가 이 com.aspose.psd.region 내에 포함되는지 테스트합니다. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | 지정된 사각형의 일부가 지정된 com.aspose.psd.graphics를 사용하여 그린 경우 이 com.aspose.psd.Region 내에 포함되는지 테스트합니다. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | 지정된 점이 지정된 com.aspose.psd.Graphics 객체를 사용하여 그린 경우 이 com.aspose.psd.Region 객체 내에 포함되는지 테스트합니다. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 지정된 사각형의 일부가 이 com.aspose.psd.region 내에 포함되는지 테스트합니다. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | 지정된 사각형의 일부가 지정된 com.aspose.psd.graphics를 사용하여 그린 경우 이 com.aspose.psd.Region 내에 포함되는지 테스트합니다. |
| [makeEmpty()](#makeEmpty--) | 이 com.aspose.psd.Region을 빈 내부로 초기화합니다. |
| [makeInfinite()](#makeInfinite--) | 이 com.aspose.psd.Region 객체를 무한한 내부로 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | 변경 시 영역을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | 지정된 com.aspose.psd.matrix에 따라 이 com.aspose.psd.Region을 변환합니다. |
| [translate(float dx, float dy)](#translate-float-float-) | 지정된 양만큼 이 com.aspose.psd.Region의 좌표를 오프셋합니다. |
| [translate(int dx, int dy)](#translate-int-int-) | 지정된 양만큼 이 com.aspose.psd.Region의 좌표를 오프셋합니다. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.graphicsPath의 합집합으로 업데이트합니다. |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.Rectangle 구조의 합집합으로 업데이트합니다. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.RectangleF 구조의 합집합으로 업데이트합니다. |
| [union(Region region)](#union-com.aspose.psd.Region-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.region의 합집합으로 업데이트합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.graphicsPath와의 교차를 제외한 합집합으로 업데이트합니다. |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.Rectangle 구조와의 교차를 제외한 합집합으로 업데이트합니다. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.RectangleF 구조와의 교차를 제외한 합집합으로 업데이트합니다. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | 이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.region와의 교차를 제외한 합집합으로 업데이트합니다. |
### Region() {#Region--}
```
public Region()
```


새로운  T:Aspose.Imaging.Region 를 초기화합니다.

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


지정된  T:Aspose.Imaging.RectangleF  구조에서 새로운  T:Aspose.Imaging.Region  를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 새 T:Aspose.Imaging.Region의 내부를 정의하는 T:Aspose.Imaging.RectangleF 구조입니다. |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


지정된  T:Aspose.Imaging.Rectangle  구조에서 새로운  T:Aspose.Imaging.Region  를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 새 T:Aspose.Imaging.Region의 내부를 정의하는 T:Aspose.Imaging.Rectangle 구조입니다. |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


지정된  T:Aspose.Imaging.GraphicsPath  로 새로운  T:Aspose.Imaging.Region  를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 새 T:Aspose.Imaging.Region을 정의하는 T:Aspose.Imaging.GraphicsPath입니다. |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.GraphicsPath와 교차하지 않는 부분을 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 이 com.aspose.psd.region을 보완하는 com.aspose.psd.GraphicsPath입니다. |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.Rectangle 구조와 교차하지 않는 부분을 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 이 com.aspose.psd.region을 보완하는 com.aspose.psd.Rectangle 구조입니다. |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.RectangleF 구조와 교차하지 않는 부분을 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 이 com.aspose.psd.region을 보완하는 com.aspose.psd.RectangleF 구조입니다. |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.Region과 교차하지 않는 부분을 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 이 com.aspose.psd.Region 객체를 보완하는 com.aspose.psd.Region 객체입니다. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


이 com.aspose.psd.region의 정확한 깊은 복사본을 생성합니다.

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.graphicsPath와 교차하지 않는 내부 부분만 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 이 com.aspose.psd.region에서 제외할 com.aspose.psd.GraphicsPath. |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.Rectangle 구조와 교차하지 않는 내부 부분만 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 이 com.aspose.psd.region에서 제외할 com.aspose.psd.Rectangle 구조체. |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.RectangleF 구조와 교차하지 않는 내부 부분만 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 이 com.aspose.psd.region에서 제외할 com.aspose.psd.RectangleF 구조체. |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


이 com.aspose.psd.Region을 업데이트하여 지정된 com.aspose.psd.region와 교차하지 않는 내부 부분만 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 이 com.aspose.psd.region에서 제외할 com.aspose.psd.Region. |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


region 작업을 가져옵니다.

**Returns:**
com.aspose.internal.RegionAction[] - 영역 작업들.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


이 com.aspose.psd.Region을 지정된 com.aspose.psd.graphicsPath와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 이 com.aspose.psd.region와 교차할 com.aspose.psd.GraphicsPath. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


이 com.aspose.psd.Region을 지정된 com.aspose.psd.Rectangle 구조와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 이 com.aspose.psd.region와 교차할 com.aspose.psd.Rectangle 구조체. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


이 com.aspose.psd.Region을 지정된 com.aspose.psd.RectangleF 구조와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 이 com.aspose.psd.region와 교차할 com.aspose.psd.RectangleF 구조체. |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


이 com.aspose.psd.Region을 지정된 com.aspose.psd.region와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 이 com.aspose.psd.region와 교차할 com.aspose.psd.Region. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


지정된 그리기 표면에서 이 com.aspose.psd.Region이 비어 있는 내부를 가지고 있는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | 그리기 표면을 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - g와 연관된 변환이 적용될 때 이 com.aspose.psd.Region의 내부가 비어 있으면 true; 그렇지 않으면 false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


지정된 그리기 표면에서 지정된 com.aspose.psd.Region이 이 com.aspose.psd.Region과 동일한지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 테스트할 com.aspose.psd.Region. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그리기 표면을 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - g 매개변수와 연관된 변환이 적용될 때 region의 내부가 이 region의 내부와 동일하면 True; 그렇지 않으면 false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


지정된 그리기 표면에서 이 com.aspose.psd.Region이 무한한 내부를 가지고 있는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | 그리기 표면을 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - g와 연관된 변환이 적용될 때 이 com.aspose.psd.Region의 내부가 무한하면 true; 그렇지 않으면 false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


지정된 com.aspose.psd.Point 구조가 이 com.aspose.psd.region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 테스트할 com.aspose.psd.Point 구조체. |

**Returns:**
boolean - point가 이 com.aspose.psd.Region 내에 포함되면 true; 그렇지 않으면 false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.Point 구조가 이 com.aspose.psd.Region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 테스트할 com.aspose.psd.Point 구조체. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - point가 이 com.aspose.psd.Region 내에 포함되면 true; 그렇지 않으면 false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


지정된 com.aspose.psd.PointF 구조가 이 com.aspose.psd.region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 테스트할 com.aspose.psd.PointF 구조체. |

**Returns:**
boolean - point가 이 com.aspose.psd.Region 내에 포함되면 true; 그렇지 않으면 false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.PointF 구조가 이 com.aspose.psd.Region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 테스트할 com.aspose.psd.PointF 구조체. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - point가 이 com.aspose.psd.Region 내에 포함되면 true; 그렇지 않으면 false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


지정된 com.aspose.psd.Rectangle 구조의 일부가 이 com.aspose.psd.region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 테스트할 com.aspose.psd.Rectangle 구조체. |

**Returns:**
boolean - rect의 어느 부분이라도 이 com.aspose.psd.Region 내에 포함되면 true를 반환합니다; 그렇지 않으면 false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.Rectangle 구조의 일부가 이 com.aspose.psd.Region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 테스트할 com.aspose.psd.Rectangle 구조체. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - rect의 어느 부분이라도 이 com.aspose.psd.Region 내에 포함되면 true; 그렇지 않으면 false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


지정된 com.aspose.psd.RectangleF 구조의 일부가 이 com.aspose.psd.region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 테스트할 com.aspose.psd.RectangleF 구조체. |

**Returns:**
boolean - rect의 어느 부분이라도 이 com.aspose.psd.Region 내에 포함되면 true; 그렇지 않으면 false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


지정된 com.aspose.psd.graphics를 사용하여 그릴 때 지정된 com.aspose.psd.RectangleF 구조의 일부가 이 com.aspose.psd.Region에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 테스트할 com.aspose.psd.RectangleF 구조체. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - rect가 이 com.aspose.psd.Region에 포함되면 true; 그렇지 않으면 false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


지정된 점이 이 com.aspose.psd.region 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |

**Returns:**
boolean - 지정된 point가 이 com.aspose.psd.Region에 포함되면 True; 그렇지 않으면 false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


지정된 점이 지정된 com.aspose.psd.graphics를 사용하여 그린 경우 이 com.aspose.psd.Region 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 point가 이 com.aspose.psd.Region에 포함되면 True; 그렇지 않으면 false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


지정된 사각형의 일부가 이 com.aspose.psd.region 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 사각형의 왼쪽 위 모서리의 x좌표. |
| y | float | 테스트할 사각형의 왼쪽 위 모서리의 y좌표. |
| 너비 | float | 테스트할 사각형의 너비. |
| 높이 | float | 테스트할 사각형의 높이. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 com.aspose.psd.Region 객체에 포함될 경우 true; 그렇지 않으면 false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


지정된 사각형의 일부가 지정된 com.aspose.psd.graphics를 사용하여 그린 경우 이 com.aspose.psd.Region 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 사각형의 왼쪽 위 모서리의 x좌표. |
| y | float | 테스트할 사각형의 왼쪽 위 모서리의 y좌표. |
| 너비 | float | 테스트할 사각형의 너비. |
| 높이 | float | 테스트할 사각형의 높이. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 com.aspose.psd.Region에 포함될 경우 true; 그렇지 않으면 false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


지정된 점이 지정된 com.aspose.psd.Graphics 객체를 사용하여 그린 경우 이 com.aspose.psd.Region 객체 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 점이 이 com.aspose.psd.Region에 포함될 경우 true; 그렇지 않으면 false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


지정된 사각형의 일부가 이 com.aspose.psd.region 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 사각형의 왼쪽 위 모서리의 x좌표. |
| y | int | 테스트할 사각형의 왼쪽 위 모서리의 y좌표. |
| 너비 | int | 테스트할 사각형의 너비. |
| 높이 | int | 테스트할 사각형의 높이. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 com.aspose.psd.Region에 포함될 경우 true; 그렇지 않으면 false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


지정된 사각형의 일부가 지정된 com.aspose.psd.graphics를 사용하여 그린 경우 이 com.aspose.psd.Region 내에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 사각형의 왼쪽 위 모서리의 x좌표. |
| y | int | 테스트할 사각형의 왼쪽 위 모서리의 y좌표. |
| 너비 | int | 테스트할 사각형의 너비. |
| 높이 | int | 테스트할 사각형의 높이. |
| g | [Graphics](../../com.aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 com.aspose.psd.Graphics. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 com.aspose.psd.Region에 포함될 경우 true; 그렇지 않으면 false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


이 com.aspose.psd.Region을 빈 내부로 초기화합니다.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


이 com.aspose.psd.Region 객체를 무한한 내부로 초기화합니다.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


변경 시 영역을 가져오거나 설정합니다.

값: 변경 시 영역.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


지정된 com.aspose.psd.matrix에 따라 이 com.aspose.psd.Region을 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 이 com.aspose.psd.region를 변환하는 데 사용되는 com.aspose.psd.Matrix. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


지정된 양만큼 이 com.aspose.psd.Region의 좌표를 오프셋합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | 이 com.aspose.psd.Region을 수평으로 오프셋하는 양. |
| dy | float | 이 com.aspose.psd.Region을 수직으로 오프셋하는 양. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


지정된 양만큼 이 com.aspose.psd.Region의 좌표를 오프셋합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | int | 이 com.aspose.psd.Region을 수평으로 오프셋하는 양. |
| dy | int | 이 com.aspose.psd.Region을 수직으로 오프셋하는 양. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.graphicsPath의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 이 com.aspose.psd.region와 합치기 위한 com.aspose.psd.GraphicsPath. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.Rectangle 구조의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 이 com.aspose.psd.region와 합치기 위한 com.aspose.psd.Rectangle 구조체. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.RectangleF 구조의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 이 com.aspose.psd.region와 합치기 위한 com.aspose.psd.RectangleF 구조체. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.region의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 이 com.aspose.psd.region와 합치기 위한 com.aspose.psd.Region. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.graphicsPath와의 교차를 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 이 com.aspose.psd.region와 XOR 연산을 수행할 com.aspose.psd.GraphicsPath. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.Rectangle 구조와의 교차를 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 이 com.aspose.psd.region와 XOR 연산을 수행할 com.aspose.psd.Rectangle 구조체. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.RectangleF 구조와의 교차를 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 이 com.aspose.psd.region와 XOR 연산을 수행할 com.aspose.psd.RectangleF 구조체. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


이 com.aspose.psd.Region을 자체와 지정된 com.aspose.psd.region와의 교차를 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 이 com.aspose.psd.region와 XOR 연산을 수행할 com.aspose.psd.Region. |

