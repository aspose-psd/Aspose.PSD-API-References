---
title: Enum CompressionMethod
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.CompressionMethod enumeración. Define el método de compresión utilizado para los datos de imagen.
type: docs
weight: 1620
url: /es/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Define el método de compresión utilizado para los datos de imagen.

```csharp
public enum CompressionMethod : short
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Raw | `0` | Sin compresión. Los datos de imagen almacenados como bytes sin procesar en orden plano RGBA. Eso significa que primero se escriben todos los datos R, luego se escriben todos los G, luego todos los B y finalmente se escriben todos los datos A. |
| RLE | `1` | RLE comprimido, los datos de la imagen comienzan con los recuentos de bytes para todas las líneas de exploración (filas * canales), con cada recuento almacenado como un valor de dos bytes. Siguen los datos comprimidos RLE, con cada línea de exploración comprimida por separado. La compresión RLE es el mismo algoritmo de compresión utilizado por la rutina PackBits de ROM de Macintosh y el estándar TIFF. |
| ZipWithoutPrediction | `2` | ZIP sin predicción. |
| ZipWithPrediction | `3` | ZIP con predicción. |

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* asamblea [Aspose.PSD](../../)


