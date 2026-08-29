---
title: "क्लास StrokeSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.StrokeSettings क्लास। शैप्स की स्ट्रोक सेटिंग्स"
type: docs
weight: 3420
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/
---
{{< psd/tize >}}
## StrokeSettings class

शेप्स के स्ट्रोक सेटिंग्स।

```csharp
public class StrokeSettings : IStrokeSettings
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [StrokeSettings](strokesettings/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/enabled/) { get; set; } | स्ट्रोक सक्षम है या नहीं, इसे प्राप्त करता है या सेट करता है। |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/fill/) { get; set; } | स्ट्रोक की फ़िल सेटिंग्स प्राप्त करता या सेट करता है। |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linealignment/) { get; set; } | स्ट्रोक शैली की लाइन संरेखण प्राप्त करता या सेट करता है। |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linecap/) { get; set; } | स्ट्रोक लाइन कैप प्रकार को प्राप्त करता है या सेट करता है। |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linedashset/) { get; set; } | लाइन डैश की एरे प्राप्त करता या सेट करता है। |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linejoin/) { get; set; } | स्ट्रोक लाइन जॉइन प्रकार को प्राप्त करता है या सेट करता है। |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/size/) { get; set; } | स्ट्रोक लाइन की चौड़ाई प्राप्त करता या सेट करता है। |

## उदाहरण

निम्नलिखित कोड शैप स्ट्रोक के रेंडरिंग समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "StrokeShapeTest.psd";
string outputFilePsd = "StrokeShapeTest.out.psd";
string outputFilePng = "StrokeShapeTest.out.png";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer = image.Layers[1];
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.GreenYellow;
    shapeLayer.Update();

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    gradientSettings.Dither = true;
    gradientSettings.Reverse = true;
    gradientSettings.AlignWithLayer = false;
    gradientSettings.Angle = 20;
    gradientSettings.Scale = 50;
    solidGradient.ColorPoints[0].Location = 100;
    solidGradient.ColorPoints[1].Location = 4000;
    solidGradient.TransparencyPoints[0].Location = 200;
    solidGradient.TransparencyPoints[1].Location = 3800;
    solidGradient.TransparencyPoints[0].Opacity = 90;
    solidGradient.TransparencyPoints[1].Opacity = 10;
    shapeLayer2.Update();

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    strokeSettings.Size = 15;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    strokeFillSettings.Color = Color.GreenYellow;
    shapeLayer3.Update();

    image.Save(outputFilePsd);
    image.Save(outputFilePng, new PngOptions());
}

// बदलाव डेटा की जाँच करें।
using (PsdImage image = (PsdImage)Image.Load(outputFilePsd))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    AssertAreEqual(Color.GreenYellow, fillSettings.Color);

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    AssertAreEqual(true, gradientSettings.Dither);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.AlignWithLayer);
    AssertAreEqual(20.0, gradientSettings.Angle);
    AssertAreEqual(50, gradientSettings.Scale);
    AssertAreEqual(100, solidGradient.ColorPoints[0].Location);
    AssertAreEqual(4000, solidGradient.ColorPoints[1].Location);
    AssertAreEqual(200, solidGradient.TransparencyPoints[0].Location);
    AssertAreEqual(3800, solidGradient.TransparencyPoints[1].Location);
    AssertAreEqual(90.0, solidGradient.TransparencyPoints[0].Opacity);
    AssertAreEqual(10.0, solidGradient.TransparencyPoints[1].Opacity);

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    AssertAreEqual(15.0, strokeSettings.Size);
    AssertAreEqual(Color.GreenYellow, strokeFillSettings.Color);
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

* interface [IStrokeSettings](../istrokesettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


