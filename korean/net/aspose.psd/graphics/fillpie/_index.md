---
title: "Graphics.FillPie"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. RectangleF 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다."
type: docs
weight: 380
url: /ko/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

두 개의 방사선과 [`RectangleF`](../../rectanglef/) 구조로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| rect | Rectangle | `[`Rectangle`](../../rectangle/)` 구조는 파이 섹션이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | 단일 | x축에서 파이 섹션의 첫 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | 단일 | *startAngle* 매개변수에서 파이 섹션의 두 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

두 개의 방사선과 [`RectangleF`](../../rectanglef/) 구조로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| rect | RectangleF | `[`RectangleF`](../../rectanglef/)` 구조는 파이 섹션이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | 단일 | x축에서 파이 섹션의 첫 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | 단일 | *startAngle* 매개변수에서 파이 섹션의 두 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| x | 단일 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | 단일 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| width | 단일 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| height | 단일 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | 단일 | x축에서 파이 섹션의 첫 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | 단일 | *startAngle* 매개변수에서 파이 섹션의 두 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| x | Int32 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | Int32 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| width | Int32 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| height | Int32 | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | Int32 | x축에서 파이 섹션의 첫 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | Int32 | *startAngle* 매개변수에서 파이 섹션의 두 번째 면까지 시계 방향으로 측정한 각도(도)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


