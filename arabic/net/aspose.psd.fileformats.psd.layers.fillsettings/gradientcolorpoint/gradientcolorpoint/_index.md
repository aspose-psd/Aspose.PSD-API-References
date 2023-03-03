---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD لمرجع .NET API
description: GradientColorPoint البناء. يقوم بتهيئة مثيل جديد لملفGradientColorPoint فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`GradientColorPoint`](../) فئة .

```csharp
public GradientColorPoint()
```

### أنظر أيضا

* class [GradientColorPoint](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* المجسم [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`GradientColorPoint`](../) فئة .

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| color | Color | نقطة اللون على التدرج. |
| location | Int32 | موقع نقطة اللون على التدرج. |
| medianPointLocation | Int32 | موقع نقطة الانحدار الوسيط. |

### أمثلة

يوضح المثال التالي كيفية إنشاء / تحرير كائن تأثير GradientOverlayEffect في الطبقة.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// ينشئ / يحصل ويحرر تأثير تراكب التدرج في الطبقة.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // بحث GradientOverlayEffect في طبقة.
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

    // أضف القليل من الشفافية للتأثير.
    gradientOverlayEffect.Opacity = 200;

    // تغيير وضع المزج لتأثير التدرج.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Gets GradientFillSettings لتكوين إعدادات تراكب التدرج.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // إعداد تدرج جديد بلونين.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // يعين ميل التدرج بزاوية 80 درجة.
    settings.Angle = 80;

    // تأثير التدرج اللوني يصل إلى 150٪.
    settings.Scale = 150;

    // يعين نوع التدرج.
    settings.GradientType = GradientType.Linear;

    // اجعل التدرج معتمًا عن طريق ضبط التعتيم على 100٪ عند كل نقطة شفافية.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### أنظر أيضا

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* المجسم [Aspose.PSD](../../../)


