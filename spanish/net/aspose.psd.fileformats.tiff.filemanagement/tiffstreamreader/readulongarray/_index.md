---
title: "TiffStreamReader.ReadULongArray"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método TiffStreamReader. Lee una matriz de valores enteros sin signo del flujo"
type: docs
weight: 200
url: /es/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadULongArray method

Lee una matriz de valores enteros sin signo del flujo.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | Int64 | La posición desde la cual leer. |
| count | Int64 | El recuento de elementos. |

### Valor devuelto

La matriz de valores enteros sin signo.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | count;El recuento total de bytes es negativo. + count + x4= + totalBytes |

### Ver también

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


