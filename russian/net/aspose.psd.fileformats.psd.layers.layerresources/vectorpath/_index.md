---
title: "Класс VectorPath"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPath. Класс, содержащий векторные пути."
type: docs
weight: 3730
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/
---
{{< psd/tize >}}
## VectorPath class

Класс, содержащий векторные пути.

```csharp
public class VectorPath : IPath
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorPath](vectorpath/)() | Инициализирует новый экземпляр класса `VectorPath`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isdisabled/) { get; set; } | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [IsFillStartsWithAllPixels](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isfillstartswithallpixels/) { get; set; } | Получает или задает значение, указывающее, начинается ли заливка со всех пикселей. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isinverted/) { get; set; } | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isnotlinked/) { get; set; } | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/version/) { get; set; } | Получает или задает версию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/getitems/)() | Получает массив фигур в пути. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/setitems/)(IPathShape[]) | Задает массив фигур в пути. |

## Примеры

Следующий код демонстрирует объекты пути из ресурсов vsms или vmsk для ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(
    srcFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Удалить одну фигуру
    shapes.RemoveAt(1);

    // Сохранить изменённые данные в ресурс
    List<VectorPathRecord> path = new List<VectorPathRecord>();
    path.Add(new PathFillRuleRecord(null));
    path.Add(new InitialFillRuleRecord(isFillStartsWithAllPixels));

    for (ushort i = 0; i < shapes.Count; i++)
    {
        PathShape shape = (PathShape)shapes[i];
        shape.ShapeIndex = i;
        path.AddRange(shape.ToVectorPathRecords());
    }

    vectorPathDataResource.Paths = path.ToArray();

    image.Save(outFile);
}

// Проверьте изменённые значения в сохранённом файле
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Сохранённый файл должен содержать 1 фигуру
    AssertAreEqual(1, shapes.Count);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

List<IPathShape> GetShapesFromResource(
    VectorPathDataResource vectorPathDataResource,
    out bool isFillStartsWithAllPixels)
{
    List<IPathShape> shapes = new List<IPathShape>();
    LengthRecord lengthRecord = null;
    isFillStartsWithAllPixels = false;
    List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

    foreach (var pathRecord in vectorPathDataResource.Paths)
    {
        if (pathRecord is LengthRecord)
        {
            if (bezierKnotRecords.Count > 0)
            {
                shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
                lengthRecord = null;
                bezierKnotRecords.Clear();
            }

            lengthRecord = (LengthRecord)pathRecord;
        }
        else if (pathRecord is BezierKnotRecord)
        {
            bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
        }
        else if (pathRecord is InitialFillRuleRecord)
        {
            InitialFillRuleRecord initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            isFillStartsWithAllPixels = initialFillRuleRecord.IsFillStartsWithAllPixels;
        }
    }

    if (bezierKnotRecords.Count > 0)
    {
        shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
        lengthRecord = null;
        bezierKnotRecords.Clear();
    }

    return shapes;
}
```

### См. также

* interface [IPath](../ipath/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


