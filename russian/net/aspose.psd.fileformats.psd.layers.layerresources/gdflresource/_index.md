---
title: Class GdFlResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GdFlResource сорт. Класс GdFlResource. Этот ресурс содержит информацию о смешивании отсеченного элемента.
type: docs
weight: 2500
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
## GdFlResource class

Класс GdFlResource. Этот ресурс содержит информацию о смешивании отсеченного элемента.

```csharp
public class GdFlResource : FillLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GdFlResource](gdflresource/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer/) { get; set; } | Получает или задает значение, указывающее, следует ли [выравнивать со слоем]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle/) { get; set; } | Получает или задает угол. |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color/) { get; set; } | Получает цвет RGB. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints/) { get; set; } | Получает точки цвета. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither/) { get; set; } | Получает или задает значение, указывающее, является ли это`GdFlResource` дизеринг. |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval/) { get; set; } | Получает или задает интервал градиента. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname/) { get; set; } | Получает или задает имя градиента. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype/) { get; set; } | Получает или задает тип градиента. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset/) { get; set; } | Получает или задает смещение по горизонтали. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/psdversion/) { get; } | Получает минимальную версию psd, необходимую для ресурса слоя. 0 означает отсутствие ограничений. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse/) { get; set; } | Получает или задает значение, указывающее, является ли это`GdFlResource` является обратным. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale/) { get; set; } | Получает или задает масштаб. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/signature/) { get; } | Получает подпись ресурса слоя. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints/) { get; set; } | Получает очки прозрачности. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset/) { get; set; } | Получает или задает вертикальное смещение. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey/) | Информационный ключ типа инструмента. |

### Примеры

В следующем примере демонстрируется поддержка загрузки ресурсов GdFlResource.

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string exportPath = "ComplexGradientFillLayer_after.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is GdFlResource)
                {
                    // Чтение
                    var resource = (GdFlResource)res;
                    if (resource.AlignWithLayer != false ||
                     (Math.Abs(resource.Angle - 45.0) > 0.001) ||
                     resource.Dither != true ||
                     resource.Reverse != false ||
                     resource.Color != Color.Empty ||
                     Math.Abs(resource.HorizontalOffset - (-39)) > 0.001 ||
                     Math.Abs(resource.VerticalOffset - (-5)) > 0.001 ||
                     resource.TransparencyPoints.Length != 3 ||
                     resource.ColorPoints.Length != 2)
                    {
                        throw new Exception("Resource Parameters were read wrong");
                    }
                    var transparencyPoints = resource.TransparencyPoints;
                    if (Math.Abs(100.0 - transparencyPoints[0].Opacity) > 0.25 ||
                     transparencyPoints[0].Location != 0 ||
                     transparencyPoints[0].MedianPointLocation != 50 ||
                     Math.Abs(50.0 - transparencyPoints[1].Opacity) > 0.25 ||
                     transparencyPoints[1].Location != 2048 ||
                     transparencyPoints[1].MedianPointLocation != 50 ||
                     Math.Abs(100.0 - transparencyPoints[2].Opacity) > 0.25 ||
                     transparencyPoints[2].Location != 4096 ||
                     transparencyPoints[2].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Transparency Points were read Wrong");
                    }
                    var colorPoints = resource.ColorPoints;
                    if (colorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
                     colorPoints[0].Location != 0 ||
                     colorPoints[0].MedianPointLocation != 50 ||
                     colorPoints[1].Color != Color.FromArgb(203, 0, 0) ||
                     colorPoints[1].Location != 4096 ||
                     colorPoints[1].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Color Points were read Wrong");
                    }
                    // Редактирование
                    resource.Angle = 30.0;
                    resource.Dither = false;
                    resource.AlignWithLayer = true;
                    resource.Reverse = true;
                    resource.HorizontalOffset = 25;
                    resource.VerticalOffset = -15;
                    var newColorPoints = new List<IGradientColorPoint>(resource.ColorPoints);
                    var
                     newTransparencyPoints = new
                    List<IGradientTransparencyPoint>(resource.TransparencyPoints);
                    newColorPoints.Add(new GradientColorPoint()
                    {
                        Color = Color.Violet,
                        Location = 4096,
                        MedianPointLocation = 75
                    });
                    colorPoints[1].Location = 3000;
                    newTransparencyPoints.Add(new GradientTransparencyPoint()
                    {
                        Opacity = 80.0,
                        Location = 4096,
                        MedianPointLocation = 25
                    });
                    transparencyPoints[2].Location = 3000;
                    resource.ColorPoints = newColorPoints.ToArray();
                    resource.TransparencyPoints = newTransparencyPoints.ToArray();
                    im.Save(exportPath);
                }
                break;
            }
            break;
        }
    }
}
```

### Смотрите также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* сборка [Aspose.PSD](../../)


