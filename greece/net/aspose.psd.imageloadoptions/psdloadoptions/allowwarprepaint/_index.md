---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdLoadOptions. Λαμβάνει ή ορίζει εάν θα αποθηκευτεί η αποδοθείσα εικόνα με ή χωρίς παραμόρφωση"
type: docs
weight: 30
url: /el/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Λαμβάνει ή ορίζει αν αποθηκευτεί με την αποδοθείσα εικόνα, με ή χωρίς παραμόρφωση.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` αποδίδει την εικόνα με παραμόρφωση `false`.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την απόδοση του εφέ Warp.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### Δείτε επίσης

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


