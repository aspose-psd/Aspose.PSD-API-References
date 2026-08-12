---
title: "Region.IsVisible"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Region-metoden. Testar om den angivna punkten finns inom detta Region"
type: docs
weight: 100
url: /sv/net/aspose.psd/region/isvisible/
---
{{< psd/tize >}}
## IsVisible(float, float) {#isvisible_11}

Testar om den angivna punkten finns inom detta [`Region`](../).

```csharp
public bool IsVisible(float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Single | X-koordinaten för punkten som ska testas. |
| y | Single | Y-koordinaten för punkten som ska testas. |

### Returvärde

Sant när den angivna punkten finns inom detta [`Region`](../); annars falskt.

### Se även

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF) {#isvisible_2}

Testar om den angivna [`PointF`](../../pointf/) strukturen finns inom detta [`Region`](../).

```csharp
public bool IsVisible(PointF point)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | PointF | Den [`PointF`](../../pointf/) strukturen att testa. |

### Returvärde

true när *point* finns inom detta [`Region`](../); annars false.

### Se även

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

Testar om den angivna punkten finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Single | X-koordinaten för punkten som ska testas. |
| y | Single | Y-koordinaten för punkten som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

Sant när den angivna punkten finns inom detta [`Region`](../); annars falskt.

### Se även

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

Testar om den angivna [`PointF`](../../pointf/) strukturen finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | PointF | Den [`PointF`](../../pointf/) strukturen att testa. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när *point* finns inom detta [`Region`](../); annars false.

### Se även

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

Testar om någon del av den angivna rektangeln finns inom detta [`Region`](../).

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Single | X-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| y | Single | Y-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| bredd | Single | Bredden på rektangeln som ska testas. |
| höjd | Single | Höjden på rektangeln som ska testas. |

### Returvärde

true när någon del av den angivna rektangeln finns inom detta [`Region`](../)-objekt; annars false.

### Se även

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

Testar om någon del av den angivna [`RectangleF`](../../rectanglef/)-strukturen finns inom detta [`Region`](../).

```csharp
public bool IsVisible(RectangleF rect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | RectangleF | Den [`RectangleF`](../../rectanglef/)-strukturen som ska testas. |

### Returvärde

true när någon del av *rect* finns inom detta [`Region`](../); annars false.

### Se även

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

Testar om någon del av den angivna rektangeln finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Single | X-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| y | Single | Y-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| bredd | Single | Bredden på rektangeln som ska testas. |
| höjd | Single | Höjden på rektangeln som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när någon del av den angivna rektangeln finns inom detta [`Region`](../); annars false.

### Se även

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

Testar om någon del av den angivna [`RectangleF`](../../rectanglef/)-strukturen finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | RectangleF | Den [`RectangleF`](../../rectanglef/)-strukturen som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när *rect* finns inom detta [`Region`](../); annars false.

### Se även

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

Testar om den angivna punkten finns inom detta [`Region`](../)-objekt när den ritas med det angivna [`Graphics`](../../graphics/)-objektet.

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Int32 | X-koordinaten för punkten som ska testas. |
| y | Int32 | Y-koordinaten för punkten som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när den angivna punkten finns inom detta [`Region`](../); annars false.

### Se även

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point) {#isvisible}

Testar om den angivna [`Point`](../../point/)-strukturen finns inom detta [`Region`](../).

```csharp
public bool IsVisible(Point point)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | Point | Den [`Point`](../../point/)-strukturen som ska testas. |

### Returvärde

true när *point* finns inom detta [`Region`](../); annars false.

### Se även

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

Testar om den angivna [`Point`](../../point/)-strukturen finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(Point point, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | Point | Den [`Point`](../../point/)-strukturen som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när *point* finns inom detta [`Region`](../); annars false.

### Se även

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

Testar om någon del av den angivna rektangeln finns inom detta [`Region`](../).

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Int32 | X-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| y | Int32 | Y-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| bredd | Int32 | Bredden på rektangeln som ska testas. |
| höjd | Int32 | Höjden på rektangeln som ska testas. |

### Returvärde

true när någon del av den angivna rektangeln finns inom detta [`Region`](../); annars false.

### Se även

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

Testar om någon del av den angivna [`Rectangle`](../../rectangle/)-strukturen finns inom detta [`Region`](../).

```csharp
public bool IsVisible(Rectangle rect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den [`Rectangle`](../../rectangle/)-strukturen som ska testas. |

### Returvärde

Denna metod returnerar true när någon del av *rect* finns inom detta [`Region`](../); annars false.

### Se även

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

Testar om någon del av den angivna rektangeln finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Int32 | X-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| y | Int32 | Y-koordinaten för det övre vänstra hörnet på rektangeln som ska testas. |
| bredd | Int32 | Bredden på rektangeln som ska testas. |
| höjd | Int32 | Höjden på rektangeln som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när någon del av den angivna rektangeln finns inom detta [`Region`](../); annars false.

### Se även

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

Testar om någon del av den angivna [`Rectangle`](../../rectangle/)-strukturen finns inom detta [`Region`](../) när den ritas med den angivna [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den [`Rectangle`](../../rectangle/)-strukturen som ska testas. |
| g | Graphics | Ett [`Graphics`](../../graphics/) som representerar en grafikkontext. |

### Returvärde

true när någon del av *rect* finns inom detta [`Region`](../); annars false.

### Se även

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


