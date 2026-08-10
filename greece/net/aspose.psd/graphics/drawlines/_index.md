---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Graphics. Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών Point"
type: docs
weight: 270
url: /el/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα από δομές [`Point`](../../point/).

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των τμημάτων γραμμής. |
| points | Point[] | Πίνακας από δομές [`Point`](../../point/) που αντιπροσωπεύουν τα σημεία προς σύνδεση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |
| ArgumentException | Ο πίνακας *points* περιέχει λιγότερα από 2 σημεία. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα από δομές [`PointF`](../../pointf/).

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των τμημάτων γραμμής. |
| points | PointF[] | Πίνακας από δομές [`PointF`](../../pointf/) που αντιπροσωπεύουν τα σημεία προς σύνδεση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |
| ArgumentException | Ο πίνακας *points* περιέχει λιγότερα από 2 σημεία. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


