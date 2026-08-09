---
title: "الفئة Timeline"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline. نموذج خيارات الخط الزمني"
type: docs
weight: 1980
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

نموذج خيارات الخط الزمني.

```csharp
public sealed class Timeline
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Timeline](timeline/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | يسترجع فهرس الإطار النشط. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | يحصل على أو يضبط قيمة AFSt. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | يحصل على قائمة الإطارات. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | يحصل على أو يضبط قيمة FsID. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | يحصل على أو يضبط عدد الحلقات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | يحفظ بيانات PsdImage و Timeline إلى الدفق المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | يحفظ بيانات PsdImage و Timeline إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | يبدل الإطار النشط إلى المستهدف. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


