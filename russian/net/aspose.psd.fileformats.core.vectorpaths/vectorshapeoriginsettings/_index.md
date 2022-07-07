---
title: VectorShapeOriginSettings
second_title: Справочник по Aspose.PSD для .NET API
description: Настройки создания векторной формы.
type: docs
weight: 1440
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

Настройки создания векторной формы.

```csharp
public sealed class VectorShapeOriginSettings
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings#constructor)() | Инициализирует новый экземпляр класса[`VectorShapeOriginSettings`](../vectorshapeoriginsettings). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent) { get; } | Получает значение, указывающее, имеет ли этот экземпляр свойство углов исходного блока. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent) { get; } | Получает значение, указывающее, имеет ли этот экземпляр свойство индекса происхождения. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent) { get; } | Получает значение, указывающее, имеет ли данный экземпляр свойство прямоугольника исходных радиусов. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent) { get; } | Получает значение, указывающее, имеет ли этот экземпляр свойство разрешения источника. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent) { get; } | Получает значение, указывающее, имеет ли этот экземпляр свойство прямоугольника. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent) { get; } | Получает значение, указывающее, имеет ли этот экземпляр свойство типа происхождения. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated) { get; set; } | Получает или задает значение, указывающее, является ли фигура недействительной. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent) { get; } | Получает значение, указывающее, имеет ли этот экземпляр набор недействительных свойств фигуры. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent) { get; } | Получает значение, указывающее, имеет ли данный экземпляр свойство transform. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners) { get; set; } | Получает или задает исходные углы коробки. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex) { get; set; } | Получает или задает индекс исходной формы. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle) { get; set; } | Получает или задает исходный прямоугольник радиусов. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution) { get; set; } | Получает или задает исходное разрешение. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox) { get; set; } | Получает или задает ограничивающую рамку исходной формы. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype) { get; set; } | Получает или задает тип источника. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform) { get; set; } | Получает или задает матрицу преобразования. |

### Примеры

В следующем примере демонстрируется поддержка ресурса VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Чтение
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Редактирование
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
