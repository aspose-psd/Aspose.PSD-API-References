---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Graphics μέθοδος. Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος"
type: docs
weight: 170
url: /el/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| x | Single | Η συντεταγμένη x του επάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη. |
| y | Single | Η συντεταγμένη y του επάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | Single | Πλάτος του ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | Single | Ύψος του ορθογωνίου που ορίζει την έλλειψη. |
| startAngle | Single | Γωνία σε μοίρες μετρημένη δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης της καμπύλης. |
| sweepAngle | Single | Γωνία σε μοίρες μετρημένη δεξιόστροφα από την παράμετρο *startAngle* έως το σημείο λήξης της καμπύλης. |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Σχεδιάζει μια καμπύλη που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [`RectangleF`](../../rectanglef/).

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) δομή που ορίζει τα όρια της έλλειψης. |
| startAngle | Single | Γωνία σε μοίρες μετρημένη δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης της καμπύλης. |
| sweepAngle | Single | Γωνία σε μοίρες μετρημένη δεξιόστροφα από την παράμετρο *startAngle* έως το σημείο λήξης της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| x | Int32 | Η συντεταγμένη x του επάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη. |
| y | Int32 | Η συντεταγμένη y του επάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | Int32 | Πλάτος του ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | Int32 | Ύψος του ορθογωνίου που ορίζει την έλλειψη. |
| startAngle | Int32 | Γωνία σε μοίρες μετρημένη δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης της καμπύλης. |
| sweepAngle | Int32 | Γωνία σε μοίρες μετρημένη δεξιόστροφα από την παράμετρο *startAngle* έως το σημείο λήξης της καμπύλης. |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Σχεδιάζει μια καμπύλη που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [`Rectangle`](../../rectangle/).

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) δομή που ορίζει τα όρια της έλλειψης. |
| startAngle | Single | Γωνία σε μοίρες μετρημένη δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης της καμπύλης. |
| sweepAngle | Single | Γωνία σε μοίρες μετρημένη δεξιόστροφα από την παράμετρο *startAngle* έως το σημείο λήξης της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


