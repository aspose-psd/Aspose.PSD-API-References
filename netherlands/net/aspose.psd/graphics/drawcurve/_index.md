---
title: Graphics.DrawCurve
second_title: Aspose.PSD voor .NET API-referentie
description: Graphics methode. Tekent een kardinale spline door een gespecificeerde reeks vanPointF structuren. Deze methode gebruikt een standaardspanning van 05.
type: docs
weight: 200
url: /nl/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../../pointf/) structuren. Deze methode gebruikt een standaardspanning van 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | PointF[] | Reeks van[`PointF`](../../pointf/) structuren die de spline definiëren. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../../pointf/) constructies met een gespecificeerde spanning.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | PointF[] | Reeks van[`PointF`](../../pointf/) structuren die de punten vertegenwoordigen die de curve definiëren. |
| tension | Single | Waarde groter dan of gelijk aan 0,0F die de spanning van de curve specificeert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../../pointf/) structuren. De tekening begint offset vanaf het begin van de array. Deze methode gebruikt een standaardspanning van 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | PointF[] | Reeks van[`PointF`](../../pointf/) structuren die de spline definiëren. |
| offset | Int32 | Verschuiving vanaf het eerste element in de array van de*points* parameter naar het startpunt in de curve. |
| numberOfSegments | Int32 | Aantal segmenten na het startpunt dat in de curve moet worden opgenomen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../../pointf/) constructies met een bepaalde spanning. De tekening begint offset vanaf het begin van de array.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | PointF[] | Reeks van[`PointF`](../../pointf/) structuren die de spline definiëren. |
| offset | Int32 | Verschuiving vanaf het eerste element in de array van de*points* parameter naar het startpunt in de curve. |
| numberOfSegments | Int32 | Aantal segmenten na het startpunt dat in de curve moet worden opgenomen. |
| tension | Single | Waarde groter dan of gelijk aan 0,0F die de spanning van de curve specificeert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Tekent een kardinale spline door een gespecificeerde reeks van[`Point`](../../point/) structuren.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | Point[] | Reeks van[`Point`](../../point/) structuren die de spline definiëren. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Tekent een kardinale spline door een gespecificeerde reeks van[`Point`](../../point/) constructies met een gespecificeerde spanning.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | Point[] | Reeks van[`Point`](../../point/) structuren die de spline definiëren. |
| tension | Single | Waarde groter dan of gelijk aan 0,0F die de spanning van de curve specificeert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Tekent een kardinale spline door een gespecificeerde reeks van[`Point`](../../point/) constructies met een gespecificeerde spanning.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | Point[] | Reeks van[`Point`](../../point/) structuren die de spline definiëren. |
| offset | Int32 | Verschuiving vanaf het eerste element in de array van de*points* parameter naar het startpunt in de curve. |
| numberOfSegments | Int32 | Aantal segmenten na het startpunt dat in de curve moet worden opgenomen. |
| tension | Single | Waarde groter dan of gelijk aan 0,0F die de spanning van de curve specificeert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)


