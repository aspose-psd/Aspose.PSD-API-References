---
title: "WarpSettings.ProcessingArea"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà WarpSettings. Ottiene o imposta il valore della dimensione dell'area di elaborazione. Il valore predefinito è 10. L'intervallo è 240"
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Ottiene o imposta il valore della dimensione dell'area di elaborazione. Il valore predefinito è 10. L'intervallo è [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Esempi

Il codice seguente dimostra la proprietà WarpSettings.ProcessingArea per configurare la deformazione

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Ottiene WarpSettings dal livello Smart
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Imposta la dimensione dell'area di elaborazione del warp
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Non dovrebbe esserci alcun errore qui
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Vedi anche

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


