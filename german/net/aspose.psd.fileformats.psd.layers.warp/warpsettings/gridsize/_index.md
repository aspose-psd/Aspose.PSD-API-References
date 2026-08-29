---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "WarpSettings-Eigenschaft. Ruft die Größe des Verzerrungsrasters ab oder legt sie fest. Standard ist 1"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Liest oder setzt die Größe des Verzerrungsrasters. Standardwert ist 1.

```csharp
public Size GridSize { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der WarpSettings.GridSize-Eigenschaft.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Warp-Einstellungen abrufen
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Neue Größe festlegen
    // Für Photoshop kann der Wert zwischen 1 und 50 liegen und Sie können die PSD-Datei nicht korrekt speichern.
    warpSettings.GridSize = new Size(100, 100);

    // Gültigen Wert festlegen
    warpSettings.GridSize = new Size(3, 3);

    // Beispieldatei mit x3-Raster rendern
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Siehe auch

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


