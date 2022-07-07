---
title: PtFlResource
second_title: Справочник по Aspose.PSD для .NET API
description: Класс PtFlResource. Содержит данные слоя заполнения узором.
type: docs
weight: 2880
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
## PtFlResource class

Класс PtFlResource. Содержит данные слоя заполнения узором.

```csharp
public class PtFlResource : FillLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PtFlResource](ptflresource)(string, string) | Инициализирует новый экземпляр класса[`PtFlResource`](../ptflresource). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer) { get; set; } | Получает или задает значение, указывающее, следует ли [выравнивать со слоем]. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer) { get; set; } | Получает или задает значение, указывающее, связан ли этот экземпляр со слоем. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length) { get; } | Получает длину ресурса слоя в байтах. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset) { get; set; } | Получает или задает смещение. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid) { get; set; } | Получает или задает идентификатор шаблона. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname) { get; set; } | Получает или задает имя шаблона. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion) { get; } | Получает минимальную версию psd, необходимую для ресурса слоя. 0 означает отсутствие ограничений. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale) { get; set; } | Получает или задает масштаб. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature) { get; } | Получает подпись ресурса слоя. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey) | Клавиша информации о типе инструмента. |

### Примеры

В следующем примере демонстрируется поддержка загрузки и редактирования ресурса PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
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
                if (res is PtFlResource)
                {
                    // Чтение
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // Редактирование
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // У нас нет данных шаблона в PattResource, поэтому мы можем их добавить.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Смотрите также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* class [FillLayerResource](../filllayerresource)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
