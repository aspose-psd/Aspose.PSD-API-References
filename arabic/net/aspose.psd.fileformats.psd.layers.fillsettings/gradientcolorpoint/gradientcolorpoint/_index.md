---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ GradientColorPoint. يهيئ مثيلًا جديدًا من الفئة GradientColorPoint"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

يهيئ مثيلًا جديدًا من الفئة [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### انظر أيضًا

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

يهيئ مثيلًا جديدًا من الفئة [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| لون | لون | نقطة اللون على التدرج. |
| الموقع | Int32 | موقع نقطة اللون على التدرج. |
| medianPointLocation | Int32 | موقع نقطة التدرج المتوسطة. |

## أمثلة

يوضح المثال التالي كيفية إنشاء/تحرير كائن تأثير GradientOverlayEffect في الطبقة.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// ينشئ/يحصل ويحرر تأثير التراكب المتدرج في طبقة.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // ابحث عن GradientOverlayEffect في طبقة.
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // يمكنك إنشاء GradientOverlayEffect جديد إذا لم يكن موجودًا.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // أضف قليلًا من الشفافية إلى التأثير.
    gradientOverlayEffect.Opacity = 200;

    // غيّر وضع المزج لتأثير التدرج.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // يحصل على كائن GradientFillSettings لتكوين إعدادات التراكب المتدرج.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // إعداد تدرج جديد بلونين.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // يضبط ميل التدرج بزاوية 80 درجة.
    settings.Angle = 80;

    // قُم بتكبير تأثير التدرج حتى 150٪.
    settings.Scale = 150;

    // يضبط نوع التدرج.
    settings.GradientType = GradientType.Linear;

    // اجعل التدرج غير شفاف عن طريق ضبط الشفافية إلى 100٪ في كل نقطة شفافية.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### انظر أيضًا

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


