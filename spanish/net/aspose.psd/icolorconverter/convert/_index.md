---
title: "IColorConverter.Convert"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método IColorConverter. Convierte los datos proporcionados al formato de salida"
type: docs
weight: 10
url: /es/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Convierte los datos proporcionados al formato de salida.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | El formato de origen. |
| datos | Byte[] | Los datos de origen. |
| desplazamiento | Int32 | El desplazamiento en bytes donde debe comenzar la copia de datos. |
| bitStart | Int32 | El inicio de bit. Nota: este valor no está alineado a bytes, sino que es el bit real donde debe comenzar la copia. |
| samplesCount | Int32 | El recuento de muestras. |
| linesCount | Int32 | El recuento de líneas. |
| destFormat | PixelDataFormat | El formato de destino. |
| outputData | Byte[] | Los datos de salida. |
| outputOffset | Int32 | El desplazamiento de salida donde debe comenzar la copia de datos. |

### Valor devuelto

El recuento de bytes convertidos.

### Ver también

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


