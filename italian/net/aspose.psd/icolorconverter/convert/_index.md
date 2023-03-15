---
title: IColorConverter.Convert
second_title: Aspose.PSD per riferimento API .NET
description: IColorConverter metodo. Converte i dati passati nel formato di output.
type: docs
weight: 10
url: /it/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Converte i dati passati nel formato di output.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Il formato sorgente. |
| data | Byte[] | I dati di origine. |
| offset | Int32 | L'offset in byte in cui deve iniziare la copia dei dati. |
| bitStart | Int32 | Il pezzo inizia. Nota che questo valore non è un valore allineato al byte, invece questo è il bit effettivo in cui dovrebbe iniziare la copia. |
| samplesCount | Int32 | I campioni contano. |
| linesCount | Int32 | Le righe contano. |
| destFormat | PixelDataFormat | Il formato di destinazione. |
| outputData | Byte[] | I dati di uscita. |
| outputOffset | Int32 | L'offset di output in cui dovrebbe iniziare la copia dei dati. |

### Valore di ritorno

Il conteggio dei byte convertiti.

### Guarda anche

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* spazio dei nomi [Aspose.PSD](../../icolorconverter/)
* assemblea [Aspose.PSD](../../../)


