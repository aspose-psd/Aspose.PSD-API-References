---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "WarpSettings प्रॉपर्टी। वॉर्प ग्रिड का आकार प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 1 है।"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

वॉर्प ग्रिड का आकार प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 1 है।

```csharp
public Size GridSize { get; set; }
```

## उदाहरण

निम्नलिखित कोड WarpSettings.GridSize प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // वॉर्प सेटिंग्स प्राप्त करें
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // नया आकार सेट करें
    // फ़ोटोशॉप के लिए मान 1 से 50 के बीच हो सकता है और आप PSD फ़ाइल को सही ढंग से सहेज नहीं सकते।
    warpSettings.GridSize = new Size(100, 100);

    // वैध मान सेट करें
    warpSettings.GridSize = new Size(3, 3);

    // x3 ग्रिड के साथ उदाहरण फ़ाइल रेंडर करें
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### देखें भी

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


