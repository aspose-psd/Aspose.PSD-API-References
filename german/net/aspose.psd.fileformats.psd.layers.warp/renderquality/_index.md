---
title: "Enum RenderQuality"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Beschreibt die Renderqualität von Warp"
type: docs
weight: 3990
url: /de/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Beschreibt die Renderqualität von Warp.

```csharp
public enum RenderQuality
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Turbo | `4` | Die schnellste Option, aber die Qualität leidet. |
| VeryFast | `18` | Wenn Sie es schnell benötigen, kann es für kleine Krümmungen geeignet sein. |
| Fast | `35` | Ermöglicht ein schnelleres Rendern mit einem kleinen Qualitätsverlust. |
| Normal | `60` | Empfohlener Wert für die meisten Krümmungen |
| Good | `130` | Höher als die Standardqualität, langsamere Geschwindigkeit. Empfohlen für starke Verzerrungen. |
| Excellent | `260` | Die langsamste Option. Empfohlen für starke Verzerrungen und hohe Auflösungen. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


