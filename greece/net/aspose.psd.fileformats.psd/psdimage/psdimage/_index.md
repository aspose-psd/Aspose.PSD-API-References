---
title: PsdImage.PsdImage
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουPsdImage κλάση από καθορισμένη διαδρομή από εικόνα ράστερ όχι εικόνα psd στη διαδρομή. Χρησιμοποιείται για την προετοιμασία της εικόνας psd με προεπιλεγμένες παραμέτρους  Λειτουργία χρώματος  rgb 4 κανάλια 8 bit ανά κανάλι συμπίεση  Raw.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd στη διαδρομή). Χρησιμοποιείται για την προετοιμασία της εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, συμπίεση - Raw.

```csharp
public PsdImage(string path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Η διαδρομή για τη φόρτωση των δεδομένων pixel και της παλέτας από και την προετοιμασία με. |

### Δείτε επίσης

* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd στη διαδρομή) με παραμέτρους κατασκευαστή.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Η διαδρομή για τη φόρτωση των δεδομένων pixel και της παλέτας από και την προετοιμασία με. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit PSD ανά κανάλι. |
| channels | Int16 | Τα κανάλια PSD μετράνε. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση προς χρήση. |

### Δείτε επίσης

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd σε ροή). Χρησιμοποιείται για την προετοιμασία της εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, συμπίεση - Raw.

```csharp
public PsdImage(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή για τη φόρτωση δεδομένων εικονοστοιχείων και παλέτας και αρχικοποίηση. |

### Δείτε επίσης

* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd σε ροή) με παραμέτρους κατασκευαστή.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή για τη φόρτωση δεδομένων εικονοστοιχείων και παλέτας και αρχικοποίηση. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit PSD ανά κανάλι. |
| channels | Int16 | Τα κανάλια PSD μετράνε. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση προς χρήση. |

### Δείτε επίσης

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../)κλάση από υπάρχουσα εικόνα ράστερ (όχι εικόνα psd) με λειτουργία χρώματος RGB με 4 κανάλια 8 bit/κανάλι και χωρίς συμπίεση.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | RasterImage | Η εικόνα για φόρτωση δεδομένων pixel και παλέτας και αρχικοποίηση. |

### Δείτε επίσης

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κλάση από υπάρχουσα εικόνα ράστερ (όχι εικόνα psd) με παραμέτρους κατασκευαστή.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | RasterImage | Η εικόνα για φόρτωση δεδομένων pixel και παλέτας και αρχικοποίηση. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit PSD ανά κανάλι. |
| channels | Int16 | Τα κανάλια PSD μετράνε. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση προς χρήση. |

### Δείτε επίσης

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κατηγορία με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την προετοιμασία της άδειας εικόνας psd.

```csharp
public PsdImage(int width, int height)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | Int32 | Το πλάτος της εικόνας. |
| height | Int32 | Το ύψος της εικόνας. |

### Δείτε επίσης

* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`PsdImage`](../) κλάση με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, πλήθος καναλιών και μήκος bit καναλιών και καθορισμένες παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την προετοιμασία της άδειας εικόνας psd.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | Int32 | Το πλάτος της εικόνας. |
| height | Int32 | Το ύψος της εικόνας. |
| colorPalette | IColorPalette | Η χρωματική παλέτα. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit PSD ανά κανάλι. |
| channels | Int16 | Τα κανάλια PSD μετράνε. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση προς χρήση. |

### Δείτε επίσης

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


