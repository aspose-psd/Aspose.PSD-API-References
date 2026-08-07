---
title: "TiffOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές μορφής αρχείου tiff."
type: docs
weight: 25
url: /el/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Οι επιλογές μορφής αρχείου tiff. Σημειώστε ότι οι ετικέτες πλάτους και ύψους θα αντικατασταθούν κατά τη δημιουργία της εικόνας από τις παραμέτρους πλάτους και ύψους, οπότε δεν χρειάζεται να τις καθορίσετε άμεσα. Σημειώστε ότι πολλές επιλογές επιστρέφουν μια προεπιλεγμένη τιμή, αλλά αυτό δεν σημαίνει ότι αυτή η επιλογή έχει οριστεί ρητά ως τιμή ετικέτας. Για να επαληθεύσετε ότι η ετικέτα υπάρχει, χρησιμοποιήστε την ιδιότητα Tags ή τη σχετική μέθοδο IsTagPresent.

ΠΡΟΕΙΔΟΠΟΙΗΣΗ! Μην τροποποιείτε ποτέ τις επιλογές tiff κατά την αποθήκευση, καθώς αυτό μπορεί να προκαλέσει ανεπιθύμητες παρενέργειες και σφάλματα δύσκολα εντοπίσιμα. Η παρακάτω γραμμή αφήθηκε ειδικά σχολιασμένη επειδή προκάλεσε λανθασμένο προσδιορισμό της αρχής των δεδομένων. Οι περασμένες επιλογές δεν περιείχαν spp (αν και οι επιλογές δεν είναι σωστές σε τέτοια περίπτωση, όμως αυτό το σενάριο προκαλεί σφάλματα) και η επόμενη γραμμή πρόσθεσε τις ετικέτες +spp και +bpp, και όταν οι επιλογές γράφτηκαν μετά την πλήρη εγγραφή των δεδομένων, αντικατέστησαν την αρχή των δεδομένων για τον ασυμπίεστο κωδικοποιητή!!! Δείτε TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Προσθέτει μια νέα ετικέτα. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Προσθέτει τις ετικέτες. |
| [clone()](#clone--) |  |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης άλφα. |
| [getArtist()](#getArtist--) | Λαμβάνει ή ορίζει τον καλλιτέχνη. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Λαμβάνει ή ορίζει το χρώμα του φόντου. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει τα bits ανά εικονοστοιχείο. |
| [getBitsPerSample()](#getBitsPerSample--) | Λαμβάνει τα bits ανά δείγμα. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [getByteOrder()](#getByteOrder--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά byte του tiff. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Λαμβάνει την κρυφή μνήμη. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Λαμβάνει ή ορίζει τον χάρτη χρωμάτων. |
| [getCompressedQuality()](#getCompressedQuality--) | Λαμβάνει την ποιότητα συμπιεσμένης εικόνας. |
| [getCompression()](#getCompression--) | Λαμβάνει τη συμπίεση. |
| [getCopyright()](#getCopyright--) | Λαμβάνει το δικαίωμα πνευματικής ιδιοκτησίας. |
| [getDateTime()](#getDateTime--) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getDocumentName()](#getDocumentName--) | Λαμβάνει ή ορίζει το όνομα του εγγράφου. |
| [getExifIfd()](#getExifIfd--) | Λαμβάνει ή ορίζει τον δείκτη στο EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Λαμβάνει τον αριθμό των επιπλέον δειγμάτων. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Λαμβάνει τις τιμές των επιπλέον δειγμάτων. |
| [getFaxT4Options()](#getFaxT4Options--) | Λαμβάνει ή ορίζει τις επιλογές fax t4. |
| [getFileStandard()](#getFileStandard--) | Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF. |
| [getFillOrder()](#getFillOrder--) | Λαμβάνει ή ορίζει τη σειρά γεμίσματος των bits του byte. |
| [getFullFrame()](#getFullFrame--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο]. |
| [getHalfToneHints()](#getHalfToneHints--) | Λαμβάνει ή ορίζει τις υποδείξεις ημιδιαφάνειας. |
| [getIccProfile()](#getIccProfile--) | Λαμβάνει τη ροή προφίλ icc. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [getImageDescription()](#getImageDescription--) | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| [getImageLength()](#getImageLength--) | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| [getImageWidth()](#getImageWidth--) | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| [getInkNames()](#getInkNames--) | Λαμβάνει ή ορίζει τα ονόματα μελάνης. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| [getMinSampleValue()](#getMinSampleValue--) | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Οι επιλογές πολλαπλών σελίδων |
| [getOrientation()](#getOrientation--) | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| [getPageName()](#getPageName--) | Λαμβάνει ή ορίζει το όνομα σελίδας. |
| [getPageNumber()](#getPageNumber--) | Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας. |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [getPhotometric()](#getPhotometric--) | Λαμβάνει ή ορίζει το φωτομετρικό. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου. |
| [getPredictor()](#getPredictor--) | Λαμβάνει ή ορίζει τον προβλέπτη για συμπίεση LZW. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά πρέπει να προπολλαπλασιαστούν. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [getResolutionSettings()](#getResolutionSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [getResolutionUnit()](#getResolutionUnit--) | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Λαμβάνει ή ορίζει τις γραμμές ανά λωρίδα. |
| [getSampleFormat()](#getSampleFormat--) | Λαμβάνει ή ορίζει τη μορφή δείγματος. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Λαμβάνει τα δείγματα ανά pixel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Λαμβάνει ή ορίζει τον κατασκευαστή του σαρωτή. |
| [getScannerModel()](#getScannerModel--) | Λαμβάνει ή ορίζει το μοντέλο του σαρωτή. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| [getSminSampleValue()](#getSminSampleValue--) | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. |
| [getSoftwareType()](#getSoftwareType--) | Λαμβάνει ή ορίζει τον τύπο λογισμικού. |
| [getSource()](#getSource--) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [getStripByteCounts()](#getStripByteCounts--) | Λαμβάνει ή ορίζει τις μετρήσεις byte της λωρίδας. |
| [getStripOffsets()](#getStripOffsets--) | Λαμβάνει ή ορίζει τις μετατοπίσεις λωρίδας. |
| [getSubFileType()](#getSubFileType--) | Λαμβάνει ή ορίζει μια γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Λαμβάνει το αντικείμενο της ετικέτας ανά τύπο. |
| [getTags()](#getTags--) | Λαμβάνει ή ορίζει τις ετικέτες. |
| [getTargetPrinter()](#getTargetPrinter--) | Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο. |
| [getThreshholding()](#getThreshholding--) | Λαμβάνει ή ορίζει το κατώφλι. |
| [getTileByteCounts()](#getTileByteCounts--) | Λαμβάνει ή ορίζει τις μετρήσεις byte του πλακιδίου. |
| [getTileLength()](#getTileLength--) | Λαμβάνει ή ορίζει το μήκος του πλακιδίου. |
| [getTileOffsets()](#getTileOffsets--) | Λαμβάνει ή ορίζει τις μετατοπίσεις του πλακιδίου. |
| [getTileWidth()](#getTileWidth--) | Λαμβάνει ή ορίζει το πλάτος του πλακιδίου. |
| [getTotalPages()](#getTotalPages--) | Λαμβάνει το σύνολο των σελίδων. |
| [getValidTagCount()](#getValidTagCount--) | Λαμβάνει τον έγκυρο αριθμό ετικετών. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Λαμβάνει τον αριθμό των έγκυρων ετικετών. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [getXPAuthor()](#getXPAuthor--) | Λαμβάνει τον δημιουργό της εικόνας, ο οποίος χρησιμοποιείται από τον Windows Explorer. |
| [getXPComment()](#getXPComment--) | Λαμβάνει το σχόλιο στην εικόνα, το οποίο χρησιμοποιείται από τον Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Λαμβάνει την εικόνα θέματος, η οποία χρησιμοποιείται από τον Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Λαμβάνει πληροφορίες για την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer. |
| [getXPTitle()](#getXPTitle--) | Λαμβάνει πληροφορίες για την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer. |
| [getXmpData()](#getXmpData--) | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [getXposition()](#getXposition--) | Λαμβάνει ή ορίζει τη θέση x. |
| [getXresolution()](#getXresolution--) | Λαμβάνει ή ορίζει την ανάλυση x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Λαμβάνει ή ορίζει τα YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Λαμβάνει ή ορίζει τους παράγοντες υποδειγματοληψίας για το φωτομετρικό YCbCr. |
| [getYposition()](#getYposition--) | Λαμβάνει ή ορίζει τη θέση y. |
| [getYresolution()](#getYresolution--) | Λαμβάνει ή ορίζει την ανάλυση y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα επιπλέον δείγματα είναι παρόντα. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Καθορίζει εάν η ετικέτα είναι παρούσα στις επιλογές ή όχι. |
| [isTiled()](#isTiled--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι σε πλακίδια. |
| [isValid()](#isValid--) | Λαμβάνει μια τιμή που υποδεικνύει εάν οι  TiffOptions  έχουν διαμορφωθεί σωστά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Αφαιρεί την ετικέτα. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης άλφα. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Λαμβάνει ή ορίζει τον καλλιτέχνη. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει το χρώμα του φόντου. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Ορίζει τα bits ανά δείγμα. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [setByteOrder(int value)](#setByteOrder-int-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά byte του tiff. |
| [setColorMap(int[] value)](#setColorMap-int---) | Λαμβάνει ή ορίζει τον χάρτη χρωμάτων. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Ορίζει την ποιότητα της συμπιεσμένης εικόνας. |
| [setCompression(int value)](#setCompression-int-) | Ορίζει τη συμπίεση. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Ορίζει το δικαίωμα πνευματικής ιδιοκτησίας. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του εγγράφου. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Ορίζει τις τιμές των επιπλέον δειγμάτων. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Λαμβάνει ή ορίζει τις επιλογές fax t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF. |
| [setFillOrder(int value)](#setFillOrder-int-) | Λαμβάνει ή ορίζει τη σειρά γεμίσματος των bits του byte. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Λαμβάνει ή ορίζει τις υποδείξεις ημιδιαφάνειας. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Ορίζει τη ροή προφίλ icc. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| [setImageLength(long value)](#setImageLength-long-) | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| [setImageWidth(long value)](#setImageWidth-long-) | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Λαμβάνει ή ορίζει τα ονόματα μελάνης. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Οι επιλογές πολλαπλών σελίδων |
| [setOrientation(int value)](#setOrientation-int-) | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα σελίδας. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [setPhotometric(int value)](#setPhotometric-int-) | Λαμβάνει ή ορίζει το φωτομετρικό. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου. |
| [setPredictor(int value)](#setPredictor-int-) | Λαμβάνει ή ορίζει τον προβλέπτη για συμπίεση LZW. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά πρέπει να προπολλαπλασιαστούν. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Λαμβάνει ή ορίζει τις γραμμές ανά λωρίδα. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Λαμβάνει ή ορίζει τη μορφή δείγματος. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Λαμβάνει ή ορίζει τον κατασκευαστή του σαρωτή. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Λαμβάνει ή ορίζει το μοντέλο του σαρωτή. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Λαμβάνει ή ορίζει τον τύπο λογισμικού. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Λαμβάνει ή ορίζει τις μετρήσεις byte της λωρίδας. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Λαμβάνει ή ορίζει τις μετατοπίσεις λωρίδας. |
| [setSubFileType(long value)](#setSubFileType-long-) | Λαμβάνει ή ορίζει μια γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Λαμβάνει ή ορίζει τις ετικέτες. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο. |
| [setThreshholding(int value)](#setThreshholding-int-) | Λαμβάνει ή ορίζει το κατώφλι. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Λαμβάνει ή ορίζει τις μετρήσεις byte του πλακιδίου. |
| [setTileLength(long value)](#setTileLength-long-) | Λαμβάνει ή ορίζει το μήκος του πλακιδίου. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Λαμβάνει ή ορίζει τις μετατοπίσεις του πλακιδίου. |
| [setTileWidth(long value)](#setTileWidth-long-) | Λαμβάνει ή ορίζει το πλάτος του πλακιδίου. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Ορίζει τον δημιουργό της εικόνας, ο οποίος χρησιμοποιείται από τον Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Ορίζει το σχόλιο στην εικόνα, το οποίο χρησιμοποιείται από τον Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Ορίζει το θέμα της εικόνας, το οποίο χρησιμοποιείται από τον Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Ορίζει πληροφορίες σχετικά με την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Ορίζει πληροφορίες σχετικά με την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει τη θέση x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ανάλυση x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει τα YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Λαμβάνει ή ορίζει τους παράγοντες υποδειγματοληψίας για το φωτομετρικό YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει τη θέση y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ανάλυση y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Επικυρώνει εάν οι επιλογές έχουν έγκυρο συνδυασμό ετικετών. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expectedFormat | int | Η αναμενόμενη μορφή αρχείου tiff. |
| byteOrder | int | Η σειρά byte της μορφής αρχείου tiff που θα χρησιμοποιηθεί. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  TiffOptions . Από προεπιλογή χρησιμοποιείται η σύμβαση little endian.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expectedFormat | int | Η αναμενόμενη μορφή αρχείου tiff. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Οι επιλογές από τις οποίες θα γίνει αντιγραφή. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  TiffOptions  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι ετικέτες με τις οποίες θα αρχικοποιηθούν οι επιλογές. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Προσθέτει μια νέα ετικέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Η ετικέτα προς προσθήκη. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Προσθέτει τις ετικέτες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι ετικέτες προς προσθήκη. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Λαμβάνει ή ορίζει την επιλογή αποθήκευσης άλφα. Επιλογές εκτός του  TiffAlphaStorage.Unspecified  χρησιμοποιούνται όταν ορίζονται περισσότερα από 3  SamplesPerPixel .

**Returns:**
int - Η επιλογή αποθήκευσης άλφα.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Λαμβάνει ή ορίζει τον καλλιτέχνη.

**Returns:**
java.lang.String - Ο καλλιτέχνης.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Αποκτά ή ορίζει το χρώμα του φόντου. Χρησιμοποιείται για εσωτερικούς σκοπούς για την αποθήκευση του χρώματος φόντου της εικόνας.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Λαμβάνει τα bits ανά εικονοστοιχείο.

**Returns:**
int - Τα bits ανά pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Λαμβάνει τα bits ανά δείγμα.

**Returns:**
int[] - Η τιμή των bits ανά δείγμα.

Κατά τον ορισμό αυτής της τιμής, λάβετε υπόψη ότι θα ορίσει επίσης την τιμή SamplesPerPixel στο μήκος του πίνακα. Αυτές οι 2 ιδιότητες είναι πολύ στενά συνδεδεμένες, οπότε μπορούν να οριστούν μόνο μαζί.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά byte του tiff.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Λαμβάνει την κρυφή μνήμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ετικέτα | int | Η ετικέτα (που είναι τύπου πίνακα). |

**Returns:**
long[] - Η τιμή της ετικέτας.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Λαμβάνει ή ορίζει τον χάρτη χρωμάτων.

**Returns:**
int[] - Ο χάρτης χρωμάτων.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Αποκτά την ποιότητα της συμπιεσμένης εικόνας. Χρησιμοποιείται με τη συμπίεση Jpeg.

**Returns:**
int - ποιότητα συμπιεσμένης εικόνας.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Λαμβάνει τη συμπίεση.

**Returns:**
int - Η συμπίεση.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Λαμβάνει το δικαίωμα πνευματικής ιδιοκτησίας.

**Returns:**
java.lang.String - Το πνευματικό δικαίωμα.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα.

**Returns:**
java.lang.String - Η ημερομηνία και ώρα.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης.

**Returns:**
int - Το προεπιλεγμένο όριο κατανομής μνήμης.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για την σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώσης στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Τιμή: Η προεπιλεγμένη εναλλακτική γραμματοσειρά.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Λαμβάνει ή ορίζει το όνομα του εγγράφου.

**Returns:**
java.lang.String - Το όνομα του εγγράφου.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Λαμβάνει ή ορίζει τον δείκτη στο EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Λαμβάνει τον αριθμό των επιπλέον δειγμάτων.

Τιμή: Ο επιπλέον αριθμός δειγμάτων.

**Returns:**
long - ο επιπλέον αριθμός δειγμάτων.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Λαμβάνει τις τιμές των επιπλέον δειγμάτων.

Τιμή: Η τιμή των επιπλέον δειγμάτων.

**Returns:**
int[] - οι τιμές των επιπλέον δειγμάτων.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Λαμβάνει ή ορίζει τις επιλογές fax t4.

**Returns:**
long - Οι επιλογές fax t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF.

**Returns:**
int - Το πρότυπο αρχείου TIFF.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Λαμβάνει ή ορίζει τη σειρά γεμίσματος των bits του byte.

**Returns:**
int - Η σειρά γεμίσματος των bits του byte.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο].

Τιμή:  true  εάν [full frame]; διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Λαμβάνει ή ορίζει τις υποδείξεις ημιδιαφάνειας.

**Returns:**
int[] - Οι υποδείξεις ημιδιαφάνειας.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Λαμβάνει τη ροή προφίλ icc.

**Returns:**
byte[] - Το προφίλ icc.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος.

Τιμή:  true  εάν αγνοείται μετά τη δημιουργία του συμβάντος· διαφορετικά,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Λαμβάνει ή ορίζει την περιγραφή της εικόνας.

**Returns:**
java.lang.String - Η περιγραφή της εικόνας.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Λαμβάνει ή ορίζει το μήκος της εικόνας.

**Returns:**
long - Το μήκος της εικόνας.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Λαμβάνει ή ορίζει το πλάτος της εικόνας.

**Returns:**
long - Το πλάτος της εικόνας.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Λαμβάνει ή ορίζει τα ονόματα μελάνης.

**Returns:**
java.lang.String - Τα ονόματα μελάνης.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος.

**Returns:**
int[] - Η μέγιστη τιμή δείγματος.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος.

**Returns:**
int[] - Η ελάχιστη τιμή δείγματος.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Οι επιλογές πολλαπλών σελίδων

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Λαμβάνει ή ορίζει τον προσανατολισμό.

**Returns:**
int - Ο προσανατολισμός.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Λαμβάνει ή ορίζει το όνομα σελίδας.

**Returns:**
java.lang.String - Το όνομα σελίδας.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας.

**Returns:**
int[] - Η ετικέτα αριθμού σελίδας.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Λαμβάνει ή ορίζει την παλέτα χρωμάτων.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Λαμβάνει ή ορίζει το φωτομετρικό.

**Returns:**
int - Η φωτομετρική.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου.

**Returns:**
int - Η διαμόρφωση επιπέδου.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Λαμβάνει ή ορίζει τον προβλέπτη για συμπίεση LZW.

**Returns:**
int - Ο τύπος προβλέπτη.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά πρέπει να προπολλαπλασιαστούν.

**Returns:**
boolean -  true  εάν τα συστατικά πρέπει να προπολλαπλασιαστούν· διαφορετικά,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Λαμβάνει ή ορίζει τη μονάδα ανάλυσης.

**Returns:**
int - Η μονάδα ανάλυσης.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Λαμβάνει ή ορίζει τις γραμμές ανά λωρίδα.

**Returns:**
long - Οι γραμμές ανά ταινία.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Λαμβάνει ή ορίζει τη μορφή δείγματος.

**Returns:**
int[] - Η μορφή δείγματος.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ανακτά τα δείγματα ανά pixel. Για να αλλάξετε αυτήν την τιμή ιδιότητας, χρησιμοποιήστε τον setter της ιδιότητας  BitsPerSample .

**Returns:**
int - Τα δείγματα ανά pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Λαμβάνει ή ορίζει τον κατασκευαστή του σαρωτή.

**Returns:**
java.lang.String - Ο κατασκευαστής του σαρωτή.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Λαμβάνει ή ορίζει το μοντέλο του σαρωτή.

**Returns:**
java.lang.String - Το μοντέλο του σαρωτή.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Ανακτά ή ορίζει τη μέγιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα με τα δεδομένα δείγματος (τύπος Byte, Short ή Long).

**Returns:**
long[] - Η μέγιστη τιμή δείγματος.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Ανακτά ή ορίζει τη ελάχιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα με τα δεδομένα δείγματος (τύπος Byte, Short ή Long).

**Returns:**
long[] - Η ελάχιστη τιμή δείγματος.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Λαμβάνει ή ορίζει τον τύπο λογισμικού.

**Returns:**
java.lang.String - Ο τύπος λογισμικού.
### getSource() {#getSource--}
```
public final Source getSource()
```


Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας.

Τιμή: Η πηγή για τη δημιουργία της εικόνας.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Λαμβάνει ή ορίζει τις μετρήσεις byte της λωρίδας.

**Returns:**
long[] - Οι μετρήσεις byte ταινίας.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Λαμβάνει ή ορίζει τις μετατοπίσεις λωρίδας.

**Returns:**
long[] - Οι μετατοπίσεις λωρίδας.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Λαμβάνει ή ορίζει μια γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο.

**Returns:**
long - Η γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Λαμβάνει το αντικείμενο της ετικέτας ανά τύπο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tagKey | int | Το κλειδί ετικέτας. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Λαμβάνει ή ορίζει τις ετικέτες.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Οι ετικέτες.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο.

**Returns:**
java.lang.String - Ο εκτυπωτής-στόχος.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Λαμβάνει ή ορίζει το κατώφλι.

**Returns:**
int - Η οριοθέτηση.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Λαμβάνει ή ορίζει τις μετρήσεις byte του πλακιδίου.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Λαμβάνει ή ορίζει το μήκος του πλακιδίου.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Λαμβάνει ή ορίζει τις μετατοπίσεις του πλακιδίου.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Λαμβάνει ή ορίζει το πλάτος του πλακιδίου.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Λαμβάνει το σύνολο των σελίδων.

**Returns:**
int - Οι συνολικές σελίδες.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Λαμβάνει τον έγκυρο αριθμό ετικετών. Αυτό δεν είναι ο συνολικός αριθμός ετικετών αλλά ο αριθμός των ετικετών που μπορεί να διατηρηθεί.

**Returns:**
int - Ο έγκυρος αριθμός ετικετών.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Λαμβάνει τον αριθμό των έγκυρων ετικετών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι ετικέτες προς επικύρωση. |

**Returns:**
int - Ο αριθμός των έγκυρων ετικετών.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Λαμβάνει τον δημιουργό της εικόνας, ο οποίος χρησιμοποιείται από τον Windows Explorer.

Τιμή: Συγγραφέας εικόνας, χρησιμοποιείται από τον Windows Explorer. Το  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) αγνοείται από τον Windows Explorer εάν υπάρχει η ετικέτα Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)).

**Returns:**
java.lang.String - Συγγραφέας εικόνας, που χρησιμοποιείται από τον Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Λαμβάνει το σχόλιο στην εικόνα, το οποίο χρησιμοποιείται από τον Windows Explorer.

Τιμή: Σχόλιο στην εικόνα, χρησιμοποιείται από τον Windows Explorer.

**Returns:**
java.lang.String - Σχόλιο στην εικόνα, που χρησιμοποιείται από τον Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Λαμβάνει την εικόνα θέματος, η οποία χρησιμοποιείται από τον Windows Explorer.

Τιμή: Θέμα εικόνας, χρησιμοποιείται από τον Windows Explorer.

**Returns:**
java.lang.String - Θέμα εικόνας, που χρησιμοποιείται από τον Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Λαμβάνει πληροφορίες για την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer.

Τιμή: Πληροφορίες για την εικόνα, χρησιμοποιούνται από τον Windows Explorer.

**Returns:**
java.lang.String - Πληροφορίες για την εικόνα, που χρησιμοποιούνται από τον Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Λαμβάνει πληροφορίες για την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer.

Τιμή: Πληροφορίες για την εικόνα, χρησιμοποιούνται από τον Windows Explorer. Το  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) αγνοείται από τον Windows Explorer εάν υπάρχει η ετικέτα ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)).

**Returns:**
java.lang.String - Πληροφορίες για την εικόνα, που χρησιμοποιούνται από τον Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Λαμβάνει ή ορίζει τη θέση x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Λαμβάνει ή ορίζει την ανάλυση x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Λαμβάνει ή ορίζει τα YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Οι συντελεστές YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Λαμβάνει ή ορίζει τους παράγοντες υποδειγματοληψίας για το φωτομετρικό YCbCr.

**Returns:**
int[] - Οι παράγοντες υποδειγματοληψίας για το φθοριστικό YCbCr.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Λαμβάνει ή ορίζει τη θέση y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Λαμβάνει ή ορίζει την ανάλυση y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα επιπλέον δείγματα είναι παρόντα.

**Returns:**
boolean -  true  εάν υπάρχει το επιπλέον δείγμα· διαφορετικά,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Καθορίζει εάν η ετικέτα είναι παρούσα στις επιλογές ή όχι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ετικέτα | int | Το αναγνωριστικό ετικέτας για έλεγχο. |

**Returns:**
boolean -  true  εάν η ετικέτα υπάρχει· διαφορετικά,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι σε πλακίδια.

**Returns:**
boolean -  true  εάν η εικόνα είναι σε πλακίδια· διαφορετικά,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν οι  TiffOptions  έχουν ρυθμιστεί σωστά. Χρησιμοποιήστε τη μέθοδο Validate για να βρείτε τον λόγο αποτυχίας.

**Returns:**
boolean -  true  εάν οι TiffOptions είναι ρυθμισμένοι σωστά· διαφορετικά,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Αφαιρεί την ετικέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ετικέτα | int | Η ετικέτα προς αφαίρεση. |

**Returns:**
boolean - true εάν αφαιρεθεί επιτυχώς
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Λαμβάνει ή ορίζει την επιλογή αποθήκευσης άλφα. Επιλογές εκτός του  TiffAlphaStorage.Unspecified  χρησιμοποιούνται όταν ορίζονται περισσότερα από 3  SamplesPerPixel .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η επιλογή αποθήκευσης άλφα. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Λαμβάνει ή ορίζει τον καλλιτέχνη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Ο καλλιτέχνης. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Αποκτά ή ορίζει το χρώμα του φόντου. Χρησιμοποιείται για εσωτερικούς σκοπούς για την αποθήκευση του χρώματος φόντου της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Το χρώμα του φόντου. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Ορίζει τα bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int[] | Η τιμή των bits ανά δείγμα. |

Κατά τον ορισμό αυτής της τιμής, λάβετε υπόψη ότι θα ορίσει επίσης την τιμή SamplesPerPixel στο μήκος του πίνακα. Αυτές οι 2 ιδιότητες είναι πολύ στενά συνδεδεμένες, οπότε μπορούν να οριστούν μόνο μαζί. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά byte του tiff.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Λαμβάνει ή ορίζει τον χάρτη χρωμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Ο χάρτης χρωμάτων. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Ορίζει την ποιότητα συμπιεσμένης εικόνας. Χρησιμοποιείται με τη συμπίεση Jpeg.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | ποιότητα συμπιεσμένης εικόνας. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Ορίζει τη συμπίεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συμπίεση. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Ορίζει το δικαίωμα πνευματικής ιδιοκτησίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Το δικαίωμα πνευματικής ιδιοκτησίας. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Η ημερομηνία και η ώρα. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το προεπιλεγμένο όριο κατανομής μνήμης. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για την σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώσης στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Τιμή: Η προεπιλεγμένη εναλλακτική γραμματοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Λαμβάνει ή ορίζει το όνομα του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Το όνομα του εγγράφου. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Ορίζει τις τιμές των επιπλέον δειγμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Η τιμή των επιπλέον δειγμάτων. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Λαμβάνει ή ορίζει τις επιλογές fax t4.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Οι επιλογές fax t4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το πρότυπο αρχείου TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Λαμβάνει ή ορίζει τη σειρά γεμίσματος των bits του byte.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η σειρά γεμίσματος bits byte. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν [full frame].

Τιμή:  true  εάν [full frame]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Λαμβάνει ή ορίζει τις υποδείξεις ημιδιαφάνειας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Οι υποδείξεις ημιτονοειδούς. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Ορίζει τη ροή προφίλ icc.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] | Το προφίλ icc. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος.

Τιμή:  true  εάν αγνοείται μετά τη δημιουργία του συμβάντος· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Λαμβάνει ή ορίζει την περιγραφή της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Η περιγραφή της εικόνας. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Λαμβάνει ή ορίζει το μήκος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Το μήκος της εικόνας. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Λαμβάνει ή ορίζει το πλάτος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Το πλάτος της εικόνας. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Λαμβάνει ή ορίζει τα ονόματα μελάνης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Τα ονόματα μελάνης. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Η μέγιστη τιμή δείγματος. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Η ελάχιστη τιμή δείγματος. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Οι επιλογές πολλαπλών σελίδων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Λαμβάνει ή ορίζει τον προσανατολισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Ο προσανατολισμός. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Λαμβάνει ή ορίζει το όνομα σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Το όνομα σελίδας. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Η ετικέτα αριθμού σελίδας. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Λαμβάνει ή ορίζει την παλέτα χρωμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Λαμβάνει ή ορίζει το φωτομετρικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η φωτομετρική. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η επίπεδη διαμόρφωση. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Λαμβάνει ή ορίζει τον προβλέπτη για συμπίεση LZW.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Ο τύπος προβλέπτη. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά πρέπει να προπολλαπλασιαστούν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | αληθές εάν τα στοιχεία πρέπει να προπολλαπλασιαστούν· διαφορετικά, ψευδές. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η μονάδα ανάλυσης. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Λαμβάνει ή ορίζει τις γραμμές ανά λωρίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Οι γραμμές ανά λωρίδα. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Λαμβάνει ή ορίζει τη μορφή δείγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Η μορφή δείγματος. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Λαμβάνει ή ορίζει τον κατασκευαστή του σαρωτή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Ο κατασκευαστής σαρωτή. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Λαμβάνει ή ορίζει το μοντέλο του σαρωτή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Το μοντέλο σαρωτή. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Ανακτά ή ορίζει τη μέγιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα με τα δεδομένα δείγματος (τύπος Byte, Short ή Long).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long[] | Η μέγιστη τιμή δείγματος. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Ανακτά ή ορίζει τη ελάχιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα με τα δεδομένα δείγματος (τύπος Byte, Short ή Long).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long[] | Η ελάχιστη τιμή δείγματος. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Λαμβάνει ή ορίζει τον τύπο λογισμικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Ο τύπος λογισμικού. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας.

Τιμή: Η πηγή για τη δημιουργία της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Λαμβάνει ή ορίζει τις μετρήσεις byte της λωρίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long[] | Οι μετρήσεις byte λωρίδας. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Λαμβάνει ή ορίζει τις μετατοπίσεις λωρίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long[] | Οι μετατοπίσεις λωρίδας. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Λαμβάνει ή ορίζει μια γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Η γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Λαμβάνει ή ορίζει τις ετικέτες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι ετικέτες. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Ο εκτυπωτής προορισμού. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Λαμβάνει ή ορίζει το κατώφλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η οριοθέτηση. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Λαμβάνει ή ορίζει τις μετρήσεις byte του πλακιδίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Λαμβάνει ή ορίζει το μήκος του πλακιδίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Λαμβάνει ή ορίζει τις μετατοπίσεις του πλακιδίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Λαμβάνει ή ορίζει το πλάτος του πλακιδίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Ορίζει τον δημιουργό της εικόνας, ο οποίος χρησιμοποιείται από τον Windows Explorer.

Τιμή: Συγγραφέας εικόνας, χρησιμοποιείται από τον Windows Explorer. Η  XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) αγνοείται από τον Windows Explorer εάν υπάρχει η ετικέτα Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | συγγραφέας εικόνας, που χρησιμοποιείται από τον Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Ορίζει το σχόλιο στην εικόνα, το οποίο χρησιμοποιείται από τον Windows Explorer.

Τιμή: Σχόλιο στην εικόνα, χρησιμοποιείται από τον Windows Explorer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | σχόλιο στην εικόνα, που χρησιμοποιείται από τον Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Ορίζει το θέμα της εικόνας, το οποίο χρησιμοποιείται από τον Windows Explorer.

Τιμή: Θέμα εικόνας, χρησιμοποιείται από τον Windows Explorer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | θέμα εικόνας, που χρησιμοποιείται από τον Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Ορίζει πληροφορίες σχετικά με την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer.

Τιμή: Πληροφορίες για την εικόνα, χρησιμοποιούνται από τον Windows Explorer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | πληροφορίες για την εικόνα, που χρησιμοποιούνται από τον Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Ορίζει πληροφορίες σχετικά με την εικόνα, οι οποίες χρησιμοποιούνται από τον Windows Explorer.

Τιμή: Πληροφορίες για την εικόνα, χρησιμοποιούνται από τον Windows Explorer. Η  XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) αγνοείται από τον Windows Explorer εάν υπάρχει η ετικέτα ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | πληροφορίες για την εικόνα, που χρησιμοποιούνται από τον Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Το δοχείο δεδομένων XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Λαμβάνει ή ορίζει τη θέση x.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Η θέση x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Λαμβάνει ή ορίζει την ανάλυση x.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Η ανάλυση x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Λαμβάνει ή ορίζει τα YCbCrCoefficients.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Οι συντελεστές YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Λαμβάνει ή ορίζει τους παράγοντες υποδειγματοληψίας για το φωτομετρικό YCbCr.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] | Οι παράγοντες υποδειγματοληψίας για τη φωτομετρική YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Λαμβάνει ή ορίζει τη θέση y.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Η θέση y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Λαμβάνει ή ορίζει την ανάλυση y.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Η ανάλυση y. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


Επικυρώνει εάν οι επιλογές έχουν έγκυρο συνδυασμό ετικετών.

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

