---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "WarpSettings प्रॉपर्टी। warp रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है, गति और गुणवत्ता के बीच"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

वॉर्प रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है - गति और गुणवत्ता के बीच

```csharp
public RenderQuality RenderQuality { get; set; }
```

## उदाहरण

निम्नलिखित कोड WarpSettings.RenderQuality प्रॉपर्टी को दिखाता है जो वॉर्प विकृति को कॉन्फ़िगर करता है।

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // यह Smart Layer से WarpSettings प्राप्त करता है
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // यह वॉर्प प्रोसेसिंग क्षेत्र का आकार सेट करता है
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // यहाँ कोई त्रुटि नहीं होनी चाहिए
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### देखें भी

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


