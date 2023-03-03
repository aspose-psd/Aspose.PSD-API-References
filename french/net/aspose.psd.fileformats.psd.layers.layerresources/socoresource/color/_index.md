---
title: SoCoResource.Color
second_title: Référence de l'API Aspose.PSD pour .NET
description: SoCoResource propriété. Obtient la couleur RVB .
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Obtient la couleur RVB .

```csharp
public Color Color { get; set; }
```

### Return_Value

La couleur RVB

### Exemples

L'exemple suivant montre comment vous modifiez SoCoResource (ressource de calque pour le calque de remplissage de couleur)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Charger une image existante dans une instance de la classe PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Recherche de FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Recherche de SoCoResource dans la liste des ressources de la couche
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Définition de la propriété SoCoResource Color
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Voir également

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* Assemblée [Aspose.PSD](../../../)


