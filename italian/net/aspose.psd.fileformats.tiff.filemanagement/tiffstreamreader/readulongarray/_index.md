---
title: TiffStreamReader.ReadULongArray
second_title: Aspose.PSD per riferimento API .NET
description: TiffStreamReader metodo. Legge un array di valori interi senza segno dallo stream.
type: docs
weight: 200
url: /it/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
## TiffStreamReader.ReadULongArray method

Legge un array di valori interi senza segno dallo stream.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | Int64 | La posizione da cui leggere. |
| count | Int64 | Gli elementi contano. |

### Valore di ritorno

L'array di valori interi senza segno.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | count;Il conteggio totale dei byte è negativo. + conteggio + x4= + totalBytes |

### Guarda anche

* class [TiffStreamReader](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assemblea [Aspose.PSD](../../../)


