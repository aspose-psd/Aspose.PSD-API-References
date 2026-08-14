---
title: "Κλάση ExifData"
type: docs
weight: 10
url: /el/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ExifData()](#ExifData__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ExifData](/psd/python-net/aspose.psd.exif/exifdata/). |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) με δεδομένα από πίνακα. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) με δεδομένα από πίνακα. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την τιμή του διαφράγματος. |
| body_serial_number | string | r/w | Λαμβάνει ή ορίζει τον σειριακό αριθμό του σώματος της κάμερας. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Λαμβάνει ή ορίζει την τιμή φωτεινότητας. |
| camera_owner_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του κατόχου της κάμερας |
| cfa_pattern | byte | r/w | Λαμβάνει ή ορίζει το πρότυπο CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Λαμβάνει ή ορίζει το χρωματικό χώρο. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Λαμβάνει ή ορίζει ετικέτες που ανήκουν στην κοινή ενότητα. Αυτό ισχύει μόνο για εικόνες jpeg· σε μορφή tiff χρησιμοποιούνται οι tiffOptions αντί αυτού. |
| components_configuration | byte | r/w | Λαμβάνει ή ορίζει τη διαμόρφωση των στοιχείων. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τα συμπιεσμένα bits ανά pixel. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Λαμβάνει ή ορίζει την αντίθεση. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Λαμβάνει ή ορίζει την προσαρμοσμένη απόδοση. |
| date_time_digitized | string | r/w | Λαμβάνει ή ορίζει την ημερομηνία/ώρα ψηφιοποίησης. |
| date_time_original | string | r/w | Λαμβάνει ή ορίζει την αρχική ημερομηνία/ώρα. |
| device_setting_description | byte | r/w | Λαμβάνει ή ορίζει την περιγραφή ρυθμίσεων της συσκευής |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το ποσοστό ψηφιακού ζουμ. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Λαμβάνει ή ορίζει ετικέτες που ανήκουν μόνο στην ενότητα EXIF. |
| exif_version | byte | r/w | Λαμβάνει ή ορίζει την έκδοση EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Λαμβάνει ή ορίζει την τιμή προκατάληψης έκθεσης. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το δείκτη έκθεσης. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία έκθεσης. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Λαμβάνει ή ορίζει το πρόγραμμα έκθεσης. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το χρόνο έκθεσης. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τον αριθμό F. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Λαμβάνει ή ορίζει τον τύπο προέλευσης αρχείου. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Λαμβάνει ή ορίζει το φλας. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την ενέργεια φλας. |
| flashpix_version | byte | r/w | Λαμβάνει ή ορίζει την έκδοση flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την εστιακή απόσταση. |
| focal_length_in_35_mm_film | ushort | r/w | Λαμβάνει ή ορίζει την εστιακή απόσταση σε φιλμ 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης του εστιακού επιπέδου. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την ανάλυση x του εστιακού επιπέδου. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την ανάλυση y του εστιακού επιπέδου. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Λαμβάνει ή ορίζει το βαθμό συνολικής ρύθμισης κέρδους εικόνας. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το γάμμα. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το υψόμετρο GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Λαμβάνει ή ορίζει το υψόμετρο GPS που χρησιμοποιείται ως αναφορά υψομέτρου. |
| gps_area_information | byte | r/w | Λαμβάνει ή ορίζει τις πληροφορίες περιοχής GPS. |
| gps_date_stamp | string | r/w | Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει την ημερομηνία και ώρα σε σχέση με το UTC (Παγκόσμιο Συντονισμένο Χρόνο). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την κατεύθυνση GPS προς το σημείο προορισμού. |
| gps_dest_bearing_ref | string | r/w | Λαμβάνει ή ορίζει την αναφορά GPS που χρησιμοποιείται για την παροχή της κατεύθυνσης προς το σημείο προορισμού. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την απόσταση GPS προς το σημείο προορισμού. |
| gps_dest_distance_ref | string | r/w | Αποκτά ή ορίζει τη μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης προς το σημείο προορισμού. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Αποκτά ή ορίζει το γεωγραφικό πλάτος GPS του σημείου προορισμού. |
| gps_dest_latitude_ref | string | r/w | Αποκτά ή ορίζει την τιμή GPS που υποδεικνύει εάν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Αποκτά ή ορίζει το γεωγραφικό μήκος GPS του σημείου προορισμού. |
| gps_dest_longitude_ref | string | r/w | Αποκτά ή ορίζει την τιμή GPS που υποδεικνύει εάν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό. |
| gps_differential | ushort | r/w | Αποκτά ή ορίζει μια τιμή GPS που υποδεικνύει εάν εφαρμόζεται διαφορική διόρθωση στον δέκτη GPS. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Αποκτά ή ορίζει την κατεύθυνση GPS της εικόνας όταν λήφθηκε. |
| gps_img_direction_ref | string | r/w | Αποκτά ή ορίζει την αναφορά GPS για τον καθορισμό της κατεύθυνσης της εικόνας όταν λήφθηκε. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Αποκτά ή ορίζει το γεωγραφικό πλάτος GPS. |
| gps_latitude_ref | string | r/w | Αποκτά ή ορίζει εάν το γεωγραφικό πλάτος GPS είναι βόρειο ή νότιο. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Αποκτά ή ορίζει το γεωγραφικό μήκος GPS. |
| gps_longitude_ref | string | r/w | Αποκτά ή ορίζει εάν το γεωγραφικό μήκος GPS είναι ανατολικό ή δυτικό. |
| gps_map_datum | string | r/w | Αποκτά ή ορίζει τα γεωδαιτικά δεδομένα έρευνας GPS που χρησιμοποιούνται από τον δέκτη GPS. |
| gps_measure_mode | string | r/w | Αποκτά ή ορίζει τη λειτουργία μέτρησης GPS. |
| gps_processing_method | byte | r/w | Αποκτά ή ορίζει τη συμβολοσειρά χαρακτήρων GPS που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για τον εντοπισμό της θέσης. |
| gps_satellites | string | r/w | Λαμβάνει ή ορίζει τα δορυφόρους GPS που χρησιμοποιούνται για μετρήσεις. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την ταχύτητα κίνησης του δέκτη GPS. |
| gps_speed_ref | string | r/w | Λαμβάνει ή ορίζει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS. |
| gps_status | string | r/w | Λαμβάνει ή ορίζει την κατάσταση του δέκτη GPS όταν καταγράφεται η εικόνα. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Λαμβάνει ή ορίζει ετικέτες, που ανήκουν μόνο στην ενότητα GPS. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το χρόνο GPS ως UTC (Παγκόσμια Συγχρονισμένη Ώρα). |
| gps_track | string | r/w | Λαμβάνει ή ορίζει την κατεύθυνση κίνησης του δέκτη GPS. |
| gps_track_ref | string | r/w | Λαμβάνει ή ορίζει την αναφορά για την παροχή της κατεύθυνσης κίνησης του δέκτη GPS. |
| gps_version_id | byte | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό έκδοσης GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει το GPS DOP (βαθμός ακρίβειας δεδομένων). |
| image_unique_id | string | r/w | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό της εικόνας. |
| is_big_endian | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα EXIF της ροής που δημιουργήθηκε είναι big endian. |
| iso_speed | uint | r/w | Λαμβάνει ή ορίζει την ταχύτητα ISO |
| iso_speed_latitude_yyy | uint | r/w | Λαμβάνει ή ορίζει την τιμή yyy του γεωγραφικού πλάτους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Λαμβάνει ή ορίζει την τιμή zzz του γεωγραφικού πλάτους ταχύτητας ISO μιας κάμερας ή συσκευής εισόδου που ορίζεται στο ISO 12232. |
| lens_make | string | r/w | Λαμβάνει ή ορίζει τον κατασκευαστή του φακού. |
| lens_model | string | r/w | Λαμβάνει ή ορίζει το μοντέλο του φακού. |
| lens_serial_number | string | r/w | Λαμβάνει ή ορίζει τον σειριακό αριθμό του φακού. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τις προδιαγραφές του φακού |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Λαμβάνει ή ορίζει την πηγή φωτός. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Λαμβάνει τα δεδομένα σημειώσεων κατασκευαστή. |
| maker_note_raw_data | byte | r/w | Λαμβάνει ή ορίζει τα ακατέργαστα δεδομένα σημειώσεων κατασκευαστή. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τη μέγιστη τιμή διαφράγματος. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία μέτρησης. |
| oecf | byte | r/w | Λαμβάνει ή ορίζει τη λειτουργία Οπτοηλεκτρικής Μετατροπής (OECF) που ορίζεται στο ISO 14524. |
| photographic_sensitivity | uint | r/w | Λαμβάνει ή ορίζει την φωτογραφική ευαισθησία. |
| pixel_x_dimension | uint | r/w | Λαμβάνει ή ορίζει τη διάσταση x του pixel. |
| pixel_y_dimension | uint | r/w | Λαμβάνει ή ορίζει τη διάσταση y του pixel. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Λαμβάνει ή ορίζει όλες τις ετικέτες EXIF (συμπεριλαμβανομένων των κοινών και των ετικετών GPS). |
| recommended_exposure_index | uint | r/w | Λαμβάνει ή ορίζει τον προτεινόμενο δείκτη έκθεσης. |
| related_sound_file | string | r/w | Λαμβάνει ή ορίζει το σχετικό αρχείο ήχου. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Λαμβάνει ή ορίζει τον κορεσμό. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Λαμβάνει ή ορίζει τον τύπο λήψης σκηνής. |
| scene_type | byte | r/w | Λαμβάνει ή ορίζει τον τύπο σκηνής. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Λαμβάνει ή ορίζει τη μέθοδο ανίχνευσης. |
| sensitivity_type | ushort | r/w | Λαμβάνει ή ορίζει τον τύπο ευαισθησίας. |
| sharpness | ushort | r/w | Λαμβάνει ή ορίζει την ευκρίνεια. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Λαμβάνει ή ορίζει την τιμή ταχύτητας κλείστρου. |
| spatial_frequency_response | byte | r/w | Λαμβάνει ή ορίζει την απόκριση χωρικής συχνότητας. |
| spectral_sensitivity | string | r/w | Λαμβάνει ή ορίζει τη φασματική ευαισθησία. |
| standard_output_sensitivity | uint | r/w | Λαμβάνει ή ορίζει τη στάνταρτ ευαισθησία εξόδου |
| subject_area | ushort | r/w | Λαμβάνει ή ορίζει την περιοχή του αντικειμένου. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την απόσταση του αντικειμένου. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Λαμβάνει ή ορίζει το εύρος απόστασης του αντικειμένου. |
| subject_location | ushort | r/w | Λαμβάνει ή ορίζει τη θέση του αντικειμένου. |
| subsec_time | string | r/w | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTime. |
| subsec_time_digitized | string | r/w | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeDigitized. |
| subsec_time_original | string | r/w | Λαμβάνει ή ορίζει τα κλάσματα του δευτερολέπτου για την ετικέτα DateTimeOriginal. |
| user_comment | string | r/w | Λαμβάνει ή ορίζει το σχόλιο χρήστη. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Λαμβάνει ή ορίζει τη λευκή ισορροπία. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τη χρωματικότητα του λευκού σημείου της εικόνας. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Αφαίρεση ετικέτας από το δοχείο |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Αφαίρεση ετικέτας από το δοχείο |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ExifData](/psd/python-net/aspose.psd.exif/exifdata/).

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) με δεδομένα από πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Οι κοινές ετικέτες. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Οι ετικέτες EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Οι ετικέτες GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) με δεδομένα από πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Πίνακας ετικετών EXIF μαζί με τις κοινές και τις ετικέτες GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Αφαίρεση ετικέτας από το δοχείο

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Η ετικέτα προς αφαίρεση |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Αφαίρεση ετικέτας από το δοχείο

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tag_id | ushort | Το αναγνωριστικό ετικέτας προς αφαίρεση. |

