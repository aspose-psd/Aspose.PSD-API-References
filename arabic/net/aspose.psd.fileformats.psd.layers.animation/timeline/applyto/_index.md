---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة TimeLine. تُطبق قيم الخط الزمني الحالية على PsdImage المدخل"
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

تطبيق قيم الخط الزمني الحالية على [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public void ApplyTo(PsdImage psdImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| psdImage | PsdImage | صورة psd. |

## أمثلة

تُوفر فئة TimeLine قدرة عالية المستوى على تعديل جدول زمني لـ PsdImage، مثل تغيير تأخير الإطار أو تعديل حالة الطبقة في إطار معين.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // تغيير طريقة التخلص من الإطار 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // تغيير تأخير الإطار 2
    timeLine.Frames[1].Delay = 15;

    // تغيير شفافية 'Layer 1' في الإطار 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // نقل 'Layer 1' إلى الزاوية اليسرى السفلية في الإطار 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // يضيف إطارًا جديدًا
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // تغيير blendMode للـ'Layer 1' في الإطار 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // تطبيق التغييرات مرة أخرى على كائن PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### انظر أيضًا

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


