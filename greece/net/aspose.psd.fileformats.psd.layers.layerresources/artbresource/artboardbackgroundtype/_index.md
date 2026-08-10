---
title: "ArtBResource.ArtboardBackgroundType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ArtBResource ιδιότητα. Ανακτά ή ορίζει το ArtboardBackgroundType"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/artboardbackgroundtype/
---
{{< psd/tize >}}
## ArtBResource.ArtboardBackgroundType property

Ανακτά ή ορίζει το `ArtboardBackgroundType`

```csharp
public int ArtboardBackgroundType { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη εξαγωγής του ArtboardLayer ως ξεχωριστές εικόνες και όλες σε μία εικόνα.

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

### Δείτε επίσης

* class [ArtBResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


