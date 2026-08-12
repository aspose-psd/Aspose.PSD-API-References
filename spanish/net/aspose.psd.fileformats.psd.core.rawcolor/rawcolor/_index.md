---
title: "Clase RawColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor. La clase Raw Color ayuda a almacenar colores con cualquier número de canales, cualquier modo de color y cualquier profundidad de bits. Tenga en cuenta que algunas clases internas pueden tener problemas al convertir RawColor a su formato nativo, por lo que si la API le proporciona un color CMYK es más fiable usar el formato proporcionado. Además, pueden existir algunos casos en los que Raw Color pueda ser convertido."
type: docs
weight: 1650
url: /es/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class ayuda a almacenar colores con cualquier número de canales, cualquier modo de color y cualquier profundidad de bits. Tenga en cuenta que algunas clases internas pueden tener problemas al convertir RawColor a su formato nativo, por lo que si la API le proporciona un color CMYK, es más fiable usar el formato proporcionado. Además, pueden existir algunos casos en los que Raw Color pueda ser convertido.

```csharp
public sealed class RawColor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Inicializa una nueva instancia de la clase `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Inicializa una nueva instancia de la clase `RawColor` a partir del formato de datos de píxel usando modos de color predefinidos |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Modo que seguirá el color. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Obtiene los componentes del color. Cada componente es un canal separado, y si utilizas un esquema de color no popular, es mejor trabajar con cada canal por separado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Determina si el Object especificado es igual a esta instancia. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Obtiene el color como entero en caso de que sea posible obtenerlo. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Obtiene el color como largo en caso de que sea posible obtenerlo. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Obtiene la profundidad de bits del Color Crudo. Por ejemplo, para un color ARGB con 8 bits por canal/componente es 32; la profundidad de bits de un color ARGB completo con 16 bits por canal/componente es 64. La profundidad de bits se acumula a partir de la suma de las profundidades de bits de los canales. Es posible si diferentes canales tienen diferentes profundidades de bits. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Obtiene el nombre del modo de color. El nombre del modo de color se acumula a partir de los nombres de los canales/componentes. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Obtiene el código hash del objeto actual. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Establece los datos a todos los canales a partir del argumento entero si es posible. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Establece los datos a todos los canales a partir del argumento entero si es posible. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Implementa el operador ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Implementa el operador !=. |

## Ejemplos

El siguiente código demuestra el soporte de la clase RawColor en lugar de la estructura Color obsoleta.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


