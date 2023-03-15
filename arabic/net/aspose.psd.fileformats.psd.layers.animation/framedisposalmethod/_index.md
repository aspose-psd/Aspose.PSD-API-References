---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod تعداد. تحدد طريقة التخلص من الإطار ما إذا كان سيتم تجاهل الإطار الحالي قبل عرض الإطار التالي. يمكنك تحديد طريقة التخلص من الرسوم المتحركة التي تتضمن شفافية الخلفية لتحديد ما إذا كان الإطار الحالي سيكون مرئيًا من خلال المساحات الشفافة للإطار التالي .
type: docs
weight: 1850
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

تحدد طريقة التخلص من الإطار ما إذا كان سيتم تجاهل الإطار الحالي قبل عرض الإطار التالي. يمكنك تحديد طريقة التخلص من الرسوم المتحركة التي تتضمن شفافية الخلفية لتحديد ما إذا كان الإطار الحالي سيكون مرئيًا من خلال المساحات الشفافة للإطار التالي .

```csharp
public enum FrameDisposalMethod
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Automatic | `0` | يحدد طريقة التخلص من الإطار الحالي تلقائيًا ، مع تجاهل الإطار الحالي إذا كان الإطار التالي يحتوي على طبقة شفافة . بالنسبة لمعظم الرسوم المتحركة ، ينتج عن الخيار "تلقائي" (افتراضي) النتائج المرغوبة. |
| DoNotDispose | `1` | يحتفظ بالإطار الحالي عند إضافة الإطار التالي إلى الشاشة . قد يظهر الإطار الحالي (والإطارات السابقة) من خلال مساحات شفافة للإطار التالي . |
| Dispose | `2` | يتجاهل الإطار الحالي من الشاشة قبل عرض الإطار التالي . يتم عرض إطار واحد فقط في أي وقت (ولا يظهر الإطار الحالي من خلال المساحات الشفافة للإطار التالي) . |

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


