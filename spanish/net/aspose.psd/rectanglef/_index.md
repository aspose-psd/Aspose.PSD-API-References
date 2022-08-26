---
title: RectangleF
second_title: Referencia de API de Aspose.PSD para .NET
description: Almacena un conjunto de cuatro números de coma flotante que representan la ubicación y el tamaño de un rectángulo.
type: docs
weight: 5280
url: /es/net/aspose.psd/rectanglef/
---
## RectangleF structure

Almacena un conjunto de cuatro números de coma flotante que representan la ubicación y el tamaño de un rectángulo.

```csharp
public struct RectangleF
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Inicializa una nueva instancia del[`RectangleF`](../rectanglef) estructura con la ubicación y tamaño especificados. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Inicializa una nueva instancia del[`RectangleF`](../rectanglef) estructura con la ubicación y tamaño especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty) { get; } | Obtiene una nueva instancia del[`RectangleF`](../rectanglef) estructura que tiene[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) y[`Height`](./height) valores establecidos en cero. |
| [Bottom](../../aspose.psd/rectanglef/bottom) { get; set; } | Obtiene o establece la coordenada y que es la suma de[`Y`](./y) y[`Height`](./height) de esta[`RectangleF`](../rectanglef)estructura. |
| [Height](../../aspose.psd/rectanglef/height) { get; set; } | Obtiene o establece la altura de este[`RectangleF`](../rectanglef)estructura. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty) { get; } | Obtiene un valor que indica si el[`Width`](./width) o[`Height`](./height) propiedad de este[`RectangleF`](../rectanglef) tiene un valor de cero. |
| [Left](../../aspose.psd/rectanglef/left) { get; set; } | Obtiene o establece la coordenada x del borde izquierdo de este[`RectangleF`](../rectanglef)estructura. |
| [Location](../../aspose.psd/rectanglef/location) { get; set; } | Obtiene o establece las coordenadas de la esquina superior izquierda de este[`RectangleF`](../rectanglef)estructura. |
| [Right](../../aspose.psd/rectanglef/right) { get; set; } | Obtiene o establece la coordenada x que es la suma de[`X`](./x) y[`Width`](./width) de esta[`RectangleF`](../rectanglef)estructura. |
| [Size](../../aspose.psd/rectanglef/size) { get; set; } | Obtiene o establece el tamaño de este[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.psd/rectanglef/top) { get; set; } | Obtiene o establece la coordenada y del borde superior de este[`RectangleF`](../rectanglef)estructura. |
| [Width](../../aspose.psd/rectanglef/width) { get; set; } | Obtiene o establece el ancho de este[`RectangleF`](../rectanglef)estructura. |
| [X](../../aspose.psd/rectanglef/x) { get; set; } | Obtiene o establece la coordenada x de la esquina superior izquierda de este[`RectangleF`](../rectanglef)estructura. |
| [Y](../../aspose.psd/rectanglef/y) { get; set; } | Obtiene o establece la coordenada y de la esquina superior izquierda de este[`RectangleF`](../rectanglef)estructura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Crea un[`RectangleF`](../rectanglef) estructura con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints)(PointF, PointF) | Crea un nuevo[`Rectangle`](../rectangle) de dos puntos especificados. Dos vertices de lo creado[`Rectangle`](../rectangle) será igual a lo pasado*point1* y*point2* . Estos serían típicamente los vértices opuestos. |
| static [Inflate](../../aspose.psd/rectanglef/inflate)(RectangleF, float, float) | Crea y devuelve una copia inflada del especificado[`RectangleF`](../rectanglef) estructura. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar. |
| static [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF, RectangleF) | Devuelve un[`RectangleF`](../rectanglef) estructura que representa la intersección de dos rectángulos. Si no hay intersección, y vacío[`RectangleF`](../rectanglef) se devuelve. |
| static [Union](../../aspose.psd/rectanglef/union)(RectangleF, RectangleF) | Crea el tercer rectángulo más pequeño posible que puede contener dos rectángulos que forman una unión. |
| [Contains](../../aspose.psd/rectanglef/contains#contains)(PointF) | Determina si el punto especificado está contenido dentro de este[`RectangleF`](../rectanglef)estructura. |
| [Contains](../../aspose.psd/rectanglef/contains#contains_1)(RectangleF) | Determina si la región rectangular representada por*rect* está completamente contenido dentro de este[`RectangleF`](../rectanglef)estructura. |
| [Contains](../../aspose.psd/rectanglef/contains#contains_2)(float, float) | Determina si el punto especificado está contenido dentro de este[`RectangleF`](../rectanglef)estructura. |
| override [Equals](../../aspose.psd/rectanglef/equals)(object) | Comprueba si*obj* es un[`RectangleF`](../rectanglef) con la misma ubicación y tamaño de este[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode)() | Obtiene el código hash para este[`RectangleF`](../rectanglef)estructura. |
| [Inflate](../../aspose.psd/rectanglef/inflate#inflate)(SizeF) | infla esto[`RectangleF`](../rectanglef) por la cantidad especificada. |
| [Inflate](../../aspose.psd/rectanglef/inflate#inflate_1)(float, float) | infla esto[`RectangleF`](../rectanglef) estructura por la cantidad especificada. |
| [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF) | Reemplaza esto[`RectangleF`](../rectanglef) estructura con la intersección de sí mismo y el especificado[`RectangleF`](../rectanglef)estructura. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith)(RectangleF) | Determina si este rectángulo se cruza con*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize)() | Normaliza el rectángulo haciendo que el ancho y la altura sean positivos, la izquierda menos que la derecha y la parte superior menos que la inferior. |
| [Offset](../../aspose.psd/rectanglef/offset#offset)(PointF) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [Offset](../../aspose.psd/rectanglef/offset#offset_1)(float, float) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| override [ToString](../../aspose.psd/rectanglef/tostring)() | Convierte los atributos de este[`RectangleF`](../rectanglef) a una cadena legible por humanos. |
| [operator /](../../aspose.psd/rectanglef/op_division) | Implementa el operador /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality) | Comprueba si dos[`RectangleF`](../rectanglef) las estructuras tienen la misma ubicación y tamaño. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit) | Convierte el especificado[`Rectangle`](../rectangle) estructura a un[`RectangleF`](../rectanglef)estructura. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality) | Comprueba si dos[`RectangleF`](../rectanglef) las estructuras difieren en ubicación o tamaño. |
| [operator *](../../aspose.psd/rectanglef/op_multiply) | Implementa el operador *. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
