---
title: TimeLine.InitializeFrom
second_title: Aspose.PSD لمرجع .NET API
description: TimeLine طريقة. إنشاء مثيل جديد لـTimeLine  مهيأ من الإدخالPsdImage .
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/
---
## TimeLine.InitializeFrom method

إنشاء مثيل جديد لـ[`TimeLine`](../) ، مهيأ من الإدخال[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) .

```csharp
public static TimeLine InitializeFrom(PsdImage psdImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| psdImage | PsdImage | صورة مديرية الأمن العام. |

### قيمة الإرجاع

المثيل الجديد لـ[`TimeLine`](../) ، مهيأ من الإدخال[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

### أمثلة

توفر فئة TimeLine قدرة عالية المستوى على معالجة الجدول الزمني لـ PsdImage ، مثل تغيير تأخير الإطار أو تحرير حالة الطبقة في إطار معين.

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

    // تغيير عتامة "الطبقة 1" في الإطار 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // انقل "Layer 1" إلى الزاوية اليسرى السفلية في الإطار 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // يضيف إطارًا جديدًا
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // تغيير blendMode لـ 'Layer 1' في الإطار 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // تطبيق التغييرات مرة أخرى على مثيل PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### أنظر أيضا

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* المجسم [Aspose.PSD](../../../)


