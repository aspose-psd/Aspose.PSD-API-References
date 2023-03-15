---
title: IVectorPathData.IsDisabled
second_title: Справочник по Aspose.PSD для .NET API
description: IVectorPathData свойство. Получает или задает значение указывающее отключен ли этот экземпляр.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/
---
## IVectorPathData.IsDisabled property

Получает или задает значение, указывающее, отключен ли этот экземпляр.

```csharp
public bool IsDisabled { get; set; }
```

### Стоимость имущества

`истинный` если этот экземпляр отключен; в противном случае,`ЛОЖЬ` .

### Примеры

Этот пример демонстрирует поддержку ресурса WorkingPathResource в PsdImage.ImageResources для корректной работы операции Crop.

```csharp
[C#]

// Обрезать изображение и сохранить.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Поиск ресурса WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Обрезать и сохранить.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Загружаем сохраненное изображение и проверяем изменения.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Поиск ресурса WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Смотрите также

* interface [IVectorPathData](../)
* пространство имен [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* сборка [Aspose.PSD](../../../)


