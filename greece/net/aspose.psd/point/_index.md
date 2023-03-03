---
title: Struct Point
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Point struct. Αντιπροσωπεύει ένα διατεταγμένο ζεύγος ακεραίων x και yσυντεταγμένων που ορίζει ένα σημείο σε ένα δισδιάστατο επίπεδο.
type: docs
weight: 5260
url: /el/net/aspose.psd/point/
---
## Point structure

Αντιπροσωπεύει ένα διατεταγμένο ζεύγος ακεραίων x- και y-συντεταγμένων που ορίζει ένα σημείο σε ένα δισδιάστατο επίπεδο.

```csharp
public struct Point
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Point](point/#constructor_1)(int) | Αρχικοποιεί μια νέα παρουσία του`Point` δομή που χρησιμοποιεί συντεταγμένες που καθορίζονται από μια ακέραια τιμή. |
| [Point](point/#constructor)(Size) | Αρχικοποιεί μια νέα παρουσία του`Point` δομή από το[`Size`](../size/)δομή. |
| [Point](point/#constructor_2)(int, int) | Αρχικοποιεί μια νέα παρουσία του`Point` δομή με τις καθορισμένες συντεταγμένες. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Παίρνει μια νέα παρουσία του`Point` δομή που έχει[`X`](./x/) και[`Y`](./y/) τιμές ορίστηκαν στο μηδέν. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό`Point` είναι κενό. |
| [X](../../aspose.psd/point/x/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού`Point` . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Προσθέτει το καθορισμένο[`Size`](../size/) στο καθορισμένο`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Μετατρέπει το καθορισμένο[`PointF`](../pointf/) σε α`Point` στρογγυλοποιώντας τις τιμές του[`PointF`](../pointf/) στις επόμενες υψηλότερες ακέραιες τιμές. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Μετατρέπει το καθορισμένο[`PointF`](../pointf/) σε α`Point` αντικείμενο με στρογγυλοποίηση του`Point` τιμές στον πλησιέστερο ακέραιο. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Επιστρέφει το καθορισμένο αποτέλεσμα της αφαίρεσης[`Size`](../size/) από τα καθορισμένα`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Μετατρέπει το καθορισμένο[`PointF`](../pointf/) σε α`Point` περικόπτοντας τις τιμές του`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Καθορίζει εάν αυτό`Point` περιέχει τις ίδιες συντεταγμένες με τις καθορισμένεςObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Μεταφράζει αυτό`Point` από τα καθορισμένα`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Μεταφράζει αυτό`Point`κατά το καθορισμένο ποσό. |
| override [ToString](../../aspose.psd/point/tostring/)() | Μετατρέπει αυτό`Point` σε μια συμβολοσειρά αναγνώσιμη από τον άνθρωπο. |
| [operator +](../../aspose.psd/point/op_addition/) | Μεταφράζει α`Point` από ένα δεδομένο[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Συγκρίνει δύο`Point` αντικείμενα. Το αποτέλεσμα καθορίζει εάν οι τιμές του[`X`](./x/) και[`Y`](./y/) ιδιότητες των δύο`Point` τα αντικείμενα είναι ίσα. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Μετατρέπει το καθορισμένο`Point` δομή σε α[`Size`](../size/)δομή. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Μετατρέπει το καθορισμένο`Point` δομή στο[`PointF`](../pointf/)δομή. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Συγκρίνει δύο`Point` αντικείμενα. Το αποτέλεσμα καθορίζει εάν οι τιμές του[`X`](./x/) ή[`Y`](./y/) ιδιότητες των δύο`Point` τα αντικείμενα είναι άνισα. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Μεταφράζει α`Point` από το αρνητικό ενός δεδομένου[`Size`](../size/) . |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


