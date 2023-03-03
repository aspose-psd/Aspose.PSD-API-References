---
title: Enum TiffTags
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. Il tag tiff enum.
type: docs
weight: 4170
url: /it/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

Il tag tiff enum.

```csharp
public enum TiffTags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| SubFileType | `254` | Descrittore dati subfile. |
| OsubfileType | `255` | [obsoleto da TIFF rev. 5.0] Tipo di dati nel sottofile. |
| ImageWidth | `256` | Larghezza immagine in pixel. |
| ImageLength | `257` | Altezza dell'immagine in pixel. |
| BitsPerSample | `258` | Bit per canale (campione). |
| Compression | `259` | Tecnica di compressione dei dati. |
| Photometric | `262` | Interpretazione fotometrica. |
| Thresholding | `263` | [obsoleto da TIFF rev. 5.0] Soglia utilizzata sui dati. |
| CellWidth | `264` | [obsoleto da TIFF rev. 5.0] Larghezza matrice di dithering. |
| CellLength | `265` | [obsoleto da TIFF rev. 5.0] Altezza matrice di dithering. |
| FillOrder | `266` | Ordine dei dati all'interno di un byte. |
| DocumentName | `269` | Nome del documento che contiene l'immagine. |
| ImageDescription | `270` | Informazioni sull'immagine. |
| Make | `271` | Nome del produttore dello scanner. |
| Model | `272` | Nome/numero del modello dello scanner. |
| StripOffsets | `273` | Offset rispetto alle strisce dati. |
| Orientation | `274` | [obsoleto da TIFF rev. 5.0] Orientamento dell'immagine. |
| SamplesPerPixel | `277` | Campioni per pixel. |
| RowsPerStrip | `278` | Righe per striscia di dati. |
| StripByteCounts | `279` | Conteggio dei byte per le strisce. |
| MinSampleValue | `280` | [obsoleto da TIFF rev. 5.0] Valore minimo campione. |
| MaxSampleValue | `281` | [obsoleto da TIFF rev. 5.0] Valore massimo campione. |
| Xresolution | `282` | Pixel/risoluzione in x. |
| Yresolution | `283` | Pixel/risoluzione in y. |
| PlanarConfig | `284` | Organizzazione di archiviazione. |
| PageName | `285` | L'immagine del nome della pagina proviene da. |
| Xposition | `286` | Offset pagina X dell'immagine sx. |
| Yposition | `287` | Offset pagina Y dell'immagine sx. |
| FreeOffsets | `288` | [obsoleto da TIFF rev. 5.0] Offset byte al blocco libero. |
| FreeByteCounts | `289` | [obsoleto da TIFF rev. 5.0] Dimensioni dei blocchi liberi. |
| GrayResponseUnit | `290` | [obsoleto da TIFF rev. 6.0] Precisione della curva della scala di grigi. |
| GrayResponseCurve | `291` | [obsoleto da TIFF rev. 6.0] Curva di risposta in scala di grigi. |
| T4Options | `292` | TIFF 6.0 nome proprio alias per GROUP3OPTIONS. Opzioni per la codifica fax CCITT Gruppo 3. 32 bit di flag. |
| T6Options | `293` | Opzioni per la codifica fax CCITT Gruppo 4. 32 flag bit. Alias nome proprio TIFF 6.0 per GROUP4OPTIONS. |
| ResolutionUnit | `296` | Unità di risoluzione. |
| PageNumber | `297` | Numeri di pagina di più pagine. |
| ColorResponseUnit | `300` | [obsoleto da TIFF rev. 6.0] Precisione della curva di colore. |
| TransferFunction | `301` | Info colorimetria. |
| Software | `305` | Nome e versione. |
| DateTime | `306` | Data e ora di creazione. |
| Artist | `315` | Creatore dell'immagine. |
| HostComputer | `316` | Macchina dove creato. |
| Predictor | `317` | Schema di previsione con LZW. |
| WhitePoint | `318` | Punto di bianco dell'immagine. |
| PrimaryChromaticities | `319` | Cromaticità primarie. |
| ColorMap | `320` | Mappa RGB per l'immagine pallette. |
| HalftoneHints | `321` | Evidenzia + info ombra. |
| TileWidth | `322` | Larghezza riquadro in pixel. |
| TileLength | `323` | Altezza piastrella in pixel. |
| TileOffsets | `324` | Offset rispetto ai riquadri di dati. |
| TileByteCounts | `325` | Numero di byte per i riquadri. |
| BadFaxLines | `326` | Righe con numero di pixel errato. |
| CleanFaxData | `327` | Info linea rigenerata. |
| ConsecutiveBadFaxLines | `328` | Numero massimo di linee sbagliate consecutive. |
| SubIfd | `330` | Descrittori dell'immagine secondaria. |
| InkSet | `332` | Inchiostri nell'immagine separata. |
| InkNames | `333` | Nomi ASCII degli inchiostri. |
| NumberOfInks | `334` | Numero di inchiostri. |
| DotRange | `336` | Codici punto 0% e 100%. |
| TargetPrinter | `337` | Obiettivo di separazione. |
| ExtraSamples | `338` | Informazioni sui campioni extra. |
| SampleFormat | `339` | Formato campione dati. |
| SminSampleValue | `340` | Variabile MinSampleValue. |
| SmaxSampleValue | `341` | Variabile MaxSampleValue. |
| TransferRange | `342` | TransferRange variabile |
| ClipPath | `343` | ClipPath. Introdotto post TIFF rev 6.0 da Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Introdotto post TIFF rev 6.0 da Adobe TIFF technote 2. |
| Yclippathunits | `345` | Unità YClipPath. Introdotto post TIFF rev 6.0 da Adobe TIFF technote 2. |
| Indexed | `346` | Indicizzato. Introdotto post TIFF rev 6.0 da Adobe TIFF Technote 3. |
| JpegTables | `347` | Stream tabella JPEG. Introdotto post TIFF rev 6.0. |
| OpiProxy | `351` | Procura OPI. Introdotto post TIFF rev 6.0 da Adobe TIFF technote. |
| JpegProc | `512` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Algoritmo di elaborazione JPEG. |
| JpegInerchangeFormat | `513` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Puntatore al marcatore SOI. |
| JpegInterchangeFormatLength | `514` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Lunghezza flusso JFIF |
| JpegRestartInterval | `515` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Lunghezza intervallo di riavvio. |
| JpegLosslessPredictors | `517` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Predittore processo senza perdita. |
| JpegPointTransform | `518` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Trasformazione punto senza perdita. |
| JpegQTables | `519` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Q offset matrice. |
| JpegDCtables | `520` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Offset tabella DCT. |
| JpegACtables | `521` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Offset coefficiente AC. |
| YcbcrCoefficients | `529` | RGB -&gt; Trasformazione YCbCr. |
| YcbcrSubSampling | `530` | Fattori di sottocampionamento YCbCr. |
| YcbcrPositioning | `531` | Posizionamento sottocampione. |
| ReferenceBlackWhite | `532` | Info colorimetria. |
| XmlPacket | `700` | Pacchetto XML. Introdotto dopo TIFF rev 6.0 da Adobe XMP Specification, gennaio 2004. |
| OpiImageid | `32781` | ID immagine OPI. Introdotto post TIFF rev 6.0 da Adobe TIFF technote. |
| Refpts | `32953` | Punti di riferimento dell'immagine. Tag privato registrato a Island Graphics. |
| Copyright | `33432` | Stringa di copyright. Questo tag è elencato nel TIFF rev. 6.0 con proprietà sconosciuta. |
| PhotoshopResources | `34377` | Risorse immagine di Photoshop. |
| IccProfile | `34675` | Il profilo del dispositivo ICC incorporato |
| ExifIfdPointer | `34665` | Un puntatore all'Exif IFD. |
| XPTitle | `40091` | Informazioni sull'immagine, utilizzate da Windows Explorer. TheXPTitle viene ignorato da Esplora risorse se il fileImageDescription il tag esiste. |
| XPComment | `40092` | Commento sull'immagine, utilizzato da Windows Explorer. |
| XPAuthor | `40093` | Image Author, utilizzato da Windows Explorer. TheXPAuthor viene ignorato da Esplora risorse se il fileArtist il tag esiste. |
| XPKeywords | `40094` | Parole chiave immagine, utilizzate da Windows Explorer. |
| XPSubject | `40095` | Immagine del soggetto, utilizzata da Windows Explorer. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assemblea [Aspose.PSD](../../)


