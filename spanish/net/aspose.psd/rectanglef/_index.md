---
title: "Estructura RectangleF"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.RectangleF. Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo."
type: docs
weight: 5850
url: /es/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo.

```csharp
public struct RectangleF
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Inicializa una nueva instancia de la estructura `RectangleF` con la ubicación y el tamaño especificados. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Inicializa una nueva instancia de la estructura `RectangleF` con la ubicación y el tamaño especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Obtiene una nueva instancia de la estructura `RectangleF` que tiene los valores [`X`](./x/), [`Y`](./y/), [`Width`](./width/) y [`Height`](./height/) establecidos en cero. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Obtiene o establece la coordenada y que es la suma de [`Y`](./y/) y [`Height`](./height/) de esta estructura `RectangleF`. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Obtiene o establece la altura de esta estructura `RectangleF`. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Obtiene un valor que indica si la propiedad [`Width`](./width/) o [`Height`](./height/) de este `RectangleF` tiene un valor de cero. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Obtiene o establece la coordenada x del borde izquierdo de esta estructura `RectangleF`. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `RectangleF`. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Obtiene o establece la coordenada x que es la suma de [`X`](./x/) y [`Width`](./width/) de esta estructura `RectangleF`. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Obtiene o establece el tamaño de este `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Obtiene o establece la coordenada y del borde superior de esta estructura `RectangleF`. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Obtiene o establece el ancho de esta estructura `RectangleF`. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `RectangleF`. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `RectangleF`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Crea una estructura `RectangleF` con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Crea un nuevo [`Rectangle`](../rectangle/) a partir de dos puntos especificados. Dos vértices del [`Rectangle`](../rectangle/) creado serán iguales a los *point1* y *point2* pasados. Estos serían típicamente los vértices opuestos. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Crea y devuelve una copia inflada de la estructura `RectangleF` especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Devuelve una estructura `RectangleF` que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un `RectangleF` vacío. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Determina si el punto especificado está contenido dentro de esta estructura `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Determina si la región rectangular representada por *rect* está completamente contenida dentro de esta estructura `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Determina si el punto especificado está contenido dentro de esta estructura `RectangleF`. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Prueba si *obj* es un `RectangleF` con la misma ubicación y tamaño que este `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Obtiene el código hash de esta estructura `RectangleF`. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Infla este `RectangleF` en la cantidad especificada. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Infla la estructura `RectangleF` en la cantidad especificada. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Reemplaza esta estructura `RectangleF` con la intersección de ella misma y la estructura `RectangleF` especificada. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Determina si este rectángulo intersecta con *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normaliza el rectángulo haciendo que su ancho y alto sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Convierte los atributos de este `RectangleF` a una cadena legible. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementa el operador /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Comprueba si dos estructuras `RectangleF` tienen la misma ubicación y tamaño. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Convierte la estructura [`Rectangle`](../rectangle/) especificada a una estructura `RectangleF`. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Comprueba si dos estructuras `RectangleF` difieren en ubicación o tamaño. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementa el operador *. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


