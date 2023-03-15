---
title: ShmdResource.SubResources
second_title: Aspose.PSD per riferimento API .NET
description: ShmdResource proprietà. Ottiene le risorse secondarie della risorsa shmd.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Ottiene le risorse secondarie della risorsa shmd.

```csharp
public LayerResource[] SubResources { get; }
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

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* assemblea [Aspose.PSD](../../../)


