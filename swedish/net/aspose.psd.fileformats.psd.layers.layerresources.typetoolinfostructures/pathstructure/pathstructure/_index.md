---
title: PathStructure.PathStructure
second_title: Aspose.PSD för .NET API-referens
description: PathStructure byggare. Initierar en ny instans avPathStructure class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Initierar en ny instans av[`PathStructure`](../) class.

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyName | ClassID | Nyckelns namn. |

### Exempel

Följande kod visar förmågan att ladda fil med PathStructure-struktur.

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
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* hopsättning [Aspose.PSD](../../../)


