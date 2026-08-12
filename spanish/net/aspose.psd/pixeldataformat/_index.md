---
title: "Clase PixelDataFormat"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.PixelDataFormat. El formato de datos de píxel. Este es un objeto inmutable."
type: docs
weight: 5720
url: /es/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

El formato de datos de píxel. Este es un objeto inmutable.

```csharp
public class PixelDataFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de cian, magenta, amarillo y negro. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | Obtiene el acmyk. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | Obtiene el `PixelDataFormat` definido para 8 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255 y un componente alfa adicional de 8 bits. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 5 bits para cada uno de rojo, verde y azul, el alfa no está definido. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 5 bits para rojo, 6 bits para verde y 5 bits para azul, el alfa no está definido. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, el alfa no está definido. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, el alfa no está definido. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de los canales alfa, rojo, verde y azul. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de los canales alfa, rojo, verde y azul. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | Obtiene el `PixelDataFormat` definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Obtiene el `PixelDataFormat` definido para indexado de 1 bit por color. El almacenamiento de datos de píxeles indexados está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado. |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Obtiene el `PixelDataFormat` definido para indexado de 2 bits por color. El almacenamiento de datos de píxeles indexados está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado. |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Obtiene el `PixelDataFormat` definido para indexado de 4 bits por color. El almacenamiento de datos de píxeles indexados está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado. |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Obtiene el `PixelDataFormat` definido para indexado de 8 bits por color. El almacenamiento de datos de píxeles indexados está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado. |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de los componentes de luma, diferencia de azul y diferencia de rojo. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de los componentes de luma, diferencia de azul, diferencia de rojo y negro. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Obtiene los bits por píxel. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Obtiene la leyenda del formato de datos de píxel. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Obtiene el recuento de bits para cada canal. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Obtiene el recuento de canales. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Obtiene el formato de píxel. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Obtiene el color BGR con un número especificado de bits por muestra. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Obtiene el color BGRA con un número especificado de bits por muestra. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Obtiene el color CIE Lab con un número especificado de bits por muestra. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Obtiene el color CMYK con un número especificado de bits por muestra. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Obtiene el color CMYK con un número especificado de bits por muestra. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Obtiene el color CMYKA con un número especificado de bits por muestra. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Obtiene el color en escala de grises con un número especificado de bits por muestra. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Obtiene el color RGB con un número especificado de bits por muestra. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Obtiene el color RGB con un número especificado de bits por muestra. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Obtiene el color RGBA con un número especificado de bits por muestra. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Obtiene el color RGBA con un número especificado de bits por muestra. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Obtiene el color indexado BGRA con un número especificado de bits por muestra. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Obtiene el color YCbCr con un número especificado de bits por muestra. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Obtiene el color YCbCr con un número especificado de bits por muestra. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Obtiene el color YCCK con un número especificado de bits por muestra. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Determina si el objeto especificado es igual a esta instancia. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Devuelve un código hash para esta instancia. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | Devuelve una String que representa esta instancia. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | Devuelve el resultado de igualdad para dos clases `PixelDataFormat`. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | Devuelve el resultado de la desigualdad para dos clases `PixelDataFormat`. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


