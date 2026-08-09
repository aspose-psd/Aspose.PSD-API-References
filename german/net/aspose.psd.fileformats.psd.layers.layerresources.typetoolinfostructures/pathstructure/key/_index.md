---
title: "PathStructure.Key"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PathStructure-Eigenschaft. Gibt den Struktur‑Schlüssel zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

Liest den Struktur-Schlüssel.

```csharp
public override int Key { get; }
```

## Beispiele

Der folgende Code demonstriert die Fähigkeit, eine Datei mit der PathStructure-Struktur zu laden.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


