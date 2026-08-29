---
title: "Δομή Size"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Δομή Aspose.PSD.Size. Αντιπροσωπεύει το μέγεθος"
type: docs
weight: 6050
url: /el/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Αντιπροσωπεύει το μέγεθος.

```csharp
public struct Size
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Size](size/#constructor)(Point) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Size` από το καθορισμένο [`Point`](../point/). |
| [Size](size/#constructor_1)(int, int) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Size` από τις καθορισμένες διαστάσεις. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Λαμβάνει ένα νέο στιγμιότυπο της δομής `Size` που έχει τιμές [`Width`](./width/) και [`Height`](./height/) ορισμένες στο μηδέν. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Λαμβάνει ή ορίζει το κατακόρυφο στοιχείο αυτής της `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η `Size` έχει πλάτος και ύψος ίσο με 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Λαμβάνει ή ορίζει το οριζόντιο στοιχείο αυτής της `Size`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Προσθέτει το πλάτος και το ύψος μιας δομής `Size` στο πλάτος και το ύψος μιας άλλης δομής `Size`. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Μετατρέπει τη συγκεκριμένη δομή [`SizeF`](../sizef/) σε δομή `Size` στρογγυλοποιώντας τις τιμές της δομής `Size` προς το επόμενο μεγαλύτερο ακέραιο. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Μετατρέπει τη συγκεκριμένη δομή [`SizeF`](../sizef/) σε δομή `Size` στρογγυλοποιώντας τις τιμές της δομής [`SizeF`](../sizef/) στο πλησιέστερο ακέραιο. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Αφαιρεί το πλάτος και το ύψος μιας δομής `Size` από το πλάτος και το ύψος μιας άλλης δομής `Size`. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Μετατρέπει τη συγκεκριμένη δομή [`SizeF`](../sizef/) σε δομή `Size` περικόπτοντας τις τιμές της δομής [`SizeF`](../sizef/) στο επόμενο μικρότερο ακέραιο. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Δοκιμάζει αν το συγκεκριμένο αντικείμενο είναι μια `Size` με τις ίδιες διαστάσεις με αυτή τη `Size`. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη δομή `Size`. |
| override [ToString](../../aspose.psd/size/tostring/)() | Δημιουργεί μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτή τη `Size`. |
| [operator +](../../aspose.psd/size/op_addition/) | Προσθέτει το πλάτος και το ύψος μιας δομής `Size` στο πλάτος και το ύψος μιας άλλης δομής `Size`. |
| [operator ==](../../aspose.psd/size/op_equality/) | Δοκιμάζει εάν δύο δομές `Size` είναι ίσες. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Μετατρέπει τη συγκεκριμένη `Size` σε [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Μετατρέπει τη συγκεκριμένη `Size` σε [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Δοκιμάζει εάν δύο δομές `Size` είναι διαφορετικές. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Αφαιρεί το πλάτος και το ύψος μιας δομής `Size` από το πλάτος και το ύψος μιας άλλης δομής `Size`. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


