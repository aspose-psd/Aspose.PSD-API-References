---
title: Class LayerState
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState فصل. خيارات حالة طبقة الخط الزمني .
type: docs
weight: 1860
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

خيارات حالة طبقة الخط الزمني .

```csharp
public sealed class LayerState
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LayerState](layerstate/)(int) | يقوم بتهيئة مثيل جديد لملف`LayerState` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | الحصول على أو تحديد وضع blen . |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | الحصول على أو تعيين حالة التمكين. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | الحصول على أو تعيين قيمة عتامة التعبئة. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | الحصول على أو تعيين قيمة HorizontalFXRf . |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | الحصول على المعرف أو تعيينه. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | الحصول على قيمة التعتيم أو تعيينها. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | الحصول على أو تعيين إزاحة موضع الطبقة المتعلقة بموضع الطبقة الفعلي. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | يحصل على تأثيرات حالة الطبقة . |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | الحصول على أو تعيين قيمة VerticalFXRf. |

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


