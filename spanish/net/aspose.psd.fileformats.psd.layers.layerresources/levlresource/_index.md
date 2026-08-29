---
title: "Clase LevlResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource. Clase LevlResource. Recurso de capa de ajuste de Exposición."
type: docs
weight: 2950
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Clase LevlResource. Recurso de capa de ajuste de exposición

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Inicializa una nueva instancia de la clase `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Inicializa una nueva instancia de la clase `LevlResource`. Compatible en modos de color Escala de Grises, Duotono, RGB, CMYK, Lab 2 bytes - Versión (=2) 29 * 10 bytes - Conjuntos de registros de nivel con 5 enteros cortos 4 bytes - Cabecera Lvls (comienza en el índice 292) 2 bytes - Versión (=3) 2 bytes - Recuento total de registros de nivel 10 * (Recuento Total - 29) El terminador cero del recurso Lvls también debe plegarse para cuatro. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Obtiene la versión. El valor predeterminado es 2 |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Obtiene el canal. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


