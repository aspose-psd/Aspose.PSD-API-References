---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Timeline प्रॉपर्टी। सक्रिय फ्रेम इंडेक्स प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

सक्रिय फ्रेम इंडेक्स प्राप्त करता है।

```csharp
public int ActiveFrameIndex { get; }
```

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


