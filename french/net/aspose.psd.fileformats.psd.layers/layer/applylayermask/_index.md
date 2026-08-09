---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Layer. Applique le masque de couche à la couche puis supprime le masque"
type: docs
weight: 350
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Applique le masque de calque au calque, puis supprime le masque.

```csharp
public void ApplyLayerMask()
```

## Exemples

Le code suivant démontre la fonctionnalité d'application du masque à la couche.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


