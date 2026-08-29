---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FillLayer मेथड। फ़िल प्रकार द्वारा FillLayer क्लास का नया इंस्टेंस बनाएं।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

फ़िल प्रकार द्वारा [`FillLayer`](../) क्लास का नया इंस्टेंस बनाएं।

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fillType | FillType | फ़िल लेयर का प्रकार। |

### रिटर्न वैल्यू

फ़िल प्रकार द्वारा [`FillLayer`](../) क्लास का नया इंस्टेंस लौटाता है।

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि रनटाइम पर FillLayer प्रकार की लेयर कैसे जोड़ें।

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

### देखें भी

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


