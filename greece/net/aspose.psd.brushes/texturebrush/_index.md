---
title: "Κλάση TextureBrush"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Brushes.TextureBrush. Κάθε ιδιότητα της κλάσης TextureBrush είναι ένα αντικείμενο Brush που χρησιμοποιεί μια εικόνα για να γεμίσει το εσωτερικό ενός σχήματος. Αυτή η κλάση δεν μπορεί να κληρονομηθεί."
type: docs
weight: 210
url: /el/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Κάθε ιδιότητα της κλάσης `TextureBrush` είναι ένα αντικείμενο [`Brush`](../../aspose.psd/brush/) που χρησιμοποιεί μια εικόνα για να γεμίσει το εσωτερικό ενός σχήματος. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα και το περιοριστικό ορθογώνιο. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα και το περιοριστικό ορθογώνιο. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα και τη λειτουργία περιτύλιξης. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα, το περιοριστικό ορθογώνιο και τις ιδιότητες εικόνας. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα, το περιοριστικό ορθογώνιο και τις ιδιότητες εικόνας. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το περιοριστικό ορθογώνιο. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TextureBrush` που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το περιοριστικό ορθογώνιο. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Ανακτά το αντικείμενο [`Image`](../../aspose.psd/image/) που σχετίζεται με αυτό το αντικείμενο `TextureBrush`. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Ανακτά τα [`ImageAttributes`](./imageattributes/) που σχετίζονται με αυτό το `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Ανακτά το [`Rectangle`](../../aspose.psd/rectangle/) που σχετίζεται με αυτό το `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Αποκτά ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να βρίσκεται μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
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


