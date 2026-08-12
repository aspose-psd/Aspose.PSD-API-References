---
title: "Clase Blend"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Blend. Define un patrón de mezcla. Esta clase no puede heredarse"
type: docs
weight: 110
url: /es/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

Define un patrón de mezcla. Esta clase no puede heredarse.

```csharp
public sealed class Blend
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Blend](blend/#constructor)() | Inicializa una nueva instancia de la clase `Blend`. El número de elementos en los arreglos de factor y de mezcla será igual a 1. |
| [Blend](blend/#constructor_1)(int) | Inicializa una nueva instancia de la clase `Blend` con el número especificado de factores y posiciones. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Obtiene o establece el arreglo de factores de mezcla para el degradado. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Obtiene o establece el arreglo de posiciones de mezcla para el degradado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Comprueba si el objeto especificado es una clase `Blend` y es equivalente a esta clase `Blend`. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Devuelve un código hash para esta instancia. |

## Observaciones

El uso típico de la clase blend consiste en definir un patrón de mezcla para el pincel. Por lo tanto, las propiedades de mezcla deben inicializarse cuidadosamente. No se permiten arreglos nulos. El pincel lanzará la excepción correspondiente si los arreglos de factores de mezcla o de posiciones están vacíos o su longitud no es la misma. Si hay dos o más elementos en el arreglo de posiciones, el primer elemento debe ser 0 y el último debe ser 1.

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


