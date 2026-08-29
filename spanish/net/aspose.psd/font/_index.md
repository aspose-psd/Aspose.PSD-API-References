---
title: "Clase Font"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Font. Define un formato particular para el texto que incluye el tamaño y los atributos de estilo de la fuente. Esta clase no puede heredarse"
type: docs
weight: 4750
url: /es/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Define un formato particular para texto, incluyendo la tipografía, el tamaño y los atributos de estilo. Esta clase no puede heredarse.

```csharp
public sealed class Font
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Inicializa un nuevo `Font` que usa el `Font` existente especificado y la enumeración [`FontStyle`](../fontstyle/). |
| [Font](font/#constructor_1)(string, float) | Inicializa un nuevo `Font` usando un tamaño especificado. El conjunto de caracteres se establece en Default, la unidad gráfica en Point, y el estilo de fuente en Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Inicializa un nuevo `Font` usando un tamaño y estilo especificados. El conjunto de caracteres se establece en Default, la unidad gráfica en Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Inicializa un nuevo `Font` usando un tamaño y unidad especificados. El conjunto de caracteres se establece en Default, el estilo se establece en Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Inicializa un nuevo `Font` usando un tamaño, estilo y unidad especificados. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Inicializa un nuevo `Font` usando un tamaño, estilo, unidad y conjunto de caracteres especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Obtiene un valor que indica si este `Font` está en negrita. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Obtiene un valor de byte que especifica el conjunto de caracteres que usa este `Font`. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Obtiene un valor que indica si este `Font` está en cursiva. |
| [Name](../../aspose.psd/font/name/) { get; } | Obtiene el nombre de la tipografía de este `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | Obtiene el tamaño em de este `Font` medido en las unidades especificadas por la propiedad [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Obtiene un valor que indica si este `Font` especifica una línea horizontal a través de la fuente. |
| [Style](../../aspose.psd/font/style/) { get; } | Obtiene información de estilo para este `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Obtiene un valor que indica si este `Font` está subrayado. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Obtiene la unidad de medida de este `Font`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Crea una copia profunda exacta de este `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indica si el objeto especificado es un `Font` y tiene los mismos valores de propiedades que este `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Obtiene el código hash de este `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | Devuelve una representación de cadena legible por humanos de este `Font`. |

## Ejemplos

Este ejemplo demuestra el uso de la clase Font y SolidBrush para dibujar cadenas en la superficie de Image. El ejemplo crea una nueva Image y dibuja formas usando Figures y GraphicsPath

```csharp
[C#]

//Crea una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie de Graphics
    graphics.Clear(Color.Wheat);

    //Crea una instancia de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crea una instancia de SolidBrush con color rojo
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Dibuja una cadena
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crea opciones de exportación.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // guarde todos los cambios
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


