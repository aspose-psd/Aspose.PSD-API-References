---
title: "IColorConverter"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El convertidor de color."
type: docs
weight: 116
url: /es/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

El convertidor de color.
## Métodos

| Método | Descripción |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Convierte los datos proporcionados al formato de salida. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Convierte los datos proporcionados al formato de salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El formato de origen. |
| data | byte[] | Los datos de origen. |
| offset | int | El desplazamiento en bytes donde debe comenzar la copia de datos. |
| bitStart | int | El inicio de bit. Nota: este valor no está alineado a bytes, sino que es el bit real donde debe comenzar la copia. |
| samplesCount | int | El recuento de muestras. |
| linesCount | int | El recuento de líneas. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El formato de destino. |
| outputData | byte[] | Los datos de salida. |
| outputOffset | int | El desplazamiento de salida donde debe comenzar la copia de datos. |

**Returns:**
int - El recuento de bytes convertidos.
