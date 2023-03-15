---
title: Graphics.DrawBezier
second_title: Aspose.PSD για Αναφορά API .NET
description: Graphics μέθοδος. Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία.
type: docs
weight: 170
url: /el/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| x1 | Single | Η συντεταγμένη x του σημείου εκκίνησης της καμπύλης. |
| y1 | Single | Η συντεταγμένη y του σημείου εκκίνησης της καμπύλης. |
| x2 | Single | Η συντεταγμένη x του πρώτου σημείου ελέγχου της καμπύλης. |
| y2 | Single | Η συντεταγμένη y του πρώτου σημείου ελέγχου της καμπύλης. |
| x3 | Single | Η συντεταγμένη x του δεύτερου σημείου ελέγχου της καμπύλης. |
| y3 | Single | Η συντεταγμένη y του δεύτερου σημείου ελέγχου της καμπύλης. |
| x4 | Single | Η συντεταγμένη x του τερματικού σημείου της καμπύλης. |
| y4 | Single | Η συντεταγμένη y του τερματικού σημείου της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα[`PointF`](../../pointf/) δομές.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | PointF | [`PointF`](../../pointf/) δομή που αντιπροσωπεύει το σημείο εκκίνησης της καμπύλης. |
| pt2 | PointF | [`PointF`](../../pointf/) δομή που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη. |
| pt3 | PointF | [`PointF`](../../pointf/) δομή που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη. |
| pt4 | PointF | [`PointF`](../../pointf/) δομή που αντιπροσωπεύει το τελικό σημείο της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα[`Point`](../../point/) δομές.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) δομή που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | Point | [`Point`](../../point/) δομή που αντιπροσωπεύει το σημείο εκκίνησης της καμπύλης. |
| pt2 | Point | [`Point`](../../point/) δομή που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη. |
| pt3 | Point | [`Point`](../../point/) δομή που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη. |
| pt4 | Point | [`Point`](../../point/) δομή που αντιπροσωπεύει το τελικό σημείο της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)


