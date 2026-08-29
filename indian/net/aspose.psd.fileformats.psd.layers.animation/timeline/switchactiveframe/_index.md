---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Timeline मेथड। सक्रिय फ्रेम को लक्षित फ्रेम पर स्विच करता है"
type: docs
weight: 80
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

सक्रिय फ्रेम को लक्षित पर स्विच करता है।

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | लक्षित फ्रेम इंडेक्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IndexOutOfRangeException | सक्रिय फ्रेम का नया इंडेक्स फ्रेम काउंट रेंज में होना चाहिए। |

## उदाहरण

निम्नलिखित कोड टाइमलाइन के साथ काम करने के लिए एक नया दृष्टिकोण दर्शाता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // एक और फ्रेम जोड़ें
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### देखें भी

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


