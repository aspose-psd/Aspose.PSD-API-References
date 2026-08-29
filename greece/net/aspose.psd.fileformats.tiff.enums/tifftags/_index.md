---
title: "Enum TiffTags"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. Η enum ετικέτας tiff"
type: docs
weight: 4640
url: /el/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

Η απαρίθμηση ετικέτας tiff.

```csharp
public enum TiffTags
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| SubFileType | `254` | Περιγραφέας δεδομένων υποαρχείου. |
| OsubfileType | `255` | [obsoleted by TIFF rev. 5.0] Τύπος δεδομένων στο υποαρχείο. |
| ImageWidth | `256` | Πλάτος εικόνας σε εικονοστοιχεία. |
| ImageLength | `257` | Ύψος εικόνας σε εικονοστοιχεία. |
| BitsPerSample | `258` | Ψηφία ανά κανάλι (δείγμα). |
| Compression | `259` | Τεχνική συμπίεσης δεδομένων. |
| Photometric | `262` | Φωτομετρική ερμηνεία. |
| Thresholding | `263` | [obsoleted by TIFF rev. 5.0] Κατώφλι που χρησιμοποιείται στα δεδομένα. |
| CellWidth | `264` | [obsoleted by TIFF rev. 5.0] Πλάτος πλέγματος δόμησης. |
| CellLength | `265` | [obsoleted by TIFF rev. 5.0] Ύψος πλέγματος δόμησης |
| FillOrder | `266` | Σειρά δεδομένων μέσα σε ένα byte. |
| DocumentName | `269` | Όνομα του εγγράφου που περιέχει την εικόνα. |
| ImageDescription | `270` | Πληροφορίες σχετικά με την εικόνα. |
| Make | `271` | Όνομα κατασκευαστή σαρωτή. |
| Model | `272` | Όνομα/αριθμός μοντέλου σαρωτή. |
| StripOffsets | `273` | Μετατοπίσεις σε λωρίδες δεδομένων. |
| Orientation | `274` | [παρωχημένο από TIFF rev. 5.0] Προσανατολισμός εικόνας. |
| SamplesPerPixel | `277` | Δείγματα ανά pixel. |
| RowsPerStrip | `278` | Γραμμές ανά λωρίδα δεδομένων. |
| StripByteCounts | `279` | Αριθμός byte για λωρίδες. |
| MinSampleValue | `280` | [παρωχημένο από TIFF rev. 5.0] Ελάχιστη τιμή δείγματος. |
| MaxSampleValue | `281` | [παρωχημένο από TIFF rev. 5.0] Μέγιστη τιμή δείγματος. |
| Xresolution | `282` | Pixels/ανάλυση στον άξονα x. |
| Yresolution | `283` | Pixels/ανάλυση στον άξονα y. |
| PlanarConfig | `284` | Οργάνωση αποθήκευσης. |
| PageName | `285` | Όνομα σελίδας από την οποία προέρχεται η εικόνα. |
| Xposition | `286` | Μετατόπιση X σελίδας της εικόνας αριστερά. |
| Yposition | `287` | Μετατόπιση Y σελίδας της εικόνας αριστερά. |
| FreeOffsets | `288` | [παρωχημένο από TIFF rev. 5.0] Μετατόπιση byte σε ελεύθερο μπλοκ. |
| FreeByteCounts | `289` | [παρωχημένο από TIFF rev. 5.0] Μεγέθη ελεύθερων μπλοκ. |
| GrayResponseUnit | `290` | [παρωχημένο από TIFF rev. 6.0] Ακρίβεια καμπύλης γκρι κλίμακας. |
| GrayResponseCurve | `291` | [παρωχημένο από TIFF rev. 6.0] Καμπύλη απόκρισης γκρι κλίμακας. |
| T4Options | `292` | TIFF 6.0 σωστό όνομα ψευδώνυμο για GROUP3OPTIONS. Επιλογές για κωδικοποίηση φαξ CCITT Group 3. 32 bits σημαίας. |
| T6Options | `293` | Επιλογές για κωδικοποίηση φαξ CCITT Group 4. 32 bits σημαίας. TIFF 6.0 σωστό όνομα ψευδώνυμο για GROUP4OPTIONS. |
| ResolutionUnit | `296` | Μονάδες ανάλυσης. |
| PageNumber | `297` | Αριθμοί σελίδων πολλαπλών σελίδων. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] Ακρίβεια καμπύλης χρώματος. |
| TransferFunction | `301` | Πληροφορίες χρωματομετρίας. |
| Software | `305` | Όνομα &amp; έκδοση. |
| DateTime | `306` | Ημερομηνία και ώρα δημιουργίας. |
| Artist | `315` | Δημιουργός εικόνας. |
| HostComputer | `316` | Μηχάνημα όπου δημιουργήθηκε. |
| Predictor | `317` | Σχέδιο πρόβλεψης με LZW. |
| WhitePoint | `318` | Λευκό σημείο εικόνας. |
| PrimaryChromaticities | `319` | Κύριες χρωματικότητες. |
| ColorMap | `320` | Χάρτης RGB για εικόνα παλέτας. |
| HalftoneHints | `321` | Πληροφορίες ανάγλυφου + σκιάς. |
| TileWidth | `322` | Πλάτος πλακιδίου σε εικονοστοιχεία. |
| TileLength | `323` | Ύψος πλακιδίου σε εικονοστοιχεία. |
| TileOffsets | `324` | Μετατοπίσεις σε πλακίδια δεδομένων. |
| TileByteCounts | `325` | Αριθμός byte για πλακίδια. |
| BadFaxLines | `326` | Γραμμές με λανθασμένο αριθμό εικονοστοιχείων. |
| CleanFaxData | `327` | Πληροφορίες επαναδημιουργημένης γραμμής. |
| ConsecutiveBadFaxLines | `328` | Μέγιστος αριθμός διαδοχικών εσφαλμένων γραμμών. |
| SubIfd | `330` | Περιγραφείς υποεικόνας. |
| InkSet | `332` | Μελάνια σε διαχωρισμένη εικόνα. |
| InkNames | `333` | Ονόματα ASCII των μελανιών. |
| NumberOfInks | `334` | Αριθμός μελανιών. |
| DotRange | `336` | Κώδικες κουκίδων 0% και 100%. |
| TargetPrinter | `337` | Στόχος διαχωρισμού. |
| ExtraSamples | `338` | Πληροφορίες σχετικά με πρόσθετα δείγματα. |
| SampleFormat | `339` | Μορφή δείγματος δεδομένων. |
| SminSampleValue | `340` | Μεταβλητή MinSampleValue. |
| SmaxSampleValue | `341` | Μεταβλητή MaxSampleValue. |
| TransferRange | `342` | Μεταβλητή TransferRange |
| ClipPath | `343` | ClipPath. Εισήχθη μετά την έκδοση TIFF 6.0 από την τεχνική σημείωση Adobe TIFF 2. |
| Xclippathunits | `344` | XClipPathUnits. Εισήχθη μετά την έκδοση TIFF 6.0 από την τεχνική σημείωση Adobe TIFF 2. |
| Yclippathunits | `345` | YClipPathUnits. Εισήχθη μετά την έκδοση TIFF 6.0 από την τεχνική σημείωση Adobe TIFF 2. |
| Indexed | `346` | Indexed. Εισήχθη μετά την έκδοση TIFF 6.0 από την τεχνική σημείωση Adobe TIFF 3. |
| JpegTables | `347` | Ροή πίνακα JPEG. Εισήχθη μετά την έκδοση TIFF 6.0. |
| OpiProxy | `351` | OPI Proxy. Εισήχθη μετά την έκδοση TIFF 6.0 από την τεχνική σημείωση Adobe TIFF. |
| JpegProc | `512` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] αλγόριθμος επεξεργασίας JPEG. |
| JpegInerchangeFormat | `513` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Δείκτης στο σημάδι SOI. |
| JpegInterchangeFormatLength | `514` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Μήκος ροής JFIF |
| JpegRestartInterval | `515` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Μήκος διαστήματος επανεκκίνησης. |
| JpegLosslessPredictors | `517` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Απώλεστος προβλέπτης επεξεργασίας. |
| JpegPointTransform | `518` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Απώλεστος μετασχηματισμός σημείου. |
| JpegQTables | `519` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Μετατοπίσεις πίνακα Q. |
| JpegDCtables | `520` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Μετατοπίσεις πίνακα DCT. |
| JpegACtables | `521` | [παρωχημένο από την Τεχνική Σημείωση #2 που καθορίζει ένα αναθεωρημένο σχήμα JPEG-in-TIFF] Μετατοπίσεις συντελεστή AC. |
| YcbcrCoefficients | `529` | Μετασχηματισμός RGB -&gt; YCbCr. |
| YcbcrSubSampling | `530` | Παράγοντες υποδειγματοληψίας YCbCr. |
| YcbcrPositioning | `531` | Τοποθέτηση υποδειγμάτων. |
| ReferenceBlackWhite | `532` | Πληροφορίες χρωματομετρίας. |
| XmlPacket | `700` | XML packet. Εισήχθη μετά την έκδοση TIFF 6.0 από την προδιαγραφή Adobe XMP, Ιανουάριος 2004. |
| OpiImageid | `32781` | OPI ImageID. Εισήχθη μετά την έκδοση TIFF 6.0 από την τεχνική σημείωση Adobe TIFF. |
| Refpts | `32953` | Σημεία αναφοράς εικόνας. Ιδιωτική ετικέτα καταχωρημένη στην Island Graphics. |
| Copyright | `33432` | Συμβολοσειρά πνευματικών δικαιωμάτων. Αυτή η ετικέτα είναι καταχωρημένη στο TIFF rev. 6.0 με άγνωστη ιδιοκτησία. |
| PhotoshopResources | `34377` | Πόροι εικόνας Photoshop. |
| IccProfile | `34675` | Το ενσωματωμένο προφίλ συσκευής ICC |
| ExifIfdPointer | `34665` | Ένας δείκτης προς το Exif IFD. |
| XPTitle | `40091` | Πληροφορίες σχετικά με την εικόνα, χρησιμοποιούνται από τον Windows Explorer. Το XPTitle αγνοείται από τον Windows Explorer εάν υπάρχει η ετικέτα ImageDescription. |
| XPComment | `40092` | Σχόλιο στην εικόνα, χρησιμοποιείται από τον Windows Explorer. |
| XPAuthor | `40093` | Συγγραφέας εικόνας, χρησιμοποιείται από τον Windows Explorer. Το XPAuthor αγνοείται από τον Windows Explorer εάν υπάρχει η ετικέτα Artist. |
| XPKeywords | `40094` | Λέξεις-κλειδιά εικόνας, χρησιμοποιούνται από τον Windows Explorer. |
| XPSubject | `40095` | Θέμα εικόνας, χρησιμοποιείται από τον Windows Explorer. |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


