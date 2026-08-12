---
title: "Enumeración StringFormatFlags"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.StringFormatFlags. Especifica la información de visualización y diseño para cadenas de texto"
type: docs
weight: 6180
url: /es/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

Especifica la información de visualización y diseño para cadenas de texto.

```csharp
[Flags]
public enum StringFormatFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| DirectionRightToLeft | `1` | El texto se muestra de derecha a izquierda. |
| DirectionVertical | `2` | El texto está alineado verticalmente. |
| FitBlackBox | `4` | Se permite que partes de los caracteres sobresalgan del rectángulo de diseño de la cadena. Por defecto, los caracteres se reposicionan para evitar cualquier sobresaliente. |
| DisplayFormatControl | `20` | Los caracteres de control, como la marca de izquierda a derecha, se muestran en la salida con un glifo representativo. |
| NoFontFallback | `400` | La sustitución a fuentes alternativas para caracteres no compatibles con la fuente solicitada está deshabilitada. Cualquier carácter faltante se muestra con el glifo de falta de la fuente, usualmente un cuadrado abierto. |
| MeasureTrailingSpaces | `800` | Incluye el espacio final al final de cada línea. Por defecto, el rectángulo de límite devuelto por el método MeasureString excluye el espacio al final de cada línea. Establezca esta bandera para incluir ese espacio en la medición. |
| NoWrap | `1000` | El ajuste de texto entre líneas al formatear dentro de un rectángulo está deshabilitado. Esta bandera se implica cuando se pasa un punto en lugar de un rectángulo, o cuando el rectángulo especificado tiene una longitud de línea cero. |
| LineLimit | `2000` | Solo se disponen líneas completas en el rectángulo de formato. Por defecto, el diseño continúa hasta el final del texto, o hasta que no haya más líneas visibles como resultado del recorte, lo que ocurra primero. Tenga en cuenta que la configuración predeterminada permite que la última línea quede parcialmente oculta por un rectángulo de formato que no es un múltiplo entero de la altura de línea. Para asegurar que solo se vean líneas completas, especifique este valor y tenga cuidado de proporcionar un rectángulo de formato al menos tan alto como la altura de una línea. |
| NoClip | `4000` | Se permite que las partes sobresalientes de los glifos y el texto sin envolver que se extienden fuera del rectángulo de formato se muestren. Por defecto, todo el texto y las partes de los glifos que se extienden fuera del rectángulo de formato se recortan. |
| ExactAlignment | `8000` | La alineación exacta, el relleno correcto GDI+ |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


