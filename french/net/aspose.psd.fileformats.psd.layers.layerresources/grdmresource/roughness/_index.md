---
title: "GrdmResource.Roughness"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété GrdmResource. Facteur de rugosité. Lorsque le type de dégradé est Bruit, on peut attribuer une rugosité de 0 à 2048"
type: docs
weight: 160
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/
---
{{< psd/tize >}}
## GrdmResource.Roughness property

Facteur de rugosité. Lorsque le 'Gradient type' = 'Noise', nous pouvons assigner la 'Roughness' (0 - 2048).

```csharp
public int Roughness { get; set; }
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

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


