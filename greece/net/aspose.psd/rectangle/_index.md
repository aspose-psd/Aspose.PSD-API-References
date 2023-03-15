---
title: Struct Rectangle
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Rectangle struct. Αποθηκεύει ένα σύνολο τεσσάρων ακεραίων που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.
type: docs
weight: 5340
url: /el/net/aspose.psd/rectangle/
---
## Rectangle structure

Αποθηκεύει ένα σύνολο τεσσάρων ακεραίων που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.

```csharp
public struct Rectangle
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Αρχικοποιεί μια νέα παρουσία του`Rectangle` δομή με την καθορισμένη θέση και μέγεθος. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Αρχικοποιεί μια νέα παρουσία του`Rectangle` δομή με την καθορισμένη θέση και μέγεθος. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Παίρνει μια νέα παρουσία του`Rectangle` δομή που έχει[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) και[`Height`](./height/) τιμές ορίστηκαν στο μηδέν. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Παίρνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του[`Y`](./y/) και[`Height`](./height/) αξίες ιδιοκτησίας αυτού`Rectangle`δομή. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Λαμβάνει ή ορίζει το ύψος αυτού`Rectangle`δομή. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν όλες οι αριθμητικές ιδιότητες αυτού`Rectangle` έχουν τιμές μηδέν. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x του αριστερού άκρου αυτού`Rectangle`δομή. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω αριστερής γωνίας αυτού`Rectangle`δομή. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Παίρνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του[`X`](./x/) και[`Width`](./width/) αξίες ιδιοκτησίας αυτού`Rectangle`δομή. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος αυτού`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y του επάνω άκρου αυτού`Rectangle`δομή. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος αυτού`Rectangle`δομή. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτού`Rectangle`δομή. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτού`Rectangle`δομή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Μετατρέπει το καθορισμένο[`RectangleF`](../rectanglef/) δομή σε α`Rectangle` δομή με στρογγυλοποίηση του[`RectangleF`](../rectanglef/) τιμές στις επόμενες υψηλότερες ακέραιες τιμές. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Δημιουργεί ένα`Rectangle` δομή με τις καθορισμένες θέσεις άκρων. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Δημιουργεί ένα νέο`Rectangle` από δύο καθορισμένα σημεία. Δύο κάθετες του δημιουργημένου`Rectangle` θα είναι ίσο με το περασμένο*point1* και*point2* . Αυτές θα ήταν συνήθως οι αντίθετες κορυφές. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Δημιουργεί και επιστρέφει ένα διογκωμένο αντίγραφο του καθορισμένου`Rectangle`δομή. Το αντίγραφο διογκώνεται κατά το καθορισμένο ποσό. Το πρωτότυπο`Rectangle` η δομή παραμένει αμετάβλητη. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Επιστρέφει ένα τρίτο`Rectangle` δομή που αντιπροσωπεύει τη διασταύρωση δύο άλλων`Rectangle` δομές. Εάν δεν υπάρχει διασταύρωση, άδειο`Rectangle` επιστρέφεται. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Μετατρέπει το καθορισμένο[`RectangleF`](../rectanglef/) σε α`Rectangle` με στρογγυλοποίηση του[`RectangleF`](../rectanglef/) τιμές στις πλησιέστερες ακέραιες τιμές. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Μετατρέπει το καθορισμένο[`RectangleF`](../rectanglef/) σε α`Rectangle` περικόπτοντας το[`RectangleF`](../rectanglef/) τιμές. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Παίρνει ένα`Rectangle` δομή που περιέχει την ένωση δύο`Rectangle` δομές. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται σε αυτό`Rectangle`δομή. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από*rect* εμπεριέχεται εξ ολοκλήρου σε αυτό`Rectangle`δομή. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Καθορίζει εάν το καθορισμένο σημείο περιέχεται σε αυτό`Rectangle`δομή. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Ελέγχει εάν*obj* είναι ένα`Rectangle`δομή με την ίδια θέση και μέγεθος αυτού`Rectangle`δομή. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτό`Rectangle`δομή. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Φουσκώνει αυτό`Rectangle`κατά το καθορισμένο ποσό. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Φουσκώνει αυτό`Rectangle`κατά το καθορισμένο ποσό. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Αντικαθιστά αυτό`Rectangle` με τη διασταύρωση του εαυτού του και του καθορισμένου`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Καθορίζει αν αυτό το ορθογώνιο τέμνεται με*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Κανονικοποιεί το ορθογώνιο καθιστώντας το πλάτος και το ύψος του θετικά, αριστερά λιγότερο από δεξιά και πάνω λιγότερο από κάτω. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Προσαρμόζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Προσαρμόζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Μετατρέπει τα χαρακτηριστικά αυτού`Rectangle` σε μια συμβολοσειρά αναγνώσιμη από τον άνθρωπο. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Ελέγχει εάν δύο`Rectangle` οι δομές έχουν ίση θέση και μέγεθος. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Ελέγχει εάν δύο`Rectangle` οι δομές διαφέρουν ως προς τη θέση ή το μέγεθος. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


