---
title: Class MixrResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource clase. Clase MixrResource. Recurso de ajuste del mezclador de canales Layer
type: docs
weight: 2820
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Clase MixrResource. Recurso de ajuste del mezclador de canales Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Inicializa una nueva instancia del`MixrResource` class. La especificación de formato PSD contiene la siguiente descripción: 2 Versión ( = 1) 2 Monochrome 20 Color RGB o CMYK más constante para la configuración del mezclador. 4 * 2 bytes de color con 2 bytes de constante. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Inicializa una nueva instancia del`MixrResource` class. La especificación de formato PSD contiene la siguiente descripción: 2 Versión ( = 1) 2 Monochrome 20 Color RGB o CMYK más constante para la configuración del mezclador. 4 * 2 bytes de color con 2 bytes de constante. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Obtiene o establece un valor que indica si este`MixrResource` es monocromo. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Obtiene la versión psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtiene la firma. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Obtiene o establece la versión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Obtiene la información del canal raw data |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Establece la información del canal. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


