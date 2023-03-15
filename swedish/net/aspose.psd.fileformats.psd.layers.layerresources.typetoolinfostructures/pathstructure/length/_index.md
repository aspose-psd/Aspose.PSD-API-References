---
title: PathStructure.Length
second_title: Aspose.PSD för .NET API-referens
description: PathStructure fast egendom. FårOSTypeStructure längd i byte.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Får[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) längd i byte.

```csharp
public override int Length { get; }
```

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

* class [PathStructure](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* hopsättning [Aspose.PSD](../../../)


