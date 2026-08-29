---
title: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ο χώρος ονομάτων περιέχει οντότητες μορφής αρχείου PSD που περιέχονται σε στρώσεις"
type: docs
weight: 300
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/
---
{{< psd/tize >}}
Ο χώρος ονομάτων περιέχει οντότητες μορφής αρχείου PSD που περιέχονται σε στρώματα.

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [AbddResource](./abddresource/) | Τα δεδομένα πληροφοριών του Artboard. |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Βασική κλάση για πόρους στρώσης προσαρμογής |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | Η ενότητα με κινούμενα δεδομένα. |
| [ArtBResource](./artbresource/) | Τα δεδομένα πληροφοριών του Artboard για [`Resources`](../aspose.psd.fileformats.psd.layers/layer/resources/). |
| [ArtDResource](./artdresource/) | Τα δεδομένα πληροφοριών του Artboard για [`GlobalLayerResources`](../aspose.psd.fileformats.psd/psdimage/globallayerresources/). |
| [BaseArtboardInfoResource](./baseartboardinforesource/) | Ο πόρος δεδομένων πληροφοριών του Artboard. |
| [BaseFxResource](./basefxresource/) | Βασικός πόρος εφέ |
| [BaseLayerSectionResource](./baselayersectionresource/) | Βασική κλάση για πόρους ενότητας στρώσης |
| [BlncResource](./blncresource/) | Η κλάση BlncResource είναι πόρος της στρώσης προσαρμογής χρώματος. |
| [BlwhResource](./blwhresource/) | Η κλάση BlwhResource είναι πόρος της στρώσης προσαρμογής Μαύρο-Άσπρο. |
| [BooleanResource](./booleanresource/) | Κλάση BooleanResource. Είναι ψευδοπόρος. Το Photoshop δεν το διαθέτει. |
| [BritResource](./britresource/) | Κλάση BritResource. Πόρος της στρώσης προσαρμογής Φωτεινότητας/Αντίθεσης. |
| [CgEdResource](./cgedresource/) | Κλάση CgEdResource. Πρόσθετα δεδομένα δημιουργού περιεχομένου (Photoshop CS5) |
| [ClassID](./classid/) | Το αντικείμενο PSD Class ID. |
| [ClblResource](./clblresource/) | Κλάση ClblResource. Αυτός ο πόρος περιέχει πληροφορίες για την ανάμειξη του κομμένου στοιχείου. |
| [CmlsResource](./cmlsresource/) | Κλάση CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) έχει 6 χρωματικές περιοχές όπου μπορείτε να αλλάξετε τις παραμέτρους HSV. Κάθε περιοχή έχει 4 βασικά σημεία για τον εντοπισμό των ορίων της περιοχής. Και είναι ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Διαχειριστής για τη στρώση προσαρμογής Καμπύλες που χειρίζεται τις καμπύλες. |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Διαχειριστής για τη στρώση προσαρμογής Καμπύλες που χειρίζεται το χάρτη των pixel. |
| [CurvesManager](./curvesmanager/) | Βασική κλάση για τη διαχείριση του CurvResource. |
| [CurvResource](./curvresource/) | Κλάση CurvResource. Πόρος της στρώσης προσαρμογής Καμπύλες 1 byte - 0 αν χρησιμοποιούνται καμπύλες, 1 αν χρησιμοποιούνται pixel στον χάρτη, αν 0 τότε: 2 bytes - short. Η προεπιλογή είναι 1 4 bytes - int. Χρησιμοποιείται μόνο το τελευταίο byte ανά bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια, για παράδειγμα 2 bytes - short αριθμός σημείων 4 bytes * αριθμός σημείων - σημεία της καμπύλης 2 short: πρώτη θέση, δεύτερο ύψος 4 bytes - word "Crv " 2 bytes - short η προεπιλογή είναι 4 για Καμπύλες 4 bytes - int. Η προεπιλογή είναι 1 4 bytes - αριθμός σημείων 4 bytes * αριθμός σημείων - σημεία της καμπύλης 2 short: πρώτη θέση, δεύτερο ύψος 0-4 bytes - Προηγούμενο για τέσσερα αν 1 τότε: 2 bytes - short. Η προεπιλογή είναι 1 4 bytes - int. Χρησιμοποιείται μόνο το τελευταίο byte. Ένα κανάλι είναι σε ένα bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια, για παράδειγμα 256 * αριθμός αλλαγμένων καναλιών - διατεταγμένες τιμές καναλιού στο εύρος 0 - 255 4 bytes - word "Crv " 2 bytes - short. Η προεπιλογή είναι 3 για pixel στον χάρτη 4 bytes - int Αριθμός καναλιών (2 + 256) bytes - short 2 για δείκτη καναλιού, 256 είναι διατεταγμένες τιμές καναλιού στο εύρος 0 - 255 |
| [CustResource](./custresource/) | Κλάση CustResource. Αυτός ο πόρος περιέχει πληροφορίες για την ανάμειξη του κομμένου στοιχείου. |
| [ExpaResource](./exparesource/) | Κλάση ExpaResource. Πόρος του στρώματος ρύθμισης έκθεσης |
| [FillLayerResource](./filllayerresource/) | Βασική κλάση για πόρους στρώματος γεμίσματος. |
| [FilterEffectMaskData](./filtereffectmaskdata/) | Η κλάση δεδομένων μάσκας φίλτρου. |
| [FXidResource](./fxidresource/) | Ο πόρος Filter Effects περιέχει κανάλια, μάσκα χρήστη και μάσκα φύλλου για το έξυπνο φίλτρο. |
| [FxrpResource](./fxrpresource/) | Κλάση FxrpResource. Το σημείο αναφοράς του στρώματος |
| [GdFlResource](./gdflresource/) | Κλάση GdFlResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τη συγχώνευση του περικομμένου στοιχείου. |
| [GrdmResource](./grdmresource/) | Κλάση GrdmResource. Περιέχει πληροφορίες σχετικά με το στρώμα Gradient-Map. |
| [Hue2Resource](./hue2resource/) | Κλάση Hue2Resource. Πόρος του στρώματος ρύθμισης έκθεσης |
| [IfxsResource](./ifxsresource/) | Πόρος Ifxs (πόρος εφέ ομάδας στρώματος) |
| [ImfxResource](./imfxresource/) | Πόρος Imfx (πόρος πολλαπλών εφέ) |
| [InfxResource](./infxresource/) | Κλάση InfxResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τη συγχώνευση του περικομμένου στοιχείου. |
| [IopaResource](./ioparesource/) | Κλάση IopaResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με την ιδιότητα διαφάνειας γεμίσματος από τη φόρμα στυλ στρώματος |
| [KnkoResource](./knkoresource/) | Κλάση KnkoResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τη συγχώνευση του περικομμένου στοιχείου. |
| [LayerSectionResource](./layersectionresource/) | Ο πόρος ενότητας στρώματος. |
| [LclrResource](./lclrresource/) | Κλάση LclrResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το χρώμα του στρώματος στη λίστα στρωμάτων του PS. Είναι μόνο |
| [LevelChannel](./levelchannel/) | Κλάση για εργασία με κανάλια στο στρώμα ρύθμισης επιπέδων |
| [LevlResource](./levlresource/) | Κλάση LevlResource. Πόρος του στρώματος ρύθμισης έκθεσης |
| [Lfx2Resource](./lfx2resource/) | Πόρος Lfx2 (πόρος κανονικών εφέ) |
| [LiFdDataSource](./lifddatasource/) | Ορίζει την κλάση πηγής δεδομένων liFD στο αρχείο PSD που περιέχει πληροφορίες σχετικά με ένα ενσωματωμένο αρχείο. Αυτό αποτελεί μέρος του API Διαχείρισης Μορφής Αρχείου PSD που βοηθά στην τροποποίηση αρχείων Adobe® Photoshop®. |
| [LiFeDataSource](./lifedatasource/) | Ορίζει την κλάση LnkeDataSource που περιέχει πληροφορίες σχετικά με εξωτερικό συνδεδεμένο αρχείο. Αυτό αποτελεί μέρος του API Διαχείρισης Μορφής Αρχείου PSD που βοηθά στην τροποποίηση αρχείων Adobe® Photoshop®. |
| [LinkDataSource](./linkdatasource/) | Ορίζει την κλάση LinkDataSource που περιέχει πληροφορίες σχετικά με ένα συνδεδεμένο αρχείο ή ένα περιουσιακό στοιχείο στο αρχείο PSD. |
| [LinkResource](./linkresource/) | Ορίζει την κλάση LinkResource που περιέχει πληροφορίες σχετικά με συνδεδεμένα ή ενσωματωμένα αρχεία στην εικόνα μορφής PSD. Ο πόρος συνδέσμου μπορεί να περιέχει αρκετές [`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) παρουσίες που μπορούν να προσπελαστούν από δείκτες σε οποιαδήποτε κληρονομημένη κλάση. |
| [LmskResource](./lmskresource/) | Ο πόρος LMsk. |
| [Lnk2Resource](./lnk2resource/) | Ορίζει την κλάση που περιέχει πληροφορίες σχετικά με ενσωματωμένα αρχεία στην εικόνα μορφής PSD. Ο πόρος συνδέσμου μπορεί να περιέχει αρκετές [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) παρουσίες που μπορούν να προσπελαστούν από το δείκτη. |
| [Lnk3Resource](./lnk3resource/) | Ορίζει την κλάση που περιέχει πληροφορίες σχετικά με ένα ενσωματωμένο αρχείο στην εικόνα μορφής PSD 32 bit ανά κανάλι. Ο πόρος συνδέσμου μπορεί να περιέχει αρκετές [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) παρουσίες που μπορούν να προσπελαστούν από το δείκτη. |
| [LnkeResource](./lnkeresource/) | Ορίζει την κλάση LnkeResource που περιέχει πληροφορίες σχετικά με εξωτερικά συνδεδεμένα αρχεία ή πόρους στην εικόνα μορφής PSD. Ο πόρος συνδέσμου μπορεί να περιέχει αρκετές [`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) περιπτώσεις που μπορούν να προσπελαστούν μέσω του δείκτη. Αυτό αποτελεί μέρος του API Διαχείρισης Μορφής Αρχείου PSD που βοηθά στην προγραμματιστική τροποποίηση αρχείων Adobe® Photoshop®. |
| [LnsrResource](./lnsrresource/) | Κλάση lnsrResource. |
| [Lr16Resource](./lr16resource/) | Ο πόρος lr16. |
| [Lr32Resource](./lr32resource/) | Ο πόρος lr32. |
| [LrXxResource](./lrxxresource/) | Ο πόρος lrXX. |
| [LsdkResource](./lsdkresource/) | Ο πόρος στρώσης lsdk (πόρος ενσωματωμένου τμήματος στρώσης). |
| [LspfResource](./lspfresource/) | Ρυθμίσεις προστασίας στρώσης |
| [LuniResource](./luniresource/) | Πόρος ονόματος στρώσης |
| [LyidResource](./lyidresource/) | Κλάση LyidResource. |
| [LyvrResource](./lyvrresource/) | Ο πόρος που αντιπροσωπεύει την έκδοση Photoshop της στρώσης. |
| [MixrResource](./mixrresource/) | Κλάση MixrResource. Πόρος της Channel Mixer Adjustment Layer |
| [MlstResource](./mlstresource/) | Ο πόρος mlst. Αυτή η κλάση, μεταξύ άλλων, περιέχει πληροφορίες σχετικά με τη θέση της στρώσης στην χρονογραμμή. |
| [NvrtResource](./nvrtresource/) | Κλάση NvrtResource. Πόρος της Invert Adjustment Layer. |
| [OSTypeStructure](./ostypestructure/) | Αντιπροσωπεύει τη δομή τύπου OS. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Αντιπροσωπεύει το μητρώο πόρων [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [PathShape](./pathshape/) | Το σχήμα από τους κόμβους της καμπύλης Bezier. |
| [PattResource](./pattresource/) | Κλάση PattResource. Πόρος με δεδομένα μοτίβου |
| [PattResourceData](./pattresourcedata/) | Η κλάση για την αποθήκευση των δεδομένων μοτίβου για τον πόρο [`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PhflResource](./phflresource/) | Κλάση PhflResource. Πόρος της Exposure Adjustment Layer 2 Έκδοση ( = 3 ) ή ( = 2 ) 12 4 bytes για κάθε χρώμα XYZ (Μόνο στην Έκδοση 3) 10 2 bytes χρωματικός χώρος ακολουθούμενος από 4 * 2 bytes συνιστώσα χρώματος (Μόνο στην Έκδοση 2) 4 Πυκνότητα 1 Διατήρηση Φωτεινότητας |
| [PhflResourceVersion2](./phflresourceversion2/) | Κλάση PhflResource. Πόρος της Exposure Adjustment Layer 2 Έκδοση ( = 3 ) ή ( = 2 ) 12 4 bytes για κάθε χρώμα XYZ (Μόνο στην Έκδοση 3) 10 2 bytes χρωματικός χώρος ακολουθούμενος από 4 * 2 bytes συνιστώσα χρώματος (Μόνο στην Έκδοση 2) 4 Πυκνότητα 1 Διατήρηση Φωτεινότητας |
| [PhflResourceVersion3](./phflresourceversion3/) | Κλάση PhflResource. Πόρος της Exposure Adjustment Layer 2 Έκδοση ( = 3 ) ή ( = 2 ) 12 4 bytes για κάθε χρώμα XYZ (Μόνο στην Έκδοση 3) 10 2 bytes χρωματικός χώρος ακολουθούμενος από 4 * 2 bytes συνιστώσα χρώματος (Μόνο στην Έκδοση 2) 4 Πυκνότητα 1 Διατήρηση Φωτεινότητας |
| [PlacedResource](./placedresource/) | Ορίζει την κλάση PlacedResource που περιέχει κοινές πληροφορίες σχετικά με μια τοποθετημένη στρώση ή μια στρώση έξυπνου αντικειμένου στο αρχείο PSD. Χρησιμοποιείται για την υποστήριξη στρώσεων έξυπνου αντικειμένου σε εικόνες Adobe® Photoshop®. |
| [PlLdResource](./plldresource/) | Ορίζει την κλάση PlLdResource που περιέχει πληροφορίες σχετικά με μια τοποθετημένη στρώση στο αρχείο PSD. Χρησιμοποιείται για την υποστήριξη στρώσεων έξυπνου αντικειμένου σε εικόνες Adobe® Photoshop®. Αντικαταστάθηκε από τη SoLdResource στο Adobe® Photoshop® CS3. |
| [PostResource](./postresource/) | Κλάση PostResource. Ρυθμίσεις στρώσης Posterize. |
| [PtFlResource](./ptflresource/) | Κλάση PtFlResource. Περιέχει δεδομένα στρώσης Pattern Fill. |
| [ShmdResource](./shmdresource/) | Κλάση ShmdResource. Ρυθμίσεις μεταδεδομένων |
| [SmartObjectResource](./smartobjectresource/) | Ορίζει την κλάση SmartObjectResource που περιέχει πληροφορίες σχετικά με μια στρώση έξυπνου αντικειμένου σε αρχείο PSD. Είναι η βασική κλάση για τους πόρους Sold και Sole που χρησιμοποιείται για την υποστήριξη στρώσεων έξυπνου αντικειμένου σε εικόνες Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator/) | Ορίζει την κλάση SmartResourceCreator που μπορεί να δημιουργήσει πόρους PlLd, SoLd και SoLe. Χρησιμοποιείται για την υποστήριξη επιπέδων έξυπνων αντικειμένων στις εικόνες Adobe® Photoshop®. |
| [SoCoResource](./socoresource/) | Κλάση SoCoResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τα επίπεδα γεμίσματος χρώματος. |
| [SoLdResource](./soldresource/) | Ορίζει την κλάση SoLdResource που περιέχει πληροφορίες σχετικά με ένα επίπεδο έξυπνου αντικειμένου σε αρχείο PSD. Χρησιμοποιείται για την υποστήριξη επιπέδων έξυπνων αντικειμένων στις εικόνες Adobe� Photoshop�. |
| [SoLeResource](./soleresource/) | Ορίζει την κλάση SoLeResource που περιέχει πληροφορίες σχετικά με ένα επίπεδο έξυπνου αντικειμένου σε αρχείο PSD. Χρησιμοποιείται για την υποστήριξη επιπέδων έξυπνων αντικειμένων με εξωτερικούς συνδέσμους αρχείων στις εικόνες Adobe� Photoshop�. |
| [Txt2Resource](./txt2resource/) | Κλάση πόρου Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo/) | Περιέχει πληροφορίες σχετικά με τη γραμματοσειρά του εργαλείου κειμένου. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | Οι πληροφορίες του εργαλείου κειμένου. Για έκδοση PSD ίση ή μεγαλύτερη από 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | Οι πληροφορίες του εργαλείου κειμένου. Για έκδοση PSD μικρότερη από 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Πληροφορίες γραμμής εργαλείου κειμένου. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Πληροφορίες στυλ εργαλείου κειμένου. |
| [UnknownResource](./unknownresource/) | Ο άγνωστος πόρος. |
| [VectorPath](./vectorpath/) | Η κλάση που περιέχει διανυσματικές διαδρομές. |
| [VectorPathDataResource](./vectorpathdataresource/) | Κλάση VectorPathDataResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τη μάσκα διανυσματικού επιπέδου. |
| [VibAResource](./vibaresource/) | Πόρος VibA. |
| [VmskResource](./vmskresource/) | Κλάση VmskResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τη μάσκα διανυσματικού επιπέδου. |
| [VogkResource](./vogkresource/) | Ο πόρος Vector Origination Data. |
| [VsmsResource](./vsmsresource/) | Κλάση VsmsResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με τη μάσκα διανυσματικού επιπέδου. |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | Ο φορτωτής πόρου [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [IPath](./ipath/) | Η διεπαφή περιγράφει το σύνολο των Διαδρομών που εμφανίζονται σε επίπεδο Σχήματος. |
| [IPathShape](./ipathshape/) | Το Σχήμα από τους κόμβους της καμπύλης Bezier. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Ορίζει τη διεπαφή IPlacedLayerResource που περιέχει πληροφορίες σχετικά με ένα τοποθετημένο επίπεδο σε αρχείο PSD. Είναι μια διεπαφή σήμανσης που χρησιμοποιείται για τον καθορισμό πόρων PlLd, Sold και Sole στις εικόνες Adobe® Photoshop®. Χρησιμοποιείται για την υποστήριξη επιπέδων έξυπνων αντικειμένων στις εικόνες Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Ορίζει τη διεπαφή ISmartObjectLayerResource που περιέχει πληροφορίες σχετικά με έναν πόρο επιπέδου έξυπνου αντικειμένου σε αρχείο PSD. Είναι επίσης μια διεπαφή σήμανσης που χρησιμοποιείται για τον καθορισμό τόσο των πόρων Sold όσο και Sole στις εικόνες Adobe® Photoshop®. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Επιλογές κλειδώματος επιπέδου |
| [LayerSectionSubtype](./layersectionsubtype/) | Ο υποτύπος ενότητας |
| [LayerSectionType](./layersectiontype/) | Ο τύπος ενότητας επιπέδου |
| [LinkDataSourceType](./linkdatasourcetype/) | Ορίζει την απαρίθμηση LinkDataSourceType για τις πηγές δεδομένων στον πόρο σύνδεσης PSD. |
| [LnsrResourceType](./lnsrresourcetype/) | Ανακαλύφθηκαν πιθανοί τύποι πόρων Lnsr |
| [PlacedLayerType](./placedlayertype/) | Ορίζει την απαρίθμηση PlacedLayerType για τον πόρο τοποθετημένου στρώματος PlLd. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Πιθανά χρώματα της ρύθμισης χρώματος Φύλλου. Είναι διακοσμητικό χρώμα UI του στρώματος στη λίστα στρωμάτων στο PS. |


