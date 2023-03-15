---
title: Class TimeLine
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine فصل. نموذج خيارات الخط الزمني .
type: docs
weight: 1880
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

نموذج خيارات الخط الزمني .

```csharp
public sealed class TimeLine
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TimeLine](timeline/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | الحصول على أو تحديد فهرس الإطار النشط. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | الحصول على قيمة AFSt أو تعيينها. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | يحصل على قائمة الإطارات . |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | الحصول على أو تعيين قيمة FsID . |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | الحصول على أو تعيين مصفوفة معرف الطبقات. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | الحصول على أو تحديد عدد الحلقات . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | إنشاء مثيل جديد لـ`TimeLine` ، مهيأ من الإدخال[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | تطبيق قيم الخط الزمني الحالية على الإدخال[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* المجسم [Aspose.PSD](../../)


