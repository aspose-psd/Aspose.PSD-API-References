---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método TiffStreamReader. Lee una matriz de valores enteros con signo del flujo."
type: docs
weight: 140
url: /es/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Lee una matriz de valores enteros con signo del flujo.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | Int64 | La posición desde la cual leer. |
| count | Int64 | El recuento de elementos. |

### Valor devuelto

La matriz de valores enteros con signo.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | count;El recuento total de bytes es negativo. + count + x4= + totalBytes |

### Ver también

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


