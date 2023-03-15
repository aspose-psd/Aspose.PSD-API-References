---
title: IColorConverter.Convert
second_title: Aspose.PSD für .NET-API-Referenz
description: IColorConverter methode. Konvertiert die übergebenen Daten in das Ausgabeformat.
type: docs
weight: 10
url: /de/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Konvertiert die übergebenen Daten in das Ausgabeformat.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Das Quellformat. |
| data | Byte[] | Die Quelldaten. |
| offset | Int32 | Der Offset in Bytes, an dem das Kopieren der Daten beginnen soll. |
| bitStart | Int32 | Das Bit beginnt. Beachten Sie, dass dieser Wert kein Byte-ausgerichteter Wert ist, sondern das tatsächliche Bit, an dem das Kopieren beginnen sollte. |
| samplesCount | Int32 | Die Proben zählen. |
| linesCount | Int32 | Die Zeilen zählen. |
| destFormat | PixelDataFormat | Das Zielformat. |
| outputData | Byte[] | Die Ausgangsdaten. |
| outputOffset | Int32 | Der Ausgabe-Offset, an dem das Kopieren der Daten beginnen soll. |

### Rückgabewert

Die Anzahl der konvertierten Bytes.

### Siehe auch

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namensraum [Aspose.PSD](../../icolorconverter/)
* Montage [Aspose.PSD](../../../)


