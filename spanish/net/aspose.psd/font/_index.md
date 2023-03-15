---
title: Class Font
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Font clase. Define un formato particular para el texto incluidos los atributos de fuente tamaño y estilo. Esta clase no se puede heredar.
type: docs
weight: 4280
url: /es/net/aspose.psd/font/
---
## Font class

Define un formato particular para el texto, incluidos los atributos de fuente, tamaño y estilo. Esta clase no se puede heredar.

```csharp
public sealed class Font
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Inicializa un nuevo`Font` que utiliza el especificado existente`Font` y[`FontStyle`](../fontstyle/) enumeración. |
| [Font](font/#constructor_1)(string, float) | Inicializa un nuevo`Font` usando un tamaño específico. El conjunto de caracteres se establece enDefault , la unidad gráfica paraPoint , el estilo de fuente paraRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Inicializa un nuevo`Font` usando un tamaño y estilo especificado. El conjunto de caracteres se establece enDefault , la unidad gráfica paraPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Inicializa un nuevo`Font` utilizando un tamaño y una unidad específicos. El conjunto de caracteres se establece enDefault el estilo se establece enRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Inicializa un nuevo`Font` utilizando un tamaño, estilo y unidad especificados. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Inicializa un nuevo`Font` utilizando un tamaño, estilo, unidad y conjunto de caracteres especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Obtiene un valor que indica si este`Font` está en negrita. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Obtiene un valor de byte que especifica el conjunto de caracteres que`Font` usa. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Obtiene un valor que indica si este`Font`es cursiva. |
| [Name](../../aspose.psd/font/name/) { get; } | Obtiene el nombre de la cara de este`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Obtiene el tamaño em de este`Font` medido en las unidades especificadas por el[`Unit`](./unit/) propiedad. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Obtiene un valor que indica si este`Font` especifica una línea horizontal a través de la fuente. |
| [Style](../../aspose.psd/font/style/) { get; } | Obtiene información de estilo para este`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Obtiene un valor que indica si este`Font` está subrayado. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Obtiene la unidad de medida para este`Font` . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Crea una copia profunda exacta de este`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indica si el objeto especificado es un`Font` y tiene los mismos valores de propiedad que este`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Obtiene el código hash para este`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Devuelve una representación de cadena legible por humanos de este`Font` . |

### Ejemplos

Este ejemplo demuestra el uso de la clase Font y SolidBrush para dibujar cadenas en la superficie de la imagen. El ejemplo crea una nueva imagen y dibuja formas usando Figuras y GraphicsPath

```csharp
[C#]

//Crea una instancia de Imagen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Limpia la superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crea una instancia de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crear una instancia de SolidBrush con color rojo
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Dibujar una cadena
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crear opciones de exportación.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // guarda todos los cambios
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


