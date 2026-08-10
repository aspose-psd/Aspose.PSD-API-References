---
title: "Κλάση PathGradientBrushBase"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Brushes.PathGradientBrushBase. Αντιπροσωπεύει ένα Brush με βασική λειτουργία διαβάθμισης διαδρομής."
type: docs
weight: 180
url: /el/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

Αντιπροσωπεύει ένα [`Brush`](../../aspose.psd/brush/) με βασική λειτουργία διαβάθμισης διαδρομής.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Αποκτά ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Αποκτά ή ορίζει το σημείο εστίασης για τη μείωση της διαβάθμισης. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Αποκτά τη γραφική διαδρομή πάνω στην οποία χτίστηκε αυτό το brush. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Αποκτά ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να βρίσκεται μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Αποκτά τα σημεία διαδρομής πάνω στα οποία χτίστηκε αυτό το brush. |
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

## Σχόλια

Σημειώστε ότι κατά τη δημιουργία της κλάσης `PathGradientBrushBase` πρέπει να αρχικοποιείται τουλάχιστον με 2 σημεία. Η εσωτερική διαδρομή που δημιουργείται θα είναι πάντα κλειστή φιγούρα, το τελευταίο σημείο συνδέεται με το πρώτο σημείο. Αυτό το σχήμα γεμίζει με αυτή τη `PathGradientBrushBase`. Η υλοποίηση GDI+ ρίχνει μια OutOfMemoryException όταν περνιούνται κενά σύνολα ή σύνολα σημείων με τις ίδιες συντεταγμένες. Η `PathGradientBrushBase` ρίχνει εξαίρεση όταν ο πίνακας σημείων περιέχει λιγότερα από 2 σημεία· η ArgumentException ρίχνεται αντί για OutOfMemoryException όταν ο πίνακας σημείων είναι μη αποδεκτός. Το κεντρικό σημείο υπολογίζεται ως κέντρο μάζας των δοθέντων σημείων εξ ορισμού. Ο χρήστης μπορεί να αλλάξει αυτό το σημείο αργότερα. Η κλίμακα εστίασης είναι ένα κενό σημείο (0.0, 0.0) εξ ορισμού.

### Δείτε επίσης

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


