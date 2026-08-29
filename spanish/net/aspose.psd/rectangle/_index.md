---
title: "Estructura Rectangle"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.Rectangle. Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo"
type: docs
weight: 5840
url: /es/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.

```csharp
public struct Rectangle
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Inicializa una nueva instancia de la estructura `Rectangle` con la ubicación y el tamaño especificados. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Inicializa una nueva instancia de la estructura `Rectangle` con la ubicación y el tamaño especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Obtiene una nueva instancia de la estructura `Rectangle` que tiene los valores [`X`](./x/), [`Y`](./y/), [`Width`](./width/) y [`Height`](./height/) establecidos en cero. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades [`Y`](./y/) y [`Height`](./height/) de esta estructura `Rectangle`. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Obtiene o establece la altura de esta estructura `Rectangle`. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Obtiene un valor que indica si todas las propiedades numéricas de este `Rectangle` tienen valores cero. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Obtiene o establece la coordenada x del borde izquierdo de esta estructura `Rectangle`. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `Rectangle`. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades [`X`](./x/) y [`Width`](./width/) de esta estructura `Rectangle`. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Obtiene o establece el tamaño de este `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Obtiene o establece la coordenada y del borde superior de esta estructura `Rectangle`. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Obtiene o establece el ancho de esta estructura `Rectangle`. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `Rectangle`. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `Rectangle`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Convierte la estructura [`RectangleF`](../rectanglef/) especificada a una estructura `Rectangle` redondeando los valores de [`RectangleF`](../rectanglef/) al siguiente entero superior. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Crea una estructura `Rectangle` con las ubicaciones de borde especificadas. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Crea un nuevo `Rectangle` a partir de dos puntos especificados. Las dos verticales del `Rectangle` creado serán iguales a los puntos *point1* y *point2* proporcionados. Estos suelen ser los vértices opuestos. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Crea y devuelve una copia inflada de la estructura `Rectangle` especificada. La copia se infla en la cantidad especificada. La estructura `Rectangle` original permanece sin modificar. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Devuelve una tercera estructura `Rectangle` que representa la intersección de dos estructuras `Rectangle` distintas. Si no hay intersección, se devuelve un `Rectangle` vacío. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Convierte el [`RectangleF`](../rectanglef/) especificado a un `Rectangle` redondeando los valores de [`RectangleF`](../rectanglef/) al entero más cercano. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Convierte el [`RectangleF`](../rectanglef/) especificado a un `Rectangle` truncando los valores de [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Obtiene una estructura `Rectangle` que contiene la unión de dos estructuras `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Determina si el punto especificado está contenido dentro de esta estructura `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Determina si la región rectangular representada por *rect* está completamente contenida dentro de esta estructura `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Determina si el punto especificado está contenido dentro de esta estructura `Rectangle`. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Comprueba si *obj* es una estructura `Rectangle` con la misma ubicación y tamaño que esta estructura `Rectangle`. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Devuelve el código hash de esta estructura `Rectangle`. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Infla este `Rectangle` en la cantidad especificada. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Infla este `Rectangle` en la cantidad especificada. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Reemplaza este `Rectangle` con la intersección de sí mismo y el `Rectangle` especificado. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Determina si este rectángulo intersecta con *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normaliza el rectángulo haciendo que su ancho y alto sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Convierte los atributos de este `Rectangle` a una cadena legible por humanos. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Comprueba si dos estructuras `Rectangle` tienen la misma ubicación y tamaño. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Comprueba si dos estructuras `Rectangle` difieren en ubicación o tamaño. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


