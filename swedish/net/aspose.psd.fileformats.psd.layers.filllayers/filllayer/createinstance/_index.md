---
title: FillLayer.CreateInstance
second_title: Aspose.PSD för .NET API-referens
description: FillLayer metod. Bygg en ny instans avFillLayer klass efter typ av fyllning.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Bygg en ny instans av[`FillLayer`](../) klass efter typ av fyllning.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillType | FillType | Typen av fyllningslager. |

### Returvärde

Returnerar en ny instans av[`FillLayer`](../) klass efter typ av fyllning.

### Exempel

Följande exempel visar hur man lägger till typen FillLayer under körning.

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

### Se även

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* hopsättning [Aspose.PSD](../../../)


