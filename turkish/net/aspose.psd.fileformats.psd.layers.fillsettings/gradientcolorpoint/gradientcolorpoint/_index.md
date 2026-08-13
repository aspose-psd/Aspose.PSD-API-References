---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD for .NET API Referansı"
description: "GradientColorPoint yapıcı. GradientColorPoint sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Yeni bir [`GradientColorPoint`](../) sınıfının örneğini başlatır.

```csharp
public GradientColorPoint()
```

### Ayrıca Bakınız

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Yeni bir [`GradientColorPoint`](../) sınıfının örneğini başlatır.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renk | Renk | Gradyanda renk noktası. |
| konum | Int32 | Gradyandaki renk noktasının konumu. |
| medianPointLocation | Int32 | Orta gradyan noktasının konumu. |

## Örnekler

Aşağıdaki örnek, bir katmanda GradientOverlayEffect efekt nesnesini nasıl oluşturup/düzenleyeceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Bir katmanda gradyan kaplama efektini oluşturur/alır ve düzenler.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Bir katmanda GradientOverlayEffect ara.
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
        // GradientOverlayEffect mevcut değilse yeni bir tane oluşturabilirsiniz.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Efekte biraz şeffaflık ekleyin.
    gradientOverlayEffect.Opacity = 200;

    // Gradyan efektinin karışım modunu değiştirin.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Gradyan kaplama ayarlarını yapılandırmak için GradientFillSettings nesnesini alır.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // İki renkli yeni bir gradyan ayarlama.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Gradyanın eğimini 80 derece açıyla ayarlar.
    settings.Angle = 80;

    // Gradyan efektini %150'ye kadar ölçeklendirin.
    settings.Scale = 150;

    // Gradyan tipini ayarlar.
    settings.GradientType = GradientType.Linear;

    // Her şeffaflık noktasında opaklığı %100 olarak ayarlayarak gradyanı opak yapın.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


