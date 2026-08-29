---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος GraphicsPath. Εφαρμόζει μια παραμόρφωση που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο σε αυτό το GraphicsPath"
type: docs
weight: 180
url: /el/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Εφαρμόζει μια παραμόρφωση, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Ένας πίνακας από δομές [`PointF`](../../pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από *srcRect*. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | RectangleF | Ένα [`RectangleF`](../../rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από *destPoints*. |

### Δείτε επίσης

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Εφαρμόζει μια παραμόρφωση, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Ένας πίνακας από δομές [`PointF`](../../pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από *srcRect*. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | RectangleF | Ένα [`RectangleF`](../../rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από *destPoints*. |
| matrix | Matrix | Ένα [`Matrix`](../../matrix/) που καθορίζει μια γεωμετρική μεταστροφή για εφαρμογή στο μονοπάτι. |

### Δείτε επίσης

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Εφαρμόζει μια παραμόρφωση, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Ένας πίνακας από δομές [`PointF`](../../pointf/) που ορίζει ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από *srcRect*. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | RectangleF | Ένα [`RectangleF`](../../rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από *destPoints*. |
| matrix | Matrix | Ένα [`Matrix`](../../matrix/) που καθορίζει μια γεωμετρική μεταστροφή για εφαρμογή στο μονοπάτι. |
| warpMode | WarpMode | Μια απαρίθμηση [`WarpMode`](../../warpmode/) που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμική λειτουργία. |

### Δείτε επίσης

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Εφαρμόζει μια παραμόρφωση, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Ένας πίνακας από δομές [`PointF`](../../pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από *srcRect*. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | RectangleF | Ένα [`RectangleF`](../../rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από *destPoints*. |
| matrix | Matrix | Ένα [`Matrix`](../../matrix/) που καθορίζει μια γεωμετρική μεταστροφή για εφαρμογή στο μονοπάτι. |
| warpMode | WarpMode | Μια απαρίθμηση [`WarpMode`](../../warpmode/) που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμική λειτουργία. |
| flatness | Single | Μια τιμή από 0 έως 1 που καθορίζει πόσο επίπεδο είναι το προκύπτον μονοπάτι. Για περισσότερες πληροφορίες, δείτε τις μεθόδους [`Flatten`](../flatten/). |

### Δείτε επίσης

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


