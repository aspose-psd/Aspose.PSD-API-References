---
title: "Klass VectorPathDataResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource-klass. Klass VectorPathDataResource. Denna resurs innehåller information om vektorlagermask"
type: docs
weight: 3740
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
{{< psd/tize >}}
## VectorPathDataResource class

Klassen VectorPathDataResource. Denna resurs innehåller information om vektorlagermask.

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Hämtar eller anger ett värde som indikerar om den här instansen är inaktiverad. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Hämtar eller anger ett värde som indikerar om den här instansen är inverterad. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Hämtar eller anger ett värde som indikerar om den här instansen inte är länkad. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Hämtar eller anger sökvägsregistren. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Hämtar eller anger versionen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Exempel

Följande exempel visar stöd för bearbetning av lagervektormasker. Hur redigering av banor fungerar och hur Aspose.PSD ritar den slutliga bilden.

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// Läsning
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // Gör ändringar i vektorbanpunkterna
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // Exportering
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


