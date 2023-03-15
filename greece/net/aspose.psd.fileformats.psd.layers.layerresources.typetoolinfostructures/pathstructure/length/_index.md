---
title: PathStructure.Length
second_title: Aspose.PSD για Αναφορά API .NET
description: PathStructure ιδιοκτησία. Λαμβάνει τοOSTypeStructure μήκος σε byte.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Λαμβάνει το[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) μήκος σε byte.

```csharp
public override int Length { get; }
```

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα φόρτωσης αρχείου με δομή PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Δείτε επίσης

* class [PathStructure](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* συνέλευση [Aspose.PSD](../../../)


