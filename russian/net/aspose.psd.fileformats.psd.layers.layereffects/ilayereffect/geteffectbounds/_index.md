---
title: "ILayerEffect.GetEffectBounds"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ILayerEffect. Вычисляет и возвращает границы пикселей эффекта на основе границ пикселей входного слоя"
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Вычисляет и получает границы пикселей эффекта на основе границ пикселей входного слоя.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| layerBounds | Rectangle | Границы пикселей слоя. |
| globalAngle | Int32 | Глобальный угол для расчёта угла глобального света. |

### Возвращаемое значение

Границы пикселей эффекта, основанные на границах пикселей входного слоя.

## Примеры

Показывает, как получить границы слоя с эффектами и экспортировать их с правильным размером.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Сохранить в пределах границ PsdImage в оригинальном расположении слоя

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### См. также

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


