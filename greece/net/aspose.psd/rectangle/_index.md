---
title: "Δομή Rectangle"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Δομή Aspose.PSD.Rectangle. Αποθηκεύει ένα σύνολο τεσσάρων ακεραίων που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου."
type: docs
weight: 5840
url: /el/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Αποθηκεύει ένα σύνολο τεσσάρων ακεραίων που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.

```csharp
public struct Rectangle
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Rectangle` με τη καθορισμένη θέση και μέγεθος. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Rectangle` με τη καθορισμένη θέση και μέγεθος. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Λαμβάνει ένα νέο στιγμιότυπο της δομής `Rectangle` που έχει τις τιμές [`X`](./x/), [`Y`](./y/), [`Width`](./width/) και [`Height`](./height/) ορισμένες στο μηδέν. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα των τιμών ιδιοτήτων [`Y`](./y/) και [`Height`](./height/) αυτής της δομής `Rectangle`. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Λαμβάνει ή ορίζει το ύψος αυτής της δομής `Rectangle`. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν όλες οι αριθμητικές ιδιότητες αυτής της `Rectangle` έχουν τιμές μηδέν. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής `Rectangle`. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω-αριστερής γωνίας αυτής της δομής `Rectangle`. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα των τιμών ιδιοτήτων [`X`](./x/) και [`Width`](./width/) αυτής της δομής `Rectangle`. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος αυτής της `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτής της δομής `Rectangle`. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος αυτής της δομής `Rectangle`. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής `Rectangle`. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτής της δομής `Rectangle`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Μετατρέπει τη συγκεκριμένη δομή [`RectangleF`](../rectanglef/) σε δομή `Rectangle` στρογγυλοποιώντας τις τιμές του [`RectangleF`](../rectanglef/) προς τα επόμενα υψηλότερα ακέραια. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Δημιουργεί μια δομή `Rectangle` με τις καθορισμένες θέσεις των άκρων. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Δημιουργεί ένα νέο `Rectangle` από δύο καθορισμένα σημεία. Οι δύο κατακόρυφες πλευρές του δημιουργημένου `Rectangle` θα είναι ίσες με τα περασμένα *point1* και *point2*. Συνήθως αυτά είναι τα αντίθετα κορυφαία σημεία. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Δημιουργεί και επιστρέφει ένα διογκωμένο αντίγραφο της καθορισμένης δομής `Rectangle`. Το αντίγραφο διογκώνεται κατά το καθορισμένο ποσό. Η αρχική δομή `Rectangle` παραμένει αμετάβλητη. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Επιστρέφει μια τρίτη δομή `Rectangle` που αντιπροσωπεύει την τομή δύο άλλων δομών `Rectangle`. Εάν δεν υπάρχει τομή, επιστρέφεται ένα κενό `Rectangle`. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Μετατρέπει το καθορισμένο [`RectangleF`](../rectanglef/) σε `Rectangle` στρογγυλοποιώντας τις τιμές του [`RectangleF`](../rectanglef/) στα πλησιέστερα ακέραια. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Μετατρέπει το καθορισμένο [`RectangleF`](../rectanglef/) σε `Rectangle` περικόπτοντας τις τιμές του [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Λαμβάνει μια δομή `Rectangle` που περιέχει την ένωση δύο δομών `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το *rect* περιέχεται πλήρως μέσα σε αυτή τη δομή `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή `Rectangle`. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Δοκιμάζει εάν το *obj* είναι μια δομή `Rectangle` με την ίδια θέση και μέγεθος με αυτή τη δομή `Rectangle`. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτή τη δομή `Rectangle`. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Διογκώνει αυτό το `Rectangle` κατά το καθορισμένο ποσό. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Διογκώνει αυτό το `Rectangle` κατά το καθορισμένο ποσό. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Αντικαθιστά αυτό το `Rectangle` με την τομή του με τον καθορισμένο `Rectangle`. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Καθορίζει εάν αυτό το ορθογώνιο τέμνει το *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Κανονικοποιεί το ορθογώνιο κάνοντας το πλάτος και το ύψος του θετικά, το αριστερό μικρότερο από το δεξί και το άνω μικρότερο από το κάτω. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Μετατρέπει τα χαρακτηριστικά αυτού του `Rectangle` σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Δοκιμάζει εάν δύο δομές `Rectangle` έχουν ίση θέση και μέγεθος. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Δοκιμάζει εάν δύο δομές `Rectangle` διαφέρουν σε θέση ή μέγεθος. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


