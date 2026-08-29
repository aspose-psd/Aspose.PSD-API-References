---
title: "Κλάση Region"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Region. Περιγράφει το εσωτερικό ενός γραφικού σχήματος που αποτελείται από ορθογώνια και διαδρομές. Αυτή η κλάση δεν μπορεί να κληρονομηθεί."
type: docs
weight: 5860
url: /el/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Περιγράφει το εσωτερικό ενός γραφικού σχήματος που αποτελείται από ορθογώνια και διαδρομές. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class Region
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Region](region/#constructor)() | Αρχικοποιεί ένα νέο `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Αρχικοποιεί ένα νέο `Region` με το καθορισμένο [`GraphicsPath`](../graphicspath/). |
| [Region](region/#constructor_2)(Rectangle) | Αρχικοποιεί ένα νέο `Region` από τη συγκεκριμένη δομή [`Rectangle`](../rectangle/). |
| [Region](region/#constructor_3)(RectangleF) | Αρχικοποιεί ένα νέο `Region` από τη συγκεκριμένη δομή [`RectangleF`](../rectanglef/). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Ενημερώνει αυτό το `Region` ώστε να περιέχει το τμήμα του συγκεκριμένου [`GraphicsPath`](../graphicspath/) που δεν τέμνει αυτό το `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Ενημερώνει αυτό το `Region` ώστε να περιέχει το τμήμα του συγκεκριμένου [`Rectangle`](../rectangle/) δομής που δεν τέμνει αυτό το `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Ενημερώνει αυτό το `Region` ώστε να περιέχει το τμήμα του συγκεκριμένου [`RectangleF`](../rectanglef/) δομής που δεν τέμνει αυτό το `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Ενημερώνει αυτό το `Region` ώστε να περιέχει το τμήμα του συγκεκριμένου `Region` που δεν τέμνει αυτό το `Region`. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Ελέγχει αν τα αντικείμενα είναι ίσα. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Δοκιμάζει εάν το συγκεκριμένο `Region` είναι ταυτόσημο με αυτό το `Region` στην καθορισμένη επιφάνεια σχεδίασης. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Ενημερώνει αυτό το `Region` ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το συγκεκριμένο [`GraphicsPath`](../graphicspath/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Ενημερώνει αυτό το `Region` ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη συγκεκριμένη δομή [`Rectangle`](../rectangle/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Ενημερώνει αυτό το `Region` ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη συγκεκριμένη δομή [`RectangleF`](../rectanglef/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Ενημερώνει αυτό το `Region` ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το συγκεκριμένο `Region`. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού του τρέχοντος αντικειμένου. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Ενημερώνει αυτό το `Region` στην τομή του με το συγκεκριμένο [`GraphicsPath`](../graphicspath/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Ενημερώνει αυτό το `Region` στην τομή του με τη συγκεκριμένη δομή [`Rectangle`](../rectangle/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Ενημερώνει αυτό το `Region` στην τομή του με τη συγκεκριμένη δομή [`RectangleF`](../rectanglef/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Ενημερώνει αυτό το `Region` στην τομή του με το συγκεκριμένο `Region`. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Δοκιμάζει εάν αυτό το `Region` έχει κενό εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Δοκιμάζει εάν αυτό το `Region` έχει άπειρο εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Δοκιμάζει εάν η συγκεκριμένη δομή [`Point`](../point/) περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Δοκιμάζει εάν η συγκεκριμένη δομή [`PointF`](../pointf/) περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Δοκιμάζει εάν οποιοδήποτε τμήμα της συγκεκριμένης δομής [`Rectangle`](../rectangle/) περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Δοκιμάζει εάν οποιοδήποτε τμήμα της συγκεκριμένης δομής [`RectangleF`](../rectanglef/) περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Δοκιμάζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Δοκιμάζει εάν η συγκεκριμένη δομή [`Point`](../point/) περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το συγκεκριμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Δοκιμάζει εάν η συγκεκριμένη δομή [`PointF`](../pointf/) περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το συγκεκριμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Δοκιμάζει εάν οποιοδήποτε τμήμα της συγκεκριμένης δομής [`Rectangle`](../rectangle/) περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το συγκεκριμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Δοκιμάζει εάν οποιοδήποτε τμήμα της καθορισμένης δομής [`RectangleF`](../rectanglef/) περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Δοκιμάζει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Δοκιμάζει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το αντικείμενο `Region` όταν σχεδιάζεται χρησιμοποιώντας το αντικείμενο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το `Region` όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Αρχικοποιεί αυτό το `Region` σε ένα κενό εσωτερικό. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Αρχικοποιεί αυτό το αντικείμενο `Region` σε ένα άπειρο εσωτερικό. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Μετασχηματίζει αυτό το `Region` με τον καθορισμένο [`Matrix`](../matrix/). |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Μετατοπίζει τις συντεταγμένες αυτού του `Region` κατά το καθορισμένο ποσό. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Μετατοπίζει τις συντεταγμένες αυτού του `Region` κατά το καθορισμένο ποσό. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Ενημερώνει αυτό το `Region` στην ένωση του με το καθορισμένο [`GraphicsPath`](../graphicspath/). |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Ενημερώνει αυτό το `Region` στην ένωση του με τη καθορισμένη δομή [`Rectangle`](../rectangle/). |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Ενημερώνει αυτό το `Region` στην ένωση του με τη καθορισμένη δομή [`RectangleF`](../rectanglef/). |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Ενημερώνει αυτό το `Region` στην ένωση του με το καθορισμένο `Region`. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Ενημερώνει αυτό το `Region` στην ένωση μείον τη διατομή του με το καθορισμένο [`GraphicsPath`](../graphicspath/). |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Ενημερώνει αυτό το `Region` στην ένωση μείον τη διατομή του με τη καθορισμένη δομή [`Rectangle`](../rectangle/). |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Ενημερώνει αυτό το `Region` στην ένωση μείον τη διατομή του με τη καθορισμένη δομή [`RectangleF`](../rectanglef/). |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Ενημερώνει αυτό το `Region` στην ένωση μείον τη διατομή του με το καθορισμένο `Region`. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


