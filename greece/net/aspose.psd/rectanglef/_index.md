---
title: "Δομή RectangleF"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Δομή Aspose.PSD.RectangleF. Αποθηκεύει ένα σύνολο τεσσάρων αριθμών κινητής υποδιαστολής που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου."
type: docs
weight: 5850
url: /el/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Αποθηκεύει ένα σύνολο από τέσσερις αριθμούς κινητής υποδιαστολής που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.

```csharp
public struct RectangleF
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `RectangleF` με την καθορισμένη θέση και μέγεθος. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `RectangleF` με την καθορισμένη θέση και μέγεθος. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Λαμβάνει ένα νέο στιγμιότυπο της δομής `RectangleF` που έχει τις τιμές [`X`](./x/), [`Y`](./y/), [`Width`](./width/) και [`Height`](./height/) ορισμένες στο μηδέν. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του [`Y`](./y/) και του [`Height`](./height/) αυτής της δομής `RectangleF`. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Λαμβάνει ή ορίζει το ύψος αυτής της δομής `RectangleF`. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ιδιότητα [`Width`](./width/) ή [`Height`](./height/) αυτής της `RectangleF` έχει τιμή μηδέν. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής `RectangleF`. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω-αριστερής γωνίας αυτής της δομής `RectangleF`. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του [`X`](./x/) και του [`Width`](./width/) αυτής της δομής `RectangleF`. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος αυτής της `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτής της δομής `RectangleF`. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος αυτής της δομής `RectangleF`. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας αυτής της δομής `RectangleF`. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας αυτής της δομής `RectangleF`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Δημιουργεί μια δομή `RectangleF` με την επάνω-αριστερή γωνία και την κάτω-δεξιά γωνία στις καθορισμένες θέσεις. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Δημιουργεί ένα νέο [`Rectangle`](../rectangle/) από δύο καθορισμένα σημεία. Οι δύο κορυφές του δημιουργημένου [`Rectangle`](../rectangle/) θα είναι ίσες με τα περασμένα *point1* και *point2*. Συνήθως πρόκειται για τις αντίθετες κορυφές. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Δημιουργεί και επιστρέφει ένα φουσκωτό αντίγραφο της καθορισμένης δομής `RectangleF`. Το αντίγραφο φουσκώνεται κατά το καθορισμένο ποσό. Το αρχικό ορθογώνιο παραμένει αμετάβλητο. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Επιστρέφει μια δομή `RectangleF` που αντιπροσωπεύει την τομή δύο ορθογωνίων. Εάν δεν υπάρχει τομή, επιστρέφεται ένα κενό `RectangleF`. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Δημιουργεί το μικρότερο δυνατό τρίτο ορθογώνιο που μπορεί να περιέχει και τα δύο ορθογώνια που σχηματίζουν ένωση. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το *rect* περιέχεται πλήρως μέσα σε αυτή τη δομή `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή `RectangleF`. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Δοκιμάζει εάν το *obj* είναι ένα `RectangleF` με την ίδια θέση και μέγεθος με αυτό το `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού για αυτή τη δομή `RectangleF`. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Φουσκώνει αυτό το `RectangleF` κατά το καθορισμένο ποσό. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Φουσκώνει αυτή τη δομή `RectangleF` κατά το καθορισμένο ποσό. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Αντικαθιστά αυτή τη δομή `RectangleF` με την τομή του εαυτού της και της καθορισμένης δομής `RectangleF`. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Καθορίζει εάν αυτό το ορθογώνιο τέμνει το *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Κανονικοποιεί το ορθογώνιο κάνοντας το πλάτος και το ύψος του θετικά, το αριστερό μικρότερο από το δεξί και το άνω μικρότερο από το κάτω. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Μετατρέπει τα χαρακτηριστικά αυτού του `RectangleF` σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Υλοποιεί τον τελεστή /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Δοκιμάζει αν δύο δομές `RectangleF` έχουν ίση θέση και μέγεθος. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Μετατρέπει τη συγκεκριμένη δομή [`Rectangle`](../rectangle/) σε δομή `RectangleF`. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Δοκιμάζει αν δύο δομές `RectangleF` διαφέρουν στη θέση ή στο μέγεθος. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Υλοποιεί τον τελεστή *. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


