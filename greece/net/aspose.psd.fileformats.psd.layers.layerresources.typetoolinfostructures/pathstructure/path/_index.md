---
title: "PathStructure.Path"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PathStructure. Λαμβάνει ή ορίζει τη διαδρομή"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

Λαμβάνει ή ορίζει τη διαδρομή.

```csharp
public string Path { get; set; }
```

### Property Value

Η πλήρης διαδρομή.

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


