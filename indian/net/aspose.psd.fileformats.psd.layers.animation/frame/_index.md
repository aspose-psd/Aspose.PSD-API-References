---
title: Class Frame
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame कक्ष. टइम लइन फ्रेम आइटम के वकल्प
type: docs
weight: 1840
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

टाइम लाइन फ्रेम आइटम के विकल्प।

```csharp
public sealed class Frame
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Frame](frame/)(TimeLine) | का एक नया उदाहरण प्रारंभ करता है`Frame` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | सेंट-सेकंड में फ्रेम विलंब मान प्राप्त या सेट करता है। उदाहरण के लिए, 1 सेकंड में 100 सेंट-सेकंड होते हैं। |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | फ्रेम के निपटान विधि को प्राप्त या सेट करता है। |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | फ्रेम आईडी प्राप्त या सेट करता है। |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | फ़्रेम की परत स्थिति सेट करता है. |

### उदाहरण

TimeLine वर्ग PsdImage की समयरेखा में हेरफेर करने के लिए एक उच्च-स्तरीय क्षमता देता है, जैसे किसी विशिष्ट फ़्रेम पर फ़्रेम विलंब या संपादन परत स्थिति को बदलना।

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // फ्रेम 1 की निपटान विधि बदलें
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // फ्रेम 2 की देरी बदलें
    timeLine.Frames[1].Delay = 15;

    // फ्रेम 2 पर 'लेयर 1' की अपारदर्शिता बदलें
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 'लेयर 1' को फ्रेम 3 पर बाएँ-निचले कोने में ले जाएँ
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // नया फ्रेम जोड़ता है
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // फ्रेम 4 पर 'लेयर 1' का ब्लेंडमोड बदलें
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // PsdImage उदाहरण में परिवर्तन वापस लागू करें
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* सभा [Aspose.PSD](../../)


