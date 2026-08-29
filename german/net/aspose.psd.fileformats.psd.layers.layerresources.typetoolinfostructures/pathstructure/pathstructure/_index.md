---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PathStructure-Konstruktor. Initialisiert eine neue Instanz der PathStructure-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Initialisiert eine neue Instanz der [`PathStructure`](../)-Klasse.

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keyName | ClassID | Der Schlüsselname. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


