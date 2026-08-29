---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FillLayer मेथड। सभी गैर-पारदर्शी रंगों को नए रंग से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है। नोट: यदि आप इसे बिना पारदर्शिता वाली छवियों पर उपयोग करते हैं तो सभी रंग एक ही रंग में बदल जाएंगे।"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे।

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newColorArgb | Int32 | गैर-पारदर्शी रंगों को बदलने के लिए नया रंग ARGB मान। |

## उदाहरण

निम्नलिखित कोड CMYK कलरमोड 16 बिट के समर्थन और Aspose.PSD.Graphics क्लास का उपयोग करके ड्रॉइंग की क्षमता को दर्शाता है।

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### देखें भी

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


