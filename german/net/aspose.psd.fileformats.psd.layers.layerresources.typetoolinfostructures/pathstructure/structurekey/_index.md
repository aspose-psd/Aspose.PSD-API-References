---
title: "PathStructure.StructureKey"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PathStructure-Feld. Identifiziert den Struktur‑Schlüssel"
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
{{< psd/tize >}}
## PathStructure.StructureKey field

Identifiziert den Struktur-Schlüssel.

```csharp
public const int StructureKey;
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


