---
title: "Estructura Size"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.Size. Representa el tamaño"
type: docs
weight: 6050
url: /es/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Representa el tamaño.

```csharp
public struct Size
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Size](size/#constructor)(Point) | Inicializa una nueva instancia de la estructura `Size` a partir del [`Point`](../point/) especificado. |
| [Size](size/#constructor_1)(int, int) | Inicializa una nueva instancia de la estructura `Size` a partir de las dimensiones especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Obtiene una nueva instancia de la estructura `Size` que tiene los valores de [`Width`](./width/) y [`Height`](./height/) establecidos en cero. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Obtiene o establece el componente vertical de este `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Obtiene un valor que indica si este `Size` tiene ancho y alto de 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Obtiene o establece el componente horizontal de este `Size`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Suma el ancho y alto de una estructura `Size` al ancho y alto de otra estructura `Size`. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Convierte la estructura [`SizeF`](../sizef/) especificada a una estructura `Size` redondeando los valores de la estructura `Size` al siguiente entero mayor. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Convierte la estructura [`SizeF`](../sizef/) especificada a una estructura `Size` redondeando los valores de la estructura [`SizeF`](../sizef/) al entero más cercano. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Resta el ancho y alto de una estructura `Size` del ancho y alto de otra estructura `Size`. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Convierte la estructura [`SizeF`](../sizef/) especificada a una estructura `Size` truncando los valores de la estructura [`SizeF`](../sizef/) al siguiente entero inferior. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Comprueba si el objeto especificado es un `Size` con las mismas dimensiones que este `Size`. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Devuelve un código hash para esta estructura `Size`. |
| override [ToString](../../aspose.psd/size/tostring/)() | Crea una cadena legible que representa este `Size`. |
| [operator +](../../aspose.psd/size/op_addition/) | Suma el ancho y alto de una estructura `Size` al ancho y alto de otra estructura `Size`. |
| [operator ==](../../aspose.psd/size/op_equality/) | Comprueba si dos estructuras `Size` son iguales. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Convierte el `Size` especificado a un [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Convierte el `Size` especificado a un [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Comprueba si dos estructuras `Size` son diferentes. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Resta el ancho y alto de una estructura `Size` del ancho y alto de otra estructura `Size`. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


