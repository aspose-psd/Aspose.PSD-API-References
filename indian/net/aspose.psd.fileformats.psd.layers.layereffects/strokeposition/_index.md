---
title: "एनम StrokePosition"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition एनम। पोजीशन सेटिंग आपके स्ट्रोक को उस लेयर के साथ संरेखित करती है जिस पर यह StrokeEffect में लागू होता है।"
type: docs
weight: 2400
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
{{< psd/tize >}}
## StrokePosition enumeration

पोजीशन सेटिंग आपके स्ट्रोक को उस लेयर के साथ संरेखित करती है जिस पर यह [`StrokeEffect`](../strokeeffect/) में लागू होता है।

```csharp
public enum StrokePosition : short
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Inside | `0` | स्ट्रोक आकार के किनारे से बनाया जाएगा और अंदर की ओर बढ़ेगा, वस्तु के केंद्र तक। |
| Center | `1` | स्ट्रोक आकार के किनारे से बनाया जाएगा और अंदर और बाहर दोनों ओर बढ़ेगा। |
| Outside | `2` | स्ट्रोक आकार के किनारे से बनाया जाएगा और बाहर की ओर बढ़ेगा, वस्तु से दूर। |

## उदाहरण

यह उदाहरण विभिन्न प्रकार के फ़िल जैसे कलर, ग्रेडिएंट या पैटर्न के साथ स्ट्रोक इफ़ेक्ट जोड़ने की क्षमता को दर्शाता है।

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Inside पोजीशन पर कलर फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Outside पोजीशन पर कलर फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Center पोजीशन पर कलर फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Inside पोजीशन पर ग्रेडिएंट फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Outside पोजीशन पर ग्रेडिएंट फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Center पोजीशन पर ग्रेडिएंट फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Inside पोजीशन पर पैटर्न फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Outside पोजीशन पर पैटर्न फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Center पोजीशन पर पैटर्न फ़िल जोड़ता है
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


