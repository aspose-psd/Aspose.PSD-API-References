---
title: Graphics.DrawCurve
second_title: Aspose.PSD για Αναφορά API .NET
description: Graphics μέθοδος. Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακαPointF δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 05.
type: docs
weight: 200
url: /el/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../../pointf/) δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Συστοιχία από[`PointF`](../../pointf/) δομές που ορίζουν το spline. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../../pointf/) δομές που χρησιμοποιούν μια καθορισμένη τάση.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Συστοιχία από[`PointF`](../../pointf/) δομές που αντιπροσωπεύουν τα σημεία που ορίζουν την καμπύλη. |
| tension | Single | Τιμή μεγαλύτερη ή ίση με 0,0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../../pointf/) δομές. Το σχέδιο αρχίζει με μετατόπιση από την αρχή του πίνακα. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Συστοιχία από[`PointF`](../../pointf/) δομές που ορίζουν το spline. |
| offset | Int32 | Μετατόπιση από το πρώτο στοιχείο στον πίνακα του*points* παράμετρος στο σημείο εκκίνησης στην καμπύλη. |
| numberOfSegments | Int32 | Αριθμός τμημάτων μετά το σημείο εκκίνησης που πρέπει να συμπεριληφθούν στην καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../../pointf/) κατασκευές που χρησιμοποιούν μια καθορισμένη τάση. Το σχέδιο αρχίζει με μετατόπιση από την αρχή του πίνακα.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Συστοιχία από[`PointF`](../../pointf/) δομές που ορίζουν το spline. |
| offset | Int32 | Μετατόπιση από το πρώτο στοιχείο στον πίνακα του*points* παράμετρος στο σημείο εκκίνησης στην καμπύλη. |
| numberOfSegments | Int32 | Αριθμός τμημάτων μετά το σημείο εκκίνησης που πρέπει να συμπεριληφθούν στην καμπύλη. |
| tension | Single | Τιμή μεγαλύτερη ή ίση με 0,0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`Point`](../../point/) δομές.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | Point[] | Συστοιχία από[`Point`](../../point/) δομές που ορίζουν το spline. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`Point`](../../point/) δομές που χρησιμοποιούν μια καθορισμένη τάση.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | Point[] | Συστοιχία από[`Point`](../../point/) δομές που ορίζουν το spline. |
| tension | Single | Τιμή μεγαλύτερη ή ίση με 0,0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`Point`](../../point/) δομές που χρησιμοποιούν μια καθορισμένη τάση.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | Point[] | Συστοιχία από[`Point`](../../point/) δομές που ορίζουν το spline. |
| offset | Int32 | Μετατόπιση από το πρώτο στοιχείο στον πίνακα του*points* παράμετρος στο σημείο εκκίνησης στην καμπύλη. |
| numberOfSegments | Int32 | Αριθμός τμημάτων μετά το σημείο εκκίνησης που πρέπει να συμπεριληφθούν στην καμπύλη. |
| tension | Single | Τιμή μεγαλύτερη ή ίση με 0,0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *points* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)


