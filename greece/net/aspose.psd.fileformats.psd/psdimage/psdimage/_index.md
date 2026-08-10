---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "PsdImage κατασκευαστής. Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PsdImage από καθορισμένη διαδρομή raster εικόνας, όχι psd εικόνα στη διαδρομή. Χρησιμοποιείται για την αρχικοποίηση psd εικόνας με προεπιλεγμένες παραμέτρους  Λειτουργία χρώματος  rgb 4 κανάλια 8 bit ανά κανάλι Συμπίεση  Raw"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα στη διαδρομή). Χρησιμοποιείται για την αρχικοποίηση psd εικόνας με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw.

```csharp
public PsdImage(string path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Η διαδρομή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |

### Δείτε επίσης

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα στη διαδρομή) με παραμέτρους κατασκευής.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Η διαδρομή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit του PSD ανά κανάλι. |
| channels | Int16 | Ο αριθμός των καναλιών PSD. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση που θα χρησιμοποιηθεί. |

### Δείτε επίσης

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στη ροή). Χρησιμοποιείται για την αρχικοποίηση εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw.

```csharp
public PsdImage(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή από την οποία φορτώνεται το pixel και τα δεδομένα παλέτας και με την οποία γίνεται η αρχικοποίηση. |

### Δείτε επίσης

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στη ροή) με παραμέτρους κατασκευής.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή από την οποία φορτώνεται το pixel και τα δεδομένα παλέτας και με την οποία γίνεται η αρχικοποίηση. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit του PSD ανά κανάλι. |
| channels | Int16 | Ο αριθμός των καναλιών PSD. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση που θα χρησιμοποιηθεί. |

### Δείτε επίσης

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) από υπάρχουσα raster εικόνα (όχι εικόνα psd) με λειτουργία χρώματος RGB, 4 κανάλια, 8 bit/κανάλι και χωρίς συμπίεση.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | RasterImage | Η εικόνα από την οποία φορτώνεται το pixel και τα δεδομένα παλέτας και με την οποία γίνεται η αρχικοποίηση. |

### Δείτε επίσης

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) από υπάρχουσα raster εικόνα (όχι εικόνα psd) με παραμέτρους κατασκευής.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | RasterImage | Η εικόνα από την οποία φορτώνεται το pixel και τα δεδομένα παλέτας και με την οποία γίνεται η αρχικοποίηση. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit του PSD ανά κανάλι. |
| channels | Int16 | Ο αριθμός των καναλιών PSD. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση που θα χρησιμοποιηθεί. |

### Δείτε επίσης

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την αρχικοποίηση κενής εικόνας psd.

```csharp
public PsdImage(int width, int height)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | Int32 | Το πλάτος της εικόνας. |
| ύψος | Int32 | Το ύψος της εικόνας. |

### Δείτε επίσης

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PsdImage`](../) με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, αριθμό καναλιών και μήκος bit καναλιών καθώς και με καθορισμένες παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την αρχικοποίηση κενής εικόνας psd.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | Int32 | Το πλάτος της εικόνας. |
| ύψος | Int32 | Το ύψος της εικόνας. |
| colorPalette | IColorPalette | Η παλέτα χρωμάτων. |
| colorMode | ColorModes | Η λειτουργία χρώματος. |
| channelBitDepth | Int16 | Το βάθος bit του PSD ανά κανάλι. |
| channels | Int16 | Ο αριθμός των καναλιών PSD. |
| psdVersion | Int32 | Η έκδοση PSD. |
| compression | CompressionMethod | Η συμπίεση που θα χρησιμοποιηθεί. |

### Δείτε επίσης

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


