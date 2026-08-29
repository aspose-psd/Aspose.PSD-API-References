---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von PointF-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Alternativ-Füllmodus."
type: docs
weight: 350
url: /de/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von [`PointF`](../../pointf/) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Alternativ-Füllmodus.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von [`PointF`](../../pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Spline definieren. |
| fillmode | FillMode | Mitglied der [`FillMode`](../../fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von [`PointF`](../../pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus und der Spannung.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | Ein [`Brush`](../../brush/) der die Eigenschaften der Füllung bestimmt. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Spline definieren. |
| fillmode | FillMode | Mitglied der [`FillMode`](../../fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | Single | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von [`Point`](../../point/) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Alternativ-Füllmodus.

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von [`Point`](../../point/) Strukturen, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die Spline definieren. |
| fillmode | FillMode | Mitglied der [`FillMode`](../../fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, definiert durch ein Array von [`Point`](../../point/) Strukturen, unter Verwendung des angegebenen Füllmodus und der Spannung.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die Spline definieren. |
| fillmode | FillMode | Mitglied der [`FillMode`](../../fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | Single | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


