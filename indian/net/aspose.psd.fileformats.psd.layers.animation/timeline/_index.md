---
title: "क्लास Timeline"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline क्लास। टाइमलाइन विकल्प मॉडल"
type: docs
weight: 1980
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

टाइमलाइन विकल्प मॉडल।

```csharp
public sealed class Timeline
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Timeline](timeline/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | सक्रिय फ्रेम इंडेक्स प्राप्त करता है। |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt मान प्राप्त करता है या सेट करता है। |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | फ्रेम्स की सूची प्राप्त करता है। |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID मान प्राप्त करता है या सेट करता है। |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | लूप्स की गिनती प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में PsdImage और Timeline डेटा को सहेजता है। |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान में PsdImage और Timeline डेटा को सहेजता है। |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | सक्रिय फ्रेम को लक्षित पर स्विच करता है। |

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


