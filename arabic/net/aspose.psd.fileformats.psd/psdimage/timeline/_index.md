---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdImage. تحصل على المخطط الزمني لهذا PsdImage."
type: docs
weight: 250
url: /ar/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

يحصل على `Timeline` لهذا [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


