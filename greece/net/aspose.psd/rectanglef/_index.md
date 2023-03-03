---
title: Struct RectangleF
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.RectangleF struct. Αποθηκεύει ένα σύνολο τεσσάρων αριθμών κινητής υποδιαστολής που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.
type: docs
weight: 5350
url: /el/net/aspose.psd/rectanglef/
---
## RectangleF structure

Αποθηκεύει ένα σύνολο τεσσάρων αριθμών κινητής υποδιαστολής που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.

```csharp
public struct RectangleF
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Αρχικοποιεί μια νέα παρουσία του`RectangleF` δομή με την καθορισμένη θέση και μέγεθος. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Αρχικοποιεί μια νέα παρουσία του`RectangleF` δομή με την καθορισμένη θέση και μέγεθος. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Παίρνει μια νέα παρουσία του`RectangleF` δομή που έχει[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) και[`Height`](./height/) τιμές ορίστηκαν στο μηδέν. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Παίρνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του[`Y`](./y/) και[`Height`](./height/) από αυτό`RectangleF`δομή. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Λαμβάνει ή ορίζει το ύψος αυτού`RectangleF`δομή. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το[`Width`](./width/) ή[`Height`](./height/) ιδιοκτησία αυτού`RectangleF` έχει τιμή μηδέν. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x του αριστερού άκρου αυτού`RectangleF`δομή. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω αριστερής γωνίας αυτού`RectangleF`δομή. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Παίρνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του[`X`](./x/) και[`Width`](./width/) από αυτό`RectangleF`δομή. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος αυτού`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y του επάνω άκρου αυτού`RectangleF`δομή. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος αυτού`RectangleF`δομή. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτού`RectangleF`δομή. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτού`RectangleF`δομή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Δημιουργεί ένα`RectangleF` δομή με επάνω αριστερή γωνία και κάτω δεξιά γωνία στις καθορισμένες θέσεις. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Δημιουργεί ένα νέο[`Rectangle`](../rectangle/) από δύο καθορισμένα σημεία. Δύο κορυφές του δημιουργημένου[`Rectangle`](../rectangle/) θα είναι ίσο με το περασμένο*point1* και*point2* . Αυτές θα ήταν συνήθως οι αντίθετες κορυφές. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Δημιουργεί και επιστρέφει ένα διογκωμένο αντίγραφο του καθορισμένου`RectangleF`δομή. Το αντίγραφο διογκώνεται κατά το καθορισμένο ποσό. Το αρχικό ορθογώνιο παραμένει αμετάβλητο. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Επιστρέφει α`RectangleF` δομή που αντιπροσωπεύει την τομή δύο ορθογωνίων. Αν δεν υπάρχει διασταύρωση, και άδειο`RectangleF` επιστρέφεται. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Δημιουργεί το μικρότερο δυνατό τρίτο ορθογώνιο που μπορεί να περιέχει και τα δύο ορθογώνια που σχηματίζουν ένωση. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται σε αυτό`RectangleF`δομή. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από*rect* εμπεριέχεται εξ ολοκλήρου σε αυτό`RectangleF`δομή. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται σε αυτό`RectangleF`δομή. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Ελέγχει εάν*obj* είναι ένα`RectangleF` με την ίδια θέση και μέγεθος αυτού`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού για αυτό`RectangleF`δομή. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Φουσκώνει αυτό`RectangleF`κατά το καθορισμένο ποσό. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Φουσκώνει αυτό`RectangleF` δομή κατά το καθορισμένο ποσό. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Αντικαθιστά αυτό`RectangleF`δομή με τη διασταύρωση του εαυτού του και του καθορισμένου`RectangleF`δομή. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Καθορίζει αν αυτό το ορθογώνιο τέμνεται με*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Κανονικοποιεί το ορθογώνιο καθιστώντας το πλάτος και το ύψος του θετικά, αριστερά λιγότερο από δεξιά και πάνω λιγότερο από κάτω. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Προσαρμόζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Προσαρμόζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Μετατρέπει τα χαρακτηριστικά αυτού`RectangleF` σε μια συμβολοσειρά αναγνώσιμη από τον άνθρωπο. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Υλοποιεί τον τελεστή /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Ελέγχει εάν δύο`RectangleF` οι δομές έχουν ίση θέση και μέγεθος. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Μετατρέπει το καθορισμένο[`Rectangle`](../rectangle/) δομή σε α`RectangleF`δομή. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Ελέγχει εάν δύο`RectangleF` οι δομές διαφέρουν ως προς τη θέση ή το μέγεθος. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Υλοποιεί τον τελεστή *. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


