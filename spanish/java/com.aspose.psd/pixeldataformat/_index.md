---
title: "PixelDataFormat"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El formato de datos de píxel."
type: docs
weight: 80
url: /es/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

El formato de datos de píxel. Este es un objeto inmutable.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el System.Object especificado es igual a esta instancia. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Obtiene el color BGR con un número especificado de bits por muestra. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Obtiene el color BGRA con un número especificado de bits por muestra. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene los bits por píxel. |
| [getCaption()](#getCaption--) | Obtiene la leyenda del formato de datos de píxel. |
| [getChannelBits()](#getChannelBits--) | Obtiene el recuento de bits para cada canal. |
| [getChannelsCount()](#getChannelsCount--) | Obtiene el recuento de canales. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Obtiene el color CIE Lab con un número especificado de bits por muestra. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Obtiene el PixelDataFormat definido para 32 bits por píxel con 8 bits para cada uno de los cian, magenta, amarillo y negro. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Obtiene el color CMYK con un número especificado de bits por muestra. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Obtiene el color CMYK con un número especificado de bits por muestra. |
| [getCmyk16()](#getCmyk16--) | Obtiene el [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 64 bits por píxel con 16 bits para cada uno de los cian, magenta, amarillo y negro. |
| [getCmyka()](#getCmyka--) | Obtiene el acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Obtiene el color CMYKA con un número especificado de bits por muestra. |
| [getCmyka16()](#getCmyka16--) | Obtiene el acmyk. |
| [getGrayscale()](#getGrayscale--) | Obtiene el PixelDataFormat definido para 8 bits por píxel con 8 bits que representan la intensidad de escala de grises en el intervalo 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Obtiene el color en escala de grises con un número especificado de bits por muestra. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Obtiene el PixelDataFormat definido para 16 bits por píxel con 8 bits que representan la intensidad de escala de grises en el intervalo 0-255 y un componente alfa adicional de 8 bits. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Obtiene el [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 32 bits por píxel que representa la intensidad de escala de grises en formato de punto flotante. |
| [getPixelFormat()](#getPixelFormat--) | Obtiene el formato de píxel. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Obtiene el color RGB con un número especificado de bits por muestra. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Obtiene el color RGB con un número especificado de bits por muestra. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Obtiene el PixelDataFormat definido para 16 bits por píxel con 5 bits para cada uno de los rojo, verde y azul, el alfa no está definido. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Obtiene el PixelDataFormat definido para 16 bits por píxel con 5 bits para el rojo, 6 bits para el verde y 5 bits para el azul, el alfa no está definido. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Obtiene el PixelDataFormat definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, el alfa no está definido. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Obtiene el PixelDataFormat definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, el alfa no está definido. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Obtiene el PixelDataFormat definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Obtiene color indexado BGRA con un número especificado de bits por muestra. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Obtiene el  PixelDataFormat  definido para 1 bit indexado por color. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Obtiene el  PixelDataFormat  definido para 2 bits indexados por color. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Obtiene el  PixelDataFormat  definido para 4 bits indexados por color. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Obtiene el  PixelDataFormat  definido para 8 bits indexados por color. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Obtiene color RGBA con un número especificado de bits por muestra. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Obtiene color RGBA con un número especificado de bits por muestra. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Obtiene el PixelDataFormat definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Obtiene el [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul. |
| [getYCbCr()](#getYCbCr--) | Obtiene el  PixelDataFormat  definido para 24 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul y diferencia de rojo. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Obtiene color YCbCr con un número especificado de bits por muestra. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Obtiene color YCbCr con un número especificado de bits por muestra. |
| [getYcck()](#getYcck--) | Obtiene el  PixelDataFormat  definido para 32 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul, diferencia de rojo y negro. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Obtiene color YCCK con un número especificado de bits por muestra. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Obtiene un valor que indica si esta instancia está indexada. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Devuelve el resultado de igualdad para dos  PixelDataFormat  clases. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Devuelve el resultado de desigualdad para dos  PixelDataFormat  clases. |
| [toString()](#toString--) | Devuelve un  System.String  que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el System.Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  para comparar con esta instancia. |

**Returns:**
boolean - true si el System.Object especificado es igual a esta instancia; de lo contrario, false.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Obtiene el color BGR con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Obtiene el color BGRA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene los bits por píxel.

**Returns:**
int - Los bits por píxel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Obtiene la leyenda del formato de datos de píxel.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Obtiene el recuento de bits para cada canal.

**Returns:**
int[] - Los bits del canal.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Obtiene el recuento de canales.

**Returns:**
int - El recuento de canales.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Obtiene el color CIE Lab con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerL | int | El número de bits por canal L. |
| bitsPerA | int | El número de bits por canal A. |
| bitsPerB | int | El número de bits por canal B. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Obtiene el PixelDataFormat definido para 32 bits por píxel con 8 bits para cada uno de los cian, magenta, amarillo y negro.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Obtiene el color CMYK con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Obtiene el color CMYK con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerCyanChannel | int | El número de bits por canal Cyan. |
| bitsPerMagentaChannel | int | El número de bits por canal Magenta. |
| bitsPerYellowChannel | int | El número de bits por canal Yellow. |
| bitsPerKeyChannel | int | El número de bits por canal Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Obtiene el [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 64 bits por píxel con 16 bits para cada uno de los cian, magenta, amarillo y negro.

Valor: El [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 64 bits por píxel con 16 bits para cada uno de los cian, magenta, amarillo y negro.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Obtiene el acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Obtiene el color CMYKA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerCyanChannel | int | El número de bits por canal Cyan. |
| bitsPerMagentaChannel | int | El número de bits por canal Magenta. |
| bitsPerYellowChannel | int | El número de bits por canal Yellow. |
| bitsPerKeyChannel | int | El número de bits por canal Key. |
| bitsPerAlphaChannel | int | El número de bits por canal Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Obtiene el acmyk.

Valor: El [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 80 bits por píxel con 16 bits para cada uno de los alpha, cian, magenta, amarillo y negro.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Obtiene el PixelDataFormat definido para 8 bits por píxel con 8 bits que representan la intensidad de escala de grises en el intervalo 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Obtiene el color en escala de grises con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Obtiene el PixelDataFormat definido para 16 bits por píxel con 8 bits que representan la intensidad de escala de grises en el intervalo 0-255 y un componente alfa adicional de 8 bits.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |
| alphaChannelBits | int | El número de bits por muestra en el canal alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Obtiene el [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 32 bits por píxel que representa la intensidad de escala de grises en formato de punto flotante.

Valor: El [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 32 bits por píxel que representa la intensidad de escala de grises en formato de punto flotante

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtiene el formato de píxel.

**Returns:**
int - El formato de píxel.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Obtiene el color RGB con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Obtiene el color RGB con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerRedChannel | int | El número de bits por canal Red. |
| bitsPerGreenChannel | int | El número de bits por canal Green. |
| bitsPerBlueChannel | int | El número de bits por canal Blue. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Obtiene el PixelDataFormat definido para 16 bits por píxel con 5 bits para cada uno de los rojo, verde y azul, el alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Obtiene el PixelDataFormat definido para 16 bits por píxel con 5 bits para el rojo, 6 bits para el verde y 5 bits para el azul, el alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Obtiene el PixelDataFormat definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, el alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Obtiene el PixelDataFormat definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, el alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Obtiene el PixelDataFormat definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Obtiene color indexado BGRA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Obtiene el  PixelDataFormat  definido para indexado 1 bit por color. El almacenamiento de datos de píxeles indexado está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Obtiene el  PixelDataFormat  definido para indexado 2 bits por color. El almacenamiento de datos de píxeles indexado está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Obtiene el  PixelDataFormat  definido para indexado 4 bits por color. El almacenamiento de datos de píxeles indexado está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Obtiene el  PixelDataFormat  definido para índices de 8 bits por color. El almacenamiento de datos de píxeles indexados está destinado a permitir el almacenamiento y la recuperación de datos donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Obtiene color RGBA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Obtiene color RGBA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerRedChannel | int | El número de bits por canal Red. |
| bitsPerGreenChannel | int | El número de bits por canal Green. |
| bitsPerBlueChannel | int | El número de bits por canal Blue. |
| bitsPerAlphaChannel | int | El número de bits por canal Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Obtiene el PixelDataFormat definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Obtiene el [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul.

Valor: El [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Obtiene el  PixelDataFormat  definido para 24 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul y diferencia de rojo.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Obtiene color YCbCr con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Obtiene color YCbCr con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerY | int | El número de bits por canal Y. |
| bitsPerCb | int | El número de bits por canal Cb. |
| bitsPerCr | int | El número de bits por canal Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Obtiene el  PixelDataFormat  definido para 32 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul, diferencia de rojo y negro.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Obtiene color YCCK con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Obtiene un valor que indica si esta instancia está indexada.

Valor:  true  si esta instancia está indexada; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si esta instancia está indexada.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Devuelve el resultado de igualdad para dos  PixelDataFormat  clases.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El primer  PixelDataFormat  a comparar. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El segundo  PixelDataFormat  a comparar. |

**Returns:**
boolean - True si tanto  pixelFormat1  como  pixelFormat2  contienen datos iguales o ambos parámetros son nulos.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Devuelve el resultado de desigualdad para dos  PixelDataFormat  clases.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El primer  PixelDataFormat  a comparar. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El segundo  PixelDataFormat  a comparar. |

**Returns:**
boolean - True si tanto  pixelFormat1  como  pixelFormat2  contienen datos no iguales o uno de los parámetros es nulo.
### toString() {#toString--}
```
public String toString()
```


Devuelve un  System.String  que representa esta instancia.

**Returns:**
java.lang.String - Un  System.String  que representa esta instancia.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

