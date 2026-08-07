---
title: "PixelDataFormat"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η μορφή δεδομένων pixel."
type: docs
weight: 80
url: /el/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Η μορφή δεδομένων εικονοστοιχείων. Αυτό είναι ένα αμετάβλητο αντικείμενο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο  System.Object  είναι ίσο με αυτήν την παρουσία. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Λαμβάνει χρώμα BGR με καθορισμένο αριθμό bits ανά δείγμα. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Λαμβάνει χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει τα bits ανά εικονοστοιχείο. |
| [getCaption()](#getCaption--) | Λαμβάνει τη λεζάντα της μορφής δεδομένων εικονοστοιχείων. |
| [getChannelBits()](#getChannelBits--) | Λαμβάνει τον αριθμό των bits για κάθε κανάλι. |
| [getChannelsCount()](#getChannelsCount--) | Λαμβάνει τον αριθμό των καναλιών. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Λαμβάνει χρώμα CIE Lab με καθορισμένο αριθμό bits ανά δείγμα. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 32 bits ανά εικονοστοιχείο με 8 bits για το κυανό, ματζέντα, κίτρινο και μαύρο. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα. |
| [getCmyk16()](#getCmyk16--) | Λαμβάνει τη [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορισμένη για 64 bits ανά εικονοστοιχείο με 16 bits για το κυανό, ματζέντα, κίτρινο και μαύρο. |
| [getCmyka()](#getCmyka--) | Λαμβάνει το acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Λαμβάνει χρώμα CMYKA με καθορισμένο αριθμό bits ανά δείγμα. |
| [getCmyka16()](#getCmyka16--) | Λαμβάνει το acmyk. |
| [getGrayscale()](#getGrayscale--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 8 bits ανά εικονοστοιχείο με 8 bits που αντιπροσωπεύουν την ένταση της κλίμακας του γκρι στο διάστημα 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Λαμβάνει χρώμα κλίμακας του γκρι με καθορισμένο αριθμό bits ανά δείγμα. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 16 bits ανά εικονοστοιχείο με 8 bits που αντιπροσωπεύουν την ένταση της κλίμακας του γκρι στο διάστημα 0-255 και πρόσθετο 8-bit στοιχείο άλφα. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Λαμβάνει τη [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορισμένη για 32 bits ανά εικονοστοιχείο που αντιπροσωπεύει την ένταση της κλίμακας του γκρι σε μορφή κινητής υποδιαστολής. |
| [getPixelFormat()](#getPixelFormat--) | Λαμβάνει τη μορφή εικονοστοιχείου. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 16 bits ανά εικονοστοιχείο με 5 bits για το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 16 bits ανά εικονοστοιχείο με 5 bits για το κόκκινο, 6 bits για το πράσινο και 5 bits για το μπλε, το άλφα δεν ορίζεται. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 24 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 24 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 32 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Λαμβάνει χρώμα BGRA με ευρετήριο με καθορισμένο αριθμό bits ανά δείγμα. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Λαμβάνει το  PixelDataFormat  που ορίζεται για ευρετήριο 1 bit ανά χρώμα. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Λαμβάνει το  PixelDataFormat  που ορίζεται για ευρετήριο 2 bit ανά χρώμα. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Λαμβάνει το  PixelDataFormat  που ορίζεται για ευρετήριο 4 bit ανά χρώμα. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Λαμβάνει το  PixelDataFormat  που ορίζεται για ευρετήριο 8 bit ανά χρώμα. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Λαμβάνει τη  PixelDataFormat  ορισμένη για 32 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Λαμβάνει το [PixelDataFormat](../../com.aspose.psd/pixeldataformat) που ορίζεται για 64 bits ανά pixel με 16 bits για το καθένα από τα άλφα, κόκκινο, πράσινο και μπλε. |
| [getYCbCr()](#getYCbCr--) | Λαμβάνει το  PixelDataFormat  που ορίζεται για 24 bits ανά pixel με 8 bits για το καθένα από τα χρωματικά συστατικά luma, διαφορά-μπλε και διαφορά-κόκκινο. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα. |
| [getYcck()](#getYcck--) | Λαμβάνει το  PixelDataFormat  που ορίζεται για 32 bits ανά pixel με 8 bits για το καθένα από τα χρωματικά συστατικά luma, διαφορά-μπλε, διαφορά-κόκκινο και μαύρο. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Λαμβάνει χρώμα YCCK με καθορισμένο αριθμό bits ανά δείγμα. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ευρετηριασμένη. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Επιστρέφει το αποτέλεσμα ισότητας για δύο κλάσεις  PixelDataFormat . |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Επιστρέφει το αποτέλεσμα ανισότητας για δύο κλάσεις  PixelDataFormat . |
| [toString()](#toString--) | Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το καθορισμένο  System.Object  είναι ίσο με αυτήν την παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το  System.Object  για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  true  εάν το καθορισμένο  System.Object  είναι ίσο με αυτήν την παρουσία· διαφορετικά,  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Λαμβάνει χρώμα BGR με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Λαμβάνει χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Λαμβάνει τα bits ανά εικονοστοιχείο.

**Returns:**
int - Τα bits ανά pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Λαμβάνει τη λεζάντα της μορφής δεδομένων εικονοστοιχείων.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Λαμβάνει τον αριθμό των bits για κάθε κανάλι.

**Returns:**
int[] - Τα bits καναλιού.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Λαμβάνει τον αριθμό των καναλιών.

**Returns:**
int - Ο αριθμός καναλιών.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Λαμβάνει χρώμα CIE Lab με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerL | int | Ο αριθμός των bits ανά κανάλι L. |
| bitsPerA | int | Ο αριθμός των bits ανά κανάλι A. |
| bitsPerB | int | Ο αριθμός των bits ανά κανάλι B. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 32 bits ανά εικονοστοιχείο με 8 bits για το κυανό, ματζέντα, κίτρινο και μαύρο.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerCyanChannel | int | Ο αριθμός των bits ανά κανάλι Cyan. |
| bitsPerMagentaChannel | int | Ο αριθμός των bits ανά κανάλι Magenta. |
| bitsPerYellowChannel | int | Ο αριθμός των bits ανά κανάλι Yellow. |
| bitsPerKeyChannel | int | Ο αριθμός των bits ανά κανάλι Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Λαμβάνει τη [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορισμένη για 64 bits ανά εικονοστοιχείο με 16 bits για το κυανό, ματζέντα, κίτρινο και μαύρο.

Τιμή: Το [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορίζεται για 64 bits ανά pixel με 16 bits για καθένα από τα cyan, magenta, yellow και black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Λαμβάνει το acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Λαμβάνει χρώμα CMYKA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerCyanChannel | int | Ο αριθμός των bits ανά κανάλι Cyan. |
| bitsPerMagentaChannel | int | Ο αριθμός των bits ανά κανάλι Magenta. |
| bitsPerYellowChannel | int | Ο αριθμός των bits ανά κανάλι Yellow. |
| bitsPerKeyChannel | int | Ο αριθμός των bits ανά κανάλι Key. |
| bitsPerAlphaChannel | int | Ο αριθμός των bits ανά κανάλι Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Λαμβάνει το acmyk.

Τιμή: Το [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορίζεται για 80 bits ανά pixel με 16 bits για καθένα από τα alpha, cyan, magenta, yellow και black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 8 bits ανά εικονοστοιχείο με 8 bits που αντιπροσωπεύουν την ένταση της κλίμακας του γκρι στο διάστημα 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Λαμβάνει χρώμα κλίμακας του γκρι με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 16 bits ανά εικονοστοιχείο με 8 bits που αντιπροσωπεύουν την ένταση της κλίμακας του γκρι στο διάστημα 0-255 και πρόσθετο 8-bit στοιχείο άλφα.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |
| alphaChannelBits | int | Ο αριθμός των bits ανά δείγμα στο κανάλι alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Λαμβάνει τη [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορισμένη για 32 bits ανά εικονοστοιχείο που αντιπροσωπεύει την ένταση της κλίμακας του γκρι σε μορφή κινητής υποδιαστολής.

Τιμή: Το [PixelDataFormat](../../com.aspose.psd/pixeldataformat) ορίζεται για 32 bits ανά pixel που αντιπροσωπεύει την ένταση του γκρι σε μορφή κινητής υποδιαστολής

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Λαμβάνει τη μορφή εικονοστοιχείου.

**Returns:**
int - Η μορφή pixel.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerRedChannel | int | Ο αριθμός των bits ανά κανάλι Red. |
| bitsPerGreenChannel | int | Ο αριθμός των bits ανά κανάλι Green. |
| bitsPerBlueChannel | int | Ο αριθμός των bits ανά κανάλι Blue. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 16 bits ανά εικονοστοιχείο με 5 bits για το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 16 bits ανά εικονοστοιχείο με 5 bits για το κόκκινο, 6 bits για το πράσινο και 5 bits για το μπλε, το άλφα δεν ορίζεται.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 24 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 24 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 32 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Λαμβάνει χρώμα BGRA με ευρετήριο με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Λαμβάνει το  PixelDataFormat  ορισμένο για ευρετηριασμένο 1 bit ανά χρώμα. Η αποθήκευση ευρετηριασμένων δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων. Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτεί μετατροπή από μια παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Λαμβάνει το  PixelDataFormat  ορισμένο για ευρετηριασμένο 2 bits ανά χρώμα. Η αποθήκευση ευρετηριασμένων δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων. Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτεί μετατροπή από μια παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Λαμβάνει το  PixelDataFormat  ορισμένο για ευρετηριασμένο 4 bits ανά χρώμα. Η αποθήκευση ευρετηριασμένων δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων. Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτεί μετατροπή από μια παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Λαμβάνει το  PixelDataFormat  που ορίζεται για ευρετηριασμένο 8-bit ανά χρώμα. Η ευρετηριασμένη αποθήκευση δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων. Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτήσει μετατροπή από μια παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerRedChannel | int | Ο αριθμός των bits ανά κανάλι Red. |
| bitsPerGreenChannel | int | Ο αριθμός των bits ανά κανάλι Green. |
| bitsPerBlueChannel | int | Ο αριθμός των bits ανά κανάλι Blue. |
| bitsPerAlphaChannel | int | Ο αριθμός των bits ανά κανάλι Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Λαμβάνει τη  PixelDataFormat  ορισμένη για 32 bits ανά εικονοστοιχείο με 8 bits για το άλφα, το κόκκινο, το πράσινο και το μπλε.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Λαμβάνει το [PixelDataFormat](../../com.aspose.psd/pixeldataformat) που ορίζεται για 64 bits ανά pixel με 16 bits για το καθένα από τα άλφα, κόκκινο, πράσινο και μπλε.

Τιμή: Το [PixelDataFormat](../../com.aspose.psd/pixeldataformat) που ορίζεται για 64 bit ανά pixel με 16 bit για το καθένα από τα άλφα, κόκκινο, πράσινο και μπλε.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Λαμβάνει το  PixelDataFormat  που ορίζεται για 24 bits ανά pixel με 8 bits για το καθένα από τα χρωματικά συστατικά luma, διαφορά-μπλε και διαφορά-κόκκινο.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerY | int | Ο αριθμός των bit ανά κανάλι Y. |
| bitsPerCb | int | Ο αριθμός των bit ανά κανάλι Cb. |
| bitsPerCr | int | Ο αριθμός των bit ανά κανάλι Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Λαμβάνει το  PixelDataFormat  που ορίζεται για 32 bits ανά pixel με 8 bits για το καθένα από τα χρωματικά συστατικά luma, διαφορά-μπλε, διαφορά-κόκκινο και μαύρο.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Λαμβάνει χρώμα YCCK με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitsPerSample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ευρετηριασμένη.

Τιμή:  true  εάν αυτό το αντικείμενο είναι ευρετηριασμένο· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ευρετηριασμένο.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Επιστρέφει το αποτέλεσμα ισότητας για δύο κλάσεις  PixelDataFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Το πρώτο  PixelDataFormat  για σύγκριση. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Το δεύτερο  PixelDataFormat  για σύγκριση. |

**Returns:**
boolean - True εάν και τα  pixelFormat1  και  pixelFormat2  περιέχουν ίσα δεδομένα ή και οι δύο παράμετροι είναι null.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Επιστρέφει το αποτέλεσμα ανισότητας για δύο κλάσεις  PixelDataFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Το πρώτο  PixelDataFormat  για σύγκριση. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Το δεύτερο  PixelDataFormat  για σύγκριση. |

**Returns:**
boolean - True εάν και τα  pixelFormat1  και  pixelFormat2  περιέχουν διαφορετικά δεδομένα ή μία από τις παραμέτρους είναι null.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.

**Returns:**
java.lang.String - Ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.
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

