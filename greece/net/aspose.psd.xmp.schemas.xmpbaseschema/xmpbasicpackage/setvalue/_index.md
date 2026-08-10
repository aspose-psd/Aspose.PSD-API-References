---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "XmpBasicPackage μέθοδος. Ορίζει την τιμή"
type: docs
weight: 120
url: /el/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Ορίζει την τιμή.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | String | Η αναπαράσταση τύπου string του κλειδιού που ταυτοποιείται με την προστιθέμενη τιμή. |
| τιμή | IXmlValue | Η τιμή για προσθήκη. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


