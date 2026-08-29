---
title: "Klass ImfxResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ImfxResource klass. Imfx-resurs för flera effekter"
type: docs
weight: 2850
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/imfxresource/
---
{{< psd/tize >}}
## ImfxResource class

Imfx-resurs (multieffektsresurs)

```csharp
public sealed class ImfxResource : BaseFxResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImfxResource](imfxresource/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Hämtar beskrivarens version. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/imfxresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

## Exempel

Följande kod demonstrerar stöd för resurser med flera effekter.

```csharp
[C#]

// PSD-bilden innehåller 2 Drop Shadow-effekter
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // Den renderar PSD-bilden med 2 Drop Shadow-effekter
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Den lägger till en tredje Drop Shadow-effekt.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // Den renderar PSD-bilden med 3 Drop Shadow-effekter
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Imfx-resursen används om lagret innehåller flera effekter av samma typ.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Den rensar alla effekter
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // Den renderar PSD-bilden med 1 Drop Shadow-effekt (övriga raderades)
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Lfx2-resursen används om lagret inte innehåller flera effekter av samma typ.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Se även

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


