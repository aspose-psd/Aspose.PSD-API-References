---
title: PathStructure.Key
second_title: Aspose.PSD για Αναφορά API .NET
description: PathStructure ιδιοκτησία. Λαμβάνει το κλειδί δομής.
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Λαμβάνει το κλειδί δομής.

```csharp
public override int Key { get; }
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


