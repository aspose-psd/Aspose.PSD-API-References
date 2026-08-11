---
title: "Region.IsVisible"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Region 메서드. 지정된 점이 이 Region에 포함되는지 테스트합니다."
type: docs
weight: 100
url: /ko/net/aspose.psd/region/isvisible/
---
{{< psd/tize >}}
## IsVisible(float, float) {#isvisible_11}

지정된 점이 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(float x, float y)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | 단일 | 테스트할 점의 x좌표. |
| y | 단일 | 테스트할 점의 y좌표. |

### 반환 값

지정된 점이 이 [`Region`](../)에 포함되면 true, 그렇지 않으면 false.

### 또 보기

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF) {#isvisible_2}

지정된 [`PointF`](../../pointf/) 구조가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(PointF point)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | PointF | 테스트할 [`PointF`](../../pointf/) 구조. |

### 반환 값

*point*가 이 [`Region`](../)에 포함되면 true, 그렇지 않으면 false.

### 또 보기

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

지정된 [`Graphics`](../../graphics/)를 사용하여 그린 경우, 지정된 점이 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | 단일 | 테스트할 점의 x좌표. |
| y | 단일 | 테스트할 점의 y좌표. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

지정된 점이 이 [`Region`](../)에 포함되면 true, 그렇지 않으면 false.

### 또 보기

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

지정된 [`Graphics`](../../graphics/)를 사용하여 그린 경우, 지정된 [`PointF`](../../pointf/) 구조가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | PointF | 테스트할 [`PointF`](../../pointf/) 구조. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

*point*가 이 [`Region`](../)에 포함되면 true, 그렇지 않으면 false.

### 또 보기

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

지정된 사각형의 일부라도 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | 단일 | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | 단일 | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | 단일 | 테스트할 사각형의 너비. |
| height | 단일 | 테스트할 사각형의 높이. |

### 반환 값

지정된 사각형의 일부라도 이 [`Region`](../) 객체에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

지정된 [`RectangleF`](../../rectanglef/) 구조의 일부가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(RectangleF rect)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | RectangleF | 테스트할 [`RectangleF`](../../rectanglef/) 구조. |

### 반환 값

 *rect*의 일부라도 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

지정된 사각형을 지정된 [`Graphics`](../../graphics/)로 그렸을 때, 그 일부가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | 단일 | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | 단일 | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | 단일 | 테스트할 사각형의 너비. |
| height | 단일 | 테스트할 사각형의 높이. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

지정된 사각형의 일부라도 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

지정된 [`RectangleF`](../../rectanglef/) 구조를 지정된 [`Graphics`](../../graphics/)로 그렸을 때, 그 일부가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | RectangleF | 테스트할 [`RectangleF`](../../rectanglef/) 구조. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

*rect*가 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

지정된 [`Graphics`](../../graphics/) 객체를 사용해 그렸을 때, 지정된 점이 이 [`Region`](../) 객체에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Int32 | 테스트할 점의 x좌표. |
| y | Int32 | 테스트할 점의 y좌표. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

지정된 점이 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point) {#isvisible}

지정된 [`Point`](../../point/) 구조가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(Point point)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | Point | 테스트할 [`Point`](../../point/) 구조. |

### 반환 값

*point*가 이 [`Region`](../)에 포함되면 true, 그렇지 않으면 false.

### 또 보기

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

지정된 [`Graphics`](../../graphics/)를 사용해 그렸을 때, 지정된 [`Point`](../../point/) 구조가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(Point point, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | Point | 테스트할 [`Point`](../../point/) 구조. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

*point*가 이 [`Region`](../)에 포함되면 true, 그렇지 않으면 false.

### 또 보기

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

지정된 사각형의 일부라도 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Int32 | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | Int32 | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | Int32 | 테스트할 사각형의 너비. |
| height | Int32 | 테스트할 사각형의 높이. |

### 반환 값

지정된 사각형의 일부라도 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

지정된 [`Rectangle`](../../rectangle/) 구조의 일부가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(Rectangle rect)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 테스트할 [`Rectangle`](../../rectangle/) 구조. |

### 반환 값

이 메서드는 *rect*의 일부라도 이 [`Region`](../)에 포함될 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.

### 또 보기

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

지정된 사각형을 지정된 [`Graphics`](../../graphics/)로 그렸을 때, 그 일부가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Int32 | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | Int32 | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | Int32 | 테스트할 사각형의 너비. |
| height | Int32 | 테스트할 사각형의 높이. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

지정된 사각형의 일부라도 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

지정된 [`Rectangle`](../../rectangle/) 구조를 지정된 [`Graphics`](../../graphics/)로 그렸을 때, 그 일부가 이 [`Region`](../)에 포함되는지 테스트합니다.

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 테스트할 [`Rectangle`](../../rectangle/) 구조. |
| g | Graphics | 그래픽 컨텍스트를 나타내는 [`Graphics`](../../graphics/). |

### 반환 값

*rect*의 일부라도 이 [`Region`](../)에 포함될 경우 true; 그렇지 않으면 false.

### 또 보기

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


