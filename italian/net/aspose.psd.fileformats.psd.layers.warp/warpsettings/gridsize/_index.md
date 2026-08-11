---
title: "WarpSettings.GridSize"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà WarpSettings. Ottiene o imposta la dimensione della griglia di deformazione. Il valore predefinito è 1"
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Ottiene o imposta la dimensione della griglia warp. Il valore predefinito è 1.

```csharp
public Size GridSize { get; set; }
```

## Esempi

Il codice seguente dimostra il supporto della proprietà WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Ottieni le impostazioni di deformazione
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Imposta nuova dimensione
    // Per Photoshop il valore può essere compreso tra 1 e 50 e non è possibile salvare correttamente il file PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Imposta valore valido
    warpSettings.GridSize = new Size(3, 3);

    // Esegui il rendering del file di esempio con griglia x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Vedi anche

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


