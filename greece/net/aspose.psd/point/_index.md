---
title: "Δομή Point"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Δομή Aspose.PSD.Point. Αντιπροσωπεύει ένα ταξινομημένο ζεύγος ακέραιων x και y συντεταγμένων που ορίζει ένα σημείο σε δισδιάστατο επίπεδο."
type: docs
weight: 5760
url: /el/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Αναπαριστά ένα διατεταγμένο ζεύγος ακέραιων συντεταγμένων x και y που ορίζει ένα σημείο σε δισδιάστατο επίπεδο.

```csharp
public struct Point
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Point](point/#constructor_1)(int) | Αρχικοποιεί μια νέα παρουσία της δομής `Point` χρησιμοποιώντας συντεταγμένες που καθορίζονται από μια ακέραια τιμή. |
| [Point](point/#constructor)(Size) | Αρχικοποιεί μια νέα παρουσία της δομής `Point` από τη δομή [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | Αρχικοποιεί μια νέα παρουσία της δομής `Point` με τις καθορισμένες συντεταγμένες. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Λαμβάνει μια νέα παρουσία της δομής `Point` που έχει τιμές [`X`](./x/) και [`Y`](./y/) ορισμένες στο μηδέν. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό το `Point` είναι κενό. |
| [X](../../aspose.psd/point/x/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού του `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού του `Point`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Προσθέτει το καθορισμένο [`Size`](../size/) στο καθορισμένο `Point`. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Μετατρέπει το καθορισμένο [`PointF`](../pointf/) σε `Point` στρογγυλοποιώντας τις τιμές του [`PointF`](../pointf/) προς τα επόμενα μεγαλύτερα ακέραια. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Μετατρέπει το καθορισμένο [`PointF`](../pointf/) σε αντικείμενο `Point` στρογγυλοποιώντας τις τιμές του `Point` στο πλησιέστερο ακέραιο. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Επιστρέφει το αποτέλεσμα της αφαίρεσης του καθορισμένου [`Size`](../size/) από το καθορισμένο `Point`. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Μετατρέπει το καθορισμένο [`PointF`](../pointf/) σε `Point` περικόπτοντας τις τιμές του `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Καθορίζει αν αυτό το `Point` περιέχει τις ίδιες συντεταγμένες με το καθορισμένο Object. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Μετακινεί αυτό το `Point` κατά το καθορισμένο `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Μετακινεί αυτό το `Point` κατά το καθορισμένο ποσό. |
| override [ToString](../../aspose.psd/point/tostring/)() | Μετατρέπει αυτό το `Point` σε αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [operator +](../../aspose.psd/point/op_addition/) | Μετακινεί ένα `Point` κατά ένα δεδομένο [`Size`](../size/). |
| [operator ==](../../aspose.psd/point/op_equality/) | Συγκρίνει δύο αντικείμενα `Point`. Το αποτέλεσμα καθορίζει εάν οι τιμές των ιδιοτήτων [`X`](./x/) και [`Y`](./y/) των δύο αντικειμένων `Point` είναι ίσες. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Μετατρέπει τη συγκεκριμένη δομή `Point` σε δομή [`Size`](../size/). |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Μετατρέπει τη συγκεκριμένη δομή `Point` στη δομή [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/point/op_inequality/) | Συγκρίνει δύο αντικείμενα `Point`. Το αποτέλεσμα καθορίζει εάν οι τιμές των ιδιοτήτων [`X`](./x/) ή [`Y`](./y/) των δύο αντικειμένων `Point` είναι διαφορετικές. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Μετατοπίζει ένα `Point` με το αντίθετο του δεδομένου [`Size`](../size/). |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


