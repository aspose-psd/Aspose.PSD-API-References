---
title: "एन्यूम FrameDisposalMethod"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod एन्यूम। फ्रेम डिस्पोज़ल मेथड यह निर्धारित करता है कि अगला फ्रेम दिखाने से पहले वर्तमान फ्रेम को त्यागना है या नहीं। आप बैकग्राउंड ट्रांसपेरेंसी वाले एनीमेशन के लिए डिस्पोज़ल मेथड चुनते हैं ताकि यह निर्दिष्ट किया जा सके कि वर्तमान फ्रेम अगली फ्रेम के पारदर्शी क्षेत्रों के माध्यम से दिखाई देगा या नहीं।"
type: docs
weight: 1950
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

फ़्रेम डिस्पोज़ल मेथड यह निर्धारित करता है कि अगले फ़्रेम को प्रदर्शित करने से पहले वर्तमान फ़्रेम को त्यागा जाए या नहीं। आप उन एनीमेशन के लिए एक डिस्पोज़ल मेथड चुनते हैं जिनमें बैकग्राउंड ट्रांसपेरेंसी शामिल होती है, ताकि यह निर्दिष्ट किया जा सके कि वर्तमान फ़्रेम अगले फ़्रेम के पारदर्शी क्षेत्रों के माध्यम से दिखाई देगा या नहीं।

```csharp
public enum FrameDisposalMethod
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Automatic | `0` | वर्तमान फ्रेम के लिए डिस्पोज़ल मेथड को स्वचालित रूप से निर्धारित करता है, यदि अगला फ्रेम लेयर ट्रांसपेरेंसी रखता है तो वर्तमान फ्रेम को त्याग देता है। अधिकांश एनीमेशन के लिए, ऑटोमैटिक विकल्प (डिफ़ॉल्ट) वांछित परिणाम देता है। |
| DoNotDispose | `1` | जब अगला फ्रेम डिस्प्ले में जोड़ा जाता है तो वर्तमान फ्रेम को संरक्षित रखता है। वर्तमान फ्रेम (और पूर्ववर्ती फ्रेम) अगले फ्रेम के पारदर्शी क्षेत्रों के माध्यम से दिख सकते हैं। |
| Dispose | `2` | अगला फ्रेम दिखाने से पहले वर्तमान फ्रेम को डिस्प्ले से हटा देता है। किसी भी समय केवल एक ही फ्रेम दिखाया जाता है (और वर्तमान फ्रेम अगले फ्रेम के पारदर्शी क्षेत्रों के माध्यम से नहीं दिखता)। |

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


