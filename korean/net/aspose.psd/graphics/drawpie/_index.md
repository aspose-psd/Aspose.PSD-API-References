---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. RectangleF 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다."
type: docs
weight: 290
url: /ko/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

`[`RectangleF`](../../rectanglef/)` 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | 파이 모양의 색상, 너비 및 스타일을 결정하는 [`Pen`](../../pen/)입니다. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 구조체는 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | 단일 | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |
| sweepAngle | 단일 | *startAngle* 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |

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

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | 파이 모양의 색상, 너비 및 스타일을 결정하는 [`Pen`](../../pen/)입니다. |
| x | 단일 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x좌표입니다. |
| y | 단일 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y좌표입니다. |
| width | 단일 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| height | 단일 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | 단일 | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |
| sweepAngle | 단일 | *startAngle* 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

파이 모양을 그립니다. 이 모양은 [`Rectangle`](../../rectangle/) 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의됩니다.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | 파이 모양의 색상, 너비 및 스타일을 결정하는 [`Pen`](../../pen/)입니다. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 구조체는 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | 단일 | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |
| sweepAngle | 단일 | *startAngle* 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |

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

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | 파이 모양의 색상, 너비 및 스타일을 결정하는 [`Pen`](../../pen/)입니다. |
| x | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x좌표입니다. |
| y | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y좌표입니다. |
| width | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| height | Int32 | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | Int32 | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |
| sweepAngle | Int32 | *startAngle* 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정된 각도(도)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


