---
title: Class PathGradientBrushBase
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Brushes.PathGradientBrushBase τάξη. Αντιπροσωπεύει αBrush με λειτουργικότητα κλίσης διαδρομής βάσης.
type: docs
weight: 180
url: /el/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Αντιπροσωπεύει α[`Brush`](../../aspose.psd/brush/) με λειτουργικότητα κλίσης διαδρομής βάσης.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Λαμβάνει ή ορίζει το κεντρικό σημείο της κλίσης διαδρομής. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Λαμβάνει ή ορίζει το σημείο εστίασης για την πτώση της κλίσης. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Λαμβάνει τη διαδρομή γραφικών πάνω στην οποία βασίστηκε αυτό το πινέλο. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα, ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που αλλάζουν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με το GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Λαμβάνει ή ρυθμίζει την αδιαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η τιμή 0 σημαίνει ότι η βούρτσα είναι πλήρως ορατή, η τιμή 1 σημαίνει ότι η βούρτσα είναι πλήρως αδιαφανής. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Λαμβάνει τα σημεία διαδρομής πάνω στα οποία βασίστηκε αυτό το πινέλο. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Λαμβάνει ή ορίζει ένα αντίγραφο[`Matrix`](../../aspose.psd/matrix/) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Λαμβάνει ή ορίζει α[`WrapMode`](../../aspose.psd/wrapmode/) απαρίθμηση που υποδεικνύει τη λειτουργία αναδίπλωσης για αυτό[`TransformBrush`](../transformbrush/) . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί έναν νέο βαθύ κλώνο του ρεύματος[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Πολλαπλασιάζει το[`Matrix`](../../aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού[`LinearGradientBrush`](../lineargradientbrush/) από τα καθορισμένα[`Matrix`](../../aspose.psd/matrix/) με την προετοιμασία του καθορισμένου[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Πολλαπλασιάζει το[`Matrix`](../../aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού[`LinearGradientBrush`](../lineargradientbrush/) από τα καθορισμένα[`Matrix`](../../aspose.psd/matrix/) με την καθορισμένη σειρά. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Επαναφέρει το[`Transform`](../transformbrush/transform/) ιδιοκτησία στην ταυτότητα. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προϋποθέτει την περιστροφή στον μετασχηματισμό. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσαρτά τον πίνακα κλιμάκωσης στον μετασχηματισμό. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προϋποθέτει τη μετάφραση στον μετασχηματισμό. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |

### Παρατηρήσεις

Σημειώστε ότι κατά τη δημιουργία του`PathGradientBrushBase` κλάση θα πρέπει να αρχικοποιηθεί με 2 βαθμούς τουλάχιστον. Η εσωτερική διαδρομή create θα είναι πάντα ένα κλειστό σχήμα, το τελευταίο σημείο συνδέει το πρώτο σημείο. Αυτό το σχήμα είναι γεμάτο με αυτό`PathGradientBrushBase`. Η υλοποίηση GDI+ ρίχνει έναOutOfMemoryException όταν περνούν σε κενούς πίνακες ή σημεία που έχουν τις ίδιες συντεταγμένες. Το`PathGradientBrushBase` κάνει εξαίρεση όταν ο πίνακας σημείων περιέχει λιγότερους από 2 πόντους, τοArgumentException is πεταχτεί παράOutOfMemoryException όταν ο πίνακας σημείων δεν είναι αποδεκτός. Το κεντρικό σημείο υπολογίζεται ως κέντρο μάζας για τα περασμένα σημεία από προεπιλογή. Ένας χρήστης μπορεί να αλλάξει αυτό το σημείο αργότερα. Οι κλίμακες εστίασης είναι ένα κενό σημείο (0,0, 0,0) από προεπιλογή.

### Δείτε επίσης

* class [TransformBrush](../transformbrush/)
* χώρος ονομάτων [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* συνέλευση [Aspose.PSD](../../)


