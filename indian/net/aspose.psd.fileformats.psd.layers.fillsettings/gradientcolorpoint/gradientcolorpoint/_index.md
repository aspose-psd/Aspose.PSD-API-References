---
title: GradientColorPoint.GradientColorPoint
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: GradientColorPoint नर्मत. क एक नय उदहरण प्ररंभ करत हैGradientColorPoint वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`GradientColorPoint`](../) वर्ग.

```csharp
public GradientColorPoint()
```

### यह सभी देखें

* class [GradientColorPoint](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* सभा [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`GradientColorPoint`](../) वर्ग.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | Color | ढाल पर रंग बिंदु। |
| location | Int32 | ढाल पर रंग बिंदु का स्थान। |
| medianPointLocation | Int32 | औसत ढाल बिंदु स्थान। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि कैसे परत में GradientOverlayEffect प्रभाव वस्तु को बनाया/संपादित किया जाए।

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// एक परत में ढाल ओवरले प्रभाव बनाता/प्राप्त करता है और संपादित करता है।
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // एक लेयर में GradientOverlayEffect खोजें।
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
        // यदि यह मौजूद नहीं है तो आप एक नया GradientOverlayEffect बना सकते हैं।
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // प्रभाव में थोड़ी पारदर्शिता जोड़ें।
    gradientOverlayEffect.Opacity = 200;

    // ग्रेडिएंट इफेक्ट के ब्लेंड मोड को बदलें।
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // ढाल ओवरले सेटिंग्स को कॉन्फ़िगर करने के लिए GradientFillSettings ऑब्जेक्ट प्राप्त करें।
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // दो रंगों के साथ एक नया ग्रेडिएंट सेट करना।
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // ग्रेडिएंट का झुकाव 80 डिग्री के कोण पर सेट करता है।
    settings.Angle = 80;

    // स्केल ग्रेडिएंट प्रभाव 150% तक।
    settings.Scale = 150;

    // ढाल का प्रकार सेट करता है।
    settings.GradientType = GradientType.Linear;

    // प्रत्येक पारदर्शिता बिंदु पर अपारदर्शिता को 100% पर सेट करके ग्रेडिएंट को अपारदर्शी बनाएं।
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### यह सभी देखें

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* सभा [Aspose.PSD](../../../)


