---
title: ShmdResource.SubResources
second_title: Referencia de API de Aspose.PSD para .NET
description: ShmdResource propiedad. Obtiene los subrecursos de shmd resource.
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Obtiene los subrecursos de shmd resource.

```csharp
public LayerResource[] SubResources { get; }
```

### Ejemplos

El siguiente código demuestra la compatibilidad con el recurso MlstResource que brinda un mecanismo de bajo nivel para manipular los estados de la capa.

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

    // Deshabilitar la capa 1 en el marco 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Ver también

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* asamblea [Aspose.PSD](../../../)


