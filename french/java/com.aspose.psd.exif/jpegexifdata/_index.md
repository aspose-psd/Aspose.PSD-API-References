---
title: "JpegExifData"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Conteneur de données EXIF pour les fichiers jpeg."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Conteneur de données EXIF pour les fichiers jpeg.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initialise une nouvelle instance de la  JpegExifData  classe. |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la  JpegExifData  classe avec des données provenant d'un tableau. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la  JpegExifData  classe avec des données provenant d'un tableau. |
## Champs

| Champ | Description |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | La taille maximale du segment EXIF en octets autorisée. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Obtient ou définit la valeur de l’ouverture. |
| [getArtist()](#getArtist--) | Obtient ou définit l'artiste. |
| [getBitsPerSample()](#getBitsPerSample--) | Obtient ou définit les bits par échantillon. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Obtient ou définit le numéro de série du boîtier de l’appareil photo. |
| [getBrightnessValue()](#getBrightnessValue--) | Obtient ou définit la valeur de la luminosité. |
| [getCFAPattern()](#getCFAPattern--) | Obtient ou définit le motif CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Obtient ou définit le nom du propriétaire de l’appareil. |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Obtient ou définit l’espace colorimétrique. |
| [getCommonTags()](#getCommonTags--) | Obtient ou définit les balises qui appartiennent à la section commune. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Obtient ou définit la configuration des composants. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Obtient ou définit les bits compressés par pixel. |
| [getCompression()](#getCompression--) | Obtient ou définit la compression. |
| [getContrast()](#getContrast--) | Obtient ou définit le contraste. |
| [getCopyright()](#getCopyright--) | Obtient ou définit le droit d'auteur. |
| [getCustomRendered()](#getCustomRendered--) | Obtient ou définit le rendu personnalisé. |
| [getDateTime()](#getDateTime--) | Obtient ou définit la date et l'heure. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Obtient ou définit la date et l’heure de la numérisation. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Obtient ou définit la date et l’heure d’origine. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Obtient ou définit la description des paramètres de l’appareil. |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Obtient ou définit le rapport de zoom numérique. |
| [getExifTags()](#getExifTags--) | Obtient ou définit les balises qui appartiennent uniquement à la section EXIF. |
| [getExifVersion()](#getExifVersion--) | Obtient ou définit la version EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Obtient ou définit la valeur du biais d’exposition. |
| [getExposureIndex()](#getExposureIndex--) | Obtient ou définit l’indice d’exposition. |
| [getExposureMode()](#getExposureMode--) | Obtient ou définit le mode d'exposition. |
| [getExposureProgram()](#getExposureProgram--) | Obtient ou définit le programme d'exposition. |
| [getExposureTime()](#getExposureTime--) | Obtient ou définit le temps d'exposition. |
| [getFNumber()](#getFNumber--) | Obtient ou définit le nombre F. |
| [getFileSource()](#getFileSource--) | Obtient ou définit le type de source du fichier. |
| [getFlash()](#getFlash--) | Obtient ou définit le flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Obtient ou définit l'énergie du flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Obtient ou définit la version du flash pix. |
| [getFocalLength()](#getFocalLength--) | Obtient ou définit la distance focale. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Obtient ou définit la distance focale en film 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Obtient ou définit l'unité de résolution du plan focal. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Obtient ou définit la résolution X du plan focal. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Obtient ou définit la résolution Y du plan focal. |
| [getGPSAltitude()](#getGPSAltitude--) | Obtient ou définit l'altitude GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Obtient ou définit l'altitude GPS utilisée comme altitude de référence. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Obtient ou définit les informations de zone GPS. |
| [getGPSDOP()](#getGPSDOP--) | Obtient ou définit le DOP GPS (degré de précision des données). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Obtient ou définit l'azimut GPS vers le point de destination. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Obtient ou définit la distance GPS au point de destination. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Obtient ou définit l'unité GPS utilisée pour exprimer la distance au point de destination. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Obtient ou définit la latitude GPS du point de destination. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est nord ou sud. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Obtient ou définit la longitude GPS du point de destination. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Obtient ou définit la valeur GPS qui indique si la longitude du point de destination est à l’est ou à l’ouest. |
| [getGPSDifferential()](#getGPSDifferential--) | Obtient ou définit une valeur GPS qui indique si une correction différentielle est appliquée au récepteur GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Obtient ou définit la direction GPS de l’image lorsqu’elle a été capturée. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Obtient ou définit la référence GPS indiquant la direction de l’image lorsqu’elle est capturée. |
| [getGPSLatitude()](#getGPSLatitude--) | Obtient ou définit la latitude GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Obtient ou définit si la latitude GPS est nord ou sud. |
| [getGPSLongitude()](#getGPSLongitude--) | Obtient ou définit la longitude GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Obtient ou définit si la longitude GPS est à l’est ou à l’ouest. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Obtient ou définit les données de levé géodésique GPS utilisées par le récepteur GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Obtient ou définit le mode de mesure GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation. |
| [getGPSSatellites()](#getGPSSatellites--) | Obtient ou définit les satellites GPS utilisés pour les mesures. |
| [getGPSSpeed()](#getGPSSpeed--) | Obtient ou définit la vitesse du mouvement du récepteur GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Obtient ou définit l’unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. |
| [getGPSStatus()](#getGPSStatus--) | Obtient ou définit l’état du récepteur GPS lorsque l’image est enregistrée. |
| [getGPSTags()](#getGPSTags--) | Obtient ou définit les balises, qui appartiennent uniquement à la section GPS. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Obtient ou définit le temps GPS en UTC (Temps Universel Coordonné). |
| [getGPSTrack()](#getGPSTrack--) | Obtient ou définit la direction du mouvement du récepteur GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Obtient ou définit la référence indiquant la direction du mouvement du récepteur GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Obtient ou définit l’identifiant de version GPS. |
| [getGainControl()](#getGainControl--) | Obtient ou définit le degré d’ajustement global du gain de l’image. |
| [getGamma()](#getGamma--) | Obtient ou définit le gamma. |
| [getISOSpeed()](#getISOSpeed--) | Obtient ou définit la vitesse ISO |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Obtient ou définit la valeur de latitude yyy de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Obtient ou définit la valeur de latitude zzz de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232. |
| [getImageDescription()](#getImageDescription--) | Obtient ou définit la description de l'image. |
| [getImageLength()](#getImageLength--) | Obtient ou définit la longueur de l'image. |
| [getImageUniqueID()](#getImageUniqueID--) | Obtient ou définit l'identifiant unique de l'image. |
| [getImageWidth()](#getImageWidth--) | Obtient ou définit la largeur de l'image. |
| [getLensMake()](#getLensMake--) | Obtient ou définit le fabricant de l'objectif. |
| [getLensModel()](#getLensModel--) | Obtient ou définit le modèle de l'objectif. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Obtient ou définit le numéro de série de l'objectif. |
| [getLensSpecification()](#getLensSpecification--) | Obtient ou définit la spécification de l'objectif |
| [getLightSource()](#getLightSource--) | Obtient ou définit la source de lumière. |
| [getMake()](#getMake--) | Obtient le fabricant de l'équipement d'enregistrement. |
| [getMakerNoteData()](#getMakerNoteData--) | Obtient les données de la note du fabricant. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Obtient ou définit les données brutes de la note du fabricant. |
| [getMakerNotes()](#getMakerNotes--) | Obtient les notes du fabricant. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Obtient ou définit la valeur maximale d'ouverture. |
| [getMeteringMode()](#getMeteringMode--) | Obtient ou définit le mode de mesure. |
| [getModel()](#getModel--) | Obtient ou définit le modèle. |
| [getOECF()](#getOECF--) | Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| [getOrientation()](#getOrientation--) | Obtient ou définit l'orientation. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Obtient ou définit la sensibilité photographique. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Obtient ou définit l'interprétation photométrique. |
| [getPixelXDimension()](#getPixelXDimension--) | Obtient ou définit la dimension x du pixel. |
| [getPixelYDimension()](#getPixelYDimension--) | Obtient ou définit la dimension y du pixel. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtient ou définit la configuration planaire. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Obtient ou définit la chromaticité des trois couleurs primaires de l'image. |
| [getProperties()](#getProperties--) | Obtient ou définit toutes les balises EXIF (y compris les balises communes et GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Obtient ou définit l'indice d'exposition recommandé. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Obtient ou définit le noir et blanc de référence. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Obtient ou définit le fichier audio associé. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtient ou définit l'unité de résolution. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtient ou définit les échantillons par pixel. |
| [getSaturation()](#getSaturation--) | Obtient ou définit la saturation. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Obtient ou définit le type de capture de la scène. |
| [getSceneType()](#getSceneType--) | Obtient ou définit le type de scène. |
| [getSensingMethod()](#getSensingMethod--) | Obtient ou définit la méthode de détection. |
| [getSensitivityType()](#getSensitivityType--) | Obtient ou définit le type de sensibilité. |
| [getSharpness()](#getSharpness--) | Obtient ou définit la netteté. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Obtient ou définit la valeur de la vitesse d’obturation. |
| [getSoftware()](#getSoftware--) | Obtient ou définit le logiciel. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Obtient ou définit la réponse en fréquence spatiale. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Obtient ou définit la sensibilité spectrale. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Obtient la sensibilité de sortie standard |
| [getSubjectArea()](#getSubjectArea--) | Obtient ou définit la zone du sujet. |
| [getSubjectDistance()](#getSubjectDistance--) | Obtient ou définit la distance du sujet. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Obtient ou définit la plage de distance du sujet. |
| [getSubjectLocation()](#getSubjectLocation--) | Obtient ou définit l’emplacement du sujet. |
| [getSubsecTime()](#getSubsecTime--) | Obtient ou définit les fractions de seconde pour la balise DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal. |
| [getThumbnail()](#getThumbnail--) | Obtient ou définit l'image miniature. |
| [getTransferFunction()](#getTransferFunction--) | Obtient ou définit la fonction de transfert. |
| [getUserComment()](#getUserComment--) | Obtient ou définit le commentaire de l’utilisateur. |
| [getWhiteBalance()](#getWhiteBalance--) | Obtient ou définit la balance des blancs. |
| [getWhitePoint()](#getWhitePoint--) | Obtient ou définit la chromaticité du point blanc de l’image. |
| [getXResolution()](#getXResolution--) | Obtient ou définit la résolution x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Obtient ou définit la position des composants de chrominance par rapport au composant de luminance. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance. |
| [getYResolution()](#getYResolution--) | Obtient ou définit la résolution y. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Obtient ou définit une valeur indiquant si le flux de données EXIF créé à partir de celui‑ci est en big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Supprimer la balise du conteneur |
| [serializeExifData()](#serializeExifData--) | Sérialise les données EXIF. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la valeur de l’ouverture. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtient ou définit l'artiste. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Obtient ou définit une valeur indiquant si le flux de données EXIF créé à partir de celui‑ci est en big endian. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Obtient ou définit les bits par échantillon. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Obtient ou définit le numéro de série du boîtier de l’appareil photo. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Obtient ou définit la valeur de la luminosité. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Obtient ou définit le motif CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Obtient ou définit le nom du propriétaire de l’appareil. |
| [setColorSpace(int value)](#setColorSpace-int-) | Obtient ou définit l’espace colorimétrique. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises qui appartiennent à la section commune. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Obtient ou définit la configuration des composants. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit les bits compressés par pixel. |
| [setCompression(int value)](#setCompression-int-) | Obtient ou définit la compression. |
| [setContrast(int value)](#setContrast-int-) | Obtient ou définit le contraste. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Obtient ou définit le droit d'auteur. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Obtient ou définit le rendu personnalisé. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtient ou définit la date et l'heure. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Obtient ou définit la date et l’heure de la numérisation. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Obtient ou définit la date et l’heure d’origine. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Obtient ou définit la description des paramètres de l’appareil. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit le rapport de zoom numérique. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises qui appartiennent uniquement à la section EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Obtient ou définit la version EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Obtient ou définit la valeur du biais d’exposition. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit l’indice d’exposition. |
| [setExposureMode(int value)](#setExposureMode-int-) | Obtient ou définit le mode d'exposition. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Obtient ou définit le programme d'exposition. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit le temps d'exposition. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit le nombre F. |
| [setFileSource(byte value)](#setFileSource-byte-) | Obtient ou définit le type de source du fichier. |
| [setFlash(int value)](#setFlash-int-) | Obtient ou définit le flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit l'énergie du flash. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Obtient ou définit la version du flash pix. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la distance focale. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Obtient ou définit la distance focale en film 35 mm. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Obtient ou définit l'unité de résolution du plan focal. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution X du plan focal. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution Y du plan focal. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit l'altitude GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Obtient ou définit l'altitude GPS utilisée comme altitude de référence. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Obtient ou définit les informations de zone GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit le DOP GPS (degré de précision des données). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit l'azimut GPS vers le point de destination. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la distance GPS au point de destination. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Obtient ou définit l'unité GPS utilisée pour exprimer la distance au point de destination. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la latitude GPS du point de destination. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est nord ou sud. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la longitude GPS du point de destination. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Obtient ou définit la valeur GPS qui indique si la longitude du point de destination est à l’est ou à l’ouest. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Obtient ou définit une valeur GPS qui indique si une correction différentielle est appliquée au récepteur GPS. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la direction GPS de l’image lorsqu’elle a été capturée. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Obtient ou définit la référence GPS indiquant la direction de l’image lorsqu’elle est capturée. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la latitude GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Obtient ou définit si la latitude GPS est nord ou sud. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la longitude GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Obtient ou définit si la longitude GPS est à l’est ou à l’ouest. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Obtient ou définit les données de levé géodésique GPS utilisées par le récepteur GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Obtient ou définit le mode de mesure GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Obtient ou définit les satellites GPS utilisés pour les mesures. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la vitesse du mouvement du récepteur GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Obtient ou définit l’unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Obtient ou définit l’état du récepteur GPS lorsque l’image est enregistrée. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises, qui appartiennent uniquement à la section GPS. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit le temps GPS en UTC (Temps Universel Coordonné). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Obtient ou définit la direction du mouvement du récepteur GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Obtient ou définit la référence indiquant la direction du mouvement du récepteur GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Obtient ou définit l’identifiant de version GPS. |
| [setGainControl(int value)](#setGainControl-int-) | Obtient ou définit le degré d’ajustement global du gain de l’image. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit le gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Obtient ou définit la vitesse ISO |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Obtient ou définit la valeur de latitude yyy de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Obtient ou définit la valeur de latitude zzz de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtient ou définit la description de l'image. |
| [setImageLength(long value)](#setImageLength-long-) | Obtient ou définit la longueur de l'image. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Obtient ou définit l'identifiant unique de l'image. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtient ou définit la largeur de l'image. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Obtient ou définit le fabricant de l'objectif. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Obtient ou définit le modèle de l'objectif. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Obtient ou définit le numéro de série de l'objectif. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la spécification de l'objectif |
| [setLightSource(int value)](#setLightSource-int-) | Obtient ou définit la source de lumière. |
| [setMake(String value)](#setMake-java.lang.String-) | Définit le fabricant de l’équipement d’enregistrement. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Obtient ou définit les données brutes de la note du fabricant. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la valeur maximale d'ouverture. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Obtient ou définit le mode de mesure. |
| [setModel(String value)](#setModel-java.lang.String-) | Obtient ou définit le modèle. |
| [setOECF(byte[] value)](#setOECF-byte---) | Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| [setOrientation(int value)](#setOrientation-int-) | Obtient ou définit l'orientation. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Obtient ou définit la sensibilité photographique. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Obtient ou définit l'interprétation photométrique. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Obtient ou définit la dimension x du pixel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Obtient ou définit la dimension y du pixel. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtient ou définit la configuration planaire. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la chromaticité des trois couleurs primaires de l'image. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtient ou définit toutes les balises EXIF (y compris les balises communes et GPS). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Obtient ou définit l'indice d'exposition recommandé. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit le noir et blanc de référence. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Obtient ou définit le fichier audio associé. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtient ou définit l'unité de résolution. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Obtient ou définit les échantillons par pixel. |
| [setSaturation(int value)](#setSaturation-int-) | Obtient ou définit la saturation. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Obtient ou définit le type de capture de la scène. |
| [setSceneType(byte value)](#setSceneType-byte-) | Obtient ou définit le type de scène. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Obtient ou définit la méthode de détection. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Obtient ou définit le type de sensibilité. |
| [setSharpness(int value)](#setSharpness-int-) | Obtient ou définit la netteté. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Obtient ou définit la valeur de la vitesse d’obturation. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Obtient ou définit le logiciel. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Obtient ou définit la réponse en fréquence spatiale. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Obtient ou définit la sensibilité spectrale. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Définit la sensibilité de sortie standard |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Obtient ou définit la zone du sujet. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la distance du sujet. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Obtient ou définit la plage de distance du sujet. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Obtient ou définit l’emplacement du sujet. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Obtient ou définit les fractions de seconde pour la balise DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | Obtient ou définit l'image miniature. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Obtient ou définit la fonction de transfert. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Obtient ou définit le commentaire de l’utilisateur. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Obtient ou définit la balance des blancs. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit la chromaticité du point blanc de l’image. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Obtient ou définit la position des composants de chrominance par rapport au composant de luminance. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution y. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initialise une nouvelle instance de la  JpegExifData  classe.

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


Initialise une nouvelle instance de la  JpegExifData  classe avec des données provenant d'un tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tableau de balises EXIF ainsi que des balises communes et GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialise une nouvelle instance de la  JpegExifData  classe avec des données provenant d'un tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les balises communes. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les balises EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les balises GPS. |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


La taille maximale du segment EXIF en octets autorisée.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Obtient ou définit la valeur de l’ouverture.

Valeur : la valeur d’ouverture.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtient ou définit l'artiste.

Valeur: l'artiste.

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtient ou définit les bits par échantillon.

Valeur: les bits par échantillon.

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Obtient ou définit le numéro de série du boîtier de l’appareil photo.

Valeur : le numéro de série du boîtier.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Obtient ou définit la valeur de la luminosité.

Valeur : la valeur de luminosité.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Obtient ou définit le motif CFA.

Valeur : Le motif CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Obtient ou définit le nom du propriétaire de l’appareil.

Valeur : Le nom du propriétaire de l'appareil photo.

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


Obtient ou définit l’espace colorimétrique.

Valeur : L'espace colorimétrique.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Obtient ou définit les balises, qui appartiennent à la section commune. Cela s'applique uniquement aux images jpeg, dans le format tiff les tiffOptions sont utilisés à la place

Valeur : Les balises de la section commune.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Obtient ou définit la configuration des composants.

Valeur : La configuration des composants.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Obtient ou définit les bits compressés par pixel.

Valeur : Les bits compressés par pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtient ou définit la compression.

Valeur: la compression.

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


Obtient ou définit le contraste.

Valeur : Le contraste.

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtient ou définit le droit d'auteur.

Valeur: le droit d'auteur.

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Obtient ou définit le rendu personnalisé.

Valeur : Le rendu personnalisé.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtient ou définit la date et l'heure.

Valeur : La date et l'heure.

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Obtient ou définit la date et l’heure de la numérisation.

Valeur : La date et l'heure de numérisation.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Obtient ou définit la date et l’heure d’origine.

Valeur : La date et l'heure d'origine.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Obtient ou définit la description des paramètres de l’appareil.

Valeur : La description des paramètres de l'appareil.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Obtient ou définit le rapport de zoom numérique.

Valeur : Le rapport de zoom numérique.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Obtient ou définit les balises qui appartiennent uniquement à la section EXIF.

Valeur : Les balises de la section EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Obtient ou définit la version EXIF.

Valeur : La version EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Obtient ou définit la valeur du biais d’exposition.

Valeur : La valeur du biais d'exposition.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Obtient ou définit l’indice d’exposition.

Valeur : L'index de l'exposition.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Obtient ou définit le mode d'exposition.

Valeur : Le mode d'exposition.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Obtient ou définit le programme d'exposition.

Valeur : Le programme d'exposition.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Obtient ou définit le temps d'exposition.

Valeur : Le temps d'exposition.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Obtient ou définit le nombre F.

Valeur : Le nombre F.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Obtient ou définit le type de source du fichier.

Valeur : Le type de source du fichier.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Obtient ou définit le flash.

Valeur : Le flash.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Obtient ou définit l'énergie du flash.

Valeur : L'énergie du flash.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Obtient ou définit la version du flash pix.

Valeur: La version flash pix.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Obtient ou définit la distance focale.

Valeur: La longueur du focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Obtient ou définit la distance focale en film 35 mm.

Valeur: La longueur focale en film 35 mm.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Obtient ou définit l'unité de résolution du plan focal.

Valeur: L'unité de résolution du plan focal.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Obtient ou définit la résolution X du plan focal.

Valeur: La résolution x du plan focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Obtient ou définit la résolution Y du plan focal.

Valeur: La résolution y du plan focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Obtient ou définit l'altitude GPS.

Valeur: L'altitude GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Obtient ou définit l'altitude GPS utilisée comme altitude de référence.

Valeur: L'altitude GPS utilisée comme altitude de référence.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Obtient ou définit les informations de zone GPS.

Valeur: L'information de zone GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Obtient ou définit le DOP GPS (degré de précision des données).

Valeur: Le DOP GPS (degré de précision des données).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné).

Valeur: La chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Obtient ou définit l'azimut GPS vers le point de destination.

Valeur: L'azimut GPS vers le point de destination.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination.

Valeur: La référence GPS utilisée pour fournir l'azimut vers le point de destination.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Obtient ou définit la distance GPS au point de destination.

Valeur: La distance GPS au point de destination.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Obtient ou définit l'unité GPS utilisée pour exprimer la distance au point de destination.

Valeur: L'unité GPS utilisée pour exprimer la distance au point de destination.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Obtient ou définit la latitude GPS du point de destination.

Valeur: La latitude GPS du point de destination.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est nord ou sud.

Valeur: La valeur GPS indiquant si la latitude du point de destination est nord ou sud.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Obtient ou définit la longitude GPS du point de destination.

Valeur: La longitude GPS du point de destination.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Obtient ou définit la valeur GPS qui indique si la longitude du point de destination est à l’est ou à l’ouest.

Valeur: La valeur GPS indiquant si la longitude du point de destination est est ou ouest.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Obtient ou définit une valeur GPS qui indique si une correction différentielle est appliquée au récepteur GPS.

Valeur: La valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Obtient ou définit la direction GPS de l’image lorsqu’elle a été capturée.

Valeur: La direction GPS de l'image lorsqu'elle a été capturée.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Obtient ou définit la référence GPS indiquant la direction de l’image lorsqu’elle est capturée.

Valeur: La référence GPS pour fournir la direction de l'image lorsqu'elle est capturée.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Obtient ou définit la latitude GPS.

Valeur: La latitude GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Obtient ou définit si la latitude GPS est nord ou sud.

Valeur: La latitude GPS est nord ou sud.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Obtient ou définit la longitude GPS.

Valeur : La longitude GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Obtient ou définit si la longitude GPS est à l’est ou à l’ouest.

Valeur : La longitude GPS est la longitude est ou ouest.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Obtient ou définit les données de levé géodésique GPS utilisées par le récepteur GPS.

Valeur : Les données d'arpentage géodésique GPS utilisées par le récepteur GPS.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Obtient ou définit le mode de mesure GPS.

Valeur : Le mode de mesure GPS.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

Valeur : La chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Obtient ou définit les satellites GPS utilisés pour les mesures.

Valeur : Les satellites GPS utilisés pour les mesures.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Obtient ou définit la vitesse du mouvement du récepteur GPS.

Valeur : La vitesse du mouvement du récepteur GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Obtient ou définit l’unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS.

Valeur : L'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Obtient ou définit l’état du récepteur GPS lorsque l’image est enregistrée.

Valeur : L'état du récepteur GPS lorsque l'image est enregistrée.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Obtient ou définit les balises, qui appartiennent uniquement à la section GPS.

Valeur : Les balises GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Obtient ou définit le temps GPS en UTC (Temps Universel Coordonné).

Valeur : L'heure GPS en UTC (Temps Universel Coordonné).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Obtient ou définit la direction du mouvement du récepteur GPS.

Valeur : La direction du mouvement du récepteur GPS.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Obtient ou définit la référence indiquant la direction du mouvement du récepteur GPS.

Valeur : La référence pour donner la direction du mouvement du récepteur GPS.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Obtient ou définit l’identifiant de version GPS.

Valeur : L'identifiant de version GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Obtient ou définit le degré d’ajustement global du gain de l’image.

Valeur : Le degré d'ajustement global du gain de l'image.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Obtient ou définit le gamma.

Valeur : La valeur gamma.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Obtient ou définit la vitesse ISO

Valeur : La vitesse ISO.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Obtient ou définit la valeur de latitude yyy de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232.

Valeur : La valeur de latitude yyy de vitesse ISO d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Obtient ou définit la valeur de latitude zzz de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232.

Valeur : La valeur de latitude zzz de vitesse ISO d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudeyyy

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtient ou définit la description de l'image.

Valeur : La description de l'image.

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtient ou définit la longueur de l'image.

Valeur : La longueur de l'image.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Obtient ou définit l'identifiant unique de l'image.

Valeur : L'identifiant unique de l'image.

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtient ou définit la largeur de l'image.

Valeur : La largeur de l'image.

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Obtient ou définit le fabricant de l'objectif.

Valeur : Le fabricant de l'objectif.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Obtient ou définit le modèle de l'objectif.

Valeur : Le modèle de l'objectif.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Obtient ou définit le numéro de série de l'objectif.

Valeur : Le numéro de série de l'objectif.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Obtient ou définit la spécification de l'objectif

Valeur: La spécification de l'objectif.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Obtient ou définit la source de lumière.

Valeur: La source de lumière.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Obtient le fabricant de l'équipement d'enregistrement.

Valeur: Le fabricant de l'équipement d'enregistrement.

**Returns:**
java.lang.String - le fabricant de l'équipement d'enregistrement.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Obtient les données de la note du fabricant.

Valeur: Les données de la note du fabricant.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Obtient ou définit les données brutes de la note du fabricant.

Valeur: Les données brutes de la note du fabricant.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Obtient les notes du fabricant.

Valeur: Les notes du fabricant.

**Returns:**
com.aspose.psd.exif.MakerNote[] - les notes du fabricant.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Obtient ou définit la valeur maximale d'ouverture.

Valeur: La valeur d'ouverture maximale.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Obtient ou définit le mode de mesure.

Valeur: Le mode de mesure.

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


Obtient ou définit le modèle.

Valeur : Le modèle.

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

Valeur: La fonction de conversion opto‑électrique (OECF) spécifiée dans la norme ISO 14524.

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtient ou définit l'orientation.

Valeur : L'orientation.

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Obtient ou définit la sensibilité photographique.

Valeur: La sensibilité photographique.

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Obtient ou définit l'interprétation photométrique.

Valeur : L'interprétation photométrique.

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Obtient ou définit la dimension x du pixel.

Valeur: La dimension x du pixel.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Obtient ou définit la dimension y du pixel.

Valeur: La dimension y du pixel.

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtient ou définit la configuration planaire.

Valeur : La configuration planaire.

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Obtient ou définit la chromaticité des trois couleurs primaires de l'image.

Valeur : La chromaticité des trois couleurs primaires de l'image.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Obtient ou définit toutes les balises EXIF (y compris les balises communes et GPS).

Valeur: Les balises EXIF (y compris les balises communes et GPS).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Obtient ou définit l'indice d'exposition recommandé.

Valeur: L'indice d'exposition recommandé.

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Obtient ou définit le noir et blanc de référence.

Valeur : La référence noir et blanc.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Obtient ou définit le fichier audio associé.

Valeur: Le fichier audio associé.

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtient ou définit l'unité de résolution.

Valeur : L'unité de résolution.

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtient ou définit les échantillons par pixel.

Valeur : Les échantillons par pixel.

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Obtient ou définit la saturation.

Valeur: La saturation.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Obtient ou définit le type de capture de la scène.

Valeur: Le type de capture de la scène.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Obtient ou définit le type de scène.

Valeur: Le type de la scène.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Obtient ou définit la méthode de détection.

Valeur: La méthode de détection.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Obtient ou définit le type de sensibilité.

Valeur: Le type de sensibilité.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Obtient ou définit la netteté.

Valeur: La netteté.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Obtient ou définit la valeur de la vitesse d’obturation.

Valeur: La valeur de la vitesse d'obturation.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Obtient ou définit le logiciel.

Valeur : Le logiciel.

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Obtient ou définit la réponse en fréquence spatiale.

Valeur: La réponse en fréquence spatiale.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Obtient ou définit la sensibilité spectrale.

Valeur: La sensibilité spectrale.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Obtient la sensibilité de sortie standard

Valeur: La sensibilité de sortie standard.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Obtient ou définit la zone du sujet.

Valeur: La zone du sujet.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Obtient ou définit la distance du sujet.

Valeur: La distance du sujet.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Obtient ou définit la plage de distance du sujet.

Valeur: La plage de distance du sujet.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Obtient ou définit l’emplacement du sujet.

Valeur: L'emplacement du sujet.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Obtient ou définit les fractions de seconde pour la balise DateTime.

Valeur: Les fractions de seconde pour la balise DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized.

Valeur: Les fractions de seconde pour la balise DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal.

Valeur: Les fractions de seconde pour la balise DateTimeOriginal.

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


Obtient ou définit l'image miniature.

Valeur : La vignette.

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Obtient ou définit la fonction de transfert.

Valeur : La fonction de transfert.

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Obtient ou définit le commentaire de l’utilisateur.

Valeur: Le commentaire de l'utilisateur.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Obtient ou définit la balance des blancs.

Valeur: La balance des blancs.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Obtient ou définit la chromaticité du point blanc de l’image.

Valeur: La chromaticité du point blanc de l'image.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Obtient ou définit la résolution x.

Valeur : La résolution x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

Valeur : Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Obtient ou définit la position des composants de chrominance par rapport au composant de luminance.

Valeur : La position des composants de chrominance par rapport au composant de luminance.

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance.

Valeur : Le taux d'échantillonnage des composants de chrominance par rapport au composant de luminance.

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Obtient ou définit la résolution y.

Valeur : La résolution y.

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


Obtient ou définit une valeur indiquant si le flux de données EXIF créé à partir de celui‑ci est en big endian.

Valeur:  true  si le flux de données EXIF créé à partir de celui-ci est big endian ; sinon,  false .

**Returns:**
booléen
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


Supprimer la balise du conteneur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant de balise à supprimer. |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Sérialise les données EXIF. Écrit les valeurs et le contenu des balises. La balise de taille la plus influente est le contenu de la balise Thumbnail.

**Returns:**
byte[] - Les données EXIF sérialisées.

La taille totale du segment doit être inférieure ou égale à MaxExifSegmentSize octets afin de produire une image jpeg correcte. Astuce : essayez de réduire la taille du thumbnail ou de modifier sa compression dans le cas où vous avez une section EXIF trop grande.
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Obtient ou définit la valeur de l’ouverture.

Valeur : la valeur d’ouverture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtient ou définit l'artiste.

Valeur: l'artiste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Obtient ou définit une valeur indiquant si le flux de données EXIF créé à partir de celui‑ci est en big endian.

Valeur:  true  si le flux de données EXIF créé à partir de celui-ci est big endian ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Obtient ou définit les bits par échantillon.

Valeur: les bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Obtient ou définit le numéro de série du boîtier de l’appareil photo.

Valeur : le numéro de série du boîtier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Obtient ou définit la valeur de la luminosité.

Valeur : la valeur de luminosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Obtient ou définit le motif CFA.

Valeur : Le motif CFA.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Obtient ou définit le nom du propriétaire de l’appareil.

Valeur : Le nom du propriétaire de l'appareil photo.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Obtient ou définit l’espace colorimétrique.

Valeur : L'espace colorimétrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Obtient ou définit les balises, qui appartiennent à la section commune. Cela s'applique uniquement aux images jpeg, dans le format tiff les tiffOptions sont utilisés à la place

Valeur : Les balises de la section commune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Obtient ou définit la configuration des composants.

Valeur : La configuration des composants.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Obtient ou définit les bits compressés par pixel.

Valeur : Les bits compressés par pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Obtient ou définit la compression.

Valeur: la compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Obtient ou définit le contraste.

Valeur : Le contraste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Obtient ou définit le droit d'auteur.

Valeur: le droit d'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Obtient ou définit le rendu personnalisé.

Valeur : Le rendu personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtient ou définit la date et l'heure.

Valeur : La date et l'heure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Obtient ou définit la date et l’heure de la numérisation.

Valeur : La date et l'heure de numérisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Obtient ou définit la date et l’heure d’origine.

Valeur : La date et l'heure d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Obtient ou définit la description des paramètres de l’appareil.

Valeur : La description des paramètres de l'appareil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Obtient ou définit le rapport de zoom numérique.

Valeur : Le rapport de zoom numérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Obtient ou définit les balises qui appartiennent uniquement à la section EXIF.

Valeur : Les balises de la section EXIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Obtient ou définit la version EXIF.

Valeur : La version EXIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Obtient ou définit la valeur du biais d’exposition.

Valeur : La valeur du biais d'exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Obtient ou définit l’indice d’exposition.

Valeur : L'index de l'exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Obtient ou définit le mode d'exposition.

Valeur : Le mode d'exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Obtient ou définit le programme d'exposition.

Valeur : Le programme d'exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Obtient ou définit le temps d'exposition.

Valeur : Le temps d'exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Obtient ou définit le nombre F.

Valeur : Le nombre F.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Obtient ou définit le type de source du fichier.

Valeur : Le type de source du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Obtient ou définit le flash.

Valeur : Le flash.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Obtient ou définit l'énergie du flash.

Valeur : L'énergie du flash.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Obtient ou définit la version du flash pix.

Valeur: La version flash pix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Obtient ou définit la distance focale.

Valeur: La longueur du focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Obtient ou définit la distance focale en film 35 mm.

Valeur: La longueur focale en film 35 mm.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Obtient ou définit l'unité de résolution du plan focal.

Valeur: L'unité de résolution du plan focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Obtient ou définit la résolution X du plan focal.

Valeur: La résolution x du plan focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Obtient ou définit la résolution Y du plan focal.

Valeur: La résolution y du plan focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Obtient ou définit l'altitude GPS.

Valeur: L'altitude GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Obtient ou définit l'altitude GPS utilisée comme altitude de référence.

Valeur: L'altitude GPS utilisée comme altitude de référence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Obtient ou définit les informations de zone GPS.

Valeur: L'information de zone GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Obtient ou définit le DOP GPS (degré de précision des données).

Valeur: Le DOP GPS (degré de précision des données).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné).

Valeur: La chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Obtient ou définit l'azimut GPS vers le point de destination.

Valeur: L'azimut GPS vers le point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination.

Valeur: La référence GPS utilisée pour fournir l'azimut vers le point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Obtient ou définit la distance GPS au point de destination.

Valeur: La distance GPS au point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Obtient ou définit l'unité GPS utilisée pour exprimer la distance au point de destination.

Valeur: L'unité GPS utilisée pour exprimer la distance au point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Obtient ou définit la latitude GPS du point de destination.

Valeur: La latitude GPS du point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est nord ou sud.

Valeur: La valeur GPS indiquant si la latitude du point de destination est nord ou sud.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Obtient ou définit la longitude GPS du point de destination.

Valeur: La longitude GPS du point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Obtient ou définit la valeur GPS qui indique si la longitude du point de destination est à l’est ou à l’ouest.

Valeur: La valeur GPS indiquant si la longitude du point de destination est est ou ouest.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Obtient ou définit une valeur GPS qui indique si une correction différentielle est appliquée au récepteur GPS.

Valeur: La valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Obtient ou définit la direction GPS de l’image lorsqu’elle a été capturée.

Valeur: La direction GPS de l'image lorsqu'elle a été capturée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Obtient ou définit la référence GPS indiquant la direction de l’image lorsqu’elle est capturée.

Valeur: La référence GPS pour fournir la direction de l'image lorsqu'elle est capturée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Obtient ou définit la latitude GPS.

Valeur: La latitude GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Obtient ou définit si la latitude GPS est nord ou sud.

Valeur: La latitude GPS est nord ou sud.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Obtient ou définit la longitude GPS.

Valeur : La longitude GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Obtient ou définit si la longitude GPS est à l’est ou à l’ouest.

Valeur : La longitude GPS est la longitude est ou ouest.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Obtient ou définit les données de levé géodésique GPS utilisées par le récepteur GPS.

Valeur : Les données d'arpentage géodésique GPS utilisées par le récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Obtient ou définit le mode de mesure GPS.

Valeur : Le mode de mesure GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

Valeur : La chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Obtient ou définit les satellites GPS utilisés pour les mesures.

Valeur : Les satellites GPS utilisés pour les mesures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Obtient ou définit la vitesse du mouvement du récepteur GPS.

Valeur : La vitesse du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Obtient ou définit l’unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS.

Valeur : L'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Obtient ou définit l’état du récepteur GPS lorsque l’image est enregistrée.

Valeur : L'état du récepteur GPS lorsque l'image est enregistrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Obtient ou définit les balises, qui appartiennent uniquement à la section GPS.

Valeur : Les balises GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Obtient ou définit le temps GPS en UTC (Temps Universel Coordonné).

Valeur : L'heure GPS en UTC (Temps Universel Coordonné).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Obtient ou définit la direction du mouvement du récepteur GPS.

Valeur : La direction du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Obtient ou définit la référence indiquant la direction du mouvement du récepteur GPS.

Valeur : La référence pour donner la direction du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Obtient ou définit l’identifiant de version GPS.

Valeur : L'identifiant de version GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Obtient ou définit le degré d’ajustement global du gain de l’image.

Valeur : Le degré d'ajustement global du gain de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Obtient ou définit le gamma.

Valeur : La valeur gamma.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Obtient ou définit la vitesse ISO

Valeur : La vitesse ISO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Obtient ou définit la valeur de latitude yyy de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232.

Valeur : La valeur de latitude yyy de vitesse ISO d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudezzz

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Obtient ou définit la valeur de latitude zzz de vitesse ISO d’un appareil photo ou dispositif d’entrée définie dans la norme ISO 12232.

Valeur : La valeur de latitude zzz de vitesse ISO d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudeyyy

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtient ou définit la description de l'image.

Valeur : La description de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtient ou définit la longueur de l'image.

Valeur : La longueur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Obtient ou définit l'identifiant unique de l'image.

Valeur : L'identifiant unique de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtient ou définit la largeur de l'image.

Valeur : La largeur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Obtient ou définit le fabricant de l'objectif.

Valeur : Le fabricant de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Obtient ou définit le modèle de l'objectif.

Valeur : Le modèle de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Obtient ou définit le numéro de série de l'objectif.

Valeur : Le numéro de série de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Obtient ou définit la spécification de l'objectif

Valeur: La spécification de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Obtient ou définit la source de lumière.

Valeur: La source de lumière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Définit le fabricant de l’équipement d’enregistrement.

Valeur: Le fabricant de l'équipement d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | le fabricant de l'équipement d'enregistrement. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Obtient ou définit les données brutes de la note du fabricant.

Valeur: Les données brutes de la note du fabricant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Obtient ou définit la valeur maximale d'ouverture.

Valeur: La valeur d'ouverture maximale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Obtient ou définit le mode de mesure.

Valeur: Le mode de mesure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Obtient ou définit le modèle.

Valeur : Le modèle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

Valeur: La fonction de conversion opto‑électrique (OECF) spécifiée dans la norme ISO 14524.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtient ou définit l'orientation.

Valeur : L'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Obtient ou définit la sensibilité photographique.

Valeur: La sensibilité photographique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Obtient ou définit l'interprétation photométrique.

Valeur : L'interprétation photométrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Obtient ou définit la dimension x du pixel.

Valeur: La dimension x du pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Obtient ou définit la dimension y du pixel.

Valeur: La dimension y du pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtient ou définit la configuration planaire.

Valeur : La configuration planaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Obtient ou définit la chromaticité des trois couleurs primaires de l'image.

Valeur : La chromaticité des trois couleurs primaires de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Obtient ou définit toutes les balises EXIF (y compris les balises communes et GPS).

Valeur: Les balises EXIF (y compris les balises communes et GPS).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Obtient ou définit l'indice d'exposition recommandé.

Valeur: L'indice d'exposition recommandé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Obtient ou définit le noir et blanc de référence.

Valeur : La référence noir et blanc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Obtient ou définit le fichier audio associé.

Valeur: Le fichier audio associé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtient ou définit l'unité de résolution.

Valeur : L'unité de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Obtient ou définit les échantillons par pixel.

Valeur : Les échantillons par pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Obtient ou définit la saturation.

Valeur: La saturation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Obtient ou définit le type de capture de la scène.

Valeur: Le type de capture de la scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Obtient ou définit le type de scène.

Valeur: Le type de la scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Obtient ou définit la méthode de détection.

Valeur: La méthode de détection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Obtient ou définit le type de sensibilité.

Valeur: Le type de sensibilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Obtient ou définit la netteté.

Valeur: La netteté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Obtient ou définit la valeur de la vitesse d’obturation.

Valeur: La valeur de la vitesse d'obturation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Obtient ou définit le logiciel.

Valeur : Le logiciel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Obtient ou définit la réponse en fréquence spatiale.

Valeur: La réponse en fréquence spatiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Obtient ou définit la sensibilité spectrale.

Valeur: La sensibilité spectrale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Définit la sensibilité de sortie standard

Valeur: La sensibilité de sortie standard.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Obtient ou définit la zone du sujet.

Valeur: La zone du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Obtient ou définit la distance du sujet.

Valeur: La distance du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Obtient ou définit la plage de distance du sujet.

Valeur: La plage de distance du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Obtient ou définit l’emplacement du sujet.

Valeur: L'emplacement du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Obtient ou définit les fractions de seconde pour la balise DateTime.

Valeur: Les fractions de seconde pour la balise DateTime.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized.

Valeur: Les fractions de seconde pour la balise DateTimeDigitized.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal.

Valeur: Les fractions de seconde pour la balise DateTimeOriginal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


Obtient ou définit l'image miniature.

Valeur : La vignette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Obtient ou définit la fonction de transfert.

Valeur : La fonction de transfert.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Obtient ou définit le commentaire de l’utilisateur.

Valeur: Le commentaire de l'utilisateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Obtient ou définit la balance des blancs.

Valeur: La balance des blancs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Obtient ou définit la chromaticité du point blanc de l’image.

Valeur: La chromaticité du point blanc de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Obtient ou définit la résolution x.

Valeur : La résolution x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

Valeur : Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Obtient ou définit la position des composants de chrominance par rapport au composant de luminance.

Valeur : La position des composants de chrominance par rapport au composant de luminance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance.

Valeur : Le taux d'échantillonnage des composants de chrominance par rapport au composant de luminance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Obtient ou définit la résolution y.

Valeur : La résolution y.

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

