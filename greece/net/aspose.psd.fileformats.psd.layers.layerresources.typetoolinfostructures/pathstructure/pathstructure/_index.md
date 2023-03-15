---
title: PathStructure.PathStructure
second_title: Aspose.PSD για Αναφορά API .NET
description: PathStructure κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουPathStructure τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Αρχικοποιεί μια νέα παρουσία του[`PathStructure`](../) τάξη.

```csharp
public PathStructure(ClassID keyName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | ClassID | Το όνομα κλειδιού. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* συνέλευση [Aspose.PSD](../../../)


