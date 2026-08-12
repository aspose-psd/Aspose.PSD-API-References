---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IfxsResource fält. Typverktygsinformationsnyckeln"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

Typverktygsinformationsnyckeln.

```csharp
public const int TypeToolKey;
```

## Exempel

Följande kod demonstrerar stödet för IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Exempel har 2 grupplager med effekter
    // Grupplager med en effekt
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Grupplager med många effekter
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Hämta antalet effekter och verifiera deras mängd
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // En effekt i grupplagret finns i resursen 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Två eller fler effekter i ett grupplager finns i resursen 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Lägg till en tredje skugga i ett grupplager med flera effekter
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Se även

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


