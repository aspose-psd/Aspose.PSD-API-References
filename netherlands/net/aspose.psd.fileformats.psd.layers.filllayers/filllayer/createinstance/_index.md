---
title: FillLayer.CreateInstance
second_title: Aspose.PSD voor .NET API-referentie
description: FillLayer methode. Bouw een nieuw exemplaar van hetFillLayer klasse op type vulling.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Bouw een nieuw exemplaar van het[`FillLayer`](../) klasse op type vulling.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillType | FillType | Het type opvullaag. |

### Winstwaarde

Retourneert een nieuw exemplaar van de[`FillLayer`](../) klasse op type vulling.

### Voorbeelden

Het volgende voorbeeld laat zien hoe de laag van het type FillLayer tijdens runtime kan worden toegevoegd.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### Zie ook

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* montage [Aspose.PSD](../../../)


