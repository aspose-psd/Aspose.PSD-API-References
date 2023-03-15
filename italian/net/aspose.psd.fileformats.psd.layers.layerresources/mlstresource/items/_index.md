---
title: MlstResource.Items
second_title: Aspose.PSD per riferimento API .NET
description: MlstResource proprietà. Ottiene o imposta le strutture.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

Ottiene o imposta le strutture.

```csharp
public OSTypeStructure[] Items { get; }
```

### Esempi

Il codice seguente illustra il supporto della risorsa MlstResource che fornisce un meccanismo di basso livello per manipolare gli stati del livello.

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

    // Disabilita il livello 1 sul fotogramma 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Guarda anche

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* assemblea [Aspose.PSD](../../../)


