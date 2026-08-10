---
title: "LayerState.BlendMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerState प्रॉपर्टी. ब्लेंडिंग मोड को प्राप्त करता है या सेट करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/
---
{{< psd/tize >}}
## LayerState.BlendMode property

ब्लेंडिंग मोड प्राप्त करता है या सेट करता है।

```csharp
public BlendMode BlendMode { get; set; }
```

## उदाहरण

Timeline क्लास PsdImage की टाइमलाइन को नियंत्रित करने की उच्च-स्तरीय क्षमता प्रदान करता है, जैसे फ्रेम डिले बदलना या विशिष्ट फ्रेम पर लेयर स्टेट को संपादित करना।

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // फ़्रेम 1 की डिस्पोज़ मेथड बदलें
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // फ़्रेम 2 का डिले बदलें
    timeline.Frames[1].Delay = 15;

    // फ़्रेम 2 पर 'Layer 1' की अपारदर्शिता बदलें
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // फ़्रेम 3 पर 'Layer 1' को बाएँ-नीचे कोने में ले जाएँ
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // नया फ्रेम जोड़ता है
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // फ़्रेम 4 पर 'Layer 1' का blendMode बदलें
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // परिवर्तनों को PsdImage इंस्टेंस पर लागू करें
    psdImage.Save(outputPsd);
}
```

### देखें भी

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


