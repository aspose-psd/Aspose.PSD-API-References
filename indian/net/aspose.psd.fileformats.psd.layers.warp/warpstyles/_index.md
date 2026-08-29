---
title: "Enum WarpStyles"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. समर्थित वॉर्प शैलियों के प्रकार"
type: docs
weight: 4020
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

समर्थित वॉर्प स्टाइल्स के प्रकार।

```csharp
public enum WarpStyles
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | `0` | यह शैली तब सेट होती है जब लेयर बिना विकृति के हो |
| Custom | `1` | बिंदुओं की मनमानी गति वाली शैली |
| Arc | `2` | वॉर्प की आर्क शैली |
| ArcUpper | `3` | वॉर्प की ऊपरी आर्क शैली |
| ArcLower | `4` | वॉर्प की निचली आर्क शैली |
| Arch | `5` | वॉर्प की आर्च शैली |
| Bulge | `6` | वॉर्प की बुल्क शैली |
| Flag | `7` | वॉर्प की फ़्लैग शैली |
| Fish | `8` | वॉर्प की फ़िश शैली |
| Rise | `9` | वॉर्प की राइज़ शैली |
| Wave | `10` | वॉर्प की वेव शैली |
| Twist | `11` | वॉर्प का ट्विस्ट प्रकार |
| Squeeze | `12` | वॉर्प का स्क्वीज़ प्रकार |
| Inflate | `13` | वॉर्प का इन्फ्लेट प्रकार |

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


