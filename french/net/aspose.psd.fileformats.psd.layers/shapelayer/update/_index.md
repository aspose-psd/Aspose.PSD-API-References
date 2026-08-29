---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ShapeLayer. Met à jour les ressources à partir des propriétés du calque de forme"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

Met à jour les ressources à partir des propriétés du calque Shape.

```csharp
public void Update()
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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


