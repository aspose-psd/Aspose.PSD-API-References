---
title: "Κλάση LinearMulticolorGradientBrush"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Brushes.LinearMulticolorGradientBrush. Αντιπροσωπεύει ένα Brush με γραμμικό gradient ορισμένο από πολλαπλά χρώματα και κατάλληλες θέσεις. Αυτή η κλάση δεν μπορεί να κληρονομηθεί"
type: docs
weight: 160
url: /el/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

Αντιπροσωπεύει ένα [`Brush`](../../aspose.psd/brush/) με γραμμικό gradient ορισμένο από πολλαπλά χρώματα και κατάλληλες θέσεις. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` με προεπιλεγμένες παραμέτρους. Το αρχικό χρώμα είναι μαύρο, το τελικό χρώμα είναι λευκό, η γωνία είναι 45 μοίρες και το ορθογώνιο βρίσκεται στο (0,0) με μέγεθος (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` με τα καθορισμένα σημεία. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` με τα καθορισμένα σημεία. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `LinearMulticolorGradientBrush` βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία του gradient. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η διόρθωση γάμμα είναι ενεργοποιημένη για αυτό το [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Λαμβάνει ή ορίζει ένα [`ColorBlend`](../../aspose.psd/colorblend/) που ορίζει ένα πολυχρωματικό γραμμικό gradient. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το [`Angle`](../lineargradientbrushbase/angle/) αλλάζει κατά τις μετασχηματισμούς με αυτό το [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
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

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


