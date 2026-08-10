---
title: "क्लास GrdmResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource क्लास। क्लास GrdmResource। GradientMap लेयर के बारे में जानकारी रखता है"
type: docs
weight: 2770
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

क्लास GrdmResource. ग्रेडिएंट-मैप लेयर के बारे में जानकारी रखता है।

```csharp
public class GrdmResource : AdjustmentLayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GrdmResource](grdmresource/)(int) | `GrdmResource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | कलर मॉडल। जब 'Gradient type' = 'Noise' हो, तो हम 'Color Model' को RGB/SHB/LAB (3/4/6) में असाइन कर सकते हैं। |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | कलर पॉइंट्स को प्राप्त करता है या सेट करता है। |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | क्या ग्रेडिएंट डिथर किया गया है। |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | एक्सपैंशन काउंट (Photoshop 6.0 के लिए = 2)। |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | इस ग्रेडिएंट के लिए मोड निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)। |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | ग्रेडिएंट का नाम: यूनिकोड स्ट्रिंग, पैडेड। |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | इंटरपोलेशन। जब 'Gradient Type' = 'Solid' हो (GradientMode = 0) तो स्मूदनेस निर्धारित करता है। |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/) { get; set; } | ग्रेडिएंट के लिए इंटरपोलेशन मेथड प्राप्त करता या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; set; } | PixelDataFormat.Rgba64Bpp फॉर्मेट का अधिकतम रंग। रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है। |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; set; } | PixelDataFormat.Rgba64Bpp फॉर्मेट का न्यूनतम रंग। रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | इस संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। जब इंटरपोलेशन मेथड स्पष्ट रूप से संग्रहीत हो तो संस्करण 3 आवश्यक है। |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | क्या ग्रेडिएंट उलटा है। |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | Noise ग्रेडिएंट के लिए रंग उत्पन्न करने हेतु उपयोग किया गया रैंडम नंबर सीड। |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | रफ़नेस फ़ैक्टर। जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) असाइन कर सकते हैं। |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | ट्रांसपेरेंसी दिखाने के लिए फ़्लैग। जब 'Gradient type' = 'Noise' हो, तो हम 'Add transparency' को true सेट कर सकते हैं। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | ट्रांसपेरेंसी पॉइंट्स को प्राप्त करता है या सेट करता है। |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | वेक्टर रंग उपयोग करने के लिए फ़्लैग। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन डेटा को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

## उदाहरण

निम्नलिखित कोड GrdmResource संसाधन के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // वर्तमान मानों की जाँच करें
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // दूसरे ग्रेडिएंट रंग बिंदु के लिए लाल रंग
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // बदलाव वाले मानों की जाँच करें
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### देखें भी

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


