---
title: Enum StrokePosition
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition एनुम. स्थत सेटंग आपके स्ट्रक के संरेखण क उस परत पर नयंत्रत करत है जस पर इसे लगू कय गय हैStrokeEffect .
type: docs
weight: 2200
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
## StrokePosition enumeration

स्थिति सेटिंग आपके स्ट्रोक के संरेखण को उस परत पर नियंत्रित करती है जिस पर इसे लागू किया गया है[`StrokeEffect`](../strokeeffect/) .

```csharp
public enum StrokePosition : short
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Inside | `0` | स्ट्रोक आकृति के किनारे से बनाया जाएगा और अंदर की ओर बढ़ेगा, वस्तु के केंद्र तक। |
| Center | `1` | स्ट्रोक आकृति के किनारे से बनाया जाएगा और अंदर और बाहर दोनों तरफ बढ़ेगा। |
| Outside | `2` | स्ट्रोक आकृति के किनारे से बनाया जाएगा और वस्तु से दूर, बाहर की ओर बढ़ेगा। |

### उदाहरण

यह उदाहरण विभिन्न प्रकार के भरण जैसे रंग, ग्रेडिएंट या पैटर्न के साथ स्ट्रोक प्रभाव जोड़ने की क्षमता प्रदर्शित करता है।

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. अंदर की स्थिति में रंग भरण जोड़ता है
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. बाहर की स्थिति में रंग भरण जोड़ता है
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. स्थिति केंद्र में रंग भरण जोड़ता है
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. अंदर की स्थिति में ग्रेडिएंट फिल जोड़ता है
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. ग्रेडिएंट फिल को बाहर की स्थिति में जोड़ता है
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. पोजीशन सेंटर में ग्रेडिएंट फिल जोड़ता है
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. अंदर की स्थिति में पैटर्न भरण जोड़ता है
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. बाहर की स्थिति में पैटर्न भरण जोड़ता है
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. स्थिति केंद्र में पैटर्न भरण जोड़ता है
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* सभा [Aspose.PSD](../../)


