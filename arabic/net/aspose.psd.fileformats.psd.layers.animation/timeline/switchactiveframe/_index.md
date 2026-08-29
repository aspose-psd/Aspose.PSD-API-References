---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Timeline. يبدل الإطار النشط إلى المستهدف"
type: docs
weight: 80
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

يبدل الإطار النشط إلى المستهدف.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | مؤشر الإطار المستهدف. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IndexOutOfRangeException | يجب أن يكون الفهرس الجديد للإطار النشط ضمن نطاق عدد الإطارات. |

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


