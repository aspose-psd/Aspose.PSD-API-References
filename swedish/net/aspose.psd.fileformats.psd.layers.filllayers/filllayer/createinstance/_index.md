---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FillLayer-metoden. Skapa en ny instans av FillLayer-klassen efter fyllningstyp"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Skapa en ny instans av [`FillLayer`](../)-klassen efter fyllningstyp.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillType | FillType | Typen av fyllningslager. |

### Returvärde

Returnerar en ny instans av [`FillLayer`](../)-klassen efter fyllningstyp.

## Exempel

Följande exempel demonstrerar hur man lägger till ett FillLayer‑lager av den typen vid körning.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


