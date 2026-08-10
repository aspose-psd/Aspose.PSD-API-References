---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "WarpSettings प्रॉपर्टी। प्रोसेसिंग एरिया आकार का मान प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 10 है। रेंज 240 है।"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

प्रोसेसिंग एरिया आकार का मान प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 10 है। रेंज [2;40] है।

```csharp
public int ProcessingArea { get; set; }
```

## उदाहरण

निम्नलिखित कोड WarpSettings.ProcessingArea प्रॉपर्टी को दिखाता है जो वार्प डिफॉर्मेशन को कॉन्फ़िगर करता है।

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // यह Smart Layer से WarpSettings प्राप्त करता है
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // यह वॉर्प प्रोसेसिंग क्षेत्र का आकार सेट करता है
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // यहाँ कोई त्रुटि नहीं होनी चाहिए
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### देखें भी

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


