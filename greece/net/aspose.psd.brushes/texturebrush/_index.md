---
title: Class TextureBrush
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Brushes.TextureBrush τάξη. Κάθε ιδιότητα τουTextureBrush η τάξη είναι αBrush αντικείμενο που χρησιμοποιεί μια εικόνα για να γεμίσει το εσωτερικό ενός σχήματος. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 210
url: /el/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Κάθε ιδιότητα του`TextureBrush` η τάξη είναι α[`Brush`](../../aspose.psd/brush/) αντικείμενο που χρησιμοποιεί μια εικόνα για να γεμίσει το εσωτερικό ενός σχήματος. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush` κλάση που χρησιμοποιεί την καθορισμένη εικόνα. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush` κλάση που χρησιμοποιεί την καθορισμένη εικόνα και το οριοθετημένο ορθογώνιο. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush` κλάση που χρησιμοποιεί την καθορισμένη εικόνα και το οριοθετημένο ορθογώνιο. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush` κλάση που χρησιμοποιεί την καθορισμένη λειτουργία εικόνας και αναδίπλωσης. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush` κλάση που χρησιμοποιεί τα χαρακτηριστικά εικόνας, οριοθέτησης ορθογωνίου και εικόνας. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush` κλάση που χρησιμοποιεί τα χαρακτηριστικά εικόνας, οριοθέτησης ορθογωνίου και εικόνας. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush`κλάση που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία αναδίπλωσης και το οριοθετημένο ορθογώνιο. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Αρχικοποιεί μια νέα παρουσία του`TextureBrush`κλάση που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία αναδίπλωσης και το οριοθετημένο ορθογώνιο. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Λαμβάνει το[`Image`](../../aspose.psd/image/) αντικείμενο που σχετίζεται με αυτό`TextureBrush` αντικείμενο. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Λαμβάνει το[`ImageAttributes`](./imageattributes/) συνδέονται με αυτό`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Λαμβάνει το[`Rectangle`](../../aspose.psd/rectangle/) συνδέονται με αυτό`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα, ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που αλλάζουν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με το GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Λαμβάνει ή ρυθμίζει την αδιαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η τιμή 0 σημαίνει ότι η βούρτσα είναι πλήρως ορατή, η τιμή 1 σημαίνει ότι η βούρτσα είναι πλήρως αδιαφανής. |
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

### Δείτε επίσης

* class [TransformBrush](../transformbrush/)
* χώρος ονομάτων [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* συνέλευση [Aspose.PSD](../../)


