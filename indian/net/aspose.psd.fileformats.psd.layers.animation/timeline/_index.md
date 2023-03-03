---
title: Class TimeLine
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine कक्ष. टइम लइन वकल्प मडल
type: docs
weight: 1880
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

टाइम लाइन विकल्प मॉडल।

```csharp
public sealed class TimeLine
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TimeLine](timeline/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | सक्रिय फ्रेम इंडेक्स प्राप्त या सेट करता है। |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt मान प्राप्त या सेट करता है। |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | फ्रेम की सूची प्राप्त करता है। |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID मान प्राप्त या सेट करता है। |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | लेयर आईडी सरणी प्राप्त या सेट करता है। |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | लूप की संख्या प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | का नया उदाहरण बनाता है`TimeLine` , इनपुट से आरंभ किया गया[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | इनपुट के लिए वर्तमान समय रेखा मान लागू करें[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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


