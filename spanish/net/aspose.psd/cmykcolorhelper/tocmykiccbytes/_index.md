---
title: CmykColorHelper.ToCmykIccBytes
second_title: Referencia de API de Aspose.PSD para .NET
description: CmykColorHelper método. Convierte RGB a CMYK utilizando perfiles ICC personalizados.
type: docs
weight: 120
url: /es/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Convierte RGB a CMYK utilizando perfiles ICC personalizados.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pixels | Int32[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | Int32 | El índice de inicio del color RGB. |
| length | Int32 | El número de píxeles RGB para convertir. |
| rgbIccStream | Stream | El flujo de perfil RGB. |
| cmykIccStream | Stream | El flujo de perfil CMYK. |

### Valor_devuelto

Los colores CMYK presentados como una matriz de bytes.

### Ver también

* class [CmykColorHelper](../)
* espacio de nombres [Aspose.PSD](../../cmykcolorhelper/)
* asamblea [Aspose.PSD](../../../)


