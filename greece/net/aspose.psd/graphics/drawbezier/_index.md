---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Graphics. Σχεδίαζει μια καμπύλη Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία."
type: docs
weight: 180
url: /el/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| x1 | Single | Η x-συντεταγμένη του αρχικού σημείου της καμπύλης. |
| y1 | Single | Η y-συντεταγμένη του αρχικού σημείου της καμπύλης. |
| x2 | Single | Η x-συντεταγμένη του πρώτου σημείου ελέγχου της καμπύλης. |
| y2 | Single | Η y-συντεταγμένη του πρώτου σημείου ελέγχου της καμπύλης. |
| x3 | Single | Η x-συντεταγμένη του δεύτερου σημείου ελέγχου της καμπύλης. |
| y3 | Single | Η y-συντεταγμένη του δεύτερου σημείου ελέγχου της καμπύλης. |
| x4 | Single | Η x-συντεταγμένη του τελικού σημείου της καμπύλης. |
| y4 | Single | Η y-συντεταγμένη του τελικού σημείου της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Σχεδίαζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [`PointF`](../../pointf/).

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | PointF | `[`PointF`](../../pointf/) δομή που αντιπροσωπεύει το αρχικό σημείο της καμπύλης.` |
| pt2 | PointF | `[`PointF`](../../pointf/) δομή που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη.` |
| pt3 | PointF | `[`PointF`](../../pointf/) δομή που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη.` |
| pt4 | PointF | `[`PointF`](../../pointf/) δομή που αντιπροσωπεύει το τελικό σημείο της καμπύλης.` |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [`Point`](../../point/).

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/) δομή που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης.` |
| pt1 | Point | `[`Point`](../../point/) δομή που αντιπροσωπεύει το αρχικό σημείο της καμπύλης.` |
| pt2 | Point | `[`Point`](../../point/) δομή που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη.` |
| pt3 | Point | `[`Point`](../../point/) δομή που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη.` |
| pt4 | Point | `[`Point`](../../point/) δομή που αντιπροσωπεύει το τελικό σημείο της καμπύλης.` |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


