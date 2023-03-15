---
title: StrokeEffect.Overprint
second_title: Aspose.PSD لمرجع .NET API
description: StrokeEffect ملكية. الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذاStrokeEffect سوف يمزج السكتة الدماغية مع محتويات الطبقة الحالية.
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/overprint/
---
## StrokeEffect.Overprint property

الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`StrokeEffect`](../) سوف يمزج السكتة الدماغية مع محتويات الطبقة الحالية.

```csharp
public bool Overprint { get; set; }
```

### Property_Value

`حقيقي` إذا كان يجب أن يمزج الحد مع محتويات الطبقة الحالية ؛ خلاف ذلك،`خطأ شنيع` .

### أمثلة

يوضح هذا المثال القدرة على إضافة تأثير الحد بأنواع مختلفة من التعبئة مثل اللون أو التدرج أو النمط.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. يضيف تعبئة اللون ، في الموضع بالداخل
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. يضيف تعبئة اللون في الموضع بالخارج
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. يضيف تعبئة اللون في مركز الموضع
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. يضيف تعبئة متدرجة ، في الموضع بالداخل
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. يضيف تعبئة متدرجة ، في الموضع بالخارج
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. يضيف تعبئة متدرجة ، في مركز الموضع
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. يضيف تعبئة النموذج ، في الموضع بالداخل
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. يضيف تعبئة النموذج ، في الموضع بالخارج
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. يضيف تعبئة النموذج ، في مركز الموضع
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### أنظر أيضا

* class [StrokeEffect](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* المجسم [Aspose.PSD](../../../)


