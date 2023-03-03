---
title: Class CmykColorHelper
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.CmykColorHelper clase. Métodos auxiliares para trabajar con color CMYK presentado como un valor entero de 32 bits con signo. Proporciona una API similar a laCmykColorstruct. Es más liviano porque el color CMYK se presenta como Int32 en lugar de una estructura con campos internos. Prefiere usar métodos estáticos de esta clase cuando sea posible en lugar del obsoleto CmykColor estructura.
type: docs
weight: 280
url: /es/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

Métodos auxiliares para trabajar con color CMYK presentado como un valor entero de 32 bits con signo. Proporciona una API similar a la[`CmykColor`](../cmykcolor/)struct. Es más liviano porque el color CMYK se presenta como Int32 en lugar de una estructura con campos internos. Prefiere usar métodos estáticos de esta clase cuando sea posible en lugar del obsoleto [`CmykColor`](../cmykcolor/) estructura.

```csharp
public static class CmykColorHelper
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Obtiene el valor del componente cian. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Obtiene el valor del componente negro. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Obtiene el valor del componente magenta. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Obtiene el valor del componente amarillo. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | La conversión de color CMYK a color ARGB. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | La conversión de colores CMYK a colores ARGB. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | La conversión de colores CMYK a colores ARGB. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | La conversión de color CMYK a color ARGB utilizando la conversión Icc con perfiles predeterminados. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | La conversión de colores CMYK a colores ARGB utilizando la conversión Icc con perfiles predeterminados. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | La conversión de color CMYK a color ARGB utilizando la conversión Icc con perfil personalizado. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | La conversión de colores CMYK a colores ARGB utilizando la conversión Icc con perfiles personalizados. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | La conversión de color ARGB a color CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | La conversión de colores ARGB a colores CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | La conversión de color ARGB a color CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | La conversión de colores ARGB a colores CMYK. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Convierte RGB a CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | La conversión de color ARGB a color CMYK utilizando la conversión Icc con perfiles predeterminados. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | La conversión de colores ARGB a colores CMYK utilizando la conversión Icc con perfiles predeterminados. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | La conversión de color ARGB a color CMYK utilizando la conversión Icc con perfiles personalizados. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | La conversión de colores ARGB a colores CMYK utilizando la conversión Icc con perfiles personalizados. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Convierte RGB a CMYK utilizando perfiles ICC personalizados. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


