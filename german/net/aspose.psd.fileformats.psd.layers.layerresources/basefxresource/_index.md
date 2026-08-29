---
title: "Klasse BaseFxResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource Klasse. Ressource für Basiseffekte"
type: docs
weight: 2550
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

Basis‑Effekt‑Ressource.

```csharp
public abstract class BaseFxResource : LayerResource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Ruft die Versionsbeschreibung ab. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der Mehrfacheffekt-Ressource.

```csharp
[C#]

// PSD-Bild enthält 2 Drop-Shadow-Effekte
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // Es rendert das PSD-Bild mit 2 Drop-Shadow-Effekten
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Es fügt einen dritten Drop-Shadow-Effekt hinzu.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // Es rendert das PSD-Bild mit 3 Drop-Shadow-Effekten
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Die imfx-Ressource wird verwendet, wenn die Ebene mehrere Effekte desselben Typs enthält.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Es löscht alle Effekte.
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // Es rendert das PSD-Bild mit 1 Drop-Shadow-Effekt (andere wurden gelöscht).
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Die lfx2-Ressource wird verwendet, wenn die Ebene nicht mehrere Effekte desselben Typs enthält.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


