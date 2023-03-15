---
title: Class InnerShadowEffect
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect сорт. Эффект слоя внутренней тени
type: docs
weight: 2160
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Эффект слоя внутренней тени

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Получает или задает угол в градусах. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Получает или задает режим наложения. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Получает или задает цвет. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Получает или задает расстояние в пикселях. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Получает тип эффекта |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Получает или задает значение, указывающее, виден ли этот экземпляр. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Получает или задает шум. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Получает или задает прозрачность. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Получает или задает значение размытия в пикселях. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Получает или задает разброс (дроссель) в процентах. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Получает или задает значение, указывающее, следует ли [использовать этот угол во всех эффектах слоя]. |

### Примеры

Следующий код демонстрирует, как изменить настройки эффекта слоя внутренней тени.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### Смотрите также

* interface [IShadowEffect](../ishadoweffect/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* сборка [Aspose.PSD](../../)


