---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método CmykColorHelper. Convierte RGB a CMYK usando perfiles ICC personalizados"
type: docs
weight: 120
url: /es/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Convierte RGB a CMYK usando perfiles ICC personalizados.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | Int32[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | Int32 | El índice de inicio del color RGB. |
| longitud | Int32 | El número de píxeles RGB a convertir. |
| rgbIccStream | Flujo | El flujo del perfil RGB. |
| cmykIccStream | Flujo | El flujo del perfil CMYK. |

### Valor devuelto

Los colores CMYK presentados como una matriz de bytes.

### Ver también

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


