---
title: "Enumeración CompressionMethod"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.FileFormats.Psd.CompressionMethod. Define el método de compresión utilizado para los datos de la imagen."
type: docs
weight: 1630
url: /es/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Define el método de compresión utilizado para los datos de imagen.

```csharp
public enum CompressionMethod : short
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Raw | `0` | Sin compresión. Los datos de la imagen se almacenan como bytes sin procesar en orden planar RGBA. Eso significa que primero se escribe todo el dato R, luego todo el dato G, luego todo el dato B y finalmente todo el dato A. |
| RLE | `1` | Los datos de la imagen comprimidos con RLE comienzan con los recuentos de bytes para todas las líneas de escaneo (filas * canales), con cada recuento almacenado como un valor de dos bytes. A continuación vienen los datos comprimidos con RLE, con cada línea de escaneo comprimida por separado. La compresión RLE es el mismo algoritmo de compresión utilizado por la rutina PackBits del ROM de Macintosh y el estándar TIFF. |
| ZipWithoutPrediction | `2` | ZIP sin predicción. |
| ZipWithPrediction | `3` | ZIP con predicción. |

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


