---
title: MlstResource.Items
second_title: Référence de l'API Aspose.PSD pour .NET
description: MlstResource propriété. Obtient ou définit les structures.
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

Obtient ou définit les structures.

```csharp
public OSTypeStructure[] Items { get; }
```

### Exemples

Le code suivant illustre la prise en charge de la ressource MlstResource qui fournit un mécanisme de bas niveau pour manipuler les états des couches.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Désactive le calque 1 sur l'image 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Voir également

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* Assemblée [Aspose.PSD](../../../)


