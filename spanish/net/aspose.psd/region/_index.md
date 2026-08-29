---
title: "Clase Region"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Region. Describe el interior de una forma gráfica compuesta por rectángulos y rutas. Esta clase no puede heredarse"
type: docs
weight: 5860
url: /es/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Describe el interior de una forma gráfica compuesta de rectángulos y rutas. Esta clase no puede heredarse.

```csharp
public sealed class Region
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Region](region/#constructor)() | Inicializa una nueva `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Inicializa una nueva `Region` con el [`GraphicsPath`](../graphicspath/) especificado. |
| [Region](region/#constructor_2)(Rectangle) | Inicializa una nueva `Region` a partir de la estructura [`Rectangle`](../rectangle/) especificada. |
| [Region](region/#constructor_3)(RectangleF) | Inicializa una nueva `Region` a partir de la estructura [`RectangleF`](../rectanglef/) especificada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Actualiza este `Region` para que contenga la parte del [`GraphicsPath`](../graphicspath/) especificado que no intersecta con este `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Actualiza este `Region` para que contenga la parte de la estructura [`Rectangle`](../rectangle/) especificada que no intersecta con este `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Actualiza este `Region` para que contenga la parte de la estructura [`RectangleF`](../rectanglef/) especificada que no intersecta con este `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Actualiza este `Region` para que contenga la parte del `Region` especificado que no intersecta con este `Region`. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Crea una copia profunda exacta de este `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Comprueba si los objetos son iguales. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Comprueba si el `Region` especificado es idéntico a este `Region` en la superficie de dibujo especificada. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Actualiza este `Region` para que contenga solo la parte de su interior que no intersecta con el [`GraphicsPath`](../graphicspath/) especificado. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Actualiza este `Region` para que contenga solo la parte de su interior que no intersecta con la estructura [`Rectangle`](../rectangle/) especificada. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Actualiza este `Region` para que contenga solo la parte de su interior que no intersecta con la estructura [`RectangleF`](../rectanglef/) especificada. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Actualiza este `Region` para que contenga solo la parte de su interior que no intersecta con el `Region` especificado. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Obtiene el código hash del objeto actual. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Actualiza este `Region` a la intersección de sí mismo con el [`GraphicsPath`](../graphicspath/) especificado. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Actualiza este `Region` a la intersección de sí mismo con la estructura [`Rectangle`](../rectangle/) especificada. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Actualiza este `Region` a la intersección de sí mismo con la estructura [`RectangleF`](../rectanglef/) especificada. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Actualiza este `Region` a la intersección de sí mismo con el `Region` especificado. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Comprueba si este `Region` tiene un interior vacío en la superficie de dibujo especificada. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Comprueba si este `Region` tiene un interior infinito en la superficie de dibujo especificada. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Comprueba si la estructura [`Point`](../point/) especificada está contenida dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Comprueba si la estructura [`PointF`](../pointf/) especificada está contenida dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Comprueba si alguna parte de la estructura [`Rectangle`](../rectangle/) especificada está contenida dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Comprueba si alguna parte de la estructura [`RectangleF`](../rectanglef/) especificada está contenida dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Comprueba si el punto especificado está contenido dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Comprueba si la estructura [`Point`](../point/) especificada está contenida dentro de este `Region` al dibujarse con el [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Comprueba si la estructura [`PointF`](../pointf/) especificada está contenida dentro de este `Region` al dibujarse con el [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Comprueba si alguna parte de la estructura [`Rectangle`](../rectangle/) especificada está contenida dentro de este `Region` al dibujarse con el [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Comprueba si alguna parte de la estructura [`RectangleF`](../rectanglef/) especificada está contenida dentro de este `Region` cuando se dibuja usando el [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Comprueba si el punto especificado está contenido dentro de este `Region` cuando se dibuja usando el [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Comprueba si el punto especificado está contenido dentro de este objeto `Region` cuando se dibuja usando el objeto [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `Region` cuando se dibuja usando el [`Graphics`](../graphics/) especificado. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `Region` cuando se dibuja usando el [`Graphics`](../graphics/) especificado. |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Inicializa este `Region` con un interior vacío. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Inicializa este objeto `Region` con un interior infinito. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Transforma este `Region` mediante la [`Matrix`](../matrix/) especificada. |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Desplaza las coordenadas de este `Region` en la cantidad especificada. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Desplaza las coordenadas de este `Region` en la cantidad especificada. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Actualiza este `Region` a la unión de sí mismo y el [`GraphicsPath`](../graphicspath/) especificado. |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Actualiza este `Region` a la unión de sí mismo y la estructura [`Rectangle`](../rectangle/) especificada. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Actualiza este `Region` a la unión de sí mismo y la estructura [`RectangleF`](../rectanglef/) especificada. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Actualiza este `Region` a la unión de sí mismo y el `Region` especificado. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Actualiza este `Region` a la unión menos la intersección de sí mismo con el [`GraphicsPath`](../graphicspath/) especificado. |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Actualiza este `Region` a la unión menos la intersección de sí mismo con la estructura [`Rectangle`](../rectangle/) especificada. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Actualiza este `Region` a la unión menos la intersección de sí mismo con la estructura [`RectangleF`](../rectanglef/) especificada. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Actualiza este `Region` a la unión menos la intersección de sí mismo con el `Region` especificado. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


