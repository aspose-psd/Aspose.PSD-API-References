---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IGradientFillSettings-Eigenschaft. Ruft die normalisierte Farbverlaufs-Skala in Prozent ab oder legt sie fest"
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Liest oder setzt die **normalisierte** Gradienten‑Skala (in Prozent).

```csharp
public int Scale { get; set; }
```

### Property Value

Die Skalierung.

## Beispiele

Das folgende Beispiel demonstriert, wie die Scale‑Eigenschaft verwendet wird, um ein FillLayer mit Verlauf zu skalieren.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // Abrufen eines FillLayers
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // Scale-Wert aktualisieren
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Siehe auch

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


