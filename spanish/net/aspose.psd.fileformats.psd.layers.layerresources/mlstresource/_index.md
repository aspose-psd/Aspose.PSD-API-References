---
title: Class MlstResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource clase. El recurso mlst. Esta clase entre otras cosas contiene información sobre la posición de la capa en la línea de tiempo.
type: docs
weight: 2830
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

El recurso mlst. Esta clase, entre otras cosas, contiene información sobre la posición de la capa en la línea de tiempo.

```csharp
public class MlstResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MlstResource](mlstresource/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Obtiene o establece la versión del descriptor. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Obtiene o establece las estructuras. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Obtiene la versión psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Guarda el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


