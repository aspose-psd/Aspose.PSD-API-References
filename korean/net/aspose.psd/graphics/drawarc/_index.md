---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. 좌표 쌍과 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다."
type: docs
weight: 170
url: /ko/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은 호의 색상, 너비 및 스타일을 결정합니다. |
| x | 단일 | 타원을 정의하는 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | 단일 | 타원을 정의하는 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | 단일 | 타원을 정의하는 사각형의 너비. |
| height | 단일 | 타원을 정의하는 사각형의 높이. |
| startAngle | 단일 | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweepAngle | 단일 | *startAngle* 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

[`RectangleF`](../../rectanglef/) 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은 호의 색상, 너비 및 스타일을 결정합니다. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 구조체는 타원의 경계를 정의합니다. |
| startAngle | 단일 | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweepAngle | 단일 | *startAngle* 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은 호의 색상, 너비 및 스타일을 결정합니다. |
| x | Int32 | 타원을 정의하는 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | Int32 | 타원을 정의하는 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | Int32 | 타원을 정의하는 사각형의 너비. |
| height | Int32 | 타원을 정의하는 사각형의 높이. |
| startAngle | Int32 | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweepAngle | Int32 | *startAngle* 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

[`Rectangle`](../../rectangle/) 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은 호의 색상, 너비 및 스타일을 결정합니다. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) 구조체는 타원의 경계를 정의합니다. |
| startAngle | 단일 | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweepAngle | 단일 | *startAngle* 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


