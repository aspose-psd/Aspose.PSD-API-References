---
title: FillLayer.CreateInstance
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FillLayer तरक. क एक नय उदहरण बनएँFillLayer भरण के प्रकर के अनुसर वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

का एक नया उदाहरण बनाएँ[`FillLayer`](../) भरण के प्रकार के अनुसार वर्ग.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillType | FillType | भरण परत का प्रकार। |

### प्रतिलाभ की मात्रा

का एक नया उदाहरण देता है[`FillLayer`](../) भरण के प्रकार से वर्ग।

### उदाहरण

निम्न उदाहरण दर्शाता है कि कैसे रनटाइम पर फिललेयर प्रकार की परत को जोड़ना है।

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* सभा [Aspose.PSD](../../../)


