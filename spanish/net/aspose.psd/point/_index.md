---
title: "Estructura Point"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.Point. Representa un par ordenado de coordenadas enteras x e y que define un punto en un plano bidimensional."
type: docs
weight: 5760
url: /es/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Representa un par ordenado de coordenadas enteras x e y que define un punto en un plano bidimensional.

```csharp
public struct Point
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Point](point/#constructor_1)(int) | Inicializa una nueva instancia de la estructura `Point` usando coordenadas especificadas por un valor entero. |
| [Point](point/#constructor)(Size) | Inicializa una nueva instancia de la estructura `Point` a partir de la estructura [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | Inicializa una nueva instancia de la estructura `Point` con las coordenadas especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Obtiene una nueva instancia de la estructura `Point` que tiene los valores [`X`](./x/) y [`Y`](./y/) establecidos en cero. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Obtiene un valor que indica si este `Point` está vacío. |
| [X](../../aspose.psd/point/x/) { get; set; } | Obtiene o establece la coordenada x de este `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Obtiene o establece la coordenada y de este `Point`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Agrega el [`Size`](../size/) especificado al `Point` especificado. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Convierte el [`PointF`](../pointf/) especificado a un `Point` redondeando los valores del [`PointF`](../pointf/) al siguiente entero superior. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Convierte el [`PointF`](../pointf/) especificado a un objeto `Point` redondeando los valores del `Point` al entero más cercano. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Devuelve el resultado de restar el [`Size`](../size/) especificado del `Point` especificado. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Convierte el [`PointF`](../pointf/) especificado a un `Point` truncando los valores del `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Especifica si este `Point` contiene las mismas coordenadas que el Objeto especificado. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Devuelve un código hash para este `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Traslada este `Point` por el `Point` especificado. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Traslada este `Point` por la cantidad especificada. |
| override [ToString](../../aspose.psd/point/tostring/)() | Convierte este `Point` a una cadena legible por humanos. |
| [operator +](../../aspose.psd/point/op_addition/) | Traslada un `Point` por un [`Size`](../size/) dado. |
| [operator ==](../../aspose.psd/point/op_equality/) | Compara dos objetos `Point`. El resultado indica si los valores de las propiedades [`X`](./x/) y [`Y`](./y/) de los dos objetos `Point` son iguales. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Convierte la estructura `Point` especificada a una estructura [`Size`](../size/). |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Convierte la estructura `Point` especificada a la estructura [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/point/op_inequality/) | Compara dos objetos `Point`. El resultado indica si los valores de las propiedades [`X`](./x/) o [`Y`](./y/) de los dos objetos `Point` son diferentes. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Traslada un `Point` por el negativo de un [`Size`](../size/) dado. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


