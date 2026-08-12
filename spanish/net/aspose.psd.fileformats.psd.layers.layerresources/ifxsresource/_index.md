---
title: "Clase IfxsResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource. Recurso de grupo de efectos de capa Ifxs"
type: docs
weight: 2840
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Recurso Ifxs (recurso de efectos de capa de grupo)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [IfxsResource](ifxsresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Obtiene la versión del descriptor. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

## Ejemplos

El siguiente código demuestra el soporte de IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // El ejemplo tiene 2 capas de grupo con efectos
    // Capa de grupo con un efecto
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Capa de grupo con muchos efectos
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Obtén el número de efectos y verifica su cantidad
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Un efecto en la capa de grupo está en el recurso 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Dos o más efectos en una capa de grupo están en el recurso 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Agrega una tercera sombra a una capa de grupo con múltiples efectos
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Ver también

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


