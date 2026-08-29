---
title: "Enum RenderQuality"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Het beschrijft de renderkwaliteit van Warp"
type: docs
weight: 3990
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Het beschrijft de renderkwaliteit van Warp.

```csharp
public enum RenderQuality
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Turbo | `4` | De snelste optie, maar de kwaliteit lijdt eronder. |
| VeryFast | `18` | Als je het snel nodig hebt, kan het geschikt zijn voor kleine krommingen. |
| Fast | `35` | Staat je toe om het renderen sneller te maken met een kleine kwaliteitsvermindering. |
| Normal | `60` | Aanbevolen waarde voor de meeste krommingen |
| Good | `130` | Hoger dan standaardkwaliteit, tragere snelheid. Aanbevolen voor sterke vervormingen. |
| Excellent | `260` | De langzaamste optie. Aanbevolen voor sterke vervormingen en hoge resoluties. |

## Voorbeelden

De volgende code toont de WarpSettings.RenderQuality-eigenschap om warp-deformatie te configureren.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Het haalt WarpSettings op van de Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Het stelt de grootte van het warp-verwerkingsgebied in
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Er zou hier geen fout moeten zijn
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Zie ook

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


