---
title: IColorConverter.Convert
second_title: Referencia de API de Aspose.PSD para .NET
description: IColorConverter método. Convierte los datos pasados al formato de salida.
type: docs
weight: 10
url: /es/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Convierte los datos pasados al formato de salida.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | El formato de origen. |
| data | Byte[] | Los datos de origen. |
| offset | Int32 | El desplazamiento en bytes donde debe comenzar la copia de datos. |
| bitStart | Int32 | El comienzo del bit. Tenga en cuenta que este valor no es un valor alineado por bytes, sino que es un bit real donde debe comenzar la copia. |
| samplesCount | Int32 | Las muestras cuentan. |
| linesCount | Int32 | Las líneas cuentan. |
| destFormat | PixelDataFormat | El formato de destino. |
| outputData | Byte[] | Los datos de salida. |
| outputOffset | Int32 | El desplazamiento de salida donde debe comenzar la copia de datos. |

### Valor_devuelto

El conteo de bytes convertidos.

### Ver también

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* espacio de nombres [Aspose.PSD](../../icolorconverter/)
* asamblea [Aspose.PSD](../../../)


