---
title: "ArtBResource.ArtboardBackgroundType"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà ArtBResource. Ottiene o imposta l'ArtboardBackgroundType"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/artboardbackgroundtype/
---
{{< psd/tize >}}
## ArtBResource.ArtboardBackgroundType property

Ottiene o imposta l'`ArtboardBackgroundType`

```csharp
public int ArtboardBackgroundType { get; set; }
```

## Esempi

Il codice seguente dimostra il supporto per l'esportazione di ArtboardLayer come immagini separate e tutte in un'unica immagine.

```csharp
[C#]

string srcFile = "artboard2.psd";

string outFilePng0 = "art0.png";
string outFilePng1 = "art1.png";
string outFilePng2 = "art2.png";
string outFilePng3 = "art3.png";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtboardLayer art1 = (ArtboardLayer)psdImage.Layers[4];
    ArtboardLayer art2 = (ArtboardLayer)psdImage.Layers[9];
    ArtboardLayer art3 = (ArtboardLayer)psdImage.Layers[14];

    var pngSaveOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
    art1.Save(outFilePng1, pngSaveOptions);
    art2.Save(outFilePng2, pngSaveOptions);
    art3.Save(outFilePng3, pngSaveOptions);

    psdImage.Save(outFilePng0, pngSaveOptions);
}
```

### Vedi anche

* class [ArtBResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


