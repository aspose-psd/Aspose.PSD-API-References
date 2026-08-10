---
title: "क्लास WarpSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings क्लास। वॉर्प वाले लेयर के पैरामीटर"
type: docs
weight: 4010
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

वॉर्प वाले लेयर के पैरामीटर।

```csharp
public class WarpSettings
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | नया उदाहरण `WarpSettings` क्लास का प्रारंभ करता है। |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | नया उदाहरण `WarpSettings` क्लास का प्रारंभ करता है। |
| [WarpSettings](warpsettings/#constructor_2)(PointF[], Rectangle) | नया उदाहरण `WarpSettings` क्लास का प्रारंभ करता है। |
| [WarpSettings](warpsettings/#constructor_3)(PointF[], Rectangle, WarpStyles) | नया उदाहरण `WarpSettings` क्लास का प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | वॉर्प इमेज की सीमाएँ प्राप्त करता है या सेट करता है |
| [GridSize](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/) { get; set; } | वॉर्प ग्रिड का आकार प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 1 है। |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | फ़ोटोशॉप मेष पॉइंट्स |
| [RenderQuality](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/) { get; set; } | वॉर्प रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है - गति और गुणवत्ता के बीच |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | रोटेट मान प्राप्त करता है या सेट करता है |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | वॉर्प की शैली प्राप्त करता है या सेट करता है |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | वॉर्प का मान प्राप्त करता है या सेट करता है |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि कैसे WarpSettings को हेरफेर करके SmartObjectLayer और TexLayer पर वॉर्प परिवर्तन किया जाता है।

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


