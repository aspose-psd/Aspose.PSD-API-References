---
title: Class LinearGradientBrush
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Brushes.LinearGradientBrush τάξη. Ενθυλακώνει αBrush με γραμμική κλίση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 140
url: /el/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Ενθυλακώνει α[`Brush`](../../aspose.psd/brush/) με γραμμική κλίση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` κλάση με προεπιλεγμένες παραμέτρους. Το αρχικό χρώμα είναι μαύρο, το τελικό χρώμα είναι λευκό, η γωνία είναι 45 μοίρες και το ορθογώνιο βρίσκεται στο (0,0) με μέγεθος (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` τάξη με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` τάξη με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` τάξη βασισμένη σε ορθογώνιο, χρώματα έναρξης και λήξης και γωνία προσανατολισμού. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` τάξη βασισμένη σε ορθογώνιο, χρώματα έναρξης και λήξης και γωνία προσανατολισμού. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` τάξη βασισμένη σε ορθογώνιο, χρώματα έναρξης και λήξης και γωνία προσανατολισμού. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Αρχικοποιεί μια νέα παρουσία του`LinearGradientBrush` τάξη βασισμένη σε ορθογώνιο, χρώματα έναρξης και λήξης και γωνία προσανατολισμού. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία κλίσης. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Λαμβάνει ή ορίζει α[`Blend`](../../aspose.psd/blend/) που καθορίζει θέσεις και παράγοντες που καθορίζουν μια προσαρμοσμένη πτώση για την κλίση. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Λαμβάνει ή ορίζει το τελικό χρώμα ντεγκραντέ. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η διόρθωση γάμμα είναι ενεργοποιημένη για αυτό[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν[`Angle`](../lineargradientbrushbase/angle/) αλλάζει κατά τη διάρκεια των μετασχηματισμών με αυτό[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα, ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που αλλάζουν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με το GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Λαμβάνει ή ρυθμίζει την αδιαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η τιμή 0 σημαίνει ότι η βούρτσα είναι πλήρως ορατή, η τιμή 1 σημαίνει ότι η βούρτσα είναι πλήρως αδιαφανής. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Λαμβάνει ή ορίζει μια ορθογώνια περιοχή που ορίζει τα σημεία έναρξης και τέλους της κλίσης. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Λαμβάνει ή ορίζει το αρχικό χρώμα ντεγκραντέ. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Λαμβάνει ή ορίζει ένα αντίγραφο[`Matrix`](../../aspose.psd/matrix/) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Λαμβάνει ή ορίζει α[`WrapMode`](../../aspose.psd/wrapmode/) απαρίθμηση που υποδεικνύει τη λειτουργία αναδίπλωσης για αυτό[`TransformBrush`](../transformbrush/) . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί έναν νέο βαθύ κλώνο του ρεύματος[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Πολλαπλασιάζει το[`Matrix`](../../aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού`LinearGradientBrush` από τα καθορισμένα[`Matrix`](../../aspose.psd/matrix/) με την προετοιμασία του καθορισμένου[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Πολλαπλασιάζει το[`Matrix`](../../aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού`LinearGradientBrush` από τα καθορισμένα[`Matrix`](../../aspose.psd/matrix/) με την καθορισμένη σειρά. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Επαναφέρει το[`Transform`](../transformbrush/transform/) ιδιοκτησία στην ταυτότητα. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προϋποθέτει την περιστροφή στον μετασχηματισμό. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσαρτά τον πίνακα κλιμάκωσης στον μετασχηματισμό. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Δημιουργεί μια γραμμική κλίση με ένα κεντρικό χρώμα και μια γραμμική πτώση σε ένα μόνο χρώμα και στα δύο άκρα. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Δημιουργεί μια γραμμική κλίση με ένα κεντρικό χρώμα και μια γραμμική πτώση σε ένα μόνο χρώμα και στα δύο άκρα. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Δημιουργεί μια πτώση κλίσης με βάση μια καμπύλη σε σχήμα καμπάνας. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Δημιουργεί μια πτώση κλίσης με βάση μια καμπύλη σε σχήμα καμπάνας. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προϋποθέτει τη μετάφραση στον μετασχηματισμό. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |

### Δείτε επίσης

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* χώρος ονομάτων [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* συνέλευση [Aspose.PSD](../../)


