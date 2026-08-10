---
title: "Κλάση SmartObjectLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer class. Ορίζει την κλάση SmartObjectLayer που περιέχει ενσωματωμένο στο αρχείο PSD ή συνδεδεμένο έξυπνο αντικείμενο στο εξωτερικό αρχείο. Με τα Smart Objects μπορείτε να εκτελείτε μη καταστροφικούς μετασχηματισμούς. Μπορείτε να κλιμακώσετε, περιστρέψετε, παραμορφώσετε, διαστρεβλώσετε, αλλάξετε προοπτική ή να παραμορφώσετε (warp) ένα επίπεδο χωρίς να χάσετε τα αρχικά δεδομένα εικόνας ή την ποιότητα, επειδή οι μετασχηματισμοί δεν επηρεάζουν τα αρχικά δεδομένα. Εργαστείτε με διανυσματικά δεδομένα όπως διανυσματικά γραφικά από το Illustrator που διαφορετικά θα rasterize. Εκτελέστε μη καταστροφικό φιλτράρισμα. Μπορείτε να επεξεργαστείτε τα φίλτρα που εφαρμόζονται στα Smart Objects ανά πάσα στιγμή. Επεξεργαστείτε ένα Smart Object και ενημερώστε αυτόματα όλες τις συνδεδεμένες εμφανίσεις του. Εφαρμόστε μια μάσκα επιπέδου που είναι είτε συνδεδεμένη είτε μη συνδεδεμένη στο επίπεδο Smart Object. Δοκιμάστε διάφορα σχέδια με εικόνες placeholder χαμηλής ανάλυσης που θα αντικαταστήσετε αργότερα με τις τελικές εκδόσεις. Στο Adobe Photoshop μπορείτε να ενσωματώσετε το περιεχόμενο μιας εικόνας σε ένα έγγραφο PSD. Περισσότερες πληροφορίες εδώ https//helpx.adobe.com/photoshop/using/createsmartobjects.html Ένα επίπεδο με ενσωματωμένο smart object περιέχει τοποθετημένους πόρους PlLd και SoLd με ιδιότητες smart object. Ο πόρος PlLd μπορεί να είναι μόνος του για εκδόσεις PSD παλαιότερες από το 10. Αυτοί οι πόροι περιέχουν UniqueId του LiFdDataSource στο παγκόσμιο Lnk2Resource με το ενσωματωμένο όνομα αρχείου και άλλες παραμέτρους, συμπεριλαμβανομένου του ενσωματωμένου περιεχομένου αρχείου στην αρχική μορφή ως πίνακα byte."
type: docs
weight: 3910
url: /el/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
{{< psd/tize >}}
## SmartObjectLayer class

Ορίζει την κλάση SmartObjectLayer που περιέχει ενσωματωμένο στο αρχείο PSD ή συνδεδεμένο smart object στο εξωτερικό αρχείο. Με τα Smart Objects, μπορείτε: Να εκτελείτε μη καταστροφικές μετασχηματίσεις. Μπορείτε να κλιμακώσετε, να περιστρέψετε, να κλίνετε, να παραμορφώσετε, να εφαρμόσετε προοπτική ή να παραμορφώσετε ένα επίπεδο χωρίς να χάσετε τα αρχικά δεδομένα εικόνας ή την ποιότητα, επειδή οι μετασχηματισμοί δεν επηρεάζουν τα αρχικά δεδομένα. Να εργάζεστε με διανυσματικά δεδομένα, όπως διανυσματικά γραφικά από το Illustrator, που διαφορετικά θα rasterize. Να εκτελείτε μη καταστροφικό φιλτράρισμα. Μπορείτε να επεξεργάζεστε τα φίλτρα που εφαρμόζονται στα Smart Objects ανά πάσα στιγμή. Επεξεργαστείτε ένα Smart Object και ενημερώστε αυτόματα όλες τις συνδεδεμένες εμφανίσεις του. Εφαρμόστε μια μάσκα επιπέδου που είναι είτε συνδεδεμένη είτε αποσυνδεδεμένη από το επίπεδο Smart Object. Δοκιμάστε διάφορα σχέδια με εικόνες placeholder χαμηλής ανάλυσης που θα αντικαταστήσετε αργότερα με τις τελικές εκδόσεις. Στο Adobe Photoshop, μπορείτε να ενσωματώσετε το περιεχόμενο μιας εικόνας σε ένα έγγραφο PSD. Περισσότερες πληροφορίες εδώ: [https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Ένα επίπεδο με ενσωματωμένο smart object περιέχει πόρους placed (PlLd) και SoLd με ιδιότητες smart object. Ο πόρος PlLd μπορεί να είναι μόνος για εκδόσεις PSD παλαιότερες από το 10. Αυτοί οι πόροι περιέχουν UniqueId του LiFdDataSource στο παγκόσμιο Lnk2Resource με το ενσωματωμένο όνομα αρχείου και άλλες παραμέτρους, συμπεριλαμβανομένου του ενσωματωμένου περιεχομένου αρχείου στην αρχική μορφή ως πίνακα byte.

```csharp
public class SmartObjectLayer : Layer
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SmartObjectLayer](smartobjectlayer/)(Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SmartObjectLayer`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν γίνεται αυτόματη προσαρμογή παλέτας. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Λαμβάνει ή ορίζει τη συγχώνευση του περικομμένου στοιχείου. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Λαμβάνει τις επιλογές συγχώνευσης. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Λαμβάνει ή ορίζει το κλειδί της λειτουργίας ανάμειξης. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Λαμβάνει την υπογραφή της λειτουργίας ανάμειξης. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Λαμβάνει ή ορίζει τη θέση του κάτω επιπέδου. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Λαμβάνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Λαμβάνει ή ορίζει τις πληροφορίες του καναλιού. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Λαμβάνει τον αριθμό των καναλιών του επιπέδου. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Λαμβάνει ή ορίζει την αποκοπή του επιπέδου. 0 = βάση, 1 = μη-βάση. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το κοντέινερ [`Image`](../../aspose.psd/image/). |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Λαμβάνει ή ορίζει τα περιεχόμενα του επιπέδου smart object. Τα ενσωματωμένα περιεχόμενα smart object είναι το ενσωματωμένο ακατέργαστο αρχείο εικόνας: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) και οι ιδιότητές του. Τα συνδεδεμένα περιεχόμενα smart object είναι το ακατέργαστο περιεχόμενο του συνδεδεμένου αρχείου εικόνας εάν είναι διαθέσιμο και οι ιδιότητές του: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Δεν υποστηρίζουμε τη φόρτωση από τη βιβλιοθήκη γραφικών Adobe Photoshop όταν το [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) είναι true. Για κανονικά αρχεία συνδέσμου, αρχικά χρησιμοποιούμε το [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) για να αναζητήσουμε το αρχείο σχετικά με τη διαδρομή της πηγαίας εικόνας SourceImagePath, εάν δεν είναι διαθέσιμο κοιτάζουμε το [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), αν όχι τότε αναζητούμε το αρχείο συνδέσμου στον ίδιο φάκελο όπου βρίσκεται η εικόνα μας: SourceImagePath. |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Λαμβάνει ή ορίζει τα όρια του περιεχομένου του smart object. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Λαμβάνει ή ορίζει την πηγή του περιεχομένου του smart object. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Λαμβάνει τον τύπο του περιεχομένου του επιπέδου smart object. Τα ενσωματωμένα περιεχόμενα smart object είναι το ενσωματωμένο ακατέργαστο αρχείο εικόνας: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/). Τα συνδεδεμένα περιεχόμενα smart object είναι το ακατέργαστο περιεχόμενο του συνδεδεμένου αρχείου εικόνας εάν είναι διαθέσιμο: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Δεν υποστηρίζουμε τη φόρτωση από τη βιβλιοθήκη γραφικών Adobe Photoshop όταν το [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) είναι true. Για κανονικά αρχεία συνδέσμου, αρχικά χρησιμοποιούμε το [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) για να αναζητήσουμε το αρχείο σχετικά με τη διαδρομή της πηγαίας εικόνας SourceImagePath, εάν δεν είναι διαθέσιμο κοιτάζουμε το [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), αν όχι τότε αναζητούμε το αρχείο συνδέσμου στον ίδιο φάκελο όπου βρίσκεται η εικόνα μας: SourceImagePath. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Λαμβάνει ή ορίζει το εμφανιζόμενο όνομα του επιπέδου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Λαμβάνει το μήκος των επιπλέον πληροφοριών του επιπέδου σε bytes. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή μορφής αρχείου |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Λαμβάνει ή ορίζει το γέμισμα του επιπέδου. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια γεμίσματος. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες του στρώματος. bit 0 = προστασία διαφάνειας· bit 1 = ορατό· bit 2 = παρωχημένο· bit 3 = 1 για Photoshop 5.0 και μεταγενέστερα, υποδεικνύει εάν το bit 4 περιέχει χρήσιμες πληροφορίες· bit 4 = δεδομένα pixel που δεν επηρεάζουν την εμφάνιση του εγγράφου. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει άλφα. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα εικόνας είναι προσωρινά αποθηκευμένα αυτή τη στιγμή. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στρώμα είναι ορατό |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή στην ομάδα (Εάν το στρώμα δεν βρίσκεται σε ομάδα, σημαίνει ότι είναι η ριζική ομάδα). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα περιοχών ανάμειξης του στρώματος. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Λαμβάνει ή ορίζει την ημερομηνία και ώρα δημιουργίας του στρώματος. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Λαμβάνει ή ορίζει το κλείδωμα του στρώματος. Σημειώστε ότι εάν η σημαία LayerFlags.TransparencyProtected είναι ορισμένη, θα αντικατασταθεί από τη σημαία κλειδώματος στρώματος. Για να επιστραφεί η σημαία LayerFlags.TransparencyProtected, πρέπει να εφαρμοστεί η επιλογή στρώματος layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα μάσκας του στρώματος. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Λαμβάνει τις επιλογές του στρώματος. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Λαμβάνει ή ορίζει τη θέση αριστερά του στρώματος. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Λαμβάνει το συνολικό μήκος του στρώματος σε bytes. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του στρώματος. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια του στρώματος. 0 = διαφανές, 255 = αδιαφανές. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να είναι προπολλαπλασιασμένα. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ανακτά ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Ανακτά ή ορίζει τον μετατροπέα χρωμάτων με δείκτη |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Λαμβάνει το μέγεθος της ακατέργαστης γραμμής σε byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Ανακτά ή ορίζει τους πόρους στρώσης. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Ανακτά ή ορίζει τη θέση της δεξιάς στρώσης. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Ανακτά ή ορίζει την επισήμανση χρώματος διακοσμητικού φύλλου στη λίστα στρώσεων |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Λαμβάνει τα έξυπνα φίλτρα. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Λαμβάνει τον πάροχο έξυπνων αντικειμένων. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Ανακτά ή ορίζει τη θέση της επάνω στρώσης. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ανακτά ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η παλέτα της εικόνας. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ανακτά ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Ανακτά ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [`RasterImage`](../../aspose.psd/rasterimage/). |
| [WarpSettings](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/warpsettings/) { get; set; } | Ανακτά ή ορίζει τις παραμέτρους Warp που είχαν οριστεί ή ληφθεί από τον πόρο (προεπιλογή) |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Ανακτά ή ορίζει τα μεταδεδομένα XMP. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Προσθέτει τη μάσκα στην τρέχουσα στρώση. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Ρύθμιση της φωτεινότητας για την εικόνα. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Αντίθεση εικόνας |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Διόρθωση γάμμα μιας εικόνας. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Διόρθωση γάμμα μιας εικόνας. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Εφαρμόζει τη μάσκα στρώσης στο στρώμα, στη συνέχεια διαγράφει τη μάσκα. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στη συγκεκριμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Μετατρέπει αυτό το ενσωματωμένο έξυπνο αντικείμενο σε συνδεδεμένο έξυπνο αντικείμενο. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Περικοπή της εικόνας. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Περικοπή εικόνας με μετατοπίσεις. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Σχεδιάζει την εικόνα στο layer. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Δημιουργεί ένα νέο επίπεδο έξυπνου αντικειμένου αντιγράφοντας αυτό το. Σημειώστε ότι για ενσωματωμένα έξυπνα αντικείμενα η ενσωματωμένη εικόνα μοιράζεται. Εάν θέλετε να αντιγράψετε την ενσωματωμένη εικόνα, χρησιμοποιήστε τη μέθοδο [`NewSmartObjectViaCopy`](./newsmartobjectviacopy/). |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Ενσωματώνει το συνδεδεμένο έξυπνο αντικείμενο σε αυτό το layer. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Εξάγει τα ενσωματωμένα ή συνδεδεμένα περιεχόμενα σε ένα αρχείο. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Επιστρέφει έναν κωδικό hash για αυτήν την παρουσία. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρηθεί το βάθος χρώματος και άλλες παράμετροι της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο [`Save`](../../aspose.psd/datastreamsupporter/save/), θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά pixel. Για να το αποφύγουμε και να αποθηκεύσουμε την PNG εικόνα με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο [`Save`](../../aspose.psd/image/save/) ως δεύτερη παράμετρο. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Λαμβάνει ένα pixel εικόνας. Προειδοποίηση απόδοσης: Αποφύγετε τη χρήση αυτής της μεθόδου για επανάληψη σε όλα τα pixel της εικόνας, καθώς μπορεί να προκαλέσει σημαντικά προβλήματα απόδοσης. Για πιο αποδοτική διαχείριση pixel, χρησιμοποιήστε τη μέθοδο `LoadArgb32Pixels` για να ανακτήσετε ολόκληρο τον πίνακα pixel ταυτόχρονα. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Λαμβάνει τη γωνία κλίσης. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου, για τον προσδιορισμό της γωνίας κλίσης κατά τη σάρωση. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Μετασχηματισμός μιας εικόνας στην γκρι κλίμακα της |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία 32-bit ARGB. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία 64-bit ARGB. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία σε μορφή CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Φορτώνει εικονοστοιχεία σε μορφή CMYK. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Αποκτά τα ενσωματωμένα ή συνδεδεμένα περιεχόμενα εικόνας του επιπέδου smart object. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Φορτώνει εικονοστοιχεία 32-bit ARGB μερικώς ανά πακέτα. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Φορτώνει εικονοστοιχεία μερικώς ανά πακέτα. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Φορτώνει εικονοστοιχεία. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Συγχωνεύει το επίπεδο με το καθορισμένο επίπεδο |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Δημιουργεί ένα νέο επίπεδο smart object αντιγράφοντας αυτό. Αναπαράγει τη λειτουργία `Layer -> Smart Objects -> New Smart Object via Copy` του Adobe Photoshop. Σημειώστε ότι είναι ενεργοποιημένη μόνο για ενσωματωμένα smart objects, επειδή η ενσωματωμένη εικόνα επίσης αντιγράφεται. Εάν θέλετε να μοιραστείτε την ενσωματωμένη εικόνα, χρησιμοποιήστε τη μέθοδο [`DuplicateLayer`](./duplicatelayer/). |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος είναι εφαρμόσιμη σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της κλίσης της σάρωσης. Αυτή η μέθοδος χρησιμοποιεί τις μεθόδους [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) και [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος είναι εφαρμόσιμη σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της κλίσης της σάρωσης. Αυτή η μέθοδος χρησιμοποιεί τις μεθόδους [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) και [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Επανασυνδέει το συνδεδεμένο smart object σε νέο αρχείο. Δεν χρειάζεται να κληθεί η μέθοδος UpdateModifiedContent μετά. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Αντικαθιστά τα περιεχόμενα του smart object που είναι ενσωματωμένα στο επίπεδο smart object. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Αντικαθιστά τα περιεχόμενα με ένα αρχείο. Δεν χρειάζεται να κληθεί η μέθοδος UpdateModifiedContent μετά. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Αντικαθιστά τα περιεχόμενα του smart object που είναι ενσωματωμένα στο επίπεδο smart object. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_5)(string, bool) | Αντικαθιστά τα περιεχόμενα με ένα αρχείο. Δεν χρειάζεται να κληθεί η μέθοδος UpdateModifiedContent μετά. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Αντικαθιστά τα περιεχόμενα με ένα αρχείο. Δεν χρειάζεται να κληθεί η μέθοδος UpdateModifiedContent μετά. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_4)(string, ResolutionSetting, bool) | Αντικαθιστά τα περιεχόμενα με ένα αρχείο. Δεν χρειάζεται να κληθεί η μέθοδος UpdateModifiedContent μετά. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Αλλάζει το πλάτος αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Αλλάζει το πλάτος αναλογικά. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στο καθορισμένο ρεύμα. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Αποθηκεύει τα 32-bit ARGB pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Αποθηκεύει τα pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Αποθηκεύει τα pixel. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Αποθηκεύει τα pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Αποθηκεύει τα ακατέργαστα δεδομένα. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ορίζει ένα 32-bit ARGB pixel εικόνας για τη συγκεκριμένη θέση. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα της εικόνας. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ορίζει το pixel της εικόνας για τη συγκεκριμένη θέση. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Ορίζει την ανάλυση για αυτή τη [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Δημιουργεί ένα ρηχό αντίγραφο του τρέχοντος Layer. Παρακαλώ [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) για εξήγηση. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Μετατρέπει την raster εικόνα σε bitmap. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Ενημερώνει την προσωρινή μνήμη εικόνας του επιπέδου smart object με το τροποποιημένο περιεχόμενο. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των ενσωματωμένων Smart objects.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Αυτό το παράδειγμα δείχνει πώς να αλλάξετε το επίπεδο smart object στο αρχείο PSD και να εξάγετε / ενημερώσετε τα αρχικά ενσωματωμένα περιεχόμενα του smart object.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Ας εξάγουμε την ενσωματωμένη εικόνα smart object από το επίπεδο smart object του PSD
        smartObjectLayer.ExportContents(exportPath);

        // Ας ελέγξουμε αν η αρχική εικόνα αποθηκεύτηκε σωστά
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Ας αντιστρέψουμε την αρχική εικόνα smart object
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Ας αντικαταστήσουμε την ενσωματωμένη εικόνα smart object στο επίπεδο PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Ας ελέγξουμε αν η ενημερωμένη εικόνα αποθηκεύτηκε σωστά
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Δείτε επίσης

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../)


