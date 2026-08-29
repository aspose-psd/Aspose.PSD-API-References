---
title: "Clase CustomLineCap"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.CustomLineCap. Encapsula una tapa de línea personalizada definida por el usuario"
type: docs
weight: 710
url: /es/net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

Encapsula una tapa de línea personalizada definida por el usuario.

```csharp
public class CustomLineCap
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | Inicializa una nueva instancia de la clase `CustomLineCap` con el contorno y el relleno especificados. |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | Inicializa una nueva instancia de la clase `CustomLineCap` a partir de la enumeración [`LineCap`](../linecap/) existente especificada, con el contorno y el relleno especificados. |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | Inicializa una nueva instancia de la clase `CustomLineCap` a partir de la enumeración [`LineCap`](../linecap/) existente especificada, con el contorno, el relleno y el inserto especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | Obtiene o establece la enumeración [`LineCap`](../linecap/) en la que se basa este `CustomLineCap`. |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | Obtiene o establece la distancia entre la tapa y la línea. |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | Obtiene o establece el objeto que define el relleno para la tapa personalizada. |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | Obtiene o establece la enumeración [`LineJoin`](../linejoin/) que determina cómo se unen las líneas que componen este objeto `CustomLineCap`. |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | Obtiene o establece el objeto que define el contorno de la tapa personalizada. |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | Obtiene o establece la cantidad por la que escalar este objeto de clase `CustomLineCap` con respecto al ancho del objeto Pen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


