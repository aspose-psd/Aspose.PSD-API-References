---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية Timeline. تُرجع فهرس الإطار النشط"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

يسترجع فهرس الإطار النشط.

```csharp
public int ActiveFrameIndex { get; }
```

## أمثلة

الكود التالي يوضح نهجًا جديدًا للعمل مع الـ Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // أضف إطارًا آخر
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### انظر أيضًا

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


