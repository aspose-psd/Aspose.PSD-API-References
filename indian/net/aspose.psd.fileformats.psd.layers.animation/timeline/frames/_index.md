---
title: TimeLine.Frames
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: TimeLine संपत्त. फ्रेम क सूच प्रप्त करत है
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
## TimeLine.Frames property

फ्रेम की सूची प्राप्त करता है।

```csharp
public Frame[] Frames { get; set; }
```

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

* class [Frame](../../frame/)
* class [TimeLine](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* सभा [Aspose.PSD](../../../)


