---
title: "Estructura SizeF"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.SizeF. Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo."
type: docs
weight: 6060
url: /es/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo.

```csharp
public struct SizeF
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Inicializa una nueva instancia de la estructura `SizeF` a partir del [`PointF`](../pointf/) especificado. |
| [SizeF](sizef/#constructor_1)(SizeF) | Inicializa una nueva instancia de la estructura `SizeF` a partir del `SizeF` especificado. |
| [SizeF](sizef/#constructor_2)(float, float) | Inicializa una nueva instancia de la estructura `SizeF` a partir de las dimensiones especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Obtiene una nueva instancia de la estructura `SizeF` que tiene los valores [`Width`](./width/) y [`Height`](./height/) establecidos en cero. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Obtiene o establece el componente vertical de este `SizeF`. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Obtiene un valor que indica si este `SizeF` tiene ancho y alto cero. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Obtiene o establece el componente horizontal de este `SizeF`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Suma el ancho y alto de una estructura `SizeF` al ancho y alto de otra estructura `SizeF`. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Resta el ancho y alto de una estructura `SizeF` del ancho y alto de otra estructura `SizeF`. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Comprueba si el objeto especificado es un `SizeF` con las mismas dimensiones que este `SizeF`. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Devuelve un código hash para esta estructura [`Size`](../size/). |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Convierte un `SizeF` a un [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Convierte un `SizeF` a una estructura [`Size`](../size/) con valores de tamaño truncados. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Crea una cadena legible que representa este `SizeF`. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Suma el ancho y alto de una estructura `SizeF` al ancho y alto de otra estructura `SizeF`. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Comprueba si dos estructuras `SizeF` son iguales. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Convierte el `SizeF` especificado a un [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Comprueba si dos estructuras `SizeF` son diferentes. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Resta el ancho y alto de una estructura `SizeF` del ancho y alto de otra estructura `SizeF`. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


