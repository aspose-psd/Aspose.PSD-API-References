---
title: PathStructure.Prefix
second_title: Aspose.PSD για Αναφορά API .NET
description: PathStructure ιδιοκτησία. Λαμβάνει ή ορίζει το πρόθεμα διαδρομής.
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
## PathStructure.Prefix property

Λαμβάνει ή ορίζει το πρόθεμα διαδρομής.

```csharp
public string Prefix { get; set; }
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


