---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "XmpBasicPackage μέθοδος. Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί"
type: docs
weight: 40
url: /el/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί.

```csharp
public override bool ContainsKey(string key)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | String | Το κλειδί που θα ελεγχθεί. |

### Τιμή Επιστροφής

Επιστρέφει true εάν το καθορισμένο κλειδί περιέχει το κλειδί.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη χρήση της επιλογής UpdateMetadata για την ενημέρωση της τιμής CreatorTool στα δεδομένα xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Εάν θέλετε το εργαλείο δημιουργού να αλλάξει, βεβαιωθείτε ότι η ιδιότητα "UpdateMetadata" είναι ορισμένη σε true. Είναι ορισμένη σε true από προεπιλογή.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Αποθήκευση της εικόνας.
    image.Save(path, psdOptions);

    // Έλεγχος του εργαλείου δημιουργού στον κώδικα.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Εδώ θα ενημερωθεί η πληροφορία του εργαλείου δημιουργού.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Δείτε επίσης

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


