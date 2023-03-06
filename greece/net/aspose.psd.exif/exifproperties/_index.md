---
title: Enum ExifProperties
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Exif.ExifProperties αρίθμηση. Λίστα ετικετών Exif
type: docs
weight: 1000
url: /el/net/aspose.psd.exif/exifproperties/
---
## ExifProperties enumeration

Λίστα ετικετών Exif

```csharp
public enum ExifProperties : ushort
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| ImageWidth | `256` | Ο αριθμός των στηλών δεδομένων εικόνας, ίσος με τον αριθμό των pixel ανά σειρά. |
| ImageLength | `257` | Ο αριθμός των σειρών δεδομένων εικόνας. |
| BitsPerSample | `258` | Ο αριθμός των bit ανά στοιχείο εικόνας. Σε αυτό το πρότυπο, κάθε στοιχείο της εικόνας είναι 8 bit, επομένως η τιμή για αυτήν την ετικέτα είναι 8. |
| Compression | `259` | Το σχήμα συμπίεσης που χρησιμοποιείται για τα δεδομένα εικόνας. Όταν μια κύρια εικόνα είναι συμπιεσμένη JPEG, αυτή η ονομασία δεν είναι απαραίτητη και παραλείπεται. |
| PhotometricInterpretation | `262` | Η σύνθεση pixel. |
| ImageDescription | `270` | Μια συμβολοσειρά χαρακτήρων που δίνει τον τίτλο της εικόνας. Μπορεί να είναι ένα σχόλιο όπως "1988 εταιρικό πικνίκ" ή κάτι παρόμοιο. |
| Make | `271` | Ο κατασκευαστής της συσκευής ελέγχου. Αυτός είναι ο κατασκευαστής του DSC, του σαρωτή, του ψηφιοποιητή βίντεο ή άλλου εξοπλισμού που δημιούργησε την εικόνα. Όταν το πεδίο μείνει κενό, αντιμετωπίζεται ως άγνωστο. |
| Model | `272` | Το όνομα του μοντέλου ή ο αριθμός μοντέλου του εξοπλισμού. Αυτό είναι το όνομα ή ο αριθμός μοντέλου του DSC, του σαρωτή, του ψηφιοποιητή βίντεο ή άλλου εξοπλισμού που δημιούργησε την εικόνα. Όταν το πεδίο μείνει κενό, αντιμετωπίζεται ως άγνωστο. |
| Orientation | `274` | Ο προσανατολισμός της εικόνας που προβάλλεται σε γραμμές και στήλες. |
| SamplesPerPixel | `277` | Ο αριθμός των στοιχείων ανά pixel. Εφόσον αυτό το πρότυπο ισχύει για εικόνες RGB και YCbCr, η τιμή που έχει οριστεί για αυτήν την ετικέτα είναι 3. |
| XResolution | `282` | Ο αριθμός των pixel ανά Μονάδα Ανάλυσης στην κατεύθυνση ImageWidth. Όταν η ανάλυση της εικόνας είναι άγνωστη, ορίζεται 72 [dpi]. |
| YResolution | `283` | Ο αριθμός των pixel ανά Μονάδα Ανάλυσης στην κατεύθυνση ImageLength. Η ίδια τιμή με το XResolution ορίζεται. |
| PlanarConfiguration | `284` | Υποδεικνύει εάν τα στοιχεία pixel έχουν εγγραφεί σε ογκώδη ή επίπεδη μορφή. Εάν αυτό το πεδίο δεν υπάρχει, η προεπιλογή TIFF του 1 (χοντρό) θεωρείται. |
| ResolutionUnit | `296` | Η μονάδα μέτρησης XResolution και YResolution. Η ίδια μονάδα χρησιμοποιείται τόσο για το XResolution όσο και για το YResolution. Εάν η ανάλυση της εικόνας είναι άγνωστη, ορίζονται 2 (ίντσες). |
| TransferFunction | `301` | Μια συνάρτηση μεταφοράς για την εικόνα, που περιγράφεται σε στυλ πίνακα. Κανονικά αυτή η ετικέτα δεν είναι απαραίτητη, αφού ο χρωματικός χώρος καθορίζεται στην ετικέτα πληροφοριών χρωματικού χώρου ColorSpace. |
| Software | `305` | Αυτή η ετικέτα καταγράφει το όνομα και την έκδοση του λογισμικού ή του υλικολογισμικού της κάμερας ή της συσκευής εισαγωγής εικόνας που χρησιμοποιείται για τη δημιουργία της εικόνας. Η λεπτομερής μορφή δεν καθορίζεται, αλλά συνιστάται να ακολουθήσετε το παράδειγμα που φαίνεται παρακάτω. Όταν το πεδίο μείνει κενό, αντιμετωπίζεται ως άγνωστο. |
| DateTime | `306` | Η ημερομηνία και η ώρα δημιουργίας της εικόνας. Στο πρότυπο Exif, είναι η ημερομηνία και η ώρα που άλλαξε το αρχείο. |
| Artist | `315` | Αυτή η ετικέτα καταγράφει το όνομα του κατόχου της κάμερας, του φωτογράφου ή του δημιουργού εικόνας. Η λεπτομερής μορφή δεν προσδιορίζεται, αλλά συνιστάται οι πληροφορίες να γράφονται όπως στο παρακάτω παράδειγμα για ευκολία διαλειτουργικότητας. Όταν το πεδίο μείνει κενό, αντιμετωπίζεται ως άγνωστο. Π.χ.) "Κάτοχος κάμερας, John Smith; Φωτογράφος, Michael Brown; Δημιουργός εικόνας, Ken James" |
| WhitePoint | `318` | Η χρωματικότητα του λευκού σημείου της εικόνας. Κανονικά αυτή η ετικέτα δεν είναι απαραίτητη, καθώς ο χρωματικός χώρος καθορίζεται στην ετικέτα ColorSpace πληροφοριών χρωματικού χώρου. |
| PrimaryChromaticities | `319` | Η χρωματικότητα των τριών βασικών χρωμάτων της εικόνας. Κανονικά αυτή η ετικέτα δεν είναι απαραίτητη, καθώς το Colorspace καθορίζεται στην ετικέτα ColorSpace πληροφοριών χώρου χρωμάτων. |
| YCbCrCoefficients | `529` | Οι συντελεστές μήτρας για μετατροπή από δεδομένα εικόνας RGB σε YCbCr. |
| YCbCrSubSampling | `530` | Η αναλογία δειγματοληψίας των στοιχείων χρωματισμού σε σχέση με τη συνιστώσα φωτεινότητας. |
| YCbCrPositioning | `531` | Η θέση των στοιχείων χρωματισμού σε σχέση με το στοιχείο φωτεινότητας . Αυτό το πεδίο ορίζεται μόνο για συμπιεσμένα δεδομένα JPEG ή μη συμπιεσμένα δεδομένα YCbCr. Η προεπιλογή TIFF είναι 1 (στο κέντρο). αλλά όταν Y:Cb:Cr = 4:2:2, συνιστάται σε αυτό το πρότυπο να χρησιμοποιούνται 2 (co-sited) για εγγραφή δεδομένων, προκειμένου να βελτιωθεί η ποιότητα της εικόνας κατά την προβολή σε συστήματα τηλεόρασης. Όταν αυτό το πεδίο δεν υπάρχει, ο αναγνώστης θα υποθέσει την προεπιλογή TIFF. Στην περίπτωση Y:Cb:Cr = 4:2:0, συνιστάται η προεπιλογή TIFF (στο κέντρο). Εάν το reader δεν έχει τη δυνατότητα να υποστηρίζει και τα δύο είδη YCbCrPositioning, θα ακολουθεί την προεπιλογή TIFF ανεξάρτητα από της τιμής σε αυτό το πεδίο. Είναι προτιμότερο οι αναγνώστες " να μπορούν να υποστηρίζουν την κεντραρισμένη και συντοποθετημένη τοποθέτηση. |
| ReferenceBlackWhite | `532` | Η τιμή αναφοράς μαύρου σημείου και τιμή αναφοράς λευκού σημείου . Δεν δίνονται προεπιλογές στο TIFF, αλλά οι παρακάτω τιμές δίνονται ως προεπιλογές εδώ. Ο χρωματικός χώρος δηλώνεται σε μια ετικέτα πληροφοριών χρωματικού χώρου, με την τιμή default να είναι η τιμή που δίνει τα βέλτιστα χαρακτηριστικά εικόνας Διαλειτουργικότητα αυτές οι συνθήκες |
| Copyright | `33432` | Πληροφορίες πνευματικών δικαιωμάτων. Σε αυτό το πρότυπο, η ετικέτα χρησιμοποιείται για να υποδείξει τα πνευματικά δικαιώματα τόσο του φωτογράφου όσο και του συντάκτη . Είναι η ειδοποίηση πνευματικών δικαιωμάτων του ατόμου ή του οργανισμού που διεκδικεί δικαιώματα στην εικόνα. Η δήλωση Διαλειτουργικότητας copyright , συμπεριλαμβανομένης της ημερομηνίας και των δικαιωμάτων, θα πρέπει να γραφτεί σε αυτό το πεδίο . π.χ. "Πνευματικά δικαιώματα, John Smith, 19xx. Με επιφύλαξη παντός δικαιώματος .". Σε αυτό το πρότυπο το πεδίο καταγράφει και τα πνευματικά δικαιώματα του φωτογράφου και του συντάκτη , με το καθένα να καταγράφεται σε ένα ξεχωριστό μέρος της δήλωσης. Όταν υπάρχει σαφής διάκριση μεταξύ των πνευματικών δικαιωμάτων φωτογράφου και συντάκτη, αυτά πρέπει να είναι γραμμένα με τη σειρά του φωτογράφου ακολουθούμενα από πνευματικά δικαιώματα του συντάκτη, διαχωρισμένα με NULL (σε αυτήν την περίπτωση, εφόσον η δήλωση τελειώνει επίσης με a NULL, υπάρχουν δύο NULL κωδικοί ). Όταν δίνεται μόνο το πνευματικό δικαίωμα του φωτογράφου , αυτό τερματίζεται με έναν κωδικό NULL. Όταν δίνεται μόνο τα πνευματικά δικαιώματα του συντάκτη, το τμήμα πνευματικών δικαιωμάτων φωτογράφου part αποτελείται από ένα κενό που ακολουθείται από έναν τερματικό κωδικό NULL, τότε δίνονται τα πνευματικά δικαιώματα του συντάκτη. Όταν το πεδίο μείνει κενό, αντιμετωπίζεται ως άγνωστο. |
| ExposureTime | `33434` | Χρόνος έκθεσης, σε δευτερόλεπτα. |
| FNumber | `33437` | Ο αριθμός F. |
| ExposureProgram | `34850` | Η κλάση του προγράμματος που χρησιμοποιείται από την κάμερα για να ρυθμίσει την έκθεση κατά τη λήψη της φωτογραφίας. |
| SpectralSensitivity | `34852` | Υποδεικνύει τη φασματική ευαισθησία κάθε καναλιού της κάμερας που χρησιμοποιείται. |
| PhotographicSensitivity | `34855` | Υποδεικνύει την ταχύτητα ISO και το γεωγραφικό πλάτος ISO της κάμερας ή της συσκευής εισόδου όπως ορίζεται στο ISO 12232. |
| OECF | `34856` | Υποδεικνύει τη Λειτουργία Οπτικοηλεκτρικής Μετατροπής (OECF) που καθορίζεται στο ISO 14524. |
| ExifVersion | `36864` | Η έκδοση exif. |
| DateTimeOriginal | `36867` | Η ημερομηνία και η ώρα που δημιουργήθηκαν τα αρχικά δεδομένα εικόνας. |
| DateTimeDigitized | `36868` | Η ημερομηνία ψηφιοποιήθηκε η ώρα. |
| ComponentsConfiguration | `37121` | Η διαμόρφωση των στοιχείων. |
| CompressedBitsPerPixel | `37122` | Ειδικά για συμπιεσμένα δεδομένα. δηλώνει τα συμπιεσμένα bit ανά pixel. |
| ShutterSpeedValue | `37377` | Η τιμή της ταχύτητας κλείστρου. |
| ApertureValue | `37378` | Η τιμή του διαφράγματος του φακού. |
| BrightnessValue | `37379` | Η τιμή φωτεινότητας. |
| ExposureBiasValue | `37380` | Η τιμή μεροληψίας έκθεσης. |
| MaxApertureValue | `37381` | Η μέγιστη τιμή διαφράγματος. |
| SubjectDistance | `37382` | Η απόσταση από το θέμα, δίνεται σε μέτρα. |
| MeteringMode | `37383` | Η λειτουργία μέτρησης. |
| LightSource | `37384` | Η ευγενική πηγή φωτός. |
| Flash | `37385` | Υποδεικνύει την κατάσταση του φλας κατά τη λήψη της εικόνας. |
| FocalLength | `37386` | Η πραγματική εστιακή απόσταση του φακού, σε mm. |
| SubjectArea | `37396` | Αυτή η ετικέτα υποδεικνύει τη θέση και την περιοχή του κύριου θέματος στη συνολική σκηνή. |
| MakerNote | `37500` | Μια ετικέτα για τους κατασκευαστές εγγραφών Exif για την καταγραφή οποιασδήποτε επιθυμητής πληροφορίας. Τα περιεχόμενα εναπόκεινται στον κατασκευαστή, αλλά αυτή η ετικέτα δεν πρέπει να χρησιμοποιείται για άλλον σκοπό εκτός από τον προορισμό της. |
| UserComment | `37510` | Μια ετικέτα για τους χρήστες του Exif για να γράφουν λέξεις-κλειδιά ή σχόλια στην εικόνα εκτός από αυτές στο ImageDescription και χωρίς τους περιορισμούς κωδικών χαρακτήρων της ετικέτας ImageDescription. |
| SubsecTime | `37520` | Μια ετικέτα που χρησιμοποιείται για την εγγραφή κλασμάτων δευτερολέπτων για την ετικέτα DateTime. |
| SubsecTimeOriginal | `37521` | Μια ετικέτα που χρησιμοποιείται για την καταγραφή κλασμάτων δευτερολέπτων για την ετικέτα DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Μια ετικέτα που χρησιμοποιείται για την καταγραφή κλασμάτων δευτερολέπτων για την ετικέτα DateTimeDigitized. |
| FlashpixVersion | `40960` | Η έκδοση μορφής Flashpix που υποστηρίζεται από ένα αρχείο FPXR. |
| ColorSpace | `40961` | Η ετικέτα πληροφοριών χρωματικού χώρου (ColorSpace) καταγράφεται πάντα ως προσδιοριστής χρωματικού χώρου. |
| RelatedSoundFile | `40964` | Το σχετικό αρχείο ήχου. |
| FlashEnergy | `41483` | Υποδεικνύει την ενέργεια στροβοσκοπίου τη στιγμή που λαμβάνεται η εικόνα, όπως μετράται σε Δευτερόλεπτα ισχύος κεριού δέσμης (BCPS). |
| SpatialFrequencyResponse | `41484` | Αυτή η ετικέτα καταγράφει τον πίνακα χωρικών συχνοτήτων της κάμερας ή της συσκευής εισόδου και τις τιμές SFR προς την κατεύθυνση του πλάτους της εικόνας, του ύψους της εικόνας και της διαγώνιας κατεύθυνσης, όπως ορίζεται στο ISO 12233. |
| FocalPlaneXResolution | `41486` | Υποδεικνύει τον αριθμό των pixel στην κατεύθυνση του πλάτους της εικόνας (X) ανά FocalPlaneResolutionUnit στο εστιακό επίπεδο της κάμερας. |
| FocalPlaneYResolution | `41487` | Υποδεικνύει τον αριθμό των pixel στην κατεύθυνση του ύψους της εικόνας (Y) ανά FocalPlaneResolutionUnit στο εστιακό επίπεδο της κάμερας. |
| FocalPlaneResolutionUnit | `41488` | Υποδεικνύει τη μονάδα μέτρησης FocalPlaneXResolution και FocalPlaneYResolution. Αυτή η τιμή είναι ίδια με το ResolutionUnit. |
| SubjectLocation | `41492` | Υποδεικνύει τη θέση του κύριου θέματος στη σκηνή. Η τιμή αυτής της ετικέτας αντιπροσωπεύει το εικονοστοιχείο στο κέντρο του κύριου θέματος σε σχέση με την αριστερή άκρη, πριν από την επεξεργασία περιστροφής σύμφωνα με την ετικέτα περιστροφής. |
| ExposureIndex | `41493` | Υποδεικνύει τον δείκτη έκθεσης που επιλέχθηκε στην κάμερα ή στη συσκευή εισόδου τη στιγμή που λαμβάνεται η εικόνα. |
| SensingMethod | `41495` | Υποδεικνύει τον τύπο του αισθητήρα εικόνας στην κάμερα ή στη συσκευή εισόδου. |
| FileSource | `41728` | Η πηγή του αρχείου. |
| SceneType | `41729` | Υποδεικνύει τον τύπο της σκηνής. Εάν ένα DSC κατέγραψε την εικόνα, αυτή η τιμή ετικέτας θα ορίζεται πάντα σε 1, υποδεικνύοντας ότι η εικόνα φωτογραφήθηκε απευθείας. |
| CFAPattern | `41730` | Υποδεικνύει το γεωμετρικό μοτίβο της συστοιχίας φίλτρου χρώματος (CFA) του αισθητήρα εικόνας όταν χρησιμοποιείται ένας αισθητήρας χρωματικής περιοχής ενός τσιπ. Δεν ισχύει για όλες τις μεθόδους ανίχνευσης. |
| CustomRendered | `41985` | Αυτή η ετικέτα υποδεικνύει τη χρήση ειδικής επεξεργασίας σε δεδομένα εικόνας, όπως η απόδοση προσαρμοσμένη στην έξοδο. Όταν εκτελείται ειδική επεξεργασία, ο αναγνώστης αναμένεται να απενεργοποιήσει ή να ελαχιστοποιήσει οποιαδήποτε περαιτέρω επεξεργασία. |
| ExposureMode | `41986` | Αυτή η ετικέτα υποδεικνύει τη λειτουργία έκθεσης που ορίστηκε κατά τη λήψη της εικόνας. Στη λειτουργία αυτόματης συγκράτησης, η κάμερα τραβάει μια σειρά καρέ της ίδιας σκηνής σε διαφορετικές ρυθμίσεις έκθεσης. |
| WhiteBalance | `41987` | Αυτή η ετικέτα υποδεικνύει τη λειτουργία ισορροπίας λευκού που ορίστηκε κατά τη λήψη της εικόνας. |
| DigitalZoomRatio | `41988` | Αυτή η ετικέτα υποδεικνύει την αναλογία ψηφιακού ζουμ κατά τη λήψη της εικόνας. Εάν ο αριθμητής της καταγεγραμμένης τιμής είναι 0, αυτό σημαίνει ότι δεν χρησιμοποιήθηκε ψηφιακό ζουμ. |
| FocalLengthIn35MmFilm | `41989` | Αυτή η ετικέτα υποδεικνύει την ισοδύναμη εστιακή απόσταση, υποθέτοντας μια κάμερα φιλμ 35 mm, σε mm. Η τιμή 0 σημαίνει ότι η εστιακή απόσταση είναι άγνωστη. Σημειώστε ότι αυτή η ετικέτα διαφέρει από την ετικέτα FocalLength. |
| SceneCaptureType | `41990` | Αυτή η ετικέτα υποδεικνύει τον τύπο της σκηνής που γυρίστηκε. Μπορεί επίσης να χρησιμοποιηθεί για την εγγραφή της λειτουργίας με την οποία τραβήχτηκε η εικόνα. |
| GainControl | `41991` | Αυτή η ετικέτα υποδεικνύει τον βαθμό προσαρμογής της συνολικής απολαβής εικόνας. |
| Contrast | `41992` | Αυτή η ετικέτα υποδεικνύει την κατεύθυνση της επεξεργασίας αντίθεσης που εφαρμόζεται από την κάμερα κατά τη λήψη της εικόνας. |
| Saturation | `41993` | Αυτή η ετικέτα υποδεικνύει την κατεύθυνση της επεξεργασίας κορεσμού που εφαρμόζεται από την κάμερα κατά τη λήψη της εικόνας. |
| Sharpness | `41994` | Αυτή η ετικέτα υποδεικνύει την κατεύθυνση επεξεργασίας ευκρίνειας που εφαρμόζεται από την κάμερα κατά τη λήψη της εικόνας |
| DeviceSettingDescription | `41995` | Αυτή η ετικέτα υποδεικνύει πληροφορίες σχετικά με τις συνθήκες λήψης φωτογραφιών ενός συγκεκριμένου μοντέλου κάμερας. Η ετικέτα χρησιμοποιείται μόνο για να υποδεικνύει τις συνθήκες λήψης φωτογραφιών στον αναγνώστη. |
| SubjectDistanceRange | `41996` | Αυτή η ετικέτα υποδεικνύει την απόσταση από το θέμα. |
| ImageUniqueID | `42016` | Μοναδικό αναγνωριστικό της εικόνας. |
| GPSVersionID | `0` | Υποδεικνύει την έκδοση του GPSInfoIFD. |
| GPSLatitudeRef | `1` | Υποδεικνύει εάν το γεωγραφικό πλάτος είναι βόρειο ή νότιο γεωγραφικό πλάτος. |
| GPSLatitude | `2` | Υποδεικνύει το γεωγραφικό πλάτος. Το γεωγραφικό πλάτος εκφράζεται ως τρεις ΟΡΘΙΚΕΣ τιμές δίνοντας τις μοίρες, τα λεπτά και δευτερόλεπτα, αντίστοιχα. Εάν το γεωγραφικό πλάτος εκφράζεται ως μοίρες, λεπτά και δευτερόλεπτα, μια τυπική μορφή θα ήταν dd/1,mm/1,ss/1. Όταν χρησιμοποιούνται μοίρες και λεπτά και, για παράδειγμα, δίνονται κλάσματα λεπτών έως δύο δεκαδικά ψηφία, η μορφή θα είναι dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Υποδεικνύει εάν το γεωγραφικό μήκος είναι ανατολικό ή δυτικό γεωγραφικό μήκος. |
| GPSLongitude | `4` | Υποδεικνύει το γεωγραφικό μήκος. Το γεωγραφικό μήκος εκφράζεται ως τρεις ΛΟΓΙΚΕΣ τιμές δίνοντας τις μοίρες, τα λεπτά και δευτερόλεπτα, αντίστοιχα. Εάν το γεωγραφικό μήκος εκφράζεται ως μοίρες, λεπτά και δευτερόλεπτα, μια τυπική μορφή θα ήταν ddd/1,mm/1,ss/1. Όταν χρησιμοποιούνται μοίρες και λεπτά και, για παράδειγμα, δίνονται κλάσματα λεπτών έως δύο δεκαδικά ψηφία, η μορφή θα είναι ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Υποδεικνύει το υψόμετρο που χρησιμοποιείται ως υψόμετρο αναφοράς. Εάν η αναφορά είναι η στάθμη της θάλασσας και το υψόμετρο είναι πάνω από την επιφάνεια της θάλασσας, δίνεται 0. Εάν το υψόμετρο είναι κάτω από την επιφάνεια της θάλασσας, δίνεται η τιμή 1 και το υψόμετρο υποδεικνύεται ως απόλυτη τιμή σε την ετικέτα GPSAltitude. |
| GPSAltitude | `6` | Υποδεικνύει το υψόμετρο με βάση την αναφορά στο GPSAltitudeRef. Το υψόμετρο εκφράζεται ως μία RATIONAL τιμή. Η μονάδα αναφοράς είναι μέτρα. |
| GPSTimestamp | `7` | Υποδεικνύει την ώρα ως UTC (Συντονισμένη Παγκόσμια Ώρα). Η χρονική σήμανση εκφράζεται ως τρεις ΛΟΓΙΚΕΣ τιμές δίνοντας την ώρα, το λεπτό και το δευτερόλεπτο. |
| GPSSatellites | `8` | Υποδεικνύει τους δορυφόρους GPS που χρησιμοποιούνται για μετρήσεις. Αυτή η ετικέτα μπορεί να χρησιμοποιηθεί για να περιγράψει τον αριθμό των δορυφόρων, τον αριθμό ID τους, τη γωνία ανύψωσης, το αζιμούθιο, το SNR και άλλες πληροφορίες σε συμβολισμό ASCII. Η μορφή δεν έχει καθοριστεί . Εάν ο δέκτης GPS δεν μπορεί να πραγματοποιήσει μετρήσεις, η τιμή της ετικέτας θα οριστεί σε NULL. |
| GPSStatus | `9` | Υποδεικνύει την κατάσταση του δέκτη GPS κατά την εγγραφή της εικόνας. |
| GPSMeasureMode | `10` | Υποδεικνύει τη λειτουργία μέτρησης GPS. - 2- ή 3- διαστάσεων. |
| GPSDOP | `11` | Υποδεικνύει το GPS DOP (βαθμός ακρίβειας δεδομένων). Μια τιμή HDOP γράφεται κατά τη δισδιάστατη μέτρηση, και PDOP κατά τη διάρκεια της τρισδιάστατης μέτρησης. |
| GPSSpeedRef | `12` | Υποδεικνύει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS. Το 'K' 'M' και το 'N' αντιπροσωπεύουν χιλιόμετρα ανά ώρα, μίλια ανά ώρα και κόμβους. |
| GPSSpeed | `13` | Υποδεικνύει την ταχύτητα κίνησης του δέκτη GPS. |
| GPSTrackRef | `14` | Υποδεικνύει την αναφορά για την κατεύθυνση της κίνησης του δέκτη GPS. Το 'T' δηλώνει την αληθινή κατεύθυνση και το 'M' είναι μαγνητική κατεύθυνση. |
| GPSTrack | `15` | Υποδεικνύει την κατεύθυνση κίνησης του δέκτη GPS. Το εύρος τιμών είναι από 0,00 έως 359,99. |
| GPSImgDirectionRef | `16` | Υποδεικνύει την αναφορά για την κατεύθυνση της εικόνας κατά τη λήψη της. Το 'T' δηλώνει την αληθινή κατεύθυνση και το 'M' είναι μαγνητική κατεύθυνση. |
| GPSImgDirection | `17` | Υποδεικνύει την κατεύθυνση της εικόνας όταν τραβήχτηκε. Το εύρος τιμών είναι από 0,00 έως 359,99. |
| GPSMapDatum | `18` | Υποδεικνύει τα δεδομένα γεωδαιτικής έρευνας που χρησιμοποιούνται από τον δέκτη GPS. |
| GPSDestLatitudeRef | `19` | Υποδεικνύει εάν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο γεωγραφικό πλάτος. Η τιμή ASCII 'N' υποδεικνύει βόρεια γεωγραφικό πλάτος και το 'S' είναι νότιο γεωγραφικό πλάτος. |
| GPSDestLatitude | `20` | Υποδεικνύει το γεωγραφικό πλάτος του σημείου προορισμού. Το γεωγραφικό πλάτος εκφράζεται ως τρεις ΟΡΘΙΚΕΣ τιμές που δίνουν τις μοίρες, λεπτά και δευτερόλεπτα, αντίστοιχα. Εάν το γεωγραφικό πλάτος εκφράζεται ως μοίρες, λεπτά και δευτερόλεπτα, μια τυπική μορφή θα είναι dd/1,mm/1,ss/1. Όταν χρησιμοποιούνται μοίρες και λεπτά και, για παράδειγμα, τα κλάσματα των λεπτών δίνονται έως δύο δεκαδικά ψηφία, η μορφή θα είναι dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Υποδεικνύει εάν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό γεωγραφικό μήκος. Το ASCII 'E' δείχνει ανατολικό γεωγραφικό μήκος, και το 'W' είναι δυτικό γεωγραφικό μήκος. |
| GPSDestLongitude | `22` | Υποδεικνύει το γεωγραφικό μήκος του σημείου προορισμού. Το γεωγραφικό μήκος εκφράζεται ως τρεις ΛΟΓΙΚΕΣ τιμές που δίνουν τις μοίρες, λεπτά και δευτερόλεπτα, αντίστοιχα. Εάν το γεωγραφικό μήκος εκφράζεται ως μοίρες, λεπτά και δευτερόλεπτα, μια τυπική μορφή θα είναι ddd/1,mm/1,ss/1. Όταν χρησιμοποιούνται μοίρες και λεπτά και, για παράδειγμα, τα κλάσματα των λεπτών δίνονται έως δύο δεκαδικά ψηφία, η μορφή θα είναι ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Υποδεικνύει την αναφορά που χρησιμοποιείται για τη μεταφορά του ρουλεμάν στο σημείο προορισμού. Το 'T' δηλώνει την αληθινή κατεύθυνση και το 'M' είναι μαγνητική κατεύθυνση. |
| GPSDestBearing | `24` | Υποδεικνύει το ρουλεμάν στο σημείο προορισμού. Το εύρος τιμών είναι από 0,00 έως 359,99. |
| GPSDestDistanceRef | `25` | Υποδεικνύει τη μονάδα που χρησιμοποιείται για να εκφράσει την απόσταση από το σημείο προορισμού. Τα 'K', 'M' και 'N' αντιπροσωπεύουν χιλιόμετρα, μίλια και κόμβους. |
| GPSDestDistance | `26` | Υποδεικνύει την απόσταση από το σημείο προορισμού. |
| GPSProcessingMethod | `27` | Μια συμβολοσειρά χαρακτήρων που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για την εύρεση θέσης. Το πρώτο byte υποδεικνύει τον κωδικό χαρακτήρα που χρησιμοποιείται και ακολουθείται από το όνομα της μεθόδου. |
| GPSAreaInformation | `28` | Μια συμβολοσειρά χαρακτήρων που καταγράφει το όνομα της περιοχής GPS. Το πρώτο byte υποδεικνύει τον κωδικό χαρακτήρων που χρησιμοποιείται, και αυτό ακολουθείται από το όνομα της περιοχής GPS. |
| GPSDateStamp | `29` | Μια συμβολοσειρά χαρακτήρων που καταγράφει πληροφορίες ημερομηνίας και ώρας σε σχέση με το UTC (Συντονισμένη Παγκόσμια Ώρα). Η μορφή είναι ΕΕΕΕ:ΜΜ:ΗΗ. |
| GPSDifferential | `30` | Υποδεικνύει εάν εφαρμόζεται διόρθωση διαφορικού στον δέκτη GPS. |
| StripOffsets | `273` | Για κάθε λωρίδα, η μετατόπιση byte αυτής της λωρίδας. Συνιστάται να επιλεγεί έτσι ώστε ο αριθμός των byte strip να μην υπερβαίνει τα 64 Kbyte. Aux tag. |
| JPEGInterchangeFormat | `513` | Η μετατόπιση στο αρχικό byte (SOI) των συμπιεσμένων δεδομένων μικρογραφιών JPEG. Αυτό δεν χρησιμοποιείται για δεδομένα JPEG κύριας εικόνας. |
| JPEGInterchangeFormatLength | `514` | Ο αριθμός των byte συμπιεσμένων δεδομένων μικρογραφιών JPEG. Αυτό δεν χρησιμοποιείται για δεδομένα JPEG κύριας εικόνας. Οι μικρογραφίες JPEG δεν χωρίζονται αλλά καταγράφονται ως συνεχής ροή bit JPEG από το SOI στο EOI. Οι δείκτες Appn και COM δεν πρέπει να καταγράφονται. Οι συμπιεσμένες μικρογραφίες πρέπει να εγγράφονται σε όχι περισσότερα από 64 Kbyte, συμπεριλαμβανομένων όλων των άλλων δεδομένων που θα εγγραφούν στο APP1. |
| ExifIfdPointer | `34665` | Ένας δείκτης στο Exif IFD. Διαλειτουργικότητα, το Exif IFD έχει την ίδια δομή με αυτή του IFD που καθορίζεται στο TIFF. συνήθως, ωστόσο, δεν περιέχει δεδομένα εικόνας όπως στην περίπτωση του TIFF. |
| GPSIfdPointer | `34853` | Ο δείκτης gps ifd. |
| RowsPerStrip | `278` | Ο αριθμός των σειρών ανά λωρίδα. Αυτός είναι ο αριθμός των σειρών στην εικόνα μιας λωρίδας όταν μια εικόνα χωρίζεται σε λωρίδες. |
| StripByteCounts | `279` | Ο συνολικός αριθμός byte σε κάθε λωρίδα. |
| PixelXDimension | `40962` | Πληροφορίες ειδικά για συμπιεσμένα δεδομένα. Όταν εγγράφεται ένα συμπιεσμένο αρχείο, το έγκυρο πλάτος της εικόνας με νόημα θα καταγράφεται σε αυτήν την ετικέτα, ανεξάρτητα από το αν υπάρχουν δεδομένα συμπλήρωσης ή δείκτης επανεκκίνησης. |
| PixelYDimension | `40963` | Πληροφορίες ειδικά για συμπιεσμένα δεδομένα. Όταν εγγράφεται ένα συμπιεσμένο αρχείο, το έγκυρο ύψος της εικόνας με νόημα θα καταγράφεται σε αυτήν την ετικέτα |
| Gamma | `42240` | Τιμή γάμμα |
| SensitivityType | `34864` | Τύπος φωτογραφικής ευαισθησίας |
| StandardOutputSensitivity | `34865` | Υποδεικνύει τυπική ευαισθησία εξόδου της κάμερας |
| RecommendedExposureIndex | `34866` | Υποδεικνύει συνιστώμενο δείκτη έκθεσης |
| ISOSpeed | `34867` | Πληροφορίες σχετικά με την τιμή ταχύτητας iso όπως ορίζεται στο ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Αυτή η ετικέτα υποδεικνύει την τιμή γεωγραφικού πλάτους ταχύτητας ISO εεε όπως ορίζεται στο ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Αυτή η ετικέτα υποδεικνύει την τιμή zzz γεωγραφικού πλάτους ταχύτητας ISO όπως ορίζεται στο ISO 12232 |
| CameraOwnerName | `42032` | Περιέχει όνομα κατόχου κάμερας |
| BodySerialNumber | `42033` | Περιέχει σειριακό αριθμό σώματος κάμερας |
| LensMake | `42035` | Αυτή η ετικέτα καταγράφει κατασκευαστή φακού |
| LensModel | `42036` | Αυτή η ετικέτα καταγράφει το όνομα και τον αριθμό μοντέλου του φακού |
| LensSerialNumber | `42037` | Αυτή η ετικέτα καταγράφει τον σειριακό αριθμό του εναλλάξιμου φακού |
| LensSpecification | `42034` | Αυτή η ετικέτα σημειώνει ελάχιστη εστιακή απόσταση, μέγιστη εστιακή απόσταση, ελάχιστο αριθμό F στην ελάχιστη εστιακή απόσταση και ελάχιστο αριθμό F στη μέγιστη εστιακή απόσταση |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.Exif](../../aspose.psd.exif/)
* συνέλευση [Aspose.PSD](../../)

