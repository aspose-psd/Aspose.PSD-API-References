---
title: "ArtboardLayer.BackgroundColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ArtboardLayer प्रॉपर्टी। आर्टबोर्ड पृष्ठभूमि रंग प्राप्त या सेट करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers/artboardlayer/backgroundcolor/
---
{{< psd/tize >}}
## ArtboardLayer.BackgroundColor property

आर्टबोर्ड पृष्ठभूमि रंग को प्राप्त करता है या सेट करता है।

```csharp
public override Color BackgroundColor { get; set; }
```

## उदाहरण

निम्न कोड दर्शाता है कि ArtboardLayer को अलग-अलग छवियों और एक ही छवि में निर्यात करने का समर्थन कैसे किया जाता है।

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

### देखें भी

* struct [Color](../../../aspose.psd/color/)
* class [ArtboardLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


