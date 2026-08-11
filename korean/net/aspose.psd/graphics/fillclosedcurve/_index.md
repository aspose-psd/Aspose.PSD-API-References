---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. PointF 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 장력 0.5와 Alternate 채우기 모드를 사용합니다."
type: docs
weight: 350
url: /ko/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

[`PointF`](../../pointf/) 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 장력 0.5와 Alternate 채우기 모드를 사용합니다.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| points | PointF[] | 스플라인을 정의하는 [`PointF`](../../pointf/) 구조의 배열입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

지정된 채우기 모드를 사용하여 [`PointF`](../../pointf/) 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 장력 0.5를 사용합니다.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| points | PointF[] | 스플라인을 정의하는 [`PointF`](../../pointf/) 구조의 배열입니다. |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

지정된 채우기 모드와 장력을 사용하여 [`PointF`](../../pointf/) 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | 채우기의 특성을 결정하는 [`Brush`](../../brush/)입니다. |
| points | PointF[] | 스플라인을 정의하는 [`PointF`](../../pointf/) 구조의 배열입니다. |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |
| 장력 | 단일 | 곡선의 장력을 지정하는 0.0F 이상 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

[`Point`](../../point/) 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 장력 0.5와 Alternate 채우기 모드를 사용합니다.

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| points | Point[] | 스플라인을 정의하는 [`Point`](../../point/) 구조체 배열. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

지정된 채우기 모드를 사용하여 [`Point`](../../point/) 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 장력 0.5를 사용합니다.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| points | Point[] | 스플라인을 정의하는 [`Point`](../../point/) 구조체 배열. |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

지정된 채우기 모드와 장력을 사용하여 [`Point`](../../point/) 구조체 배열에 의해 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | Brush | `[`Brush`](../../brush/)`는 채우기의 특성을 결정합니다. |
| points | Point[] | 스플라인을 정의하는 [`Point`](../../point/) 구조체 배열. |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |
| 장력 | 단일 | 곡선의 장력을 지정하는 0.0F 이상 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


