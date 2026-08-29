---
title: "التعداد StrokePosition"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition. إعداد الموضع يتحكم في محاذاة الحد الخاص بك إلى الطبقة التي يُطبق عليها في StrokeEffect"
type: docs
weight: 2400
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
{{< psd/tize >}}
## StrokePosition enumeration

إعداد الموضع يتحكم في محاذاة الحد الخاص بك إلى الطبقة التي يُطبق عليها في [`StrokeEffect`](../strokeeffect/).

```csharp
public enum StrokePosition : short
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Inside | `0` | سيتم إنشاء الحد من حافة الشكل ويتوسع إلى الداخل، إلى مركز الكائن. |
| Center | `1` | سيتم إنشاء الحد من حافة الشكل ويتوسع إلى الداخل والخارج معاً. |
| Outside | `2` | سيتم إنشاء الحد من حافة الشكل ويتوسع إلى الخارج، بعيداً عن الكائن. |

## أمثلة

يوضح هذا المثال القدرة على إضافة تأثير الحد باستخدام أنواع مختلفة من التعبئة مثل اللون أو التدرج أو النمط.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. يضيف تعبئة لون، في الموضع داخل
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. يضيف تعبئة لون، في الموضع خارج
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. يضيف تعبئة لون، في الموضع مركز
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. يضيف تعبئة تدرج، في الموضع داخل
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. يضيف تعبئة تدرج، في الموضع خارج
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. يضيف تعبئة تدرج، في الموضع مركز
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. يضيف تعبئة نمط، في الموضع داخل
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. يضيف تعبئة نمط، في الموضع خارج
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. يضيف تعبئة نمط، في الموضع مركز
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


