---
title: Graphics.DrawPie
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 에 의해 지정된 타원에 의해 정의된 파이 모양을 그립니다.RectangleF 구조 및 두 개의 방사형 라인.
type: docs
weight: 280
url: /ko/net/aspose.psd/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

에 의해 지정된 타원에 의해 정의된 파이 모양을 그립니다.[`RectangleF`](../../rectanglef/) 구조 및 두 개의 방사형 라인.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 파이 모양의 색상, 너비 및 스타일을 결정합니다. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타내는 구조체입니다. |
| startAngle | Single | x축에서 파이 모양의 첫 번째 면까지 시계 방향으로 측정한 각도입니다. |
| sweepAngle | Single | 에서 시계 방향으로 도 단위로 측정한 각도*startAngle* 파이 모양의 두 번째 면에 대한 매개변수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

좌표 쌍, 너비, 높이 및 두 개의 방사형 선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 파이 모양의 색상, 너비 및 스타일을 결정합니다. |
| x | Single | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모퉁이의 x 좌표입니다. |
| y | Single | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모퉁이에 대한 y좌표입니다. |
| width | Single | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| height | Single | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | Single | x축에서 파이 모양의 첫 번째 면까지 시계 방향으로 측정한 각도입니다. |
| sweepAngle | Single | 에서 시계 방향으로 도 단위로 측정한 각도*startAngle* 파이 모양의 두 번째 면에 대한 매개변수입니다. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

에 의해 지정된 타원에 의해 정의된 파이 모양을 그립니다.[`Rectangle`](../../rectangle/) 구조 및 두 개의 방사형 라인.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 파이 모양의 색상, 너비 및 스타일을 결정합니다. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타내는 구조체입니다. |
| startAngle | Single | x축에서 파이 모양의 첫 번째 면까지 시계 방향으로 측정한 각도입니다. |
| sweepAngle | Single | 에서 시계 방향으로 도 단위로 측정한 각도*startAngle* 파이 모양의 두 번째 면에 대한 매개변수입니다. |

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

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

좌표 쌍, 너비, 높이 및 두 개의 방사형 선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 파이 모양의 색상, 너비 및 스타일을 결정합니다. |
| x | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모퉁이의 x 좌표입니다. |
| y | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모퉁이에 대한 y좌표입니다. |
| width | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| height | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | Int32 | x축에서 파이 모양의 첫 번째 면까지 시계 방향으로 측정한 각도입니다. |
| sweepAngle | Int32 | 에서 시계 방향으로 도 단위로 측정한 각도*startAngle* 파이 모양의 두 번째 면에 대한 매개변수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


