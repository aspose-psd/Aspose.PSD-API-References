---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ILayerEffect. Calcule et obtient les limites des pixels d'effet en fonction des limites des pixels du calque d'entrée"
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Calcule et obtient les limites des pixels d'effet basées sur les limites des pixels du calque d'entrée.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| layerBounds | Rectangle | Les limites des pixels du calque. |
| globalAngle | Int32 | L'angle global pour calculer l'angle de lumière globale. |

### Valeur de retour

Les limites des pixels d'effet basées sur les limites des pixels du calque d'entrée.

## Exemples

Démontre comment obtenir les limites d'un calque avec effets et l'exporter avec la taille correcte.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Pour enregistrer dans les limites du PsdImage à l'emplacement d'origine du calque

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### Voir aussi

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


