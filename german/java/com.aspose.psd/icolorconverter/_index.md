---
title: "IColorConverter"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Farbkonverter."
type: docs
weight: 116
url: /de/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Der Farbkonverter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Konvertiert die übergebenen Daten in das Ausgabeformat. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Konvertiert die übergebenen Daten in das Ausgabeformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das Quellformat. |
| Daten | byte[] | Die Quelldaten. |
| Versatz | int | Der Offset in Bytes, an dem das Kopieren von Daten beginnen soll. |
| bitStart | int | Der Bit-Start. Hinweis: Dieser Wert ist nicht byte‑ausgerichtet, sondern das tatsächliche Bit, an dem das Kopieren beginnen soll. |
| samplesCount | int | Die Anzahl der Samples. |
| linesCount | int | Die Zeilenanzahl. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das Zielformat. |
| outputData | byte[] | Die Ausgabedaten. |
| outputOffset | int | Der Ausgabe-Offset, an dem das Kopieren von Daten beginnen soll. |

**Returns:**
int - Die Anzahl der konvertierten Bytes.
