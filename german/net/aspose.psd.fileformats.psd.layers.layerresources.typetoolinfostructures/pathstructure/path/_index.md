---
title: PathStructure.Path
second_title: Aspose.PSD für .NET-API-Referenz
description: PathStructure eigendom. Ruft den Pfad ab oder legt ihn fest.
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Ruft den Pfad ab oder legt ihn fest.

```csharp
public string Path { get; set; }
```

### Eigentumswert

Der vollständige Pfad.

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


