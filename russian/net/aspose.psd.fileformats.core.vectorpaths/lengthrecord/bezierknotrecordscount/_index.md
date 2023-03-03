---
title: LengthRecord.BezierKnotRecordsCount
second_title: Справочник по Aspose.PSD для .NET API
description: LengthRecord свойство. Получает или задает количество записей узлов Безье.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/bezierknotrecordscount/
---
## LengthRecord.BezierKnotRecordsCount property

Получает или задает количество записей узлов Безье.

```csharp
public int BezierKnotRecordsCount { get; set; }
```

### Примеры

В следующем примере кода демонстрируется поддержка новых свойств LengthRecord, PathOperations (логические операции), ShapeIndex и BezierKnotRecordsCount.

```csharp
[C#]

string sourceFilePath = "PathOperationsShape.psd";
string outputFilePath = "out_PathOperationsShape.psd";

using (var im = (PsdImage)Image.Load(sourceFilePath))
{
    VsmsResource resource = null;
    foreach (var layerResource in im.Layers[1].Resources)
    {
        if (layerResource is VsmsResource)
        {
            resource = (VsmsResource)layerResource;
            break;
        }
    }

    LengthRecord lengthRecord0 = (LengthRecord)resource.Paths[2];
    LengthRecord lengthRecord1 = (LengthRecord)resource.Paths[7];
    LengthRecord lengthRecord2 = (LengthRecord)resource.Paths[11];

    // Здесь мы меняем способ объединения фигур.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Смотрите также

* class [LengthRecord](../)
* пространство имен [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* сборка [Aspose.PSD](../../../)


