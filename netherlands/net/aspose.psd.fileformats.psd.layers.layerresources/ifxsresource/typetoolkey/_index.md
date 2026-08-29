---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "IfxsResource veld. De type tool info sleutel"
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

De type-tool-informatiesleutel.

```csharp
public const int TypeToolKey;
```

## Voorbeelden

De volgende code toont de ondersteuning van IfxsResource.

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
    // Voorbeeld heeft 2 groepslagen met effecten
    // Groepslaag met één effect
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Groepslaag met meerdere effecten
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Haal het aantal effecten op en controleer hun hoeveelheid
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Eén effect in de groepslaag bevindt zich in resource 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Twee of meer effecten in een groepslaag bevinden zich in resource 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Voeg een derde schaduw toe aan een groepslaag met meerdere effecten
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Zie ook

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


