---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PathStructure. Λαμβάνει ή ορίζει το πρόθεμα της διαδρομής"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Λαμβάνει ή ορίζει το πρόθεμα της διαδρομής.

```csharp
public string Prefix { get; set; }
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


