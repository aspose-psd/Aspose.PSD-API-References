---
title: "IColorConverter"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il convertitore di colore."
type: docs
weight: 116
url: /it/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Il convertitore di colore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Converte i dati forniti nel formato di output. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Converte i dati forniti nel formato di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il formato di origine. |
| dati | byte[] | I dati di origine. |
| offset | int | L'offset in byte da cui deve iniziare la copia dei dati. |
| bitStart | int | L'inizio del bit. Nota che questo valore non è allineato a byte, ma è il bit effettivo dove deve iniziare la copia. |
| samplesCount | int | Il conteggio dei campioni. |
| linesCount | int | Il conteggio delle linee. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il formato di destinazione. |
| outputData | byte[] | I dati di output. |
| outputOffset | int | L'offset di output da cui deve iniziare la copia dei dati. |

**Returns:**
int - Il conteggio dei byte convertiti.
