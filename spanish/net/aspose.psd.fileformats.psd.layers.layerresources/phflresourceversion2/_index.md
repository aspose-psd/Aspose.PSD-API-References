---
title: "Clase PhflResourceVersion2"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 clase. Clase PhflResource. Recurso de la capa de ajuste de exposición 2 Versión   3  o   2  12 4 bytes cada uno para XYZ colorOnly en la Versión 3 10 2 bytes espacio de color seguido de 4  2 bytes componente de colorOnly en la Versión 2 4 Densidad 1 Preservar luminosidad"
type: docs
weight: 3250
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

Clase PhflResource. Recurso de capa de ajuste Exposure 2 Versión ( = 3 ) o ( = 2 ) 12 4 bytes cada uno para color XYZ (Solo en la Versión 3) 10 2 bytes espacio de color seguido de 4 * 2 bytes componente de color (Solo en la Versión 2) 4 Densidad 1 Preservar Luminosidad

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | Inicializa una nueva instancia de la clase `PhflResourceVersion2`. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | Inicializa una nueva instancia de la clase `PhflResourceVersion2`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Obtiene el espacio de color. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Obtiene o establece el componente A del color |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | Obtiene o establece el componente B |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Obtiene o establece el componente L del color |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Obtiene o establece la densidad. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Obtiene o establece un valor que indica si [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Obtiene la versión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Obtiene el color. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | Establece el color RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

### Ver también

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


