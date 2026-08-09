---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "ShmdResource propriété. Obtient les sous-ressources de la ressource shmd"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

Obtient les sous-ressources de la ressource shmd.

```csharp
public LayerResource[] SubResources { get; }
```

## Exemples

Le code suivant montre la prise en charge de la ressource MlstResource qui fournit un mécanisme de bas niveau pour manipuler les états du calque.

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

    // Désactiver le calque 1 sur la trame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Voir aussi

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


