---
title: "Класс VectorShapeOriginSettings"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings класс. Настройки происхождения векторной формы."
type: docs
weight: 1450
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

Настройки происхождения векторной формы.

```csharp
public sealed class VectorShapeOriginSettings
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Инициализирует новый экземпляр класса `VectorShapeOriginSettings`. |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | Инициализирует новый экземпляр класса `VectorShapeOriginSettings`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Получает значение, указывающее, имеет ли этот экземпляр свойство углов исходного коробочного прямоугольника. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Возвращает значение, указывающее, имеет ли данный экземпляр свойство origin index. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Возвращает значение, указывающее, имеет ли данный экземпляр свойство origin radii rectangle. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Возвращает значение, указывающее, имеет ли данный экземпляр свойство origin resolution. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Возвращает значение, указывающее, имеет ли данный экземпляр свойство rectangle. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Возвращает значение, указывающее, имеет ли данный экземпляр свойство origin type. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Возвращает или задает значение, указывающее, недействительна ли форма. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Возвращает значение, указывающее, установлен ли набор свойства shape invalidated у данного экземпляра. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Возвращает значение, указывающее, имеет ли данный экземпляр свойство transform. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Возвращает или задает углы исходного бокса. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Возвращает или задает индекс исходной формы. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Возвращает или задает прямоугольник исходных радиусов. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Возвращает или задает исходное разрешение. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Возвращает или задает ограничивающий прямоугольник исходной формы. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Возвращает или задает тип исходного объекта. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Возвращает или задает матрицу преобразования. |

## Примеры

Следующий пример демонстрирует поддержку ресурса VogkResource.

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

### См. также

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


