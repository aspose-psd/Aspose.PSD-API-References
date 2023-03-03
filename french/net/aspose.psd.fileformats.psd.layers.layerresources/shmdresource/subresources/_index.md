---
title: ShmdResource.SubResources
second_title: Référence de l'API Aspose.PSD pour .NET
description: ShmdResource propriété. Obtient les sousressources de la ressource shmd.
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Obtient les sous-ressources de la ressource shmd.

```csharp
public LayerResource[] SubResources { get; }
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

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* Assemblée [Aspose.PSD](../../../)


