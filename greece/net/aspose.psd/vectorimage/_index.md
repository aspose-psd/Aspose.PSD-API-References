---
title: Class VectorImage
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.VectorImage τάξη. Η διανυσματική εικόνα είναι η βασική κλάση για όλους τους τύπους διανυσματικών εικόνων.
type: docs
weight: 5720
url: /el/net/aspose.psd/vectorimage/
---
## VectorImage class

Η διανυσματική εικόνα είναι η βασική κλάση για όλους τους τύπους διανυσματικών εικόνων.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η παλέτα αυτόματης προσαρμογής. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Λαμβάνει τα bit της εικόνας ανά πλήθος pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Παίρνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το[`Image`](../image/) δοχείο. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή της μορφής αρχείου |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Λαμβάνει το ύψος του αντικειμένου, σε ίντσες. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λήψη ή ρύθμιση της οθόνης διακοπής. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτήν τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η χρωματική παλέτα δεν χρησιμοποιείται όταν τα εικονοστοιχεία αναπαρίστανται απευθείας. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Λαμβάνει το μέγεθος του αντικειμένου, σε ίντσες. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Λαμβάνει το πλάτος του αντικειμένου, σε ίντσες. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Αποθηκεύει προσωρινά τα δεδομένα και διασφαλίζει ότι δεν θα πραγματοποιηθεί πρόσθετη φόρτωση δεδομένων από το υποκείμενο[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις περασμένες επιλογές αποθήκευσης. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές με βάση τις ρυθμίσεις του αρχικού αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρήσουμε το βάθος bit και άλλες παραμέτρους της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, αν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια αποθηκεύστε το χρησιμοποιώντας το [`Save`](../datastreamsupporter/save/) Με τη μέθοδο, θα παραχθεί η εικόνα εξόδου PNG με 8 bit ανά pixel. Για να το αποφύγετε και να αποθηκεύσετε εικόνα PNG με 1 bit ανά pixel, χρησιμοποιήστε αυτήν τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και να τις μεταφέρετε στο[`Save`](../image/save/)μέθοδος ως δεύτερη παράμετρος. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα εικόνων. |

### Δείτε επίσης

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


