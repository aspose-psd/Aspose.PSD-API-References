---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής PathStructure. Αρχικοποιεί μια νέα παρουσία της κλάσης PathStructure"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Αρχικοποιεί μια νέα παρουσία της κλάσης [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | ClassID | Το όνομα κλειδιού. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


