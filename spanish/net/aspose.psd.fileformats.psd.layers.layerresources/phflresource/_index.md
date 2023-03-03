---
title: Class PhflResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource clase. Clase PhflResource. Recurso de capa de ajuste de exposición 2 Versión   3  o   2  12 4 bytes cada uno para el color XYZ solo en la versión 3 10 2 bytes de espacio de color seguido de 4  2 bytes de componente de color solo en la versión 2 4 Densidad 1 Conservar Luminosidad
type: docs
weight: 2890
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Clase PhflResource. Recurso de capa de ajuste de exposición 2 Versión ( = 3 ) o ( = 2 ) 12 4 bytes cada uno para el color XYZ (solo en la versión 3) 10 2 bytes de espacio de color seguido de 4 * 2 bytes de componente de color (solo en la versión 2) 4 Densidad 1 Conservar Luminosidad

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Obtiene o establece la densidad. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Obtiene o establece un valor que indica si [preservar la luminosidad]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Obtiene la versión psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtiene la firma. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Obtiene la versión. El valor predeterminado es 2 o 3 |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Obtiene el color del RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Establece el color RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


