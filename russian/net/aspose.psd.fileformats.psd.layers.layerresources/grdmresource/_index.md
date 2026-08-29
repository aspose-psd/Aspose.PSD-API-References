---
title: "Класс GrdmResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource. Класс GrdmResource. Содержит информацию о слое GradientMap"
type: docs
weight: 2770
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

Класс GrdmResource. Содержит информацию о слое Gradient-Map.

```csharp
public class GrdmResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GrdmResource](grdmresource/)(int) | Инициализирует новый экземпляр класса `GrdmResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | Цветовая модель. Когда 'Gradient type' = 'Noise', мы можем задать 'Color Model' как RGB/SHB/LAB (3/4/6). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | Получает или задает цветовые точки. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | Градиент дизерирован. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | Количество расширений ( = 2 для Photoshop 6.0). |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | Режим для этого градиента определяет 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | Имя градиента: строка Unicode, дополнена. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | Интерполяция. Определяет плавность, когда 'Gradient Type' = 'Solid' (GradientMode = 0). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/) { get; set; } | Получает или задаёт метод интерполяции градиента. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; set; } | Максимальный цвет формата PixelDataFormat.Rgba64Bpp. Цвет имеет каналы ARGB, каждый канал 16 бит. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; set; } | Минимальный цвет формата PixelDataFormat.Rgba64Bpp. Цвет имеет каналы ARGB, каждый канал 16 бит. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для этого ресурса. Версия 3 требуется, когда метод интерполяции хранится явно. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | Градиент обратный. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | Сид случайного числа, используемый для генерации цветов шумового градиента. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | Коэффициент шероховатости. Когда 'Gradient type' = 'Noise', мы можем задать 'Roughness' (0 - 2048). |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | Флаг отображения прозрачности. Когда 'Gradient type' = 'Noise', мы можем установить 'Add transparency' в true. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | Получает или задает точки прозрачности. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | Флаг использования векторного цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | Сохраняет данные ресурса в указанный потоковый контейнер. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | Ключ информации о типе инструмента. |

## Примеры

Следующий код демонстрирует поддержку ресурса GrdmResource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // проверьте текущие значения
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Красный цвет для второй точки градиентного цвета
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // проверьте изменённые значения
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### См. также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


