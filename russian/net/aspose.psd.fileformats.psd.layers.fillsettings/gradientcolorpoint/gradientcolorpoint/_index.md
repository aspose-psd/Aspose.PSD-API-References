---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор GradientColorPoint. Инициализирует новый экземпляр класса GradientColorPoint"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Инициализирует новый экземпляр класса [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### См. также

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Инициализирует новый экземпляр класса [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | Color | Точка цвета на градиенте. |
| location | Int32 | Расположение точки цвета на градиенте. |
| medianPointLocation | Int32 | Расположение медианной точки градиента. |

## Примеры

В следующем примере показано, как создать/редактировать объект эффекта GradientOverlayEffect в слое.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Создаёт/получает и редактирует эффект наложения градиента в слое.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Ищет GradientOverlayEffect в слое.
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
        // Вы можете создать новый GradientOverlayEffect, если он не существует.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Добавьте немного прозрачности к эффекту.
    gradientOverlayEffect.Opacity = 200;

    // Измените режим смешивания градиентного эффекта.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Получает объект GradientFillSettings для настройки параметров наложения градиента.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Установка нового градиента с двумя цветами.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Устанавливает наклон градиента под углом 80 градусов.
    settings.Angle = 80;

    // Масштабирует эффект градиента до 150%.
    settings.Scale = 150;

    // Устанавливает тип градиента.
    settings.GradientType = GradientType.Linear;

    // Сделайте градиент непрозрачным, установив непрозрачность 100% в каждой точке прозрачности.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### См. также

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


