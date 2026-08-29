---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Graphics-metod. Ritar en båge som representerar en del av en ellips angiven av ett par koordinater, en bredd och en höjd."
type: docs
weight: 170
url: /sv/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil för bågen. |
| x | Single | X-koordinaten för den övre vänstra hörnet av rektangeln som definierar ellipsen. |
| y | Single | Y-koordinaten för den övre vänstra hörnet av rektangeln som definierar ellipsen. |
| bredd | Single | Bredden på rektangeln som definierar ellipsen. |
| höjd | Single | Höjden på rektangeln som definierar ellipsen. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från parametern *startAngle* till slutpunkten för bågen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. |

### Se även

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Ritar en båge som representerar en del av en ellips angiven av en [`RectangleF`](../../rectanglef/) struktur.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) struktur som definierar gränserna för ellipsen. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från parametern *startAngle* till slutpunkten för bågen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null |

### Se även

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil för bågen. |
| x | Int32 | X-koordinaten för den övre vänstra hörnet av rektangeln som definierar ellipsen. |
| y | Int32 | Y-koordinaten för den övre vänstra hörnet av rektangeln som definierar ellipsen. |
| bredd | Int32 | Bredden på rektangeln som definierar ellipsen. |
| höjd | Int32 | Höjden på rektangeln som definierar ellipsen. |
| startAngle | Int32 | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweepAngle | Int32 | Vinkel i grader mätt medurs från parametern *startAngle* till slutpunkten för bågen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. |

### Se även

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Ritar en båge som representerar en del av en ellips angiven av en [`Rectangle`](../../rectangle/) struktur.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) struktur som definierar gränserna för ellipsen. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från parametern *startAngle* till slutpunkten för bågen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. |

### Se även

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


