---
title: "Κλάση PathGradientBrush"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Brushes.PathGradientBrush. Περιβάλλει ένα αντικείμενο Brush με διαβάθμιση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί"
type: docs
weight: 170
url: /el/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

Περιβάλλει ένα αντικείμενο [`Brush`](../../aspose.psd/brush/) με μια διαβάθμιση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PathGradientBrush` με το καθορισμένο μονοπάτι. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PathGradientBrush` με τα καθορισμένα σημεία. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PathGradientBrush` με τα καθορισμένα σημεία. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PathGradientBrush` με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PathGradientBrush` με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Λαμβάνει ή ορίζει ένα [`Blend`](../../aspose.psd/blend/) που καθορίζει θέσεις και παράγοντες που ορίζουν μια προσαρμοσμένη εστέλιση για την κλίση. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα στο κέντρο της διαβάθμισης του μονοπατιού. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Αποκτά ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Αποκτά ή ορίζει το σημείο εστίασης για τη μείωση της διαβάθμισης. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Αποκτά τη γραφική διαδρομή πάνω στην οποία χτίστηκε αυτό το brush. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | Λαμβάνει ή ορίζει ένα [`ColorBlend`](../../aspose.psd/colorblend/) που ορίζει ένα πολυχρωματικό γραμμικό gradient. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί άλλαξαν με κάποιο τρόπο. Για παράδειγμα ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Αποκτά ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να βρίσκεται μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Αποκτά τα σημεία διαδρομής πάνω στα οποία χτίστηκε αυτό το brush. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Λαμβάνει ή ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία του μονοπατιού που γεμίζει αυτό το `PathGradientBrush`. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική εξασθένιση προς ένα περιβάλλον χρώμα. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική εξασθένιση προς κάθε περιβάλλον χρώμα. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο του μονοπατιού προς τα έξω μέχρι το όριο του μονοπατιού. Η μετάβαση από το ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο του μονοπατιού προς τα έξω μέχρι το όριο του μονοπατιού. Η μετάβαση από το ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό στην αρχή. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με τη συγκεκριμένη σειρά. |

## Σχόλια

Το κεντρικό χρώμα είναι λευκό από προεπιλογή. Ένας χρήστης μπορεί να αλλάξει αυτήν την τιμή ανά πάσα στιγμή αργότερα.

Ο πίνακας των περιβάλλοντων χρωμάτων αρχικοποιείται με ένα μόνο στοιχείο που περιέχει λευκό χρώμα από προεπιλογή. Τα περιβάλλοντα χρώματα μπορούν να αλλάξουν αργότερα, ωστόσο απαιτείται τουλάχιστον ένα στοιχείο κατά τη ρύθμιση των περιβάλλοντων χρωμάτων.

Δείτε το [`Blend`](./blend/) για περισσότερες λεπτομέρειες σχετικά με την αρχικοποίησή του.

### Δείτε επίσης

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


