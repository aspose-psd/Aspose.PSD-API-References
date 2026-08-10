---
title: "PathStructure.StructureKey"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Πεδίο PathStructure. Προσδιορίζει το κλειδί της δομής"
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
{{< psd/tize >}}
## PathStructure.StructureKey field

Αναγνωρίζει το κλειδί της δομής.

```csharp
public const int StructureKey;
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα φόρτωσης αρχείου με τη δομή PathStructure.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


