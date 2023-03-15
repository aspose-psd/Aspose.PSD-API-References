---
title: Class LayerState
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState कक्ष. टइम लइन लेयर स्टेट के वकल्प
type: docs
weight: 1860
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

टाइम लाइन लेयर स्टेट के विकल्प।

```csharp
public sealed class LayerState
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LayerState](layerstate/)(int) | का एक नया उदाहरण प्रारंभ करता है`LayerState` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | ब्लेन मोड प्राप्त करता है या सेट करता है. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | सक्षम स्थिति प्राप्त या सेट करता है। |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | भरण अपारदर्शिता मान प्राप्त या सेट करता है. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | क्षैतिज FXRf मान प्राप्त या सेट करता है। |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | आईडी प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | अस्पष्टता मान प्राप्त या सेट करता है। |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | वास्तविक परत स्थिति से संबंधित परत स्थिति ऑफ़सेट हो जाता है या सेट करता है। |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | परत स्थिति प्रभाव प्राप्त करता है। |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | वर्टिकल एफएक्सआरएफ मान प्राप्त या सेट करता है। |

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


