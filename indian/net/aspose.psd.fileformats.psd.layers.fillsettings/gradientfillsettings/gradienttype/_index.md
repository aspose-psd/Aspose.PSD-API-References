---
title: GradientFillSettings.GradientType
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: GradientFillSettings संपत्त. ग्रेडएंट के प्रकर क प्रप्त य सेट करत है
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

ग्रेडिएंट के प्रकार को प्राप्त या सेट करता है।

```csharp
public GradientType GradientType { get; set; }
```

### संपत्ति मूल्य

ग्रेडिएंट का प्रकार।

### उदाहरण

निम्न कोड विभिन्न प्रकार के ढाल के साथ छवियों को सहेजता है और दिखाता है कि कैसे Aspose.PSD ढाल को खींचता है।

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

### यह सभी देखें

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* सभा [Aspose.PSD](../../../)


