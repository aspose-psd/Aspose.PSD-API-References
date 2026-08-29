---
title: "Κλάση LinearGradientBrushBase"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Brushes.LinearGradientBrushBase. Αντιπροσωπεύει ένα Brush με δυνατότητες διαβάθμισης και κατάλληλες ιδιότητες"
type: docs
weight: 150
url: /el/net/aspose.psd.brushes/lineargradientbrushbase/
---
{{< psd/tize >}}
## LinearGradientBrushBase class

Αντιπροσωπεύει ένα [`Brush`](../../aspose.psd/brush/) με δυνατότητες διαβάθμισης και κατάλληλες ιδιότητες.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία του gradient. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η διόρθωση γάμμα είναι ενεργοποιημένη για αυτό το `LinearGradientBrushBase`. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το [`Angle`](./angle/) αλλάζει κατά τη διάρκεια των μετασχηματισμών με αυτό το `LinearGradientBrushBase`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Αποκτά ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να βρίσκεται μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Αποκτά ή ορίζει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της διαβάθμισης. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Αποκτά ή ορίζει ένα αντίγραφο του [`Matrix`](../../aspose.psd/matrix/) που ορίζει ένα τοπικό γεωμετρικό μετασχηματισμό για αυτό το [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Αποκτά ή ορίζει μια απαρίθμηση [`WrapMode`](../../aspose.psd/wrapmode/) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [`TransformBrush`](../transformbrush/). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Πολλαπλασιάζει το [`Matrix`](../../aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [`LinearGradientBrush`](../lineargradientbrush/) με το καθορισμένο [`Matrix`](../../aspose.psd/matrix/) προσθέτοντας το καθορισμένο [`Matrix`](../../aspose.psd/matrix/) στην αρχή. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Πολλαπλασιάζει το [`Matrix`](../../aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [`LinearGradientBrush`](../lineargradientbrush/) με το καθορισμένο [`Matrix`](../../aspose.psd/matrix/) με τη συγκεκριμένη σειρά. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Επαναφέρει την ιδιότητα [`Transform`](../transformbrush/transform/) στην ταυτότητα. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό στην αρχή. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με τη συγκεκριμένη σειρά. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα μεγέθη. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό στην αρχή. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα μεγέθη με τη συγκεκριμένη σειρά. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό στην αρχή. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με τη συγκεκριμένη σειρά. |

### Δείτε επίσης

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


