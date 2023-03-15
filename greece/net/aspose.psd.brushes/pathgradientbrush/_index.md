---
title: Class PathGradientBrush
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Brushes.PathGradientBrush τάξη. Ενθυλακώνει αBrush αντικείμενο με κλίση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 170
url: /el/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

Ενθυλακώνει α[`Brush`](../../aspose.psd/brush/) αντικείμενο με κλίση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Αρχικοποιεί μια νέα παρουσία του`PathGradientBrush` κλάση με την καθορισμένη διαδρομή. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Αρχικοποιεί μια νέα παρουσία του`PathGradientBrush` τάξη με τα καθορισμένα σημεία. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Αρχικοποιεί μια νέα παρουσία του`PathGradientBrush` τάξη με τα καθορισμένα σημεία. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Αρχικοποιεί μια νέα παρουσία του`PathGradientBrush` τάξη με τα καθορισμένα σημεία και τη λειτουργία αναδίπλωσης. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Αρχικοποιεί μια νέα παρουσία του`PathGradientBrush` τάξη με τα καθορισμένα σημεία και τη λειτουργία αναδίπλωσης. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Λαμβάνει ή ορίζει α[`Blend`](../../aspose.psd/blend/) που καθορίζει θέσεις και παράγοντες που καθορίζουν μια προσαρμοσμένη πτώση για την κλίση. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα στο κέντρο της κλίσης της διαδρομής. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Λαμβάνει ή ορίζει το κεντρικό σημείο της κλίσης διαδρομής. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Λαμβάνει ή ορίζει το σημείο εστίασης για την πτώση της κλίσης. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Λαμβάνει τη διαδρομή γραφικών πάνω στην οποία βασίστηκε αυτό το πινέλο. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα, ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που αλλάζουν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με το GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Λαμβάνει ή ρυθμίζει την αδιαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η τιμή 0 σημαίνει ότι η βούρτσα είναι πλήρως ορατή, η τιμή 1 σημαίνει ότι η βούρτσα είναι πλήρως αδιαφανής. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Λαμβάνει τα σημεία διαδρομής πάνω στα οποία βασίστηκε αυτό το πινέλο. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Λαμβάνει ή ορίζει μια σειρά χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής`PathGradientBrush` γεμίζει. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική πτώση σε ένα περιβάλλον χρώμα. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Δημιουργεί μια κλίση με ένα κεντρικό χρώμα και μια γραμμική πτώση σε κάθε περιβάλλον χρώμα. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Δημιουργεί ένα πινέλο ντεγκραντέ που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από το ένα χρώμα στο άλλο βασίζεται σε μια καμπύλη σε σχήμα καμπάνας. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Δημιουργεί ένα πινέλο ντεγκραντέ που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από το ένα χρώμα στο άλλο βασίζεται σε μια καμπύλη σε σχήμα καμπάνας. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προϋποθέτει τη μετάφραση στον μετασχηματισμό. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |

### Παρατηρήσεις

Το κεντρικό χρώμα είναι λευκό από προεπιλογή. Ένας χρήστης μπορεί να αλλάξει αυτήν την τιμή ανά πάσα στιγμή αργότερα.

Ο πίνακας χρωμάτων surround αρχικοποιείται με ένα μόνο στοιχείο που περιέχει λευκό χρώμα από προεπιλογή. Τα χρώματα surround ενδέχεται να αλλάξουν αργότερα, ωστόσο απαιτείται τουλάχιστον ένα στοιχείο κατά τη ρύθμιση των χρωμάτων surround.

Δείτε το[`Blend`](./blend/) για περισσότερες λεπτομέρειες σχετικά με την αρχικοποίησή του.

### Δείτε επίσης

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* χώρος ονομάτων [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* συνέλευση [Aspose.PSD](../../)


