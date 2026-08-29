---
title: "Κλάση Image"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Image. Η εικόνα είναι η βασική κλάση για όλους τους τύπους εικόνων"
type: docs
weight: 5060
url: /el/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

Η εικόνα είναι η βασική κλάση για όλους τους τύπους εικόνων.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν γίνεται αυτόματη προσαρμογή παλέτας. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Λαμβάνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Αποκτά το δοχείο `Image`. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή μορφής αρχείου |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η παλέτα της εικόνας. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στη συγκεκριμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Αποκτά τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο [`Save`](../datastreamsupporter/save/), θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά pixel. Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο [`Save`](./save/) ως δεύτερη παράμετρο. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Αλλάζει το πλάτος αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Αλλάζει το πλάτος αναλογικά. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/#save)() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στο καθορισμένο ρεύμα. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα της εικόνας. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο μονοπάτι αρχείου. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας τις καθορισμένες *loadOptions*. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο μονοπάτι αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες επιλογές ανοίγματος. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Λαμβάνει τη μορφή του αρχείου. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Λαμβάνει τη μορφή του αρχείου. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Λαμβάνει ένα ανάλογο ύψος. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Λαμβάνει ένα ανάλογο πλάτος. |

## Παραδείγματα

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image σε κάποια θέση δίσκου όπως καθορίζεται από την ιδιότητα Source του αντικειμένου PsdOptions. Πολλές ιδιότητες του αντικειμένου PsdOptions ορίζονται πριν δημιουργηθεί η πραγματική εικόνα. Ιδιαίτερα η ιδιότητα Source, που αναφέρεται στην πραγματική θέση δίσκου σε αυτή την περίπτωση.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του PsdOptions και ορίστε τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε ένα στιγμιότυπο του FileCreateSource και αναθέστε το ως Source για το στιγμιότυπο του PsdOptions
//Η δεύτερη παράμετρος Boolean καθορίζει εάν το αρχείο που θα δημιουργηθεί είναι IsTemporal ή όχι
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Δημιουργήστε ένα στιγμιότυπο του Image και αρχικοποιήστε το με το στιγμιότυπο του PsdOptions καλώντας τη μέθοδο Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //κάντε κάποια επεξεργασία εικόνας

    // αποθηκεύστε όλες τις αλλαγές
    image.Save();
}
```

### Δείτε επίσης

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


