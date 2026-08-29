---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Βοηθητική κλάση για τη διαχείριση παλετών χρωμάτων."
type: docs
weight: 28
url: /el/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Βοηθητική κλάση για τη διαχείριση παλετών χρωμάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [create4Bit()](#create4Bit--) | Δημιουργεί την παλέτα χρωμάτων 4 bit. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Δημιουργεί την παλέτα αποχρώσεων του γκρι 4 bit. |
| [create8Bit()](#create8Bit--) | Δημιουργεί την παλέτα χρωμάτων 8 bit. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Δημιουργεί την παλέτα αποχρώσεων του γκρι 8 bit. |
| [createMonochrome()](#createMonochrome--) | Δημιουργεί μια μονοχρωματική παλέτα χρωμάτων που περιέχει μόνο 2 χρώματα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πραγματοποιεί παλετοποίηση της εικόνας) σε περίπτωση που η εικόνα δεν διαθέτει παλέτα. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πραγματοποιεί παλετοποίηση της εικόνας) σε περίπτωση που η εικόνα δεν διαθέτει παλέτα. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πραγματοποιεί παλετοποίηση της εικόνας) σε περίπτωση που η εικόνα δεν διαθέτει παλέτα. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Αποκτήστε παλέτα 256 χρωμάτων, συντεθειμένη από τα άνω bits των αρχικών τιμών χρώματος της εικόνας. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Αποκτήστε ομοιόμορφη παλέτα 256 χρωμάτων. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Καθορίζει εάν η καθορισμένη παλέτα έχει διαφανή χρώματα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Δημιουργεί την παλέτα χρωμάτων 4 bit.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Δημιουργεί την παλέτα αποχρώσεων του γκρι 4 bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| minIsWhite | boolean | εάν οριστεί σε  true  η παλέτα ξεκινά με λευκό χρώμα, διαφορετικά ξεκινά με μαύρο χρώμα. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Δημιουργεί την παλέτα χρωμάτων 8 bit.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Δημιουργεί την παλέτα αποχρώσεων του γκρι 8 bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| minIsWhite | boolean | εάν οριστεί σε  true  η παλέτα ξεκινά με λευκό χρώμα, διαφορετικά ξεκινά με μαύρο χρώμα. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Δημιουργεί μια μονοχρωματική παλέτα χρωμάτων που περιέχει μόνο 2 χρώματα.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Λαμβάνει την παλέτα χρωμάτων από την raster εικόνα (πραγματοποιεί palletization της εικόνας) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια της εικόνας προορισμού. |
| entriesCount | int | Ο επιθυμητός αριθμός καταχωρήσεων. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Λαμβάνει την παλέτα χρωμάτων από την raster εικόνα (πραγματοποιεί palletization της εικόνας) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια της εικόνας προορισμού. |
| entriesCount | int | Ο επιθυμητός αριθμός καταχωρήσεων. |
| useImagePalette | boolean | Εάν οριστεί, θα χρησιμοποιήσει τη δική του παλέτα εικόνας εάν είναι διαθέσιμη. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Λαμβάνει την παλέτα χρωμάτων από την raster εικόνα (πραγματοποιεί palletization της εικόνας) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα raster. |
| entriesCount | int | Ο επιθυμητός αριθμός καταχωρήσεων. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Αποκτήστε παλέτα 256 χρωμάτων, συντεθειμένη από τα άνω bits των αρχικών τιμών χρώματος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Αποκτήστε ομοιόμορφη παλέτα 256 χρωμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Καθορίζει εάν η καθορισμένη παλέτα έχει διαφανή χρώματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα. |

**Returns:**
boolean -  true  εάν η καθορισμένη παλέτα έχει διαφανή χρώματα· διαφορετικά,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

