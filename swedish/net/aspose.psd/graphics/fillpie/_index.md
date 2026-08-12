---
title: "Graphics.FillPie"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Graphics-metod. Fyller innanmätet av en pajsektion som definieras av en ellips specificerad av en RectangleF-struktur och två radiala linjer."
type: docs
weight: 380
url: /sv/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Fyller innanmätet av en pajsektion som definieras av en ellips specificerad av en [`RectangleF`](../../rectanglef/) struktur och två radiala linjer.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) som bestämmer egenskaperna för fyllningen. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) struktur som representerar den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från *startAngle*-parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *brush* är null. |

### Se även

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Fyller innanmätet av en pajsektion som definieras av en ellips specificerad av en [`RectangleF`](../../rectanglef/) struktur och två radiala linjer.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) som bestämmer egenskaperna för fyllningen. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) struktur som representerar den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från *startAngle*-parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *brush* är null. |

### Se även

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) som bestämmer egenskaperna för fyllningen. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| bredd | Single | Bredden på den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| höjd | Single | Höjden på den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från *startAngle*-parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *brush* är null. |

### Se även

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) som bestämmer egenskaperna för fyllningen. |
| x | Int32 | X-koordinaten för det övre vänstra hörnet av den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| y | Int32 | Y-koordinaten för det övre vänstra hörnet av den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| bredd | Int32 | Bredden på den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| höjd | Int32 | Höjden på den omslutande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| startAngle | Int32 | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | Int32 | Vinkel i grader mätt medurs från *startAngle*-parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *brush* är null. |

### Se även

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


