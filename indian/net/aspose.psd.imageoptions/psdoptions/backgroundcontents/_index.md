---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdOptions प्रॉपर्टी। बैकग्राउंड का रंग प्राप्त करता है या सेट करता है। यह पारदर्शी वस्तुओं के नीचे देखा जा सकता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। यह पारदर्शी वस्तुओं के नीचे देखा जा सकता है।

```csharp
public RawColor BackgroundContents { get; set; }
```

## उदाहरण

निम्नलिखित कोड PsdOptions में BackgroundContents प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

// psd फ़ाइल प्रीव्यू में अर्ध-पारदर्शिता को गलत तरीके से प्रोसेस किया गया है।
// BackgroundContents को White पर असाइन किया गया है। पारदर्शी क्षेत्रों का रंग सफ़ेद होना चाहिए।

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### देखें भी

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


