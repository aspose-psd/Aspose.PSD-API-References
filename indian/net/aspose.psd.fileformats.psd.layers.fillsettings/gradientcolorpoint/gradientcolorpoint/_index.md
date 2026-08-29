---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GradientColorPoint कंस्ट्रक्टर। GradientColorPoint क्लास का नया इंस्टेंस इनिशियलाइज़ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

[`GradientColorPoint`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public GradientColorPoint()
```

### देखें भी

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

[`GradientColorPoint`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रंग | रंग | ग्रेडिएंट पर रंग बिंदु। |
| स्थान | Int32 | ग्रेडिएंट पर रंग बिंदु का स्थान। |
| medianPointLocation | Int32 | मध्य ग्रेडिएंट बिंदु का स्थान। |

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि लेयर में GradientOverlayEffect प्रभाव ऑब्जेक्ट को कैसे बनाएं/संपादित करें।

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// लेयर में ग्रेडिएंट ओवरले प्रभाव को बनाता/प्राप्त करता और संपादित करता है।
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // लेयर में GradientOverlayEffect खोजें।
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
        // यदि यह मौजूद नहीं है तो आप नया GradientOverlayEffect बना सकते हैं।
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // प्रभाव में थोड़ा पारदर्शिता जोड़ें।
    gradientOverlayEffect.Opacity = 200;

    // ग्रेडिएंट प्रभाव का ब्लेंड मोड बदलें।
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // ग्रेडिएंट ओवरले सेटिंग्स को कॉन्फ़िगर करने के लिए GradientFillSettings ऑब्जेक्ट प्राप्त करता है।
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // दो रंगों के साथ नया ग्रेडिएंट सेट करना।
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // ग्रेडिएंट को 80 डिग्री के कोण पर झुकाव सेट करता है।
    settings.Angle = 80;

    // ग्रेडिएंट प्रभाव को 150% तक स्केल करें।
    settings.Scale = 150;

    // ग्रेडिएंट का प्रकार सेट करता है।
    settings.GradientType = GradientType.Linear;

    // प्रत्येक पारदर्शिता बिंदु पर अपारदर्शिता को 100% सेट करके ग्रेडिएंट को अपारदर्शी बनाएं।
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### देखें भी

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


