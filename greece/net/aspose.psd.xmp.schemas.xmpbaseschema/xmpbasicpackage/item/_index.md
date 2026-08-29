---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "XmpBasicPackage ιδιότητα. Λαμβάνει ή ορίζει το Object με το καθορισμένο κλειδί"
type: docs
weight: 20
url: /el/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Λαμβάνει ή ορίζει το Object με το καθορισμένο κλειδί.

```csharp
public override object this[string key] { get; set; }
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| κλειδί | Το κλειδί που αναγνωρίζει την τιμή. |

### Τιμή Επιστροφής

Επιστρέφει το Object με το καθορισμένο κλειδί.

### Property Value

Το Object.

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


