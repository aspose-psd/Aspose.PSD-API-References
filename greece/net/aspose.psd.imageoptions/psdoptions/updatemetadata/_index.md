---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdOptions. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα. Εάν η τιμή είναι true, τα μεταδεδομένα θα ενημερωθούν κατά την αποθήκευση μιας εικόνας"
type: docs
weight: 110
url: /el/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [update metadata]. Εάν η τιμή είναι true, τα μεταδεδομένα θα ενημερωθούν κατά την αποθήκευση μιας εικόνας.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` εάν [update metadata]; διαφορετικά, `false`.

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

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


