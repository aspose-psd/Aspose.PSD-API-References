---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IColorConverter-Methode. Konvertiert die übergebenen Daten in das Ausgabeformat"
type: docs
weight: 10
url: /de/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
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
| Daten | Byte[] | Die Quelldaten. |
| offset | Int32 | Der Offset in Bytes, an dem das Kopieren der Daten beginnen soll. |
| bitStart | Int32 | Der Bit-Start. Hinweis: Dieser Wert ist nicht byte‑ausgerichtet, sondern das tatsächliche Bit, an dem das Kopieren beginnen soll. |
| samplesCount | Int32 | Die Anzahl der Samples. |
| linesCount | Int32 | Die Zeilenanzahl. |
| destFormat | PixelDataFormat | Das Zielformat. |
| outputData | Byte[] | Die Ausgabedaten. |
| outputOffset | Int32 | Der output offset, bei dem das Kopieren von Daten beginnen soll. |

### Rückgabewert

Die Anzahl konvertierter Bytes.

### Siehe auch

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


