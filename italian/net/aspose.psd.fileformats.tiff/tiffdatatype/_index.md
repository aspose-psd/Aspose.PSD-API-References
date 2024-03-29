---
title: Class TiffDataType
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Tiff.TiffDataType classe. Il tipo di dati tiff.
type: docs
weight: 4210
url: /it/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Il tipo di dati tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Ottiene la dimensione aggiuntiva dei dati in byte (nel caso in cui i 12 byte non siano sufficienti per contenere i dati del tag). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Ottiene il conteggio degli elementi. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Ottiene la dimensione aggiuntiva dei dati in byte (nel caso in cui i 12 byte non siano sufficienti per contenere i dati del tag). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Ottiene la rappresentazione intera dell'id del tag. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Ottiene un valore che indica se i dati del tag sono validi. Il tag valido contiene dati che possono essere conservati. Il tag non valido non può essere memorizzato. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Ottiene l'id del tag. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Ottiene il tipo di tag. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Ottiene o imposta il valore contenuto da questo tipo di dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Legge i dati del tag. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un numero intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordinamento dell'altro oggetto. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Esegue un clone profondo di questa istanza. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Restituisce aString che rappresenta questa istanza. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Scrive i dati aggiuntivi del tag. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Scrive i dati del tag. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assemblea [Aspose.PSD](../../)


