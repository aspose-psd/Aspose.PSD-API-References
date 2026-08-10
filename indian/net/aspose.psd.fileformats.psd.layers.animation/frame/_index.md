---
title: "क्लास Frame"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame क्लास। टाइमलाइन फ्रेम आइटम के विकल्प"
type: docs
weight: 1940
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

टाइमलाइन फ्रेम आइटम के विकल्प।

```csharp
public sealed class Frame
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Frame](frame/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | फ़्रेम देरी मान को सेंटा-सेकंड में प्राप्त करता है या सेट करता है। उदाहरण के लिए, 1 सेकंड में 100 सेंटा-सेकंड होते हैं। |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | फ़्रेम की डिस्पोज़ल मेथड को प्राप्त करता है या सेट करता है। |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | फ़्रेम आईडी को प्राप्त करता है या सेट करता है। |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | फ़्रेम की लेयर स्थितियों को प्राप्त करता है या सेट करता है। |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


