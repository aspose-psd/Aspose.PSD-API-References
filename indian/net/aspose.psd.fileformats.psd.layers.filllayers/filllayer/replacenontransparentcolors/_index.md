---
title: FillLayer.ReplaceNonTransparentColors
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FillLayer तरक. सभ गैरपरदर्श रंगं क नए रंग से बदल देत है और चकन कनरं क बचने के लए मूल अल्फ मन क संरक्षत करत है
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

सभी गैर-पारदर्शी रंगों को नए रंग से बदल देता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है।

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorArgb | Int32 | गैर पारदर्शी रंगों को बदलने के लिए नया रंग ARGB मान। |

### उदाहरण

निम्नलिखित कोड CMYK ColorMode 16 बिट के समर्थन और Aspose.PSD.Graphics वर्ग का उपयोग करके ड्राइंग करने की क्षमता को प्रदर्शित करता है।

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### यह सभी देखें

* class [FillLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* सभा [Aspose.PSD](../../../)


