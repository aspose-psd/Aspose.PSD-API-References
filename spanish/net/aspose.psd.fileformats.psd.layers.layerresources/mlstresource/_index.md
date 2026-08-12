---
title: "Clase MlstResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource. El recurso mlst. Esta clase, entre otras cosas, contiene información sobre la posición de la capa en la línea de tiempo."
type: docs
weight: 3170
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
{{< psd/tize >}}
## MlstResource class

El recurso mlst. Esta clase, entre otras cosas, contiene información sobre la posición de la capa en la línea de tiempo.

```csharp
public class MlstResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MlstResource](mlstresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Obtiene o establece la versión del descriptor. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Obtiene o establece las estructuras. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Guarda el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


