---
title: "ArtBResource.Color"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ArtBResource. الحصول أو تعيين اللون"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/color/
---
{{< psd/tize >}}
## ArtBResource.Color property

الحصول أو تعيين `Color`

```csharp
public Color Color { get; set; }
```

## أمثلة

الكود التالي يوضح دعم تصدير ArtboardLayer كصور منفصلة وكجميعها في صورة واحدة.

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

### انظر أيضًا

* struct [Color](../../../aspose.psd/color/)
* class [ArtBResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


