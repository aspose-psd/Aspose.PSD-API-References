---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD for .NET API Referansı
description: GradientColorPoint inşaatçı. Yeni bir örneğini başlatır.GradientColorPoint sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Yeni bir örneğini başlatır.[`GradientColorPoint`](../) sınıf.

```csharp
public GradientColorPoint()
```

### Ayrıca bakınız

* class [GradientColorPoint](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* toplantı [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Yeni bir örneğini başlatır.[`GradientColorPoint`](../) sınıf.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| color | Color | Gradyan üzerinde renk noktası. |
| location | Int32 | Renk noktasının gradyan üzerindeki konumu. |
| medianPointLocation | Int32 | Medyan gradyan noktası konumu. |

### Örnekler

Aşağıdaki örnek, GradientOverlayEffect efekt nesnesinin katmanda nasıl oluşturulacağını/düzenleneceğini gösterir.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Bir katmanda degrade kaplama efektini oluşturur/alır ve düzenler.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // GradientOverlayEffect'i bir katmanda arayın.
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
        // Mevcut değilse yeni bir GradientOverlayEffect oluşturabilirsiniz.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Efekte biraz şeffaflık ekleyin.
    gradientOverlayEffect.Opacity = 200;

    // Degrade efektinin karışım modunu değiştirin.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Degrade bindirme ayarlarını yapılandırmak için GradientFillSettings nesnesini alır.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // İki renkle yeni bir gradyan ayarlıyoruz.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Degradenin eğimini 80 derecelik bir açıyla ayarlar.
    settings.Angle = 80;

    // Degrade efektini %150'ye kadar ölçeklendirin.
    settings.Scale = 150;

    // Gradyan türünü ayarlar.
    settings.GradientType = GradientType.Linear;

    // Her şeffaflık noktasında opaklığı %100 olarak ayarlayarak degradeyi opak yapın.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Ayrıca bakınız

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* toplantı [Aspose.PSD](../../../)


