---
title: PathStructure.Length
second_title: Aspose.PSD für .NET-API-Referenz
description: PathStructure eigendom. Ruft die abOSTypeStructure Länge in Bytes.
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Ruft die ab[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) Länge in Bytes.

```csharp
public override int Length { get; }
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


