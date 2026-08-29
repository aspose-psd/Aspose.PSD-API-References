---
title: "License.SetLicense"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος License. Παρέχει άδεια στο στοιχείο"
type: docs
weight: 20
url: /el/net/aspose.psd/license/setlicense/
---
{{< psd/tize >}}
## SetLicense(string) {#setlicense_1}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(string licenseName)
```

## Σχόλια

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Έγγυρη διαδρομή.

2. Ο φάκελος που περιέχει τη συναρμολόγηση του στοιχείου Aspose.

3. Ο φάκελος που περιέχει τη συναρμολόγηση κλήσης του πελάτη.

4. Ο φάκελος που περιέχει τη συναρμολόγηση εισόδου (εκκίνησης).

5. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Έγγυρη διαδρομή.

2. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στο φάκελο που περιέχει το στοιχείο, στο φάκελο που περιέχει το καλούντα σύνολο, στο φάκελο του κύριου συνόλου και, στη συνέχεια, στους ενσωματωμένους πόρους του καλούντα συνόλου.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης.

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Μια ροή που περιέχει την άδεια. |

## Σχόλια

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

## Παραδείγματα

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


