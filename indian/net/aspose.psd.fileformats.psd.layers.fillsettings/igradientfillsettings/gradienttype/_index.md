---
title: "IGradientFillSettings.GradientType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IGradientFillSettings प्रॉपर्टी। प्राप्त करता है या सेट करता है ग्रेडिएंट का प्रकार"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/
---
{{< psd/tize >}}
## IGradientFillSettings.GradientType property

ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

```csharp
public GradientType GradientType { get; set; }
```

### Property Value

ग्रेडिएंट का प्रकार।

## उदाहरण

निम्नलिखित कोड विभिन्न प्रकार के ग्रेडिएंट के साथ छवियों को सहेजता है और दिखाता है कि Aspose.PSD ग्रेडिएंट को कैसे ड्रॉ करता है।

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### देखें भी

* enum [GradientType](../../gradienttype/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


