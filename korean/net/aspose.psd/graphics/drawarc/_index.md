---
title: Graphics.DrawArc
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 좌표 쌍 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.
type: docs
weight: 160
url: /ko/net/aspose.psd/graphics/drawarc/
---
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 호의 색상, 너비 및 스타일을 결정합니다. |
| x | Single | 타원을 정의하는 사각형의 왼쪽 위 모퉁이에 대한 x 좌표입니다. |
| y | Single | 타원을 정의하는 사각형의 왼쪽 위 모서리에 대한 y좌표입니다. |
| width | Single | 타원을 정의하는 사각형의 너비입니다. |
| height | Single | 타원을 정의하는 사각형의 높이입니다. |
| startAngle | Single | x축에서 호의 시작점까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | Single | 에서 시계 방향으로 측정한 도 단위의 각도*startAngle* 호의 끝점에 대한 매개변수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

에 의해 지정된 타원의 일부를 나타내는 호를 그립니다.[`RectangleF`](../../rectanglef/)구조.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 호의 색상, 너비 및 스타일을 결정합니다. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 타원의 경계를 정의하는 구조. |
| startAngle | Single | x축에서 호의 시작점까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | Single | 에서 시계 방향으로 측정한 도 단위의 각도*startAngle* 호의 끝점에 대한 매개변수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다 |

### 또한보십시오

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 호의 색상, 너비 및 스타일을 결정합니다. |
| x | Int32 | 타원을 정의하는 사각형의 왼쪽 위 모퉁이에 대한 x 좌표입니다. |
| y | Int32 | 타원을 정의하는 사각형의 왼쪽 위 모서리에 대한 y좌표입니다. |
| width | Int32 | 타원을 정의하는 사각형의 너비입니다. |
| height | Int32 | 타원을 정의하는 사각형의 높이입니다. |
| startAngle | Int32 | x축에서 호의 시작점까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | Int32 | 에서 시계 방향으로 측정한 도 단위의 각도*startAngle* 호의 끝점에 대한 매개변수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

에 의해 지정된 타원의 일부를 나타내는 호를 그립니다.[`Rectangle`](../../rectangle/)구조.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 호의 색상, 너비 및 스타일을 결정합니다. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) 타원의 경계를 정의하는 구조. |
| startAngle | Single | x축에서 호의 시작점까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | Single | 에서 시계 방향으로 측정한 도 단위의 각도*startAngle* 호의 끝점에 대한 매개변수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


