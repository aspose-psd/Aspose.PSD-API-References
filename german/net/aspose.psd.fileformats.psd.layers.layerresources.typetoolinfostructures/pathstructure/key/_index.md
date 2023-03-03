---
title: PathStructure.Key
second_title: Aspose.PSD für .NET-API-Referenz
description: PathStructure eigendom. Ruft den Strukturschlüssel ab.
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Ruft den Strukturschlüssel ab.

```csharp
public override int Key { get; }
```

### Beispiele

Der folgende Code demonstriert die Fähigkeit, Dateien mit der PathStructure-Struktur zu laden.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Siehe auch

* class [PathStructure](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* Montage [Aspose.PSD](../../../)


