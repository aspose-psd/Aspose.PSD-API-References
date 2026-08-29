---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Graphics. Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών PointF. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και εναλλακτικό τρόπο γεμίσματος."
type: docs
weight: 350
url: /el/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`PointF`](../../pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και εναλλακτικό τρόπο γεμίσματος.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει τα χαρακτηριστικά της συμπλήρωσης. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που ορίζουν την καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`PointF`](../../pointf/) χρησιμοποιώντας τον καθορισμένο τρόπο γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει τα χαρακτηριστικά της συμπλήρωσης. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που ορίζουν την καμπύλη. |
| fillmode | FillMode | Μέλος της απαρίθμησης [`FillMode`](../../fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`PointF`](../../pointf/) χρησιμοποιώντας τον καθορισμένο τρόπο γεμίσματος και τάση.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | Brush | Ένα [`Brush`](../../brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | PointF[] | Πίνακας δομών [`PointF`](../../pointf/) που ορίζουν την καμπύλη. |
| fillmode | FillMode | Μέλος της απαρίθμησης [`FillMode`](../../fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |
| ένταση | Single | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`Point`](../../point/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και εναλλακτικό τρόπο γεμίσματος.

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει τα χαρακτηριστικά της συμπλήρωσης. |
| points | Point[] | Πίνακας δομών [`Point`](../../point/) που ορίζουν την καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`Point`](../../point/) χρησιμοποιώντας τον καθορισμένο τρόπο γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει τα χαρακτηριστικά της συμπλήρωσης. |
| points | Point[] | Πίνακας δομών [`Point`](../../point/) που ορίζουν την καμπύλη. |
| fillmode | FillMode | Μέλος της απαρίθμησης [`FillMode`](../../fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`Point`](../../point/) χρησιμοποιώντας τον καθορισμένο τρόπο γεμίσματος και τάση.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει τα χαρακτηριστικά της συμπλήρωσης. |
| points | Point[] | Πίνακας δομών [`Point`](../../point/) που ορίζουν την καμπύλη. |
| fillmode | FillMode | Μέλος της απαρίθμησης [`FillMode`](../../fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |
| ένταση | Single | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *points* είναι null. |

### Δείτε επίσης

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


