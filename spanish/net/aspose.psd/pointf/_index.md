---
title: "Estructura PointF"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.PointF. Representa un par ordenado de coordenadas x e y de punto flotante que define un punto en un plano bidimensional."
type: docs
weight: 5770
url: /es/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

Representa un par ordenado de coordenadas de punto flotante x e y que define un punto en un plano bidimensional.

```csharp
public struct PointF
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PointF](pointf/)(float, float) | Inicializa una nueva instancia de la estructura `PointF` con las coordenadas especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Obtiene una nueva instancia de la estructura `PointF` que tiene los valores [`X`](./x/) y [`Y`](./y/) establecidos en cero. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Obtiene un valor que indica si este `PointF` está vacío. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Obtiene o establece la coordenada x de este `PointF`. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Obtiene o establece la coordenada y de este `PointF`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Traslada un `PointF` dado por el [`Size`](../size/) especificado. |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Traslada un `PointF` dado por un [`SizeF`](../sizef/) especificado. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Traslada un `PointF` por el negativo de un tamaño especificado. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Traslada un `PointF` por el negativo de un tamaño especificado. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Especifica si este `PointF` contiene las mismas coordenadas que el objeto especificado. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Devuelve un código hash para esta estructura `PointF`. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Convierte este `PointF` a una cadena legible por humanos. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Traslada un `PointF` por un [`Size`](../size/) dado. (2 operadores) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | Compara dos estructuras `PointF`. El resultado especifica si los valores de las propiedades [`X`](./x/) y [`Y`](./y/) de las dos estructuras `PointF` son iguales. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Determina si las coordenadas de los puntos especificados no son iguales. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Traslada un `PointF` por el negativo de un [`Size`](../size/) dado. (2 operadores) |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


