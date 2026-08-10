---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage प्रॉपर्टी। इस PsdImage की टाइमलाइन प्राप्त करता है।"
type: docs
weight: 250
url: /hi/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

इस [`PsdImage`](../) की `Timeline` प्राप्त करता है।

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


