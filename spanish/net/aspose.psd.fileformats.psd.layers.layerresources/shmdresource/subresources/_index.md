---
title: "ShmdResource.SubResources"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad de ShmdResource. Obtiene los subrecursos del recurso shmd"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

Obtiene los subrecursos del recurso shmd.

```csharp
public LayerResource[] SubResources { get; }
```

## Ejemplos

El siguiente código demuestra el soporte del recurso MlstResource que brinda un mecanismo de bajo nivel para manipular los estados de la capa.

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

    // Desactivar la capa 1 en el fotograma 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Ver también

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


