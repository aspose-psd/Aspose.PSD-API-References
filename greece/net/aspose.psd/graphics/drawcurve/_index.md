---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Graphics. Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών PointF. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5."
type: docs
weight: 210
url: /el/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../../pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που ορίζουν την καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../../pointf/) χρησιμοποιώντας καθορισμένη τάση.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που αντιπροσωπεύουν τα σημεία που ορίζουν την καμπύλη. |
| ένταση | Single | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../../pointf/). Η σχεδίαση ξεκινά με μετατόπιση από την αρχή του πίνακα. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που ορίζουν την καμπύλη. |
| offset | Int32 | Μετατόπιση από το πρώτο στοιχείο του πίνακα της παραμέτρου *points* μέχρι το αρχικό σημείο στην καμπύλη. |
| numberOfSegments | Int32 | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../../pointf/) χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση ξεκινά με μετατόπιση από την αρχή του πίνακα.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που ορίζουν την καμπύλη. |
| offset | Int32 | Μετατόπιση από το πρώτο στοιχείο του πίνακα της παραμέτρου *points* μέχρι το αρχικό σημείο στην καμπύλη. |
| numberOfSegments | Int32 | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |
| ένταση | Single | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`Point`](../../point/).

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | Point[] | Πίνακας δομών [`Point`](../../point/) που ορίζουν την καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`Point`](../../point/) χρησιμοποιώντας καθορισμένη τάση.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | Point[] | Πίνακας δομών [`Point`](../../point/) που ορίζουν την καμπύλη. |
| ένταση | Single | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Σχεδιάζει μια καρδινική καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`Point`](../../point/) χρησιμοποιώντας καθορισμένη τάση.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | Point[] | Πίνακας δομών [`Point`](../../point/) που ορίζουν την καμπύλη. |
| offset | Int32 | Μετατόπιση από το πρώτο στοιχείο του πίνακα της παραμέτρου *points* μέχρι το αρχικό σημείο στην καμπύλη. |
| numberOfSegments | Int32 | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |
| ένταση | Single | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


