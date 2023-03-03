---
title: Class Frame
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame فصل. خيارات عنصر الإطار الزمني .
type: docs
weight: 1840
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

خيارات عنصر الإطار الزمني .

```csharp
public sealed class Frame
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Frame](frame/)(TimeLine) | يقوم بتهيئة مثيل جديد لملف`Frame` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | الحصول على أو تعيين قيمة تأخير الإطار في centa-seconds. على سبيل المثال ، تحتوي 1 ثانية على 100 سنتا-ثانية. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | الحصول على أو تحديد طريقة التخلص من الإطار. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | الحصول على معرف الإطار أو تعيينه . |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | يحصل بعد ذلك على حالات طبقة الإطار. |

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


