---
title: "Κλάση VectorImage"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.VectorImage. Η διανυσματική εικόνα είναι η βασική κλάση για όλους τους τύπους διανυσματικών εικόνων"
type: docs
weight: 6220
url: /el/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

Η διανυσματική εικόνα είναι η βασική κλάση για όλους τους τύπους διανυσματικών εικόνων.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν γίνεται αυτόματη προσαρμογή παλέτας. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Λαμβάνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το κοντέινερ [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή μορφής αρχείου |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Λαμβάνει το ύψος του αντικειμένου, σε ίντσες. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Λαμβάνει το μέγεθος του αντικειμένου, σε ίντσες. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η παλέτα της εικόνας. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Λαμβάνει το πλάτος του αντικειμένου, σε ίντσες. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στη συγκεκριμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρηθεί το βάθος χρώματος και άλλες παράμετροι της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά εικονοστοιχείο και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο [`Save`](../datastreamsupporter/save/), θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά εικονοστοιχείο. Για να το αποφύγουμε και να αποθηκεύσουμε την PNG εικόνα με 1-bit ανά εικονοστοιχείο, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο [`Save`](../image/save/) ως δεύτερη παράμετρο. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Αλλάζει το πλάτος αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Αλλάζει το πλάτος αναλογικά. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στο καθορισμένο ρεύμα. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα της εικόνας. |

### Δείτε επίσης

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


