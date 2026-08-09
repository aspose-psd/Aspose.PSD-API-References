---
title: "التعداد FrameDisposalMethod"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod. تحدد طريقة التخلص من الإطار ما إذا كان يجب التخلص من الإطار الحالي قبل عرض الإطار التالي. يمكنك اختيار طريقة التخلص للرسوم المتحركة التي تشمل شفافية الخلفية لتحديد ما إذا كان الإطار الحالي سيظهر من خلال المناطق الشفافة للإطار التالي."
type: docs
weight: 1950
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

طريقة التخلص من الإطار تحدد ما إذا كان يجب تجاهل الإطار الحالي قبل عرض الإطار التالي. يمكنك اختيار طريقة التخلص للرسوم المتحركة التي تتضمن شفافية الخلفية لتحديد ما إذا كان الإطار الحالي سيظهر من خلال المناطق الشفافة للإطار التالي.

```csharp
public enum FrameDisposalMethod
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Automatic | `0` | يحدد طريقة التخلص للإطار الحالي تلقائيًا، مع التخلص من الإطار الحالي إذا كان الإطار التالي يحتوي على شفافية طبقة. بالنسبة لمعظم الرسوم المتحركة، ينتج الخيار التلقائي (الافتراضي) النتائج المطلوبة. |
| DoNotDispose | `1` | يحافظ على الإطار الحالي عند إضافة الإطار التالي إلى العرض. قد يظهر الإطار الحالي (والإطارات السابقة) من خلال المناطق الشفافة للإطار التالي. |
| Dispose | `2` | يتخلص من الإطار الحالي من العرض قبل عرض الإطار التالي. يتم عرض إطار واحد فقط في أي وقت (ولا يظهر الإطار الحالي من خلال المناطق الشفافة للإطار التالي). |

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


