---
title: Struct Point
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Point estructura. Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.
type: docs
weight: 5260
url: /es/net/aspose.psd/point/
---
## Point structure

Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.

```csharp
public struct Point
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Point](point/#constructor_1)(int) | Inicializa una nueva instancia del`Point` estructura usando coordenadas especificadas por un valor entero. |
| [Point](point/#constructor)(Size) | Inicializa una nueva instancia del`Point` estructura de la[`Size`](../size/)estructura. |
| [Point](point/#constructor_2)(int, int) | Inicializa una nueva instancia del`Point` estructura con las coordenadas especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Obtiene una nueva instancia del`Point` estructura que tiene[`X`](./x/) y[`Y`](./y/) valores establecidos en cero. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Obtiene un valor que indica si este`Point` está vacío. |
| [X](../../aspose.psd/point/x/) { get; set; } | Obtiene o establece la coordenada x de este`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Obtiene o establece la coordenada y de este`Point` . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Agrega el especificado[`Size`](../size/) a lo especificado`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Convierte el especificado[`PointF`](../pointf/) a un`Point` redondeando los valores de[`PointF`](../pointf/) a los siguientes valores enteros más altos. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Convierte el especificado[`PointF`](../pointf/) a un`Point` objeto redondeando el`Point` valores al entero más próximo. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Devuelve el resultado de restar especificado[`Size`](../size/) de lo especificado`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Convierte el especificado[`PointF`](../pointf/) a un`Point` truncando los valores de`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Especifica si este`Point` contiene las mismas coordenadas que el especificadoObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Devuelve un código hash para este`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Traduce esto`Point` por el especificado`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Traduce esto`Point`por la cantidad especificada. |
| override [ToString](../../aspose.psd/point/tostring/)() | Convierte esto`Point` a una cadena legible por humanos. |
| [operator +](../../aspose.psd/point/op_addition/) | Traduce un`Point` por un dado[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Compara dos`Point` objetos. El resultado especifica si los valores de la[`X`](./x/) y[`Y`](./y/) propiedades de los dos`Point` los objetos son iguales. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Convierte el especificado`Point` estructura a un[`Size`](../size/)estructura. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Convierte el especificado`Point` estructura a la[`PointF`](../pointf/)estructura. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Compara dos`Point` objetos. El resultado especifica si los valores de la[`X`](./x/) o[`Y`](./y/) propiedades de los dos`Point` los objetos son desiguales. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Traduce un`Point` por el negativo de un dado[`Size`](../size/) . |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


