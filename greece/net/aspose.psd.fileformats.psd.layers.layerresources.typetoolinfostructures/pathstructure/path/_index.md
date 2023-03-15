---
title: PathStructure.Path
second_title: Aspose.PSD για Αναφορά API .NET
description: PathStructure ιδιοκτησία. Λαμβάνει ή ορίζει τη διαδρομή.
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Λαμβάνει ή ορίζει τη διαδρομή.

```csharp
public string Path { get; set; }
```

### Αξία περιουσίας

Η πλήρης διαδρομή.

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


