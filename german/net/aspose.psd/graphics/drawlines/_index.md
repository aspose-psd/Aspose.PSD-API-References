---
title: Graphics.DrawLines
second_title: Aspose.PSD für .NET-API-Referenz
description: Graphics methode. Zeichnet eine Reihe von Liniensegmenten die ein Array von verbindenPoint Strukturen.
type: docs
weight: 260
url: /de/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Zeichnet eine Reihe von Liniensegmenten, die ein Array von verbinden[`Point`](../../point/) Strukturen.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die Farbe, Breite und Stil der Liniensegmente bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |
| ArgumentException | Der*points* Array enthält weniger als 2 Punkte. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Zeichnet eine Reihe von Liniensegmenten, die ein Array von verbinden[`PointF`](../../pointf/) Strukturen.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die Farbe, Breite und Stil der Liniensegmente bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |
| ArgumentException | Der*points* Array enthält weniger als 2 Punkte. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)


