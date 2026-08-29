---
title: "Estructura CmykColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Estructura Aspose.PSD.CmykColor. El color CMYK del píxel"
type: docs
weight: 270
url: /es/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

El color CMYK del píxel.

```csharp
public struct CmykColor
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Obtiene el vacío. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Obtiene el valor del componente cian de esta estructura [`Color`](../color/). |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Obtiene un valor que indica si esta estructura [`Color`](../color/) no está inicializada. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Obtiene el valor del componente negro de esta estructura [`Color`](../color/). |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Obtiene el valor del componente magenta de esta estructura [`Color`](../color/). |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Obtiene el valor del componente amarillo de esta estructura [`Color`](../color/). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Crea una estructura `CmykColor` a partir de valores de cian, magenta, amarillo y negro de 32 bits. Este método está obsoleto. Por favor, use el más eficaz [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | La conversión de ARGB de 32 bits a CMYKColor. Este método está obsoleto. Por favor, use el más eficaz [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Determina si el Object especificado es igual a esta instancia. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Obtiene el código hash. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Obtiene el valor. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use el más eficaz [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | La conversión de color ARGB de 32 bits a CMYKColor. Este método está obsoleto. Por favor, use el más eficaz [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | La conversión de CMYKColor a Color. Este método está obsoleto. Por favor, use el más eficaz [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use el más eficaz [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use el más eficaz [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use el más eficaz [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | La conversión de CMYKColor a Color usando conversión icc. Este método está obsoleto. Por favor, use el más eficaz [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | La conversión de CMYKColor a Color usando conversión icc. Este método está obsoleto. Por favor, use el más eficaz [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


