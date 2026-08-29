---
title: "Enum RenderQuality"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Descrive la qualità di rendering del Warp"
type: docs
weight: 3990
url: /it/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Descrive la qualità di rendering di Warp.

```csharp
public enum RenderQuality
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Turbo | `4` | L'opzione più veloce, ma la qualità ne risente. |
| VeryFast | `18` | Se ti serve veloce, può essere adatto per piccole curvature. |
| Fast | `35` | Consente di rendere il rendering più veloce con una piccola perdita di qualità. |
| Normal | `60` | Valore consigliato per la maggior parte delle curvature |
| Good | `130` | Qualità superiore a quella standard, velocità più lenta. Consigliato per distorsioni marcate. |
| Excellent | `260` | L'opzione più lenta. Consigliata per distorsioni marcate e alte risoluzioni. |

## Esempi

Il codice seguente dimostra la proprietà WarpSettings.RenderQuality per configurare la deformazione warp.

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
        // Ottiene WarpSettings dal livello Smart
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Imposta la dimensione dell'area di elaborazione del warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Non dovrebbe esserci alcun errore qui
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


