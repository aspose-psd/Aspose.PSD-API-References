---
title: CurvResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Clase CurvResource. Recurso de ajuste de curvas Capa 1 byte  0 si usa curvas 1 si usa píxeles en el mapa si es 0 entonces 2 bytes  corto. El valor predeterminado es 1 4 bytes  int. Usado solo el último byte por bit. El primer bit es para 1 canal el cuarto bit para 4 canales por ejemplo 2 bytes  recuento de puntos cortos 4 bytes  recuento de puntos  puntos de curva 2 cortos primera posición segunda altura 4 bytes  palabra Crv  2 bytes  corto predeterminado es 4 para Curves 4 bytes  int. El valor predeterminado es 1 4 bytes  recuento de puntos 4 bytes  recuento de puntos  puntos de la curva 2 cortos primera posición segunda altura 04 bytes  Previo a ser doblado por cuatro si 1 entonces 2 bytes  corto. El valor predeterminado es 1 4 bytes  int. Usado solo el último byte. Un canal está en un bit. El primer bit es para 1 canal el cuarto bit para 4 canales por ejemplo 256  recuento de canales cambiados  valores ordenados del canal en el rango 0  255 4 bytes  palabra Crv  2 bytes  corto. El valor predeterminado es 3 para píxeles en map 4 bytes  int Channel count 2  256 bytes  short 2 para índice de canal 256 son valores ordenados del canal en el rango 0  255
type: docs
weight: 2380
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Clase CurvResource. Recurso de ajuste de curvas Capa 1 byte - 0 si usa curvas, 1 si usa píxeles en el mapa si es 0 entonces: 2 bytes - corto. El valor predeterminado es 1 4 bytes - int. Usado solo el último byte por bit. El primer bit es para 1 canal, el cuarto bit para 4 canales por ejemplo 2 bytes - recuento de puntos cortos 4 bytes * recuento de puntos - puntos de curva 2 cortos: primera posición, segunda altura 4 bytes - palabra "Crv " 2 bytes - corto predeterminado es 4 para Curves 4 bytes - int. El valor predeterminado es 1 4 bytes - recuento de puntos 4 bytes * recuento de puntos - puntos de la curva 2 cortos: primera posición, segunda altura 0-4 bytes - Previo a ser doblado por cuatro si 1 entonces: 2 bytes - corto. El valor predeterminado es 1 4 bytes - int. Usado solo el último byte. Un canal está en un bit. El primer bit es para 1 canal, el cuarto bit para 4 canales, por ejemplo 256 * recuento de canales cambiados - valores ordenados del canal en el rango 0 - 255 4 bytes - palabra "Crv " 2 bytes - corto. El valor predeterminado es 3 para píxeles en map 4 bytes - int Channel count (2 + 256) bytes - short 2 para índice de canal, 256 son valores ordenados del canal en el rango 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CurvResource](curvresource#constructor)(byte[]) | Inicializa una nueva instancia del[`CurvResource`](../curvresource) clase. |
| [CurvResource](curvresource#constructor_1)(int) | Inicializa una nueva instancia del[`CurvResource`](../curvresource) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely) { get; set; } | Obtiene o establece un valor que indica si esta instancia son datos almacenados discretos. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion) { get; } | Obtiene la versión psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager)() | Obtiene el administrador activo. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata)(int) | Obtiene los datos del canal. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager)() | Obtiene el administrador de curvas. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey) | La clave de información de la herramienta de tipo. |

### Ver también

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
