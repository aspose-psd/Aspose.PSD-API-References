---
title: Enum FrameDisposalMethod
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod एनुम. फ्रेम नपटन वध नर्दष्ट करत है क क्य अगले फ्रेम क प्रदर्शत करने से पहले वर्तमन फ्रेम क त्यगन है आप एनमेशन के लए एक नपटन वध क चयन करते हैं जसमें यह नर्दष्ट करने के लए पृष्ठभूम परदर्शत शमल है क क्य वर्तमन फ्रेम अगले फ्रेम के परदर्श क्षेत्रं के मध्यम से दखई देग
type: docs
weight: 1850
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

फ्रेम निपटान विधि निर्दिष्ट करती है कि क्या अगले फ्रेम को प्रदर्शित करने से पहले वर्तमान फ्रेम को त्यागना है। आप एनिमेशन के लिए एक निपटान विधि का चयन करते हैं जिसमें यह निर्दिष्ट करने के लिए पृष्ठभूमि पारदर्शिता शामिल है कि क्या वर्तमान फ्रेम अगले फ्रेम के पारदर्शी क्षेत्रों के माध्यम से दिखाई देगा।

```csharp
public enum FrameDisposalMethod
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Automatic | `0` | स्वचालित रूप से वर्तमान फ्रेम के लिए एक निपटान विधि निर्धारित करता है, यदि अगले फ्रेम में परत पारदर्शिता है तो वर्तमान फ्रेम को छोड़ दें। अधिकांश एनिमेशन के लिए, स्वचालित विकल्प (डिफ़ॉल्ट) वांछित परिणाम देता है। |
| DoNotDispose | `1` | वर्तमान फ्रेम को संरक्षित करता है क्योंकि अगले फ्रेम को डिस्प्ले में जोड़ा जाता है। वर्तमान फ्रेम (और पूर्ववर्ती फ्रेम) अगले फ्रेम के पारदर्शी क्षेत्रों के माध्यम से दिखाया जा सकता है। |
| Dispose | `2` | अगला फ्रेम प्रदर्शित होने से पहले प्रदर्शन से वर्तमान फ्रेम को हटा देता है। किसी भी समय केवल एक ही फ्रेम प्रदर्शित होता है (और वर्तमान फ्रेम अगले फ्रेम के पारदर्शी क्षेत्रों के माध्यम से प्रकट नहीं होता है)। |

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


