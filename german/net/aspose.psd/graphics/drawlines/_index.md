---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet eine Reihe von Liniensegmenten, die ein Array von Point-Strukturen verbinden."
type: docs
weight: 270
url: /de/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [`Point`](../../point/) Strukturen verbinden.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |
| ArgumentException | Das *points*-Array enthält weniger als 2 Punkte. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [`PointF`](../../pointf/) Strukturen verbinden.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |
| ArgumentException | Das *points*-Array enthält weniger als 2 Punkte. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


