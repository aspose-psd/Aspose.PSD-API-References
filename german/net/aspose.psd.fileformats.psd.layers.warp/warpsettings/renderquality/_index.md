---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "WarpSettings-Eigenschaft. Ruft den Wert der Renderqualität der Verzerrung ab oder legt ihn fest, zwischen Geschwindigkeit und Qualität"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Liest oder setzt den Wert der Verzerrungs-Renderqualität – zwischen Geschwindigkeit und Qualität

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Beispiele

Der folgende Code demonstriert die WarpSettings.RenderQuality‑Eigenschaft, um die Warp‑Deformation zu konfigurieren.

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
        // Sie ruft WarpSettings aus der Smart‑Ebene ab
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Sie legt die Größe des Warp‑Verarbeitungsbereichs fest
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Hier sollte kein Fehler auftreten
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Siehe auch

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


