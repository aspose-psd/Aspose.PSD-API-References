---
title: Graphics.DrawCurve
second_title: Aspose.PSD för .NET API-referens
description: Graphics metod. Ritar en kardinal spline genom en specificerad array avPointF strukturer. Den här metoden använder en standardspänning på 0.5.
type: docs
weight: 200
url: /sv/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf/) strukturer. Den här metoden använder en standardspänning på 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf/) strukturer som definierar spline. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf/) strukturer med en specificerad spänning.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf/) strukturer som representerar de punkter som definierar kurvan. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf/) strukturer. Ritningen börjar offset från början av arrayen. Denna metod använder en standardspänning på 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf/) strukturer som definierar spline. |
| offset | Int32 | Offset från det första elementet i arrayen av*points* parametern till startpunkten i kurvan. |
| numberOfSegments | Int32 | Antal segment efter startpunkten som ska inkluderas i kurvan. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf/) strukturer med en specificerad spänning. Ritningen börjar offset från början av arrayen.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf/) strukturer som definierar spline. |
| offset | Int32 | Offset från det första elementet i arrayen av*points* parametern till startpunkten i kurvan. |
| numberOfSegments | Int32 | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Ritar en kardinal spline genom en specificerad array av[`Point`](../../point/) strukturer.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | Point[] | Uppsättning av[`Point`](../../point/) strukturer som definierar spline. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Ritar en kardinal spline genom en specificerad array av[`Point`](../../point/) strukturer med en specificerad spänning.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | Point[] | Uppsättning av[`Point`](../../point/) strukturer som definierar spline. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Ritar en kardinal spline genom en specificerad array av[`Point`](../../point/) strukturer med en specificerad spänning.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer kurvans färg, bredd och höjd. |
| points | Point[] | Uppsättning av[`Point`](../../point/) strukturer som definierar spline. |
| offset | Int32 | Offset från det första elementet i arrayen av*points* parametern till startpunkten i kurvan. |
| numberOfSegments | Int32 | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)


