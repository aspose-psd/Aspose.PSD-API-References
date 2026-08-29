---
title: "ShapeLayer.ShapeLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор ShapeLayer. Инициализирует новый экземпляр класса ShapeLayer. Все ресурсы создаются в состоянии по умолчанию"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Инициализирует новый экземпляр класса [`ShapeLayer`](../). Все ресурсы создаются в состоянии по умолчанию.

```csharp
public ShapeLayer()
```

## Примеры

Следующий код демонстрирует поддержку слоя ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    IPath layerPath = shapeLayer.Path;

    IPathShape[] pathShapeSource = layerPath.GetItems();
    List<IPathShape> pathShapesDest = new List<IPathShape>(pathShapeSource);

    // Исходный файл содержит 2 фигуры. Удалите вторую.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### См. также

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


