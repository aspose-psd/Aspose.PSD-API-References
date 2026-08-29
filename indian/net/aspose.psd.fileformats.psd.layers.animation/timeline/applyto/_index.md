---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "TimeLine मेथड। वर्तमान टाइमलाइन मानों को इनपुट PsdImage पर लागू करता है"
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

इनपुट [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) पर वर्तमान टाइमलाइन मानों को लागू करें।

```csharp
public void ApplyTo(PsdImage psdImage)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| psdImage | PsdImage | psd इमेज। |

## उदाहरण

TimeLine क्लास PsdImage की टाइमलाइन को बदलने की उच्च-स्तरीय क्षमता प्रदान करता है, जैसे फ्रेम डिले बदलना या किसी विशिष्ट फ्रेम पर लेयर स्टेट को संपादित करना।

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // फ़्रेम 1 की डिस्पोज़ मेथड बदलें
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // फ़्रेम 2 का डिले बदलें
    timeLine.Frames[1].Delay = 15;

    // फ़्रेम 2 पर 'Layer 1' की अपारदर्शिता बदलें
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // फ़्रेम 3 पर 'Layer 1' को बाएँ-नीचे कोने में ले जाएँ
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // नया फ्रेम जोड़ता है
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // फ़्रेम 4 पर 'Layer 1' का blendMode बदलें
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // परिवर्तनों को PsdImage इंस्टेंस पर लागू करें
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### देखें भी

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


