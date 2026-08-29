---
title: "Κλάση StringFormat"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.StringFormat. Περιλαμβάνει πληροφορίες διάταξης κειμένου όπως προσανατολισμός ευθυγράμμισης και εμφάνιση διαστημάτων (tab stops), χειρισμούς όπως η εισαγωγή τριπλής τελείας, η αντικατάσταση εθνικών ψηφίων και λειτουργίες OpenType. Αυτή η κλάση δεν μπορεί να κληρονομηθεί."
type: docs
weight: 6170
url: /el/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Ενσωματώνει πληροφορίες διάταξης κειμένου (όπως στοίχιση, προσανατολισμό και διακοπές στηλοθέτη) χειρισμούς εμφάνισης (όπως εισαγωγή αποσιωπητικών και αντικατάσταση εθνικών ψηφίων) και χαρακτηριστικά OpenType. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class StringFormat : DisposableObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο `StringFormat`. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Αρχικοποιεί ένα νέο αντικείμενο `StringFormat` από το καθορισμένο υπάρχον αντικείμενο `StringFormat`. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Αρχικοποιεί ένα νέο αντικείμενο `StringFormat` με την καθορισμένη απαρίθμηση [`StringFormatFlags`](../stringformatflags/) και γλώσσα. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Λαμβάνει ένα γενικό προεπιλεγμένο αντικείμενο `StringFormat`. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Λαμβάνει ένα γενικό τυπογραφικό αντικείμενο `StringFormat`. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Λαμβάνει ή ορίζει πληροφορίες στοίχισης κειμένου στον κατακόρυφο άξονα. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Λαμβάνει ή ορίζει το προσαρμοσμένο αναγνωριστικό χαρακτήρα. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Λαμβάνει ή ορίζει τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται με δυτικά ψηφία. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Λαμβάνει τον αριθμό των κενών μεταξύ της αρχής μιας γραμμής κειμένου και του πρώτου σημείου στηλοθέτη. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Λαμβάνει ή ορίζει μια απαρίθμηση [`StringFormatFlags`](../stringformatflags/) που περιέχει πληροφορίες μορφοποίησης. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Λαμβάνει ή ορίζει το αντικείμενο [`HotkeyPrefix`](../hotkeyprefix/) για αυτό το αντικείμενο `StringFormat`. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Λαμβάνει ή ορίζει τη στοίχιση γραμμής στον οριζόντιο άξονα. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Λαμβάνει έναν πίνακα αποστάσεων μεταξύ σημείων στηλοθέτη στις μονάδες που καθορίζονται από την ιδιότητα [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Λαμβάνει ή ορίζει την απαρίθμηση [`StringTrimming`](../stringtrimming/) για αυτό το αντικείμενο `StringFormat`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Δημιουργεί ένα βαθύ κλώνο αυτού του αντικειμένου `StringFormat`. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Ελέγχει αν τα αντικείμενα είναι ίσα. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού του τρέχοντος αντικειμένου. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Ορίζει σημεία στηλοθέτη για αυτό το αντικείμενο `StringFormat`. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Μετατρέπει αυτό το αντικείμενο `StringFormat` σε αναγνώσιμη από άνθρωπο συμβολοσειρά. |

### Δείτε επίσης

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


