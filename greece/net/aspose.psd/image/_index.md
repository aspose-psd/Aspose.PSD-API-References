---
title: Class Image
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Image τάξη. Η εικόνα είναι η βασική κλάση για όλους τους τύπους εικόνων.
type: docs
weight: 4590
url: /el/net/aspose.psd/image/
---
## Image class

Η εικόνα είναι η βασική κλάση για όλους τους τύπους εικόνων.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η παλέτα αυτόματης προσαρμογής. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Λαμβάνει τα bit της εικόνας ανά πλήθος pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Παίρνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το`Image` δοχείο. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή της μορφής αρχείου |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λήψη ή ρύθμιση της οθόνης διακοπής. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτήν τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η χρωματική παλέτα δεν χρησιμοποιείται όταν τα εικονοστοιχεία αναπαρίστανται απευθείας. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Φορτώνει μια νέα εικόνα από την καθορισμένη ροή. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Φορτώνει μια νέα εικόνα από την καθορισμένη ροή. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Αποθηκεύει προσωρινά τα δεδομένα και διασφαλίζει ότι δεν θα πραγματοποιηθεί πρόσθετη φόρτωση δεδομένων από το υποκείμενο[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις περασμένες επιλογές αποθήκευσης. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές με βάση τις ρυθμίσεις του αρχικού αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρήσουμε το βάθος bit και άλλες παραμέτρους της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, αν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια αποθηκεύστε το χρησιμοποιώντας το [`Save`](../datastreamsupporter/save/) Με τη μέθοδο, θα παραχθεί η εικόνα εξόδου PNG με 8 bit ανά pixel. Για να το αποφύγετε και να αποθηκεύσετε εικόνα PNG με 1 bit ανά pixel, χρησιμοποιήστε αυτήν τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και να τις μεταφέρετε στο[`Save`](./save/)μέθοδος ως δεύτερη παράμετρος. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/#save)() | Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα εικόνων. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από την καθορισμένη ροή. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από την καθορισμένη διαδρομή αρχείου. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από την καθορισμένη ροή και προαιρετικά χρησιμοποιώντας την καθορισμένη*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από την καθορισμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες ανοιχτές επιλογές. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Λαμβάνει τη μορφή αρχείου. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Λαμβάνει τη μορφή αρχείου. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Παίρνει ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Παίρνει ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Παίρνει ανάλογο ύψος. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Παίρνει αναλογικό πλάτος. |

### Παραδείγματα

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο εικόνας σε κάποια θέση δίσκου, όπως καθορίζεται από την ιδιότητα Source της παρουσίας PsdOptions. Ορίζονται πολλές ιδιότητες για την παρουσία PsdOptions πριν από τη δημιουργία της πραγματικής εικόνας. Ειδικά η ιδιότητα Source, που αναφέρεται στην πραγματική θέση του δίσκου σε αυτήν την περίπτωση.

```csharp
[C#]

//Δημιουργήστε μια παρουσία του PsdOptions και ορίστε τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του FileCreateSource και αντιστοιχίστε την ως πηγή για την παρουσία του PsdOptions
//Δεύτερη παράμετρος Boolean καθορίζει εάν το αρχείο που θα δημιουργηθεί είναι Temporal ή όχι
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Δημιουργήστε μια παρουσία της εικόνας και αρχικοποιήστε την με την παρουσία της PsdOptions καλώντας τη μέθοδο Δημιουργία
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Κάνε κάποια επεξεργασία εικόνας

    // αποθήκευση όλων των αλλαγών
    image.Save();
}
```

### Δείτε επίσης

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


