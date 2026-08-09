---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "WarpSettings-Eigenschaft. Liest oder schreibt den Wert der Größe des Verarbeitungsbereichs. Standardwert ist 10. Bereich ist 240."
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Liest oder schreibt den Wert der Größe des Verarbeitungsbereichs. Standardwert ist 10. Bereich ist [2;40].

```csharp
public int ProcessingArea { get; set; }
```

## Beispiele

Der folgende Code demonstriert die WarpSettings.ProcessingArea-Eigenschaft, um die Warp-Verzerrung zu konfigurieren.

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
        // Sie ruft WarpSettings aus der Smart‑Ebene ab
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Sie legt die Größe des Warp‑Verarbeitungsbereichs fest
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Hier sollte kein Fehler auftreten
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Siehe auch

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


