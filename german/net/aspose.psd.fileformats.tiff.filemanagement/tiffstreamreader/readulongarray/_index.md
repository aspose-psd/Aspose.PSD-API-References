---
title: "TiffStreamReader.ReadULongArray"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TiffStreamReader-Methode. Liest ein Array von unsigned integer-Werten aus dem Stream"
type: docs
weight: 200
url: /de/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadULongArray method

Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | Int64 | Die Position, von der gelesen werden soll. |
| count | Int64 | Die Elementanzahl. |

### Rückgabewert

Das Array von unsigned integer-Werten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | count;Die Gesamtanzahl der Bytes ist negativ. + count + x4= + totalBytes |

### Siehe auch

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


