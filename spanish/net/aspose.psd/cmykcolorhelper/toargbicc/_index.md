---
title: "CmykColorHelper.ToArgbIcc"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método CmykColorHelper. La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados"
type: docs
weight: 80
url: /es/net/aspose.psd/cmykcolorhelper/toargbicc/
---
{{< psd/tize >}}
## ToArgbIcc(int[]) {#toargbicc_2}

La conversión de colores CMYK a colores ARGB usando conversión ICC con perfiles predeterminados.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | Int32[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Valor devuelto

Los colores ARGB.

### Ver también

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

La conversión de colores CMYK a colores ARGB usando conversión ICC con perfiles personalizados.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | Int32[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmykIccStream | Flujo | El flujo que contiene el perfil Icc CMYK. |
| rgbIccStream | Flujo | El flujo que contiene el perfil Icc RGB. |

### Valor devuelto

Los colores ARGB.

### Ver también

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int) {#toargbicc}

La conversión de color CMYK a color ARGB usando conversión ICC con perfiles predeterminados.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | Int32 | El color CMYK presentado como un valor entero de 32 bits. |

### Valor devuelto

El color ARGB.

### Ver también

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

La conversión de color CMYK a color ARGB usando conversión ICC con perfil personalizado.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | Int32 | El color CMYK presentado como un valor entero de 32 bits. |
| cmykIccStream | Flujo | El flujo que contiene el perfil Icc CMYK. |
| rgbIccStream | Flujo | El flujo que contiene el perfil Icc RGB. |

### Valor devuelto

El color ARGB.

### Ver también

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


