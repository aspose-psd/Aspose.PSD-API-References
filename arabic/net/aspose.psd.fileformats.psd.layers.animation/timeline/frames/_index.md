---
title: "Timeline.Frames"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية Timeline. تُرجع قائمة الإطارات"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
{{< psd/tize >}}
## Timeline.Frames property

يحصل على قائمة الإطارات.

```csharp
public Frame[] Frames { get; set; }
```

## أمثلة

تمنح الفئة Timeline قدرة عالية المستوى على تعديل المخطط الزمني لـ PsdImage، مثل تغيير تأخير الإطار أو تحرير حالة الطبقة في إطار محدد.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // تغيير طريقة التخلص من الإطار 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // تغيير تأخير الإطار 2
    timeline.Frames[1].Delay = 15;

    // تغيير شفافية 'Layer 1' في الإطار 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // نقل 'Layer 1' إلى الزاوية اليسرى السفلية في الإطار 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // يضيف إطارًا جديدًا
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // تغيير blendMode للـ'Layer 1' في الإطار 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // تطبيق التغييرات مرة أخرى على كائن PsdImage
    psdImage.Save(outputPsd);
}
```

### انظر أيضًا

* class [Frame](../../frame/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


