---
title: Layer.BlendModeKey
second_title: Référence de l'API Aspose.PSD pour .NET
description: Layer propriété. Obtient ou définit la clé du mode de fusion.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

Obtient ou définit la clé du mode de fusion.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### Valeur de la propriété

La clé du mode de fusion.

### Exemples

L'exemple suivant montre comment vous pouvez utiliser le mode de fusion de calque PassThrough dans Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir également

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)


