---
title: StrokeEffect.Position
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: StrokeEffect संपत्त. PSD परत समग्र में आपके स्ट्रक के संरेखण क नयंत्रत करने के लए स्ट्रक प्रभव क स्थत प्रप्त य सेट करत है मन ह सकत हैInside PSD परत समग्र के अंदर स्ट्रक बनने के लए यOutside PSD परत समग्र के चरं ओर स्ट्रक बनने के लए औरCenter अंदर और बहर दनं तरफ से स्ट्रक बनने के लए.
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
## StrokeEffect.Position property

PSD परत सामग्री में आपके स्ट्रोक के संरेखण को नियंत्रित करने के लिए स्ट्रोक प्रभाव की स्थिति प्राप्त या सेट करता है। मान हो सकता हैInside PSD परत सामग्री के अंदर स्ट्रोक बनाने के लिए, याOutside PSD परत सामग्री के चारों ओर स्ट्रोक बनाने के लिए, औरCenter अंदर और बाहर दोनों तरफ से स्ट्रोक बनाने के लिए.

```csharp
public StrokePosition Position { get; set; }
```

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

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* सभा [Aspose.PSD](../../../)


