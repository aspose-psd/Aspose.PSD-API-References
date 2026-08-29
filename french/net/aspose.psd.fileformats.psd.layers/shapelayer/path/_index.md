---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété ShapeLayer. Obtient l'ensemble des chemins présents dans un calque de forme"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Obtient l'ensemble des chemins présents dans un calque Shape.

```csharp
public IPath Path { get; }
```

## Exemples

Le code suivant montre la prise en charge du calque ShapeLayer.

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

    // Le fichier source contient 2 figures. Supprimez la seconde.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Voir aussi

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


