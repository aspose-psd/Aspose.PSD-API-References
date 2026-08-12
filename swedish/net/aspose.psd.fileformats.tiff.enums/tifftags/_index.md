---
title: "Enum TiffTags"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. tiff-tagenum"
type: docs
weight: 4640
url: /sv/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

Den tiff-tag enumen.

```csharp
public enum TiffTags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| SubFileType | `254` | Underfilens databeskrivning. |
| OsubfileType | `255` | [föråldrad av TIFF rev. 5.0] Typ av data i underfil. |
| ImageWidth | `256` | Bildbredd i pixlar. |
| ImageLength | `257` | Bildhöjd i pixlar. |
| BitsPerSample | `258` | Bit per kanal (sample). |
| Compression | `259` | Datakomprimeringsteknik. |
| Photometric | `262` | Fotometrisk tolkning. |
| Thresholding | `263` | [föråldrad av TIFF rev. 5.0] Tröskling som används på data. |
| CellWidth | `264` | [föråldrad av TIFF rev. 5.0] Bredd på dithermatris. |
| CellLength | `265` | [föråldrad av TIFF rev. 5.0] Höjd på dithermatris. |
| FillOrder | `266` | Dataordning inom en byte. |
| DocumentName | `269` | Namn på dokument som innehåller bilden. |
| ImageDescription | `270` | Information om bilden. |
| Make | `271` | Skannertillverkarens namn. |
| Model | `272` | Skannermodellens namn/nummer. |
| StripOffsets | `273` | Förskjutningar till datastreck. |
| Orientation | `274` | [föråldrad av TIFF rev. 5.0] Bildorientering. |
| SamplesPerPixel | `277` | Prover per pixel. |
| RowsPerStrip | `278` | Rader per datastreck. |
| StripByteCounts | `279` | Byteantal för streck. |
| MinSampleValue | `280` | [föråldrad av TIFF rev. 5.0] Minsta provvärde. |
| MaxSampleValue | `281` | [föråldrad av TIFF rev. 5.0] Största provvärde. |
| Xresolution | `282` | Pixlar/upplösning i x. |
| Yresolution | `283` | Pixlar/upplösning i y. |
| PlanarConfig | `284` | Lagringsorganisation. |
| PageName | `285` | Sidnamn som bilden kommer från. |
| Xposition | `286` | X-sidförskjutning för bildens vänstra sida. |
| Yposition | `287` | Y-sidförskjutning för bildens vänstra sida. |
| FreeOffsets | `288` | [föråldrad av TIFF rev. 5.0] Byteförskjutning till fritt block. |
| FreeByteCounts | `289` | [föråldrad av TIFF rev. 5.0] Storlekar på fria block. |
| GrayResponseUnit | `290` | [föråldrad av TIFF rev. 6.0] Gråskalakurvans noggrannhet. |
| GrayResponseCurve | `291` | [föråldrad av TIFF rev. 6.0] Gråskalans svarskurva. |
| T4Options | `292` | TIFF 6.0 korrekt namn alias för GROUP3OPTIONS. Alternativ för CCITT Group 3 faxkodning. 32 flaggbitar. |
| T6Options | `293` | Alternativ för CCITT Group 4 faxkodning. 32 flaggbitar. TIFF 6.0 korrekt namn alias för GROUP4OPTIONS. |
| ResolutionUnit | `296` | Enheter för upplösningar. |
| PageNumber | `297` | Sidnummer för flersidig. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] Färgkurvans noggrannhet. |
| TransferFunction | `301` | Färgimetriinformation. |
| Software | `305` | Namn &amp; version. |
| DateTime | `306` | Skapandedatum och tid. |
| Artist | `315` | Skapare av bilden. |
| HostComputer | `316` | Maskin där den skapades. |
| Predictor | `317` | Prediktionsschema med LZW. |
| WhitePoint | `318` | Bildens vitpunkt. |
| PrimaryChromaticities | `319` | Primära kromatisiteter. |
| ColorMap | `320` | RGB-karta för palettbild. |
| HalftoneHints | `321` | Markering + skugginfo. |
| TileWidth | `322` | Tile-bredd i pixlar. |
| TileLength | `323` | Tile-höjd i pixlar. |
| TileOffsets | `324` | Offset till datatiles. |
| TileByteCounts | `325` | Byteantal för tiles. |
| BadFaxLines | `326` | Rader med fel pixelantal. |
| CleanFaxData | `327` | Regenererad radinfo. |
| ConsecutiveBadFaxLines | `328` | Maximalt antal på varandra följande felrader. |
| SubIfd | `330` | Delbildsbeskrivningar. |
| InkSet | `332` | Bläck i separerad bild. |
| InkNames | `333` | ASCII-namn på bläck. |
| NumberOfInks | `334` | Antal bläck. |
| DotRange | `336` | 0% och 100% punktkoder. |
| TargetPrinter | `337` | Separationsmål. |
| ExtraSamples | `338` | Information om extra prover. |
| SampleFormat | `339` | Data provformat. |
| SminSampleValue | `340` | Variabel MinSampleValue. |
| SmaxSampleValue | `341` | Variabel MaxSampleValue. |
| TransferRange | `342` | Variabel TransferRange |
| ClipPath | `343` | ClipPath. Introducerad efter TIFF rev 6.0 av Adobe TIFF teknisk not 2. |
| Xclippathunits | `344` | XClipPathUnits. Introducerad efter TIFF rev 6.0 av Adobe TIFF teknisk not 2. |
| Yclippathunits | `345` | YClipPathUnits. Introducerad efter TIFF rev 6.0 av Adobe TIFF teknisk not 2. |
| Indexed | `346` | Indexed. Introducerad efter TIFF rev 6.0 av Adobe TIFF teknisk not 3. |
| JpegTables | `347` | JPEG-tabellström. Introducerad efter TIFF rev 6.0. |
| OpiProxy | `351` | OPI Proxy. Introducerad efter TIFF rev 6.0 av Adobe TIFF teknisk not. |
| JpegProc | `512` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] JPEG-bearbetningsalgoritm. |
| JpegInerchangeFormat | `513` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Pekare till SOI-markör. |
| JpegInterchangeFormatLength | `514` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] JFIF-strömlängd |
| JpegRestartInterval | `515` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Omstartintervallens längd. |
| JpegLosslessPredictors | `517` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Förlustfri proc-prediktor. |
| JpegPointTransform | `518` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Förlustfri punkttransform. |
| JpegQTables | `519` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Q-matrisförskjutningar. |
| JpegDCtables | `520` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] DCT-tabellförskjutningar. |
| JpegACtables | `521` | [föråldrad av Technical Note #2 som specificerar ett reviderat JPEG-i-TIFF-schema] AC-koefficientförskjutningar. |
| YcbcrCoefficients | `529` | RGB → YCbCr-transform. |
| YcbcrSubSampling | `530` | YCbCr-subsamplingsfaktorer. |
| YcbcrPositioning | `531` | Subsamplingspositionering. |
| ReferenceBlackWhite | `532` | Färgimetriinformation. |
| XmlPacket | `700` | XML-paket. Introducerad efter TIFF rev 6.0 av Adobe XMP Specification, januari 2004. |
| OpiImageid | `32781` | OPI ImageID. Introducerad efter TIFF rev 6.0 av Adobe TIFF teknisk not. |
| Refpts | `32953` | Bildreferenspunkter. Privat tagg registrerad till Island Graphics. |
| Copyright | `33432` | Upphovsrättssträng. Denna tagg listas i TIFF rev. 6.0 med okänt ägande. |
| PhotoshopResources | `34377` | Photoshop-bildresurser. |
| IccProfile | `34675` | Den inbäddade ICC-enhetsprofilen |
| ExifIfdPointer | `34665` | En pekare till Exif IFD. |
| XPTitle | `40091` | Information om bilden, används av Windows Explorer. XPTitle ignoreras av Windows Explorer om ImageDescription‑taggen finns. |
| XPComment | `40092` | Kommentar om bilden, används av Windows Explorer. |
| XPAuthor | `40093` | Bildförfattare, används av Windows Explorer. XPAuthor ignoreras av Windows Explorer om Artist‑taggen finns. |
| XPKeywords | `40094` | Bildnyckelord, används av Windows Explorer. |
| XPSubject | `40095` | Bildämne, används av Windows Explorer. |

### Se även

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


