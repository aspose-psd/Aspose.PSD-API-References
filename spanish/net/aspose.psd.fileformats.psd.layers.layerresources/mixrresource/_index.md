---
title: "Clase MixrResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource. Clase MixrResource. Recurso de la capa de ajuste de mezclador de canales"
type: docs
weight: 3160
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Clase MixrResource. Recurso de capa de ajuste Channel Mixer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Inicializa una nueva instancia de la clase `MixrResource`. La especificación del formato PSD contiene la siguiente descripción: 2 Versión (= 1) 2 Monocromo 20 color RGB o CMYK más constante para los ajustes del mezclador. 4 * 2 bytes de color con 2 bytes de constante. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Inicializa una nueva instancia de la clase `MixrResource`. La especificación del formato PSD contiene la siguiente descripción: 2 Versión (= 1) 2 Monocromo 20 color RGB o CMYK más constante para los ajustes del mezclador. 4 * 2 bytes de color con 2 bytes de constante. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Obtiene o establece un valor que indica si este `MixrResource` es monocromo. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Obtiene o establece la versión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Obtiene los datos sin procesar de la información del canal. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Establece la información del canal. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


