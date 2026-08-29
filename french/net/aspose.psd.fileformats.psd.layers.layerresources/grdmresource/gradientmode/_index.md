---
title: "GrdmResource.GradientMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "GrdmResource propriété. Mode pour ce dégradé. Détermine le type de dégradé  Solide/Bruit 0/1"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/
---
{{< psd/tize >}}
## GrdmResource.GradientMode property

Le mode pour ce dégradé détermine 'Gradient Type' = 'Solid/Noise' (0/1).

```csharp
public GradientKind GradientMode { get; set; }
```

## Exemples

Le code suivant démontre la prise en charge de la ressource GrdmResource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // vérifier les valeurs actuelles
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Couleur rouge pour le deuxième point de couleur du dégradé
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // vérifier les valeurs modifiées
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Voir aussi

* enum [GradientKind](../../../aspose.psd.fileformats.psd.layers.gradient/gradientkind/)
* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


