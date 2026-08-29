---
title: "JpegExifData"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Δοχείο δεδομένων EXIF για αρχεία jpeg."
type: docs
weight: 12
url: /el/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Δοχείο δεδομένων EXIF για αρχεία jpeg.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Αρχικοποιεί μια νέα παρουσία της  JpegExifData  κλάσης. |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Αρχικοποιεί μια νέα παρουσία της κλάσης JpegExifData με δεδομένα από πίνακα. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Αρχικοποιεί μια νέα παρουσία της κλάσης JpegExifData με δεδομένα από πίνακα. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | Το μέγιστο μέγεθος τμήματος EXIF σε bytes που επιτρέπεται. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Λαμβάνει ή ορίζει την τιμή του διαφράγματος. |
| [getArtist()](#getArtist--) | Λαμβάνει ή ορίζει τον καλλιτέχνη. |
| [getBitsPerSample()](#getBitsPerSample--) | Λαμβάνει ή ορίζει τα bits ανά δείγμα. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Λαμβάνει ή ορίζει τον σειριακό αριθμό του σώματος της κάμερας. |
| [getBrightnessValue()](#getBrightnessValue--) | Λαμβάνει ή ορίζει την τιμή της φωτεινότητας. |
| [getCFAPattern()](#getCFAPattern--) | Λαμβάνει ή ορίζει το μοτίβο CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Λαμβάνει ή ορίζει το όνομα του ιδιοκτήτη της κάμερας. |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Λαμβάνει ή ορίζει το χρωματικό χώρο. |
| [getCommonTags()](#getCommonTags--) | Λαμβάνει ή ορίζει ετικέτες, που ανήκουν στην κοινή ενότητα. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Λαμβάνει ή ορίζει τη διαμόρφωση των συνιστωσών. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Λαμβάνει ή ορίζει τα συμπιεσμένα bits ανά pixel. |
| [getCompression()](#getCompression--) | Λαμβάνει ή ορίζει τη συμπίεση. |
| [getContrast()](#getContrast--) | Λαμβάνει ή ορίζει την αντίθεση. |
| [getCopyright()](#getCopyright--) | Λαμβάνει ή ορίζει το δικαίωμα πνευματικής ιδιοκτησίας. |
| [getCustomRendered()](#getCustomRendered--) | Λαμβάνει ή ορίζει την προσαρμοσμένη απόδοση. |
| [getDateTime()](#getDateTime--) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα ψηφιοποίησης. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα αρχικής λήψης. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Λαμβάνει ή ορίζει την περιγραφή ρυθμίσεων της συσκευής |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Λαμβάνει ή ορίζει το ποσοστό ψηφιακού ζουμ. |
| [getExifTags()](#getExifTags--) | Λαμβάνει ή ορίζει ετικέτες που ανήκουν μόνο στην ενότητα EXIF. |
| [getExifVersion()](#getExifVersion--) | Λαμβάνει ή ορίζει την έκδοση EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Λαμβάνει ή ορίζει την τιμή προκατάληψης έκθεσης. |
| [getExposureIndex()](#getExposureIndex--) | Λαμβάνει ή ορίζει τον δείκτη έκθεσης. |
| [getExposureMode()](#getExposureMode--) | Λαμβάνει ή ορίζει τη λειτουργία έκθεσης. |
| [getExposureProgram()](#getExposureProgram--) | Λαμβάνει ή ορίζει το πρόγραμμα έκθεσης. |
| [getExposureTime()](#getExposureTime--) | Λαμβάνει ή ορίζει το χρόνο έκθεσης. |
| [getFNumber()](#getFNumber--) | Λαμβάνει ή ορίζει τον αριθμό F. |
| [getFileSource()](#getFileSource--) | Λαμβάνει ή ορίζει τον τύπο προέλευσης αρχείου. |
| [getFlash()](#getFlash--) | Λαμβάνει ή ορίζει το φλας. |
| [getFlashEnergy()](#getFlashEnergy--) | Λαμβάνει ή ορίζει την ενέργεια φλας. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Λαμβάνει ή ορίζει την έκδοση flash pix. |
| [getFocalLength()](#getFocalLength--) | Λαμβάνει ή ορίζει την εστιακή απόσταση. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Λαμβάνει ή ορίζει την εστιακή απόσταση σε φιλμ 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης του εστιακού επιπέδου. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Λαμβάνει ή ορίζει την ανάλυση x του εστιακού επιπέδου. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Λαμβάνει ή ορίζει την ανάλυση y του εστιακού επιπέδου. |
| [getGPSAltitude()](#getGPSAltitude--) | Λαμβάνει ή ορίζει το υψόμετρο GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Λαμβάνει ή ορίζει το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Λαμβάνει ή ορίζει τις πληροφορίες περιοχής GPS. |
| [getGPSDOP()](#getGPSDOP--) | Λαμβάνει ή ορίζει το GPS DOP (βαθμός ακρίβειας δεδομένων). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Συγχρονισμένο Παγκόσμιο Χρόνο). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Λαμβάνει ή ορίζει την κατεύθυνση GPS προς το σημείο προορισμού. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Λαμβάνει ή ορίζει την αναφορά GPS που χρησιμοποιείται για τον καθορισμό της πορείας προς το σημείο προορισμού. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Λαμβάνει ή ορίζει την απόσταση GPS προς το σημείο προορισμού. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Λαμβάνει ή ορίζει τη μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS του σημείου προορισμού. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS του σημείου προορισμού. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό. |
| [getGPSDifferential()](#getGPSDifferential--) | Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει αν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Λαμβάνει ή ορίζει την κατεύθυνση GPS της εικόνας όταν λήφθηκε. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Λαμβάνει ή ορίζει την αναφορά GPS για τον καθορισμό της κατεύθυνσης της εικόνας όταν λήφθηκε. |
| [getGPSLatitude()](#getGPSLatitude--) | Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Λαμβάνει ή ορίζει αν το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο. |
| [getGPSLongitude()](#getGPSLongitude--) | Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Λαμβάνει ή ορίζει αν το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Λαμβάνει ή ορίζει τα γεωδαιτικά δεδομένα GPS που χρησιμοποιεί ο δέκτης GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Λαμβάνει ή ορίζει τη λειτουργία μέτρησης GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό της θέσης. |
| [getGPSSatellites()](#getGPSSatellites--) | Λαμβάνει ή ορίζει τα δορυφόρους GPS που χρησιμοποιούνται για τις μετρήσεις. |
| [getGPSSpeed()](#getGPSSpeed--) | Λαμβάνει ή ορίζει την ταχύτητα κίνησης του δέκτη GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Λαμβάνει ή ορίζει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS. |
| [getGPSStatus()](#getGPSStatus--) | Λαμβάνει ή ορίζει την κατάσταση του δέκτη GPS όταν η εικόνα καταγράφεται. |
| [getGPSTags()](#getGPSTags--) | Λαμβάνει ή ορίζει ετικέτες, που ανήκουν μόνο στην ενότητα GPS. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Λαμβάνει ή ορίζει το χρόνο GPS ως UTC (Παγκόσμια Συντονισμένη Ώρα). |
| [getGPSTrack()](#getGPSTrack--) | Λαμβάνει ή ορίζει την κατεύθυνση κίνησης του δέκτη GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Λαμβάνει ή ορίζει την αναφορά για τον καθορισμό της κατεύθυνση κίνησης του δέκτη GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Αποκτά ή ορίζει το αναγνωριστικό έκδοσης GPS. |
| [getGainControl()](#getGainControl--) | Αποκτά ή ορίζει το βαθμό συνολικής ρύθμισης ενίσχυσης εικόνας. |
| [getGamma()](#getGamma--) | Αποκτά ή ορίζει το γάμμα. |
| [getISOSpeed()](#getISOSpeed--) | Αποκτά ή ορίζει την ταχύτητα ISO |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Αποκτά ή ορίζει την τιμή yyy του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Αποκτά ή ορίζει την τιμή zzz του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232. |
| [getImageDescription()](#getImageDescription--) | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| [getImageLength()](#getImageLength--) | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| [getImageUniqueID()](#getImageUniqueID--) | Αποκτά ή ορίζει το μοναδικό αναγνωριστικό της εικόνας. |
| [getImageWidth()](#getImageWidth--) | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| [getLensMake()](#getLensMake--) | Αποκτά ή ορίζει τον κατασκευαστή του φακού. |
| [getLensModel()](#getLensModel--) | Αποκτά ή ορίζει το μοντέλο φακού. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Αποκτά ή ορίζει τον σειριακό αριθμό του φακού. |
| [getLensSpecification()](#getLensSpecification--) | Αποκτά ή ορίζει τις προδιαγραφές του φακού |
| [getLightSource()](#getLightSource--) | Αποκτά ή ορίζει την πηγή φωτός. |
| [getMake()](#getMake--) | Αποκτά τον κατασκευαστή του εξοπλισμού ηχογράφησης. |
| [getMakerNoteData()](#getMakerNoteData--) | Αποκτά τα δεδομένα σημειώσεων κατασκευαστή. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Αποκτά ή ορίζει τα ακατέργαστα δεδομένα σημειώσεων κατασκευαστή. |
| [getMakerNotes()](#getMakerNotes--) | Αποκτά τις σημειώσεις κατασκευαστή. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Αποκτά ή ορίζει τη μέγιστη τιμή διαφράγματος. |
| [getMeteringMode()](#getMeteringMode--) | Αποκτά ή ορίζει τη λειτουργία μέτρησης. |
| [getModel()](#getModel--) | Λαμβάνει ή ορίζει το μοντέλο. |
| [getOECF()](#getOECF--) | Αποκτά ή ορίζει τη λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524. |
| [getOrientation()](#getOrientation--) | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Αποκτά ή ορίζει τη φωτογραφική ευαισθησία. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Λαμβάνει ή ορίζει την φωτομετρική ερμηνεία. |
| [getPixelXDimension()](#getPixelXDimension--) | Αποκτά ή ορίζει τη διάσταση x του pixel. |
| [getPixelYDimension()](#getPixelYDimension--) | Αποκτά ή ορίζει τη διάσταση y του pixel. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Λαμβάνει ή ορίζει τη χρωματικότητα των τριών πρωτεύουσων χρωμάτων της εικόνας. |
| [getProperties()](#getProperties--) | Αποκτά ή ορίζει όλες τις ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Αποκτά ή ορίζει τον προτεινόμενο δείκτη έκθεσης. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Λαμβάνει ή ορίζει την αναφορά μαύρου-λευκού. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Αποκτά ή ορίζει το σχετικό αρχείο ήχου. |
| [getResolutionUnit()](#getResolutionUnit--) | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Λαμβάνει ή ορίζει τα δείγματα ανά pixel. |
| [getSaturation()](#getSaturation--) | Λαμβάνει ή ορίζει τον κορεσμό. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Λαμβάνει ή ορίζει τον τύπο λήψης σκηνής. |
| [getSceneType()](#getSceneType--) | Λαμβάνει ή ορίζει τον τύπο σκηνής. |
| [getSensingMethod()](#getSensingMethod--) | Λαμβάνει ή ορίζει τη μέθοδο ανίχνευσης. |
| [getSensitivityType()](#getSensitivityType--) | Λαμβάνει ή ορίζει τον τύπο ευαισθησίας. |
| [getSharpness()](#getSharpness--) | Λαμβάνει ή ορίζει την ευκρίνεια. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Λαμβάνει ή ορίζει την τιμή ταχύτητας κλείστρου. |
| [getSoftware()](#getSoftware--) | Λαμβάνει ή ορίζει το λογισμικό. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Λαμβάνει ή ορίζει την απόκριση χωρικής συχνότητας. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Λαμβάνει ή ορίζει τη φασματική ευαισθησία. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Λαμβάνει την τυπική ευαισθησία εξόδου |
| [getSubjectArea()](#getSubjectArea--) | Λαμβάνει ή ορίζει την περιοχή θέματος. |
| [getSubjectDistance()](#getSubjectDistance--) | Λαμβάνει ή ορίζει την απόσταση θέματος. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Λαμβάνει ή ορίζει το εύρος απόστασης θέματος. |
| [getSubjectLocation()](#getSubjectLocation--) | Λαμβάνει ή ορίζει τη θέση θέματος. |
| [getSubsecTime()](#getSubsecTime--) | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal. |
| [getThumbnail()](#getThumbnail--) | Λαμβάνει ή ορίζει τη μικρογραφία της εικόνας. |
| [getTransferFunction()](#getTransferFunction--) | Λαμβάνει ή ορίζει τη συνάρτηση μεταφοράς. |
| [getUserComment()](#getUserComment--) | Λαμβάνει ή ορίζει το σχόλιο χρήστη. |
| [getWhiteBalance()](#getWhiteBalance--) | Λαμβάνει ή ορίζει τη λευκή ισορροπία. |
| [getWhitePoint()](#getWhitePoint--) | Λαμβάνει ή ορίζει τη χρωματική απόδοση του λευκού σημείου της εικόνας. |
| [getXResolution()](#getXResolution--) | Λαμβάνει ή ορίζει την ανάλυση x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Λαμβάνει ή ορίζει τους συντελεστές πίνακα για τη μετατροπή από δεδομένα εικόνας RGB σε YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Λαμβάνει ή ορίζει τη θέση των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Λαμβάνει ή ορίζει τον λόγο δειγματοληψίας των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας. |
| [getYResolution()](#getYResolution--) | Λαμβάνει ή ορίζει την ανάλυση y. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα EXIF ροής που δημιουργήθηκαν είναι big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Αφαίρεση ετικέτας από το δοχείο |
| [serializeExifData()](#serializeExifData--) | Σειριοποιεί τα δεδομένα EXIF. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την τιμή του διαφράγματος. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Λαμβάνει ή ορίζει τον καλλιτέχνη. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα EXIF ροής που δημιουργήθηκαν είναι big endian. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Λαμβάνει ή ορίζει τα bits ανά δείγμα. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Λαμβάνει ή ορίζει τον σειριακό αριθμό του σώματος της κάμερας. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Λαμβάνει ή ορίζει την τιμή της φωτεινότητας. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Λαμβάνει ή ορίζει το μοτίβο CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του ιδιοκτήτη της κάμερας. |
| [setColorSpace(int value)](#setColorSpace-int-) | Λαμβάνει ή ορίζει το χρωματικό χώρο. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Λαμβάνει ή ορίζει ετικέτες, που ανήκουν στην κοινή ενότητα. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Λαμβάνει ή ορίζει τη διαμόρφωση των συνιστωσών. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει τα συμπιεσμένα bits ανά pixel. |
| [setCompression(int value)](#setCompression-int-) | Λαμβάνει ή ορίζει τη συμπίεση. |
| [setContrast(int value)](#setContrast-int-) | Λαμβάνει ή ορίζει την αντίθεση. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Λαμβάνει ή ορίζει το δικαίωμα πνευματικής ιδιοκτησίας. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Λαμβάνει ή ορίζει την προσαρμοσμένη απόδοση. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα ψηφιοποίησης. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Λαμβάνει ή ορίζει την ημερομηνία και ώρα αρχικής λήψης. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Λαμβάνει ή ορίζει την περιγραφή ρυθμίσεων της συσκευής |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει το ποσοστό ψηφιακού ζουμ. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Λαμβάνει ή ορίζει ετικέτες που ανήκουν μόνο στην ενότητα EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Λαμβάνει ή ορίζει την έκδοση EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Λαμβάνει ή ορίζει την τιμή προκατάληψης έκθεσης. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει τον δείκτη έκθεσης. |
| [setExposureMode(int value)](#setExposureMode-int-) | Λαμβάνει ή ορίζει τη λειτουργία έκθεσης. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Λαμβάνει ή ορίζει το πρόγραμμα έκθεσης. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει το χρόνο έκθεσης. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει τον αριθμό F. |
| [setFileSource(byte value)](#setFileSource-byte-) | Λαμβάνει ή ορίζει τον τύπο προέλευσης αρχείου. |
| [setFlash(int value)](#setFlash-int-) | Λαμβάνει ή ορίζει το φλας. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ενέργεια φλας. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Λαμβάνει ή ορίζει την έκδοση flash pix. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την εστιακή απόσταση. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Λαμβάνει ή ορίζει την εστιακή απόσταση σε φιλμ 35 mm. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης του εστιακού επιπέδου. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ανάλυση x του εστιακού επιπέδου. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ανάλυση y του εστιακού επιπέδου. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει το υψόμετρο GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Λαμβάνει ή ορίζει το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Λαμβάνει ή ορίζει τις πληροφορίες περιοχής GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει το GPS DOP (βαθμός ακρίβειας δεδομένων). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Συγχρονισμένο Παγκόσμιο Χρόνο). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την κατεύθυνση GPS προς το σημείο προορισμού. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Λαμβάνει ή ορίζει την αναφορά GPS που χρησιμοποιείται για τον καθορισμό της πορείας προς το σημείο προορισμού. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την απόσταση GPS προς το σημείο προορισμού. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Λαμβάνει ή ορίζει τη μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS του σημείου προορισμού. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS του σημείου προορισμού. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει αν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την κατεύθυνση GPS της εικόνας όταν λήφθηκε. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Λαμβάνει ή ορίζει την αναφορά GPS για τον καθορισμό της κατεύθυνσης της εικόνας όταν λήφθηκε. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Λαμβάνει ή ορίζει αν το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Λαμβάνει ή ορίζει αν το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Λαμβάνει ή ορίζει τα γεωδαιτικά δεδομένα GPS που χρησιμοποιεί ο δέκτης GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Λαμβάνει ή ορίζει τη λειτουργία μέτρησης GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό της θέσης. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Λαμβάνει ή ορίζει τα δορυφόρους GPS που χρησιμοποιούνται για τις μετρήσεις. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ταχύτητα κίνησης του δέκτη GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Λαμβάνει ή ορίζει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Λαμβάνει ή ορίζει την κατάσταση του δέκτη GPS όταν η εικόνα καταγράφεται. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Λαμβάνει ή ορίζει ετικέτες, που ανήκουν μόνο στην ενότητα GPS. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει το χρόνο GPS ως UTC (Παγκόσμια Συντονισμένη Ώρα). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Λαμβάνει ή ορίζει την κατεύθυνση κίνησης του δέκτη GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Λαμβάνει ή ορίζει την αναφορά για τον καθορισμό της κατεύθυνση κίνησης του δέκτη GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Αποκτά ή ορίζει το αναγνωριστικό έκδοσης GPS. |
| [setGainControl(int value)](#setGainControl-int-) | Αποκτά ή ορίζει το βαθμό συνολικής ρύθμισης ενίσχυσης εικόνας. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Αποκτά ή ορίζει το γάμμα. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Αποκτά ή ορίζει την ταχύτητα ISO |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Αποκτά ή ορίζει την τιμή yyy του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Αποκτά ή ορίζει την τιμή zzz του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| [setImageLength(long value)](#setImageLength-long-) | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Αποκτά ή ορίζει το μοναδικό αναγνωριστικό της εικόνας. |
| [setImageWidth(long value)](#setImageWidth-long-) | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Αποκτά ή ορίζει τον κατασκευαστή του φακού. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Αποκτά ή ορίζει το μοντέλο φακού. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Αποκτά ή ορίζει τον σειριακό αριθμό του φακού. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Αποκτά ή ορίζει τις προδιαγραφές του φακού |
| [setLightSource(int value)](#setLightSource-int-) | Αποκτά ή ορίζει την πηγή φωτός. |
| [setMake(String value)](#setMake-java.lang.String-) | Ορίζει τον κατασκευαστή του εξοπλισμού εγγραφής. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Αποκτά ή ορίζει τα ακατέργαστα δεδομένα σημειώσεων κατασκευαστή. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Αποκτά ή ορίζει τη μέγιστη τιμή διαφράγματος. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Αποκτά ή ορίζει τη λειτουργία μέτρησης. |
| [setModel(String value)](#setModel-java.lang.String-) | Λαμβάνει ή ορίζει το μοντέλο. |
| [setOECF(byte[] value)](#setOECF-byte---) | Αποκτά ή ορίζει τη λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524. |
| [setOrientation(int value)](#setOrientation-int-) | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Αποκτά ή ορίζει τη φωτογραφική ευαισθησία. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Λαμβάνει ή ορίζει την φωτομετρική ερμηνεία. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Αποκτά ή ορίζει τη διάσταση x του pixel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Αποκτά ή ορίζει τη διάσταση y του pixel. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει τη χρωματικότητα των τριών πρωτεύουσων χρωμάτων της εικόνας. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Αποκτά ή ορίζει όλες τις ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Αποκτά ή ορίζει τον προτεινόμενο δείκτη έκθεσης. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει την αναφορά μαύρου-λευκού. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Αποκτά ή ορίζει το σχετικό αρχείο ήχου. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Λαμβάνει ή ορίζει τα δείγματα ανά pixel. |
| [setSaturation(int value)](#setSaturation-int-) | Λαμβάνει ή ορίζει τον κορεσμό. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Λαμβάνει ή ορίζει τον τύπο λήψης σκηνής. |
| [setSceneType(byte value)](#setSceneType-byte-) | Λαμβάνει ή ορίζει τον τύπο σκηνής. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Λαμβάνει ή ορίζει τη μέθοδο ανίχνευσης. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Λαμβάνει ή ορίζει τον τύπο ευαισθησίας. |
| [setSharpness(int value)](#setSharpness-int-) | Λαμβάνει ή ορίζει την ευκρίνεια. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Λαμβάνει ή ορίζει την τιμή ταχύτητας κλείστρου. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Λαμβάνει ή ορίζει το λογισμικό. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Λαμβάνει ή ορίζει την απόκριση χωρικής συχνότητας. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Λαμβάνει ή ορίζει τη φασματική ευαισθησία. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Ορίζει την τυπική ευαισθησία εξόδου |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Λαμβάνει ή ορίζει την περιοχή θέματος. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την απόσταση θέματος. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Λαμβάνει ή ορίζει το εύρος απόστασης θέματος. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Λαμβάνει ή ορίζει τη θέση θέματος. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | Λαμβάνει ή ορίζει τη μικρογραφία της εικόνας. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Λαμβάνει ή ορίζει τη συνάρτηση μεταφοράς. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Λαμβάνει ή ορίζει το σχόλιο χρήστη. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Λαμβάνει ή ορίζει τη λευκή ισορροπία. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει τη χρωματική απόδοση του λευκού σημείου της εικόνας. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ανάλυση x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Λαμβάνει ή ορίζει τους συντελεστές πίνακα για τη μετατροπή από δεδομένα εικόνας RGB σε YCbCr. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Λαμβάνει ή ορίζει τη θέση των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Λαμβάνει ή ορίζει τον λόγο δειγματοληψίας των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Λαμβάνει ή ορίζει την ανάλυση y. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Αρχικοποιεί μια νέα παρουσία της  JpegExifData  κλάσης.

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης JpegExifData με δεδομένα από πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Πίνακας ετικετών EXIF μαζί με κοινές ετικέτες και ετικέτες GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης JpegExifData με δεδομένα από πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι κοινές ετικέτες. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι ετικέτες EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Οι ετικέτες GPS. |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


Το μέγιστο μέγεθος τμήματος EXIF σε bytes που επιτρέπεται.

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
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Λαμβάνει ή ορίζει την τιμή του διαφράγματος.

Τιμή: η τιμή του διαφράγματος.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


Λαμβάνει ή ορίζει τον καλλιτέχνη.

Τιμή: Ο καλλιτέχνης.

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Λαμβάνει ή ορίζει τα bits ανά δείγμα.

Τιμή: Τα bits ανά δείγμα.

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Λαμβάνει ή ορίζει τον σειριακό αριθμό του σώματος της κάμερας.

Τιμή: ο σειριακός αριθμός του σώματος.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Λαμβάνει ή ορίζει την τιμή της φωτεινότητας.

Τιμή: η τιμή φωτεινότητας.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Λαμβάνει ή ορίζει το μοτίβο CFA.

Τιμή: το μοτίβο CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Λαμβάνει ή ορίζει το όνομα του ιδιοκτήτη της κάμερας.

Τιμή: το όνομα του ιδιοκτήτη της κάμερας.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Λαμβάνει ή ορίζει το χρωματικό χώρο.

Τιμή: ο χρωματικός χώρος.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Λαμβάνει ή ορίζει ετικέτες που ανήκουν στην κοινή ενότητα. Αυτό ισχύει μόνο για εικόνες jpeg, ενώ για μορφή tiff χρησιμοποιούνται οι tiffOptions.

Τιμή: οι ετικέτες της κοινής ενότητας.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Λαμβάνει ή ορίζει τη διαμόρφωση των συνιστωσών.

Τιμή: η διαμόρφωση των στοιχείων.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Λαμβάνει ή ορίζει τα συμπιεσμένα bits ανά pixel.

Τιμή: τα συμπιεσμένα bits ανά pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


Λαμβάνει ή ορίζει τη συμπίεση.

Τιμή: Η συμπίεση.

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


Λαμβάνει ή ορίζει την αντίθεση.

Τιμή: η αντίθεση.

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Λαμβάνει ή ορίζει το δικαίωμα πνευματικής ιδιοκτησίας.

Τιμή: Τα πνευματικά δικαιώματα.

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Λαμβάνει ή ορίζει την προσαρμοσμένη απόδοση.

Τιμή: η προσαρμοσμένη απόδοση.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα.

Τιμή: Η ημερομηνία και ώρα.

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα ψηφιοποίησης.

Τιμή: η ημερομηνία και ώρα ψηφιοποίησης.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα αρχικής λήψης.

Τιμή: η αρχική ημερομηνία και ώρα.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Λαμβάνει ή ορίζει την περιγραφή ρυθμίσεων της συσκευής

Τιμή: η περιγραφή ρυθμίσεων της συσκευής.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Λαμβάνει ή ορίζει το ποσοστό ψηφιακού ζουμ.

Τιμή: ο λόγος ψηφιακού ζουμ.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Λαμβάνει ή ορίζει ετικέτες που ανήκουν μόνο στην ενότητα EXIF.

Τιμή: οι ετικέτες της ενότητας EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Λαμβάνει ή ορίζει την έκδοση EXIF.

Τιμή: η έκδοση EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Λαμβάνει ή ορίζει την τιμή προκατάληψης έκθεσης.

Τιμή: η τιμή προκατάληψης έκθεσης.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Λαμβάνει ή ορίζει τον δείκτη έκθεσης.

Τιμή: ο δείκτης της έκθεσης.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Λαμβάνει ή ορίζει τη λειτουργία έκθεσης.

Τιμή: η λειτουργία έκθεσης.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Λαμβάνει ή ορίζει το πρόγραμμα έκθεσης.

Τιμή: Το πρόγραμμα έκθεσης.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Λαμβάνει ή ορίζει το χρόνο έκθεσης.

Τιμή: Ο χρόνος έκθεσης.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Λαμβάνει ή ορίζει τον αριθμό F.

Τιμή: Ο αριθμός F.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Λαμβάνει ή ορίζει τον τύπο προέλευσης αρχείου.

Τιμή: Ο τύπος πηγής αρχείου.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Λαμβάνει ή ορίζει το φλας.

Τιμή: Το φλας.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Λαμβάνει ή ορίζει την ενέργεια φλας.

Τιμή: Η ενέργεια φλας.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Λαμβάνει ή ορίζει την έκδοση flash pix.

Τιμή: Η έκδοση flash pix.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Λαμβάνει ή ορίζει την εστιακή απόσταση.

Τιμή: Το μήκος του εστιακού.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Λαμβάνει ή ορίζει την εστιακή απόσταση σε φιλμ 35 mm.

Τιμή: Το εστιακό μήκος σε φιλμ 35 mm.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Λαμβάνει ή ορίζει τη μονάδα ανάλυσης του εστιακού επιπέδου.

Τιμή: Η μονάδα ανάλυσης επίπεδου εστίασης.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Λαμβάνει ή ορίζει την ανάλυση x του εστιακού επιπέδου.

Τιμή: Η ανάλυση x του επιπέδου εστίασης.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Λαμβάνει ή ορίζει την ανάλυση y του εστιακού επιπέδου.

Τιμή: Η ανάλυση y του επιπέδου εστίασης.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Λαμβάνει ή ορίζει το υψόμετρο GPS.

Τιμή: Το υψόμετρο GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Λαμβάνει ή ορίζει το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου.

Τιμή: Το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Λαμβάνει ή ορίζει τις πληροφορίες περιοχής GPS.

Τιμή: Η πληροφορία περιοχής GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Λαμβάνει ή ορίζει το GPS DOP (βαθμός ακρίβειας δεδομένων).

Τιμή: Το GPS DOP (βαθμός ακρίβειας δεδομένων).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Συγχρονισμένο Παγκόσμιο Χρόνο).

Τιμή: Η αλφαριθμητική σειρά GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Παγκόσμιο Συντονισμένο Χρόνο).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Λαμβάνει ή ορίζει την κατεύθυνση GPS προς το σημείο προορισμού.

Τιμή: Η κατεύθυνση GPS προς το σημείο προορισμού.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Λαμβάνει ή ορίζει την αναφορά GPS που χρησιμοποιείται για τον καθορισμό της πορείας προς το σημείο προορισμού.

Τιμή: Η αναφορά GPS που χρησιμοποιείται για τον καθορισμό της κατεύθυνσης προς το σημείο προορισμού.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Λαμβάνει ή ορίζει την απόσταση GPS προς το σημείο προορισμού.

Τιμή: Η απόσταση GPS προς το σημείο προορισμού.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Λαμβάνει ή ορίζει τη μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού.

Τιμή: Η μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS του σημείου προορισμού.

Τιμή: Το γεωγραφικό πλάτος GPS του σημείου προορισμού.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο.

Τιμή: Η τιμή GPS που υποδεικνύει αν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS του σημείου προορισμού.

Τιμή: Το γεωγραφικό μήκος GPS του σημείου προορισμού.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό.

Τιμή: Η τιμή GPS που υποδεικνύει εάν το μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό γεωγραφικό μήκος.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει αν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS.

Τιμή: Η τιμή GPS που υποδεικνύει εάν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Λαμβάνει ή ορίζει την κατεύθυνση GPS της εικόνας όταν λήφθηκε.

Τιμή: Η κατεύθυνση GPS της εικόνας όταν λήφθηκε.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Λαμβάνει ή ορίζει την αναφορά GPS για τον καθορισμό της κατεύθυνσης της εικόνας όταν λήφθηκε.

Τιμή: Η αναφορά GPS για την παροχή της κατεύθυνσης της εικόνας όταν λήφθηκε.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS.

Τιμή: Το γεωγραφικό πλάτος GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Λαμβάνει ή ορίζει αν το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο.

Τιμή: Το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS.

Τιμή: Το γεωγραφικό μήκος GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Λαμβάνει ή ορίζει αν το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό.

Τιμή: Το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Λαμβάνει ή ορίζει τα γεωδαιτικά δεδομένα GPS που χρησιμοποιεί ο δέκτης GPS.

Τιμή: Τα γεωδαιτικά δεδομένα GPS που χρησιμοποιούνται από τον δέκτη GPS.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Λαμβάνει ή ορίζει τη λειτουργία μέτρησης GPS.

Τιμή: Η λειτουργία μέτρησης GPS.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό της θέσης.

Τιμή: Η συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Λαμβάνει ή ορίζει τα δορυφόρους GPS που χρησιμοποιούνται για τις μετρήσεις.

Τιμή: Τα δορυφόροι GPS που χρησιμοποιούνται για μετρήσεις.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Λαμβάνει ή ορίζει την ταχύτητα κίνησης του δέκτη GPS.

Τιμή: Η ταχύτητα κίνησης του δέκτη GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Λαμβάνει ή ορίζει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS.

Τιμή: Η μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Λαμβάνει ή ορίζει την κατάσταση του δέκτη GPS όταν η εικόνα καταγράφεται.

Τιμή: Η κατάσταση του δέκτη GPS όταν η εικόνα καταγράφεται.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Λαμβάνει ή ορίζει ετικέτες, που ανήκουν μόνο στην ενότητα GPS.

Τιμή: Οι ετικέτες GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Λαμβάνει ή ορίζει το χρόνο GPS ως UTC (Παγκόσμια Συντονισμένη Ώρα).

Τιμή: Ο χρόνος GPS ως UTC (Παγκόσμια Συγχρονισμένη Ώρα).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Λαμβάνει ή ορίζει την κατεύθυνση κίνησης του δέκτη GPS.

Τιμή: Η κατεύθυνση κίνησης του δέκτη GPS.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Λαμβάνει ή ορίζει την αναφορά για τον καθορισμό της κατεύθυνση κίνησης του δέκτη GPS.

Τιμή: Η αναφορά για την παροχή της κατεύθυνσης κίνησης του δέκτη GPS.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Αποκτά ή ορίζει το αναγνωριστικό έκδοσης GPS.

Τιμή: Το αναγνωριστικό έκδοσης GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Αποκτά ή ορίζει το βαθμό συνολικής ρύθμισης ενίσχυσης εικόνας.

Τιμή: Το βαθμό συνολικής ρύθμισης κέρδους εικόνας.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Αποκτά ή ορίζει το γάμμα.

Τιμή: Η τιμή γάμμα.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Αποκτά ή ορίζει την ταχύτητα ISO

Τιμή: Η ταχύτητα ISO.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Αποκτά ή ορίζει την τιμή yyy του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Τιμή: Η τιμή ISO speed latitude yyy μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Αυτή η ετικέτα δεν πρέπει να καταγραφεί χωρίς το ISOSpeed και το ISOSpeedLatitudezzz.

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Αποκτά ή ορίζει την τιμή zzz του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Τιμή: Η τιμή του εύρους ταχύτητας ISO zzz μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Αυτή η ετικέτα δεν πρέπει να καταγραφεί χωρίς το ISOSpeed και το ISOSpeedLatitudeyyy.

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Λαμβάνει ή ορίζει την περιγραφή της εικόνας.

Τιμή: Η περιγραφή εικόνας.

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Λαμβάνει ή ορίζει το μήκος της εικόνας.

Τιμή: Το μήκος της εικόνας.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Αποκτά ή ορίζει το μοναδικό αναγνωριστικό της εικόνας.

Τιμή: Το μοναδικό αναγνωριστικό της εικόνας.

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Λαμβάνει ή ορίζει το πλάτος της εικόνας.

Τιμή: Το πλάτος της εικόνας.

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Αποκτά ή ορίζει τον κατασκευαστή του φακού.

Τιμή: Ο κατασκευαστής του φακού.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Αποκτά ή ορίζει το μοντέλο φακού.

Τιμή: Το μοντέλο του φακού.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Αποκτά ή ορίζει τον σειριακό αριθμό του φακού.

Τιμή: Ο σειριακός αριθμός του φακού.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Αποκτά ή ορίζει τις προδιαγραφές του φακού

Τιμή: Η προδιαγραφή του φακού.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Αποκτά ή ορίζει την πηγή φωτός.

Τιμή: Η πηγή φωτός.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Αποκτά τον κατασκευαστή του εξοπλισμού ηχογράφησης.

Τιμή: Ο κατασκευαστής του εξοπλισμού εγγραφής.

**Returns:**
java.lang.String - ο κατασκευαστής του εξοπλισμού εγγραφής.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Αποκτά τα δεδομένα σημειώσεων κατασκευαστή.

Τιμή: Τα δεδομένα σημειώσεων δημιουργού.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Αποκτά ή ορίζει τα ακατέργαστα δεδομένα σημειώσεων κατασκευαστή.

Τιμή: Τα ακατέργαστα δεδομένα σημειώσεων δημιουργού.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Αποκτά τις σημειώσεις κατασκευαστή.

Τιμή: Οι σημειώσεις δημιουργού.

**Returns:**
com.aspose.psd.exif.MakerNote[] - οι σημειώσεις δημιουργού.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Αποκτά ή ορίζει τη μέγιστη τιμή διαφράγματος.

Τιμή: Η μέγιστη τιμή διαφράγματος.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Αποκτά ή ορίζει τη λειτουργία μέτρησης.

Τιμή: Η λειτουργία μέτρησης.

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


Λαμβάνει ή ορίζει το μοντέλο.

Τιμή: Το μοντέλο.

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Αποκτά ή ορίζει τη λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524.

Τιμή: Η λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524.

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Λαμβάνει ή ορίζει τον προσανατολισμό.

Τιμή: Ο προσανατολισμός.

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Αποκτά ή ορίζει τη φωτογραφική ευαισθησία.

Τιμή: Η φωτογραφική ευαισθησία.

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Λαμβάνει ή ορίζει την φωτομετρική ερμηνεία.

Τιμή: Η φωτομετρική ερμηνεία.

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Αποκτά ή ορίζει τη διάσταση x του pixel.

Τιμή: Η διάσταση x του pixel.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Αποκτά ή ορίζει τη διάσταση y του pixel.

Τιμή: Η διάσταση y του pixel.

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου.

Τιμή: Η διαμόρφωση επιπέδου.

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Λαμβάνει ή ορίζει τη χρωματικότητα των τριών πρωτεύουσων χρωμάτων της εικόνας.

Τιμή: Η χρωματικότητα των τριών πρωτεύοντων χρωμάτων της εικόνας.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Αποκτά ή ορίζει όλες τις ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS).

Τιμή: Οι ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Αποκτά ή ορίζει τον προτεινόμενο δείκτη έκθεσης.

Τιμή: Ο προτεινόμενος δείκτης έκθεσης.

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Λαμβάνει ή ορίζει την αναφορά μαύρου-λευκού.

Τιμή: Η αναφορά μαύρου λευκού.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Αποκτά ή ορίζει το σχετικό αρχείο ήχου.

Τιμή: Το σχετικό αρχείο ήχου.

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Λαμβάνει ή ορίζει τη μονάδα ανάλυσης.

Τιμή: Η μονάδα ανάλυσης.

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Λαμβάνει ή ορίζει τα δείγματα ανά pixel.

Τιμή: Δείγματα ανά pixel.

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Λαμβάνει ή ορίζει τον κορεσμό.

Τιμή: Ο κορεσμός.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Λαμβάνει ή ορίζει τον τύπο λήψης σκηνής.

Τιμή: Ο τύπος λήψης σκηνής.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Λαμβάνει ή ορίζει τον τύπο σκηνής.

Τιμή: Ο τύπος της σκηνής.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Λαμβάνει ή ορίζει τη μέθοδο ανίχνευσης.

Τιμή: Η μέθοδος ανίχνευσης.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Λαμβάνει ή ορίζει τον τύπο ευαισθησίας.

Τιμή: Ο τύπος της ευαισθησίας.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Λαμβάνει ή ορίζει την ευκρίνεια.

Τιμή: Η ευκρίνεια.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Λαμβάνει ή ορίζει την τιμή ταχύτητας κλείστρου.

Τιμή: Η τιμή του χρόνου κλείστρου.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Λαμβάνει ή ορίζει το λογισμικό.

Τιμή: Το λογισμικό.

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Λαμβάνει ή ορίζει την απόκριση χωρικής συχνότητας.

Τιμή: Η απόκριση χωρικής συχνότητας.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Λαμβάνει ή ορίζει τη φασματική ευαισθησία.

Τιμή: Η φασματική ευαισθησία.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Λαμβάνει την τυπική ευαισθησία εξόδου

Τιμή: Η τυπική ευαισθησία εξόδου.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Λαμβάνει ή ορίζει την περιοχή θέματος.

Τιμή: Η περιοχή του θέματος.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Λαμβάνει ή ορίζει την απόσταση θέματος.

Τιμή: Η απόσταση του θέματος.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Λαμβάνει ή ορίζει το εύρος απόστασης θέματος.

Τιμή: Η εμβέλεια απόστασης του θέματος.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Λαμβάνει ή ορίζει τη θέση θέματος.

Τιμή: Η θέση του θέματος.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime.

Τιμή: Τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized.

Τιμή: Τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal.

Τιμή: Τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal.

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


Λαμβάνει ή ορίζει τη μικρογραφία της εικόνας.

Τιμή: Η μικρογραφία.

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Λαμβάνει ή ορίζει τη συνάρτηση μεταφοράς.

Τιμή: Η συνάρτηση μεταφοράς.

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Λαμβάνει ή ορίζει το σχόλιο χρήστη.

Τιμή: Το σχόλιο του χρήστη.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Λαμβάνει ή ορίζει τη λευκή ισορροπία.

Τιμή: Η ισορροπία λευκού.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Λαμβάνει ή ορίζει τη χρωματική απόδοση του λευκού σημείου της εικόνας.

Τιμή: Η χρωματικότητα του λευκού σημείου της εικόνας.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Λαμβάνει ή ορίζει την ανάλυση x.

Τιμή: Η ανάλυση x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Λαμβάνει ή ορίζει τους συντελεστές πίνακα για τη μετατροπή από δεδομένα εικόνας RGB σε YCbCr.

Τιμή: Οι συντελεστές πίνακα για μετασχηματισμό από δεδομένα εικόνας RGB σε YCbCr.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Λαμβάνει ή ορίζει τη θέση των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

Τιμή: Η θέση των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Λαμβάνει ή ορίζει τον λόγο δειγματοληψίας των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

Τιμή: Η αναλογία δειγματοληψίας των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Λαμβάνει ή ορίζει την ανάλυση y.

Τιμή: η ανάλυση y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα EXIF ροής που δημιουργήθηκαν είναι big endian.

Τιμή:  true  εάν τα δεδομένα EXIF του ρεύματος που δημιουργήθηκαν από είναι big endian; διαφορετικά,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Αφαίρεση ετικέτας από το δοχείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tagId | int | Ο ταυτοποιητής ετικέτας για αφαίρεση. |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Διεξάγει σειριοποίηση των δεδομένων EXIF. Γράφει τις τιμές και τα περιεχόμενα των ετικετών. Η ετικέτα μεγέθους που επηρεάζει περισσότερο είναι τα περιεχόμενα της ετικέτας Thumbnail.

**Returns:**
byte[] - Τα σειριοποιημένα δεδομένα EXIF.

Το συνολικό μέγεθος τμήματος πρέπει να είναι μικρότερο ή ίσο με τα bytes του MaxExifSegmentSize για να παραχθεί σωστή εικόνα jpeg. Υπόδειξη: προσπαθήστε να μειώσετε το μέγεθος της μικρογραφίας ή να αλλάξετε τη συμπίεσή της σε περίπτωση που έχετε πολύ μεγάλο μέγεθος τμήματος EXIF.
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Λαμβάνει ή ορίζει την τιμή του διαφράγματος.

Τιμή: η τιμή του διαφράγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Λαμβάνει ή ορίζει τον καλλιτέχνη.

Τιμή: Ο καλλιτέχνης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα EXIF ροής που δημιουργήθηκαν είναι big endian.

Τιμή:  true  εάν τα δεδομένα EXIF του ρεύματος που δημιουργήθηκαν από είναι big endian; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Λαμβάνει ή ορίζει τα bits ανά δείγμα.

Τιμή: Τα bits ανά δείγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Λαμβάνει ή ορίζει τον σειριακό αριθμό του σώματος της κάμερας.

Τιμή: ο σειριακός αριθμός του σώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Λαμβάνει ή ορίζει την τιμή της φωτεινότητας.

Τιμή: η τιμή φωτεινότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Λαμβάνει ή ορίζει το μοτίβο CFA.

Τιμή: το μοτίβο CFA.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Λαμβάνει ή ορίζει το όνομα του ιδιοκτήτη της κάμερας.

Τιμή: το όνομα του ιδιοκτήτη της κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Λαμβάνει ή ορίζει το χρωματικό χώρο.

Τιμή: ο χρωματικός χώρος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Λαμβάνει ή ορίζει ετικέτες που ανήκουν στην κοινή ενότητα. Αυτό ισχύει μόνο για εικόνες jpeg, ενώ για μορφή tiff χρησιμοποιούνται οι tiffOptions.

Τιμή: οι ετικέτες της κοινής ενότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Λαμβάνει ή ορίζει τη διαμόρφωση των συνιστωσών.

Τιμή: η διαμόρφωση των στοιχείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Λαμβάνει ή ορίζει τα συμπιεσμένα bits ανά pixel.

Τιμή: τα συμπιεσμένα bits ανά pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Λαμβάνει ή ορίζει τη συμπίεση.

Τιμή: Η συμπίεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Λαμβάνει ή ορίζει την αντίθεση.

Τιμή: η αντίθεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Λαμβάνει ή ορίζει το δικαίωμα πνευματικής ιδιοκτησίας.

Τιμή: Τα πνευματικά δικαιώματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Λαμβάνει ή ορίζει την προσαρμοσμένη απόδοση.

Τιμή: η προσαρμοσμένη απόδοση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα.

Τιμή: Η ημερομηνία και ώρα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα ψηφιοποίησης.

Τιμή: η ημερομηνία και ώρα ψηφιοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Λαμβάνει ή ορίζει την ημερομηνία και ώρα αρχικής λήψης.

Τιμή: η αρχική ημερομηνία και ώρα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Λαμβάνει ή ορίζει την περιγραφή ρυθμίσεων της συσκευής

Τιμή: η περιγραφή ρυθμίσεων της συσκευής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Λαμβάνει ή ορίζει το ποσοστό ψηφιακού ζουμ.

Τιμή: ο λόγος ψηφιακού ζουμ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Λαμβάνει ή ορίζει ετικέτες που ανήκουν μόνο στην ενότητα EXIF.

Τιμή: οι ετικέτες της ενότητας EXIF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Λαμβάνει ή ορίζει την έκδοση EXIF.

Τιμή: η έκδοση EXIF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Λαμβάνει ή ορίζει την τιμή προκατάληψης έκθεσης.

Τιμή: η τιμή προκατάληψης έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Λαμβάνει ή ορίζει τον δείκτη έκθεσης.

Τιμή: ο δείκτης της έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία έκθεσης.

Τιμή: η λειτουργία έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Λαμβάνει ή ορίζει το πρόγραμμα έκθεσης.

Τιμή: Το πρόγραμμα έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Λαμβάνει ή ορίζει το χρόνο έκθεσης.

Τιμή: Ο χρόνος έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Λαμβάνει ή ορίζει τον αριθμό F.

Τιμή: Ο αριθμός F.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Λαμβάνει ή ορίζει τον τύπο προέλευσης αρχείου.

Τιμή: Ο τύπος πηγής αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Λαμβάνει ή ορίζει το φλας.

Τιμή: Το φλας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Λαμβάνει ή ορίζει την ενέργεια φλας.

Τιμή: Η ενέργεια φλας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Λαμβάνει ή ορίζει την έκδοση flash pix.

Τιμή: Η έκδοση flash pix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Λαμβάνει ή ορίζει την εστιακή απόσταση.

Τιμή: Το μήκος του εστιακού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Λαμβάνει ή ορίζει την εστιακή απόσταση σε φιλμ 35 mm.

Τιμή: Το εστιακό μήκος σε φιλμ 35 mm.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα ανάλυσης του εστιακού επιπέδου.

Τιμή: Η μονάδα ανάλυσης επίπεδου εστίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Λαμβάνει ή ορίζει την ανάλυση x του εστιακού επιπέδου.

Τιμή: Η ανάλυση x του επιπέδου εστίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Λαμβάνει ή ορίζει την ανάλυση y του εστιακού επιπέδου.

Τιμή: Η ανάλυση y του επιπέδου εστίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Λαμβάνει ή ορίζει το υψόμετρο GPS.

Τιμή: Το υψόμετρο GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Λαμβάνει ή ορίζει το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου.

Τιμή: Το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Λαμβάνει ή ορίζει τις πληροφορίες περιοχής GPS.

Τιμή: Η πληροφορία περιοχής GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Λαμβάνει ή ορίζει το GPS DOP (βαθμός ακρίβειας δεδομένων).

Τιμή: Το GPS DOP (βαθμός ακρίβειας δεδομένων).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Συγχρονισμένο Παγκόσμιο Χρόνο).

Τιμή: Η αλφαριθμητική σειρά GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Παγκόσμιο Συντονισμένο Χρόνο).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Λαμβάνει ή ορίζει την κατεύθυνση GPS προς το σημείο προορισμού.

Τιμή: Η κατεύθυνση GPS προς το σημείο προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Λαμβάνει ή ορίζει την αναφορά GPS που χρησιμοποιείται για τον καθορισμό της πορείας προς το σημείο προορισμού.

Τιμή: Η αναφορά GPS που χρησιμοποιείται για τον καθορισμό της κατεύθυνσης προς το σημείο προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Λαμβάνει ή ορίζει την απόσταση GPS προς το σημείο προορισμού.

Τιμή: Η απόσταση GPS προς το σημείο προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Λαμβάνει ή ορίζει τη μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού.

Τιμή: Η μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS του σημείου προορισμού.

Τιμή: Το γεωγραφικό πλάτος GPS του σημείου προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο.

Τιμή: Η τιμή GPS που υποδεικνύει αν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS του σημείου προορισμού.

Τιμή: Το γεωγραφικό μήκος GPS του σημείου προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει αν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό.

Τιμή: Η τιμή GPS που υποδεικνύει εάν το μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό γεωγραφικό μήκος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει αν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS.

Τιμή: Η τιμή GPS που υποδεικνύει εάν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Λαμβάνει ή ορίζει την κατεύθυνση GPS της εικόνας όταν λήφθηκε.

Τιμή: Η κατεύθυνση GPS της εικόνας όταν λήφθηκε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Λαμβάνει ή ορίζει την αναφορά GPS για τον καθορισμό της κατεύθυνσης της εικόνας όταν λήφθηκε.

Τιμή: Η αναφορά GPS για την παροχή της κατεύθυνσης της εικόνας όταν λήφθηκε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS.

Τιμή: Το γεωγραφικό πλάτος GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Λαμβάνει ή ορίζει αν το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο.

Τιμή: Το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS.

Τιμή: Το γεωγραφικό μήκος GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Λαμβάνει ή ορίζει αν το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό.

Τιμή: Το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Λαμβάνει ή ορίζει τα γεωδαιτικά δεδομένα GPS που χρησιμοποιεί ο δέκτης GPS.

Τιμή: Τα γεωδαιτικά δεδομένα GPS που χρησιμοποιούνται από τον δέκτη GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Λαμβάνει ή ορίζει τη λειτουργία μέτρησης GPS.

Τιμή: Η λειτουργία μέτρησης GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό της θέσης.

Τιμή: Η συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Λαμβάνει ή ορίζει τα δορυφόρους GPS που χρησιμοποιούνται για τις μετρήσεις.

Τιμή: Τα δορυφόροι GPS που χρησιμοποιούνται για μετρήσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Λαμβάνει ή ορίζει την ταχύτητα κίνησης του δέκτη GPS.

Τιμή: Η ταχύτητα κίνησης του δέκτη GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Λαμβάνει ή ορίζει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS.

Τιμή: Η μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Λαμβάνει ή ορίζει την κατάσταση του δέκτη GPS όταν η εικόνα καταγράφεται.

Τιμή: Η κατάσταση του δέκτη GPS όταν η εικόνα καταγράφεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Λαμβάνει ή ορίζει ετικέτες, που ανήκουν μόνο στην ενότητα GPS.

Τιμή: Οι ετικέτες GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Λαμβάνει ή ορίζει το χρόνο GPS ως UTC (Παγκόσμια Συντονισμένη Ώρα).

Τιμή: Ο χρόνος GPS ως UTC (Παγκόσμια Συγχρονισμένη Ώρα).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Λαμβάνει ή ορίζει την κατεύθυνση κίνησης του δέκτη GPS.

Τιμή: Η κατεύθυνση κίνησης του δέκτη GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Λαμβάνει ή ορίζει την αναφορά για τον καθορισμό της κατεύθυνση κίνησης του δέκτη GPS.

Τιμή: Η αναφορά για την παροχή της κατεύθυνσης κίνησης του δέκτη GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Αποκτά ή ορίζει το αναγνωριστικό έκδοσης GPS.

Τιμή: Το αναγνωριστικό έκδοσης GPS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Αποκτά ή ορίζει το βαθμό συνολικής ρύθμισης ενίσχυσης εικόνας.

Τιμή: Το βαθμό συνολικής ρύθμισης κέρδους εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Αποκτά ή ορίζει το γάμμα.

Τιμή: Η τιμή γάμμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Αποκτά ή ορίζει την ταχύτητα ISO

Τιμή: Η ταχύτητα ISO.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Αποκτά ή ορίζει την τιμή yyy του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Τιμή: Η τιμή ISO speed latitude yyy μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Αυτή η ετικέτα δεν πρέπει να καταγραφεί χωρίς το ISOSpeed και το ISOSpeedLatitudezzz.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Αποκτά ή ορίζει την τιμή zzz του εύρους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Τιμή: Η τιμή του εύρους ταχύτητας ISO zzz μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232.

Αυτή η ετικέτα δεν πρέπει να καταγραφεί χωρίς το ISOSpeed και το ISOSpeedLatitudeyyy.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Λαμβάνει ή ορίζει την περιγραφή της εικόνας.

Τιμή: Η περιγραφή εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Λαμβάνει ή ορίζει το μήκος της εικόνας.

Τιμή: Το μήκος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Αποκτά ή ορίζει το μοναδικό αναγνωριστικό της εικόνας.

Τιμή: Το μοναδικό αναγνωριστικό της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Λαμβάνει ή ορίζει το πλάτος της εικόνας.

Τιμή: Το πλάτος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Αποκτά ή ορίζει τον κατασκευαστή του φακού.

Τιμή: Ο κατασκευαστής του φακού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Αποκτά ή ορίζει το μοντέλο φακού.

Τιμή: Το μοντέλο του φακού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Αποκτά ή ορίζει τον σειριακό αριθμό του φακού.

Τιμή: Ο σειριακός αριθμός του φακού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Αποκτά ή ορίζει τις προδιαγραφές του φακού

Τιμή: Η προδιαγραφή του φακού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Αποκτά ή ορίζει την πηγή φωτός.

Τιμή: Η πηγή φωτός.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Ορίζει τον κατασκευαστή του εξοπλισμού εγγραφής.

Τιμή: Ο κατασκευαστής του εξοπλισμού εγγραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | ο κατασκευαστής του εξοπλισμού ηχογράφησης. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Αποκτά ή ορίζει τα ακατέργαστα δεδομένα σημειώσεων κατασκευαστή.

Τιμή: Τα ακατέργαστα δεδομένα σημειώσεων δημιουργού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Αποκτά ή ορίζει τη μέγιστη τιμή διαφράγματος.

Τιμή: Η μέγιστη τιμή διαφράγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Αποκτά ή ορίζει τη λειτουργία μέτρησης.

Τιμή: Η λειτουργία μέτρησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Λαμβάνει ή ορίζει το μοντέλο.

Τιμή: Το μοντέλο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Αποκτά ή ορίζει τη λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524.

Τιμή: Η λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Λαμβάνει ή ορίζει τον προσανατολισμό.

Τιμή: Ο προσανατολισμός.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Αποκτά ή ορίζει τη φωτογραφική ευαισθησία.

Τιμή: Η φωτογραφική ευαισθησία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Λαμβάνει ή ορίζει την φωτομετρική ερμηνεία.

Τιμή: Η φωτομετρική ερμηνεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Αποκτά ή ορίζει τη διάσταση x του pixel.

Τιμή: Η διάσταση x του pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Αποκτά ή ορίζει τη διάσταση y του pixel.

Τιμή: Η διάσταση y του pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου.

Τιμή: Η διαμόρφωση επιπέδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Λαμβάνει ή ορίζει τη χρωματικότητα των τριών πρωτεύουσων χρωμάτων της εικόνας.

Τιμή: Η χρωματικότητα των τριών πρωτεύοντων χρωμάτων της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Αποκτά ή ορίζει όλες τις ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS).

Τιμή: Οι ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Αποκτά ή ορίζει τον προτεινόμενο δείκτη έκθεσης.

Τιμή: Ο προτεινόμενος δείκτης έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Λαμβάνει ή ορίζει την αναφορά μαύρου-λευκού.

Τιμή: Η αναφορά μαύρου λευκού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Αποκτά ή ορίζει το σχετικό αρχείο ήχου.

Τιμή: Το σχετικό αρχείο ήχου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα ανάλυσης.

Τιμή: Η μονάδα ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Λαμβάνει ή ορίζει τα δείγματα ανά pixel.

Τιμή: Δείγματα ανά pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Λαμβάνει ή ορίζει τον κορεσμό.

Τιμή: Ο κορεσμός.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Λαμβάνει ή ορίζει τον τύπο λήψης σκηνής.

Τιμή: Ο τύπος λήψης σκηνής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Λαμβάνει ή ορίζει τον τύπο σκηνής.

Τιμή: Ο τύπος της σκηνής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Λαμβάνει ή ορίζει τη μέθοδο ανίχνευσης.

Τιμή: Η μέθοδος ανίχνευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Λαμβάνει ή ορίζει τον τύπο ευαισθησίας.

Τιμή: Ο τύπος της ευαισθησίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Λαμβάνει ή ορίζει την ευκρίνεια.

Τιμή: Η ευκρίνεια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Λαμβάνει ή ορίζει την τιμή ταχύτητας κλείστρου.

Τιμή: Η τιμή του χρόνου κλείστρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Λαμβάνει ή ορίζει το λογισμικό.

Τιμή: Το λογισμικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Λαμβάνει ή ορίζει την απόκριση χωρικής συχνότητας.

Τιμή: Η απόκριση χωρικής συχνότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Λαμβάνει ή ορίζει τη φασματική ευαισθησία.

Τιμή: Η φασματική ευαισθησία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Ορίζει την τυπική ευαισθησία εξόδου

Τιμή: Η τυπική ευαισθησία εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Λαμβάνει ή ορίζει την περιοχή θέματος.

Τιμή: Η περιοχή του θέματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Λαμβάνει ή ορίζει την απόσταση θέματος.

Τιμή: Η απόσταση του θέματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Λαμβάνει ή ορίζει το εύρος απόστασης θέματος.

Τιμή: Η εμβέλεια απόστασης του θέματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Λαμβάνει ή ορίζει τη θέση θέματος.

Τιμή: Η θέση του θέματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime.

Τιμή: Τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized.

Τιμή: Τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal.

Τιμή: Τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


Λαμβάνει ή ορίζει τη μικρογραφία της εικόνας.

Τιμή: Η μικρογραφία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Λαμβάνει ή ορίζει τη συνάρτηση μεταφοράς.

Τιμή: Η συνάρτηση μεταφοράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Λαμβάνει ή ορίζει το σχόλιο χρήστη.

Τιμή: Το σχόλιο του χρήστη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Λαμβάνει ή ορίζει τη λευκή ισορροπία.

Τιμή: Η ισορροπία λευκού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Λαμβάνει ή ορίζει τη χρωματική απόδοση του λευκού σημείου της εικόνας.

Τιμή: Η χρωματικότητα του λευκού σημείου της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Λαμβάνει ή ορίζει την ανάλυση x.

Τιμή: Η ανάλυση x.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Λαμβάνει ή ορίζει τους συντελεστές πίνακα για τη μετατροπή από δεδομένα εικόνας RGB σε YCbCr.

Τιμή: Οι συντελεστές πίνακα για μετασχηματισμό από δεδομένα εικόνας RGB σε YCbCr.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Λαμβάνει ή ορίζει τη θέση των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

Τιμή: Η θέση των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Λαμβάνει ή ορίζει τον λόγο δειγματοληψίας των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

Τιμή: Η αναλογία δειγματοληψίας των συνιστωσών χρωματικότητας σε σχέση με τη συνιστώσα φωτεινότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Λαμβάνει ή ορίζει την ανάλυση y.

Τιμή: η ανάλυση y.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

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

