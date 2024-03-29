---
title: TiffStreamReader.ReadUShortArray
second_title: Aspose.PSD für .NET-API-Referenz
description: TiffStreamReader methode. Liest ein Array von vorzeichenlosen ganzzahligen Werten aus dem Stream.
type: docs
weight: 220
url: /de/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readushortarray/
---
## TiffStreamReader.ReadUShortArray method

Liest ein Array von vorzeichenlosen ganzzahligen Werten aus dem Stream.

```csharp
public ushort[] ReadUShortArray(long position, long count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | Int64 | Die Position, an der gelesen werden soll. |
| count | Int64 | Die Elemente zählen. |

### Rückgabewert

Das Array von Ganzzahlwerten ohne Vorzeichen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | count;Die Gesamtzahl der Bytes ist negativ. + count + x2 = + totalBytes |

### Siehe auch

* class [TiffStreamReader](../)
* namensraum [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* Montage [Aspose.PSD](../../../)


