---
title: "Класс InnerShadowEffect"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect класс. Эффект внутренней тени слоя."
type: docs
weight: 2350
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

Эффект внутренней тени слоя.

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Получает или задает угол в градусах. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Получает или задает режим наложения. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Получает или задает цвет. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Получает или задает расстояние в пикселях. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Получает тип эффекта. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Получает или задает значение, указывающее, видим ли этот экземпляр. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Получает или задает шум. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Получает или задает непрозрачность. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Получает или задает значение размытия в пикселях. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Получает или задает растяжение (зажим) в процентах. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Получает или задает значение, указывающее, следует ли [use this angle in all of the layer effects]. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | Вычисляет и получает границы пикселей эффекта на основе границ пикселей входного слоя. |

## Примеры

Следующий код демонстрирует, как изменить настройки эффекта внутренней тени слоя.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
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

### См. также

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


