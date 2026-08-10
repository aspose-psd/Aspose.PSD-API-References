---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος ColorPaletteHelper. Λαμβάνει την παλέτα χρωμάτων από την raster εικόνα που παλετοποιεί την εικόνα σε περίπτωση που η εικόνα δεν έχει μία. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί να εκτελείται υπολογισμός."
type: docs
weight: 60
url: /el/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Αποκτά την παλέτα χρωμάτων από raster εικόνα (δημιουργεί παλέτα εικόνας) σε περίπτωση που η εικόνα δεν διαθέτει παλέτα. Εάν η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | RasterImage | Η raster εικόνα. |
| entriesCount | Int32 | Ο επιθυμητός αριθμός καταχωρίσεων. |

### Τιμή Επιστροφής

Η παλέτα χρωμάτων που ξεκινά με τα πιο συχνά χρώματα από την *image* και περιέχει *entriesCount* καταχωρίσεις.

### Δείτε επίσης

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Αποκτά την παλέτα χρωμάτων από raster εικόνα (δημιουργεί παλέτα εικόνας) σε περίπτωση που η εικόνα δεν διαθέτει παλέτα. Εάν η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | RasterImage | Η raster εικόνα. |
| destBounds | Rectangle | Τα όρια της εικόνας προορισμού. |
| entriesCount | Int32 | Ο επιθυμητός αριθμός καταχωρίσεων. |

### Τιμή Επιστροφής

Η παλέτα χρωμάτων που ξεκινά με τα πιο συχνά χρώματα από την *image* και περιέχει *entriesCount* καταχωρίσεις.

### Δείτε επίσης

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Αποκτά την παλέτα χρωμάτων από raster εικόνα (δημιουργεί παλέτα εικόνας) σε περίπτωση που η εικόνα δεν διαθέτει παλέτα. Εάν η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | RasterImage | Η raster εικόνα. |
| destBounds | Rectangle | Τα όρια της εικόνας προορισμού. |
| entriesCount | Int32 | Ο επιθυμητός αριθμός καταχωρίσεων. |
| useImagePalette | Boolean | Εάν οριστεί, θα χρησιμοποιήσει τη δική του παλέτα εικόνας εάν είναι διαθέσιμη. |

### Τιμή Επιστροφής

Η παλέτα χρωμάτων που ξεκινά με τα πιο συχνά χρώματα από την *image* και περιέχει *entriesCount* καταχωρίσεις.

### Δείτε επίσης

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


