---
title: TiffStreamReader.ReadSLongArray
second_title: Aspose.PSD für .NET-API-Referenz
description: TiffStreamReader methode. Liest ein Array von vorzeichenbehafteten Ganzzahlwerten aus dem Stream.
type: docs
weight: 140
url: /de/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
## TiffStreamReader.ReadSLongArray method

Liest ein Array von vorzeichenbehafteten Ganzzahlwerten aus dem Stream.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | Int64 | Die Position, an der gelesen werden soll. |
| count | Int64 | Die Elemente zählen. |

### Rückgabewert

Das Array von ganzzahligen Werten mit Vorzeichen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | count;Die Gesamtzahl der Bytes ist negativ. + count + x4 = + totalBytes |

### Siehe auch

* class [TiffStreamReader](../)
* namensraum [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* Montage [Aspose.PSD](../../../)


