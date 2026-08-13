---
title: "ArtboardLayer.BackgroundColor"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ArtboardLayer özelliği. Çizim tahtasının arka plan rengini alır veya ayarlar"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers/artboardlayer/backgroundcolor/
---
{{< psd/tize >}}
## ArtboardLayer.BackgroundColor property

Çizim tahtası arka plan rengini alır veya ayarlar.

```csharp
public override Color BackgroundColor { get; set; }
```

## Örnekler

Aşağıdaki kod, ArtboardLayer'ın ayrı ayrı görüntüler ve tek bir görüntü olarak dışa aktarımını desteklediğini gösterir.

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

### Ayrıca Bakınız

* struct [Color](../../../aspose.psd/color/)
* class [ArtboardLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


