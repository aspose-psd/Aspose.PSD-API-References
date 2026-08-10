---
title: "Κλάση Metered"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.Metered κλάση. Παρέχει μεθόδους για ορισμό κλειδιού μετρητή"
type: docs
weight: 5610
url: /el/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Παρέχει μεθόδους για τον ορισμό κλειδιού μετρητή.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Λαμβάνει το όνομα του προϊόντος. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Ορίζει το δημόσιο και ιδιωτικό κλειδί μετρητή. Εάν αγοράσετε άδεια μετρητή, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί· συνήθως αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Λαμβάνει την πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Ελέγξτε αν το metered είναι αδειοδοτημένο |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το δημόσιο και ιδιωτικό κλειδί του metered

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


