---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TiffStreamReader-Methode. Liest ein Array von vorzeichenbehafteten Ganzzahlen aus dem Stream"
type: docs
weight: 140
url: /de/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Liest ein Array von signierten integer-Werten aus dem Stream.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | Int64 | Die Position, von der gelesen werden soll. |
| count | Int64 | Die Elementanzahl. |

### Rückgabewert

Das Array von vorzeichenbehafteten Ganzzahlen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | count;Die Gesamtanzahl der Bytes ist negativ. + count + x4= + totalBytes |

### Siehe auch

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


