---
title: Class BritResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource clase. Clase BritResource. Recurso de ajuste de brillo/contraste Layer
type: docs
weight: 2340
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

Clase BritResource. Recurso de ajuste de brillo/contraste Layer

```csharp
public class BritResource : AdjustmentLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BritResource](britresource/#constructor)() | Inicializa una nueva instancia del`BritResource` clase. |
| [BritResource](britresource/#constructor_1)(byte[]) | Inicializa una nueva instancia del`BritResource`class. La especificación de formato PSD contiene la siguiente descripción: 2 Brillo 2 Contraste 2 Valor medio de brillo y contraste 1 Lab color only No se usa en PSD moderno (CS5 y superior) donde está CgEd. CgEd almacena información properties |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Inicializa una nueva instancia del`BritResource` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Obtiene o establece el brillo. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Obtiene o establece el contraste. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Obtiene o establece un valor que indica si [color de laboratorio]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Obtiene o establece el valor medio de brillo y contraste. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion/) { get; } | Obtiene la versión psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


