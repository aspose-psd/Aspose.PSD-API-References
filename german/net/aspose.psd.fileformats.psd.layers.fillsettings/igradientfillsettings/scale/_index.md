---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD für .NET-API-Referenz
description: IGradientFillSettings eigendom. Ruft die Skalierung ab oder legt sie fest.
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Ruft die Skalierung ab oder legt sie fest.

```csharp
public int Scale { get; set; }
```

### Eigentumswert

Die Waage.

### Beispiele

Das folgende Beispiel zeigt, wie die Scale-Eigenschaft verwendet wird, um FillLayer mit Farbverlauf zu skalieren.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // eine Füllebene erhalten
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

    // Skalenwert aktualisieren
    settings.Scale = 200;
    fillLayer.Update(); // Aktualisiert Pixeldaten

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Siehe auch

* interface [IGradientFillSettings](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* Montage [Aspose.PSD](../../../)


