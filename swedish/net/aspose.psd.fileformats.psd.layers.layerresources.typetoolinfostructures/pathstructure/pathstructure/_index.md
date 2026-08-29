---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PathStructure-konstruktor. Initierar en ny instans av klassen PathStructure"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Initierar en ny instans av klassen [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyName | ClassID | Nyckelnamnet. |

## Exempel

Följande kod demonstrerar förmågan att läsa in en fil med PathStructure-struktur.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Se även

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


