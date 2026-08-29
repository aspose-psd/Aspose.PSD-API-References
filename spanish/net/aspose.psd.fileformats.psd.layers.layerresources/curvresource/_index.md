---
title: "Clase CurvResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource. Clase CurvResource. Recurso de capa de ajuste de Curvas 1 byte  0 si se usan curvas 1 si se usan píxeles en el mapa si 0 entonces 2 bytes  short. El valor predeterminado es 1 4 bytes  int. Usado solo el último byte por bit. El primer bit es para 1 canal, el cuarto bit para 4 canales, por ejemplo 2 bytes  short recuento de puntos 4 bytes  recuento de puntos de la curva 2 short primera posición segunda altura 4 bytes  word Crv  2 bytes  short predeterminado es 4 para Curvas 4 bytes  int. Predeterminado es 1 4 bytes  recuento de puntos 4 bytes  recuento de puntos de la curva 2 short primera posición segunda altura 04 bytes  Se debe plegar para cuatro si 1 entonces 2 bytes  short. Predeterminado es 1 4 bytes  int. Usado solo el último byte. Un canal está en un bit. El primer bit es para 1 canal, el cuarto bit para 4 canales, por ejemplo 256  recuento de canales cambiados  valores ordenados del canal en el rango 0  255 4 bytes  word Crv  2 bytes  short. Predeterminado es 3 para píxeles en el mapa 4 bytes  int Recuento de canales 2  256 bytes  short 2 para índice de canal 256 son valores ordenados del canal en el rango 0  255"
type: docs
weight: 2660
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Clase CurvResource. Recurso de capa de ajuste de curvas 1 byte - 0 si se usan curvas, 1 si se usan píxeles en el mapa; si es 0 entonces: 2 bytes - short. El valor predeterminado es 1 4 bytes - int. Se usa solo el último byte por bit. El primer bit es para 1 canal, el cuarto bit para 4 canales, por ejemplo 2 bytes - short contador de puntos 4 bytes * recuento de puntos - puntos de la curva 2 short: primera posición, segunda altura 4 bytes - word "Crv " 2 bytes - short predeterminado es 4 para Curvas 4 bytes - int. Predeterminado es 1 4 bytes - recuento de puntos 4 bytes * recuento de puntos - puntos de la curva 2 short: primera posición, segunda altura 0-4 bytes - Conduce a ser plegado para cuatro si es 1 entonces: 2 bytes - short. Predeterminado es 1 4 bytes - int. Se usa solo el último byte. Un canal está en un bit. El primer bit es para 1 canal, el cuarto bit para 4 canales, por ejemplo 256 * recuento de canales cambiados - valores ordenados del canal en el rango 0 - 255 4 bytes - word "Crv " 2 bytes - short. Predeterminado es 3 para píxeles en el mapa 4 bytes - int Recuento de canales (2 + 256) bytes - short 2 para índice de canal, 256 son valores ordenados del canal en el rango 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Inicializa una nueva instancia de la clase `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | Inicializa una nueva instancia de la clase `CurvResource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Obtiene o establece un valor que indica si esta instancia almacena datos de forma discreta. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Obtiene el administrador activo. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Obtiene los datos del canal. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Obtiene el administrador de curvas. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


