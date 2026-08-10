---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdLoadOptions. Λαμβάνει ή ορίζει εάν θα διατηρηθούν τα αρχικά pixel του στρώματος κατά την απόδοση εάν το στρώμα δεν έχει τροποποιηθεί"
type: docs
weight: 20
url: /el/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Λαμβάνει ή ορίζει αν διατηρηθούν τα αρχικά pixel του επιπέδου κατά τη απόδοση εάν το επίπεδο δεν έχει τροποποιηθεί.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` για να διατηρηθούν τα αρχικά pixel των αμετάβλητων στρωμάτων· διαφορετικά, `false`.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη νέα συμπεριφορά που αποτρέπει την αυτόματη επανασχεδίαση των επιπέδων πριν από τις αλλαγές.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Δείτε επίσης

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


