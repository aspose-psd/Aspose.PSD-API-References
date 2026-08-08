---
title: "ExifData"
second_title: "Aspose.PSD voor Java API-referentie"
description: "EXIF-gegevenscontainer."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

EXIF-gegevenscontainer.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ExifData()](#ExifData--) | Initialiseert een nieuw exemplaar van de  ExifData  klasse. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialiseert een nieuw exemplaar van de  ExifData  klasse met gegevens uit een array. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialiseert een nieuw exemplaar van de  ExifData  klasse met gegevens uit een array. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Haalt de diafragmawaarde op of stelt deze in. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Haalt het serienummer van de camerabehuizing op of stelt dit in. |
| [getBrightnessValue()](#getBrightnessValue--) | Haalt de helderheidswaarde op of stelt deze in. |
| [getCFAPattern()](#getCFAPattern--) | Haalt het CFA-patroon op of stelt dit in. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Haalt de naam van de camerabezitter op of stelt deze in |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Haalt de kleurruimte op of stelt deze in. |
| [getCommonTags()](#getCommonTags--) | Haalt tags op of stelt ze in, die tot de algemene sectie behoren. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Haalt de componentconfiguratie op of stelt deze in. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Haalt het aantal gecomprimeerde bits per pixel op of stelt dit in. |
| [getContrast()](#getContrast--) | Haalt het contrast op of stelt dit in. |
| [getCustomRendered()](#getCustomRendered--) | Haalt de aangepaste rendering op of stelt deze in. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Haalt de gedigitaliseerde datum/tijd op of stelt deze in. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Haalt de oorspronkelijke datum/tijd op of stelt deze in. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Geeft of stelt de beschrijving van de apparaatinstellingen in |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Geeft of stelt de digitale zoomverhouding in. |
| [getExifTags()](#getExifTags--) | Geeft of stelt tags in die alleen tot de EXIF‑sectie behoren. |
| [getExifVersion()](#getExifVersion--) | Geeft of stelt de EXIF‑versie in. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Geeft of stelt de belichtingsbiaswaarde in. |
| [getExposureIndex()](#getExposureIndex--) | Geeft of stelt de belichtingsindex in. |
| [getExposureMode()](#getExposureMode--) | Geeft of stelt de belichtingsmodus in. |
| [getExposureProgram()](#getExposureProgram--) | Geeft of stelt het belichtingsprogramma in. |
| [getExposureTime()](#getExposureTime--) | Geeft of stelt de belichtingstijd in. |
| [getFNumber()](#getFNumber--) | Geeft of stelt het F‑getal in. |
| [getFileSource()](#getFileSource--) | Geeft of stelt het type bestandbron in. |
| [getFlash()](#getFlash--) | Geeft of stelt de flits in. |
| [getFlashEnergy()](#getFlashEnergy--) | Geeft of stelt de flitsenergie in. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Geeft of stelt de flash‑pix‑versie in. |
| [getFocalLength()](#getFocalLength--) | Geeft of stelt de brandpuntsafstand in. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Geeft of stelt de brandpuntsafstand in 35 mm film in. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Geeft of stelt de resolutie‑eenheid van het brandpuntvlak in. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Geeft of stelt de X‑resolutie van het brandpuntvlak in. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Geeft of stelt de Y‑resolutie van het brandpuntvlak in. |
| [getGPSAltitude()](#getGPSAltitude--) | Geeft of stelt de GPS‑hoogte in. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Geeft of stelt de GPS‑hoogte die als referentiehoogte wordt gebruikt in. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Geeft of stelt de GPS‑gebiedsinformatie in. |
| [getGPSDOP()](#getGPSDOP--) | Geeft of stelt de GPS‑DOP (data‑graad van precisie) in. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Geeft of stelt de GPS‑karakterreeks die datum‑ en tijdinformatie registreert ten opzichte van UTC (gecoördineerde wereldtijd) in. |
| [getGPSDestBearing()](#getGPSDestBearing--) | Geeft of stelt de GPS‑richting naar het bestemmingspunt in. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Krijgt of stelt de GPS-referentie in die wordt gebruikt om de koers naar het bestemmingspunt te geven. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Krijgt of stelt de GPS-afstand tot het bestemmingspunt in. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Krijgt of stelt de GPS-eenheid in die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Krijgt of stelt de GPS-breedtegraad van het bestemmingspunt in. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Krijgt of stelt de GPS-waarde in die aangeeft of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Krijgt of stelt de GPS-lengtegraad van het bestemmingspunt in. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Krijgt of stelt de GPS-waarde in die aangeeft of de lengtegraad van het bestemmingspunt oost- of westelijk is. |
| [getGPSDifferential()](#getGPSDifferential--) | Krijgt of stelt een GPS-waarde in die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Krijgt of stelt de GPS-richting van de afbeelding in op het moment van opname. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Krijgt of stelt de GPS-referentie in voor het aangeven van de richting van de afbeelding bij opname. |
| [getGPSLatitude()](#getGPSLatitude--) | Krijgt of stelt de GPS-breedtegraad in. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Krijgt of stelt in of de GPS-breedtegraad noord- of zuiderbreedte is. |
| [getGPSLongitude()](#getGPSLongitude--) | Krijgt of stelt de GPS-lengtegraad in. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Krijgt of stelt in of de GPS-lengtegraad oost- of westelijk is. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Krijgt of stelt de GPS-geodetische surveygegevens in die door de GPS-ontvanger worden gebruikt. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Krijgt of stelt de GPS-meetmodus in. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Krijgt of stelt de GPS-tekenreeks in die de naam van de methode voor locatiebepaling registreert. |
| [getGPSSatellites()](#getGPSSatellites--) | Krijgt of stelt de GPS-satellieten in die voor metingen worden gebruikt. |
| [getGPSSpeed()](#getGPSSpeed--) | Krijgt of stelt de snelheid van de GPS-ontvangerbeweging in. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Krijgt of stelt de eenheid in die wordt gebruikt om de snelheid van de GPS-ontvangerbeweging uit te drukken. |
| [getGPSStatus()](#getGPSStatus--) | Krijgt of stelt de status van de GPS-ontvanger in wanneer de afbeelding wordt vastgelegd. |
| [getGPSTags()](#getGPSTags--) | Krijgt of stelt tags in die alleen tot de GPS-sectie behoren. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Krijgt of stelt de GPS-tijd in als UTC (gecoördineerde wereldtijd). |
| [getGPSTrack()](#getGPSTrack--) | Krijgt of stelt de richting van de GPS-ontvangerbeweging in. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Krijgt of stelt de referentie in voor het aangeven van de richting van de GPS-ontvangerbeweging. |
| [getGPSVersionID()](#getGPSVersionID--) | Haalt op of stelt de GPS-versie‑identificatie in. |
| [getGainControl()](#getGainControl--) | Haalt op of stelt de graad van algemene beeldversterkingsaanpassing in. |
| [getGamma()](#getGamma--) | Haalt op of stelt de gamma in. |
| [getISOSpeed()](#getISOSpeed--) | Haalt op of stelt de ISO-snelheid in. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Haalt op of stelt de ISO-snelheidsbreedte yyy‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Haalt op of stelt de ISO-snelheidsbreedte zzz‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232. |
| [getImageUniqueID()](#getImageUniqueID--) | Haalt op of stelt de unieke afbeelding‑identificatie in. |
| [getLensMake()](#getLensMake--) | Haalt op of stelt de fabrikant van het objectief in. |
| [getLensModel()](#getLensModel--) | Haalt op of stelt het objectiefmodel in. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Haalt op of stelt het serienummer van het objectief in. |
| [getLensSpecification()](#getLensSpecification--) | Haalt op of stelt de objectiefspecificatie in. |
| [getLightSource()](#getLightSource--) | Haalt op of stelt de lichtbron in. |
| [getMake()](#getMake--) | Haalt de fabrikant van de opname‑apparatuur op. |
| [getMakerNoteData()](#getMakerNoteData--) | Haalt de maker‑notitiegegevens op. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Haalt op of stelt de ruwe maker‑notitiegegevens in. |
| [getMakerNotes()](#getMakerNotes--) | Haalt de maker‑notities op. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Haalt op of stelt de maximale diafragmawaarde in. |
| [getMeteringMode()](#getMeteringMode--) | Haalt op of stelt de meetmodus in. |
| [getOECF()](#getOECF--) | Haalt op of stelt de Opto‑elektrische conversiefunctie (OECF) gespecificeerd in ISO 14524 in. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Haalt op of stelt de fotografische gevoeligheid in. |
| [getPixelXDimension()](#getPixelXDimension--) | Haalt op of stelt de pixel‑x‑dimensie in. |
| [getPixelYDimension()](#getPixelYDimension--) | Haalt op of stelt de pixel‑y‑dimensie in. |
| [getProperties()](#getProperties--) | Haalt op of stelt alle EXIF‑tags in (inclusief algemene en GPS‑tags). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Haalt op of stelt de aanbevolen belichtingsindex in. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Haalt op of stelt het gerelateerde geluidsbestand in. |
| [getSaturation()](#getSaturation--) | Haalt de verzadiging op of stelt deze in. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Haalt het type scène‑opname op of stelt dit in. |
| [getSceneType()](#getSceneType--) | Haalt het type scène op of stelt dit in. |
| [getSensingMethod()](#getSensingMethod--) | Haalt de detectiemethode op of stelt deze in. |
| [getSensitivityType()](#getSensitivityType--) | Haalt het type gevoeligheid op of stelt dit in. |
| [getSharpness()](#getSharpness--) | Haalt de scherpte op of stelt deze in. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Haalt de sluitertijdwaarde op of stelt deze in. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Haalt de ruimtelijke frequentierespons op of stelt deze in. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Haalt de spectrale gevoeligheid op of stelt deze in. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Haalt de standaard uitgangsgevoeligheid op |
| [getSubjectArea()](#getSubjectArea--) | Haalt het onderwerpgebied op of stelt dit in. |
| [getSubjectDistance()](#getSubjectDistance--) | Haalt de onderwerpafstand op of stelt deze in. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Haalt het bereik van de onderwerpafstand op of stelt dit in. |
| [getSubjectLocation()](#getSubjectLocation--) | Haalt de locatie van het onderwerp op of stelt deze in. |
| [getSubsecTime()](#getSubsecTime--) | Haalt de fracties van seconden voor de DateTime-tag op of stelt deze in. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Haalt de fracties van seconden voor de DateTimeDigitized-tag op of stelt deze in. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Haalt de fracties van seconden voor de DateTimeOriginal-tag op of stelt deze in. |
| [getUserComment()](#getUserComment--) | Haalt de gebruikersopmerking op of stelt deze in. |
| [getWhiteBalance()](#getWhiteBalance--) | Haalt de witbalans op of stelt deze in. |
| [getWhitePoint()](#getWhitePoint--) | Haalt de chromaticiteit van het witpunt van de afbeelding op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Haalt een waarde op of stelt deze in die aangeeft of de EXIF‑gegevensstroom die is gemaakt van big‑endian is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Verwijder tag uit container |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt de diafragmawaarde op of stelt deze in. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de EXIF‑gegevensstroom die is gemaakt van big‑endian is. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Haalt het serienummer van de camerabehuizing op of stelt dit in. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Haalt de helderheidswaarde op of stelt deze in. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Haalt het CFA-patroon op of stelt dit in. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Haalt de naam van de camerabezitter op of stelt deze in |
| [setColorSpace(int value)](#setColorSpace-int-) | Haalt de kleurruimte op of stelt deze in. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Haalt tags op of stelt ze in, die tot de algemene sectie behoren. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Haalt de componentconfiguratie op of stelt deze in. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt het aantal gecomprimeerde bits per pixel op of stelt dit in. |
| [setContrast(int value)](#setContrast-int-) | Haalt het contrast op of stelt dit in. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Haalt de aangepaste rendering op of stelt deze in. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Haalt de gedigitaliseerde datum/tijd op of stelt deze in. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Haalt de oorspronkelijke datum/tijd op of stelt deze in. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Geeft of stelt de beschrijving van de apparaatinstellingen in |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de digitale zoomverhouding in. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Geeft of stelt tags in die alleen tot de EXIF‑sectie behoren. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Geeft of stelt de EXIF‑versie in. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Geeft of stelt de belichtingsbiaswaarde in. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de belichtingsindex in. |
| [setExposureMode(int value)](#setExposureMode-int-) | Geeft of stelt de belichtingsmodus in. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Geeft of stelt het belichtingsprogramma in. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de belichtingstijd in. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt het F‑getal in. |
| [setFileSource(byte value)](#setFileSource-byte-) | Geeft of stelt het type bestandbron in. |
| [setFlash(int value)](#setFlash-int-) | Geeft of stelt de flits in. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de flitsenergie in. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Geeft of stelt de flash‑pix‑versie in. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de brandpuntsafstand in. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Geeft of stelt de brandpuntsafstand in 35 mm film in. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Geeft of stelt de resolutie‑eenheid van het brandpuntvlak in. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de X‑resolutie van het brandpuntvlak in. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de Y‑resolutie van het brandpuntvlak in. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de GPS‑hoogte in. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Geeft of stelt de GPS‑hoogte die als referentiehoogte wordt gebruikt in. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Geeft of stelt de GPS‑gebiedsinformatie in. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de GPS‑DOP (data‑graad van precisie) in. |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Geeft of stelt de GPS‑karakterreeks die datum‑ en tijdinformatie registreert ten opzichte van UTC (gecoördineerde wereldtijd) in. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Geeft of stelt de GPS‑richting naar het bestemmingspunt in. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Krijgt of stelt de GPS-referentie in die wordt gebruikt om de koers naar het bestemmingspunt te geven. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Krijgt of stelt de GPS-afstand tot het bestemmingspunt in. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Krijgt of stelt de GPS-eenheid in die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Krijgt of stelt de GPS-breedtegraad van het bestemmingspunt in. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Krijgt of stelt de GPS-waarde in die aangeeft of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Krijgt of stelt de GPS-lengtegraad van het bestemmingspunt in. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Krijgt of stelt de GPS-waarde in die aangeeft of de lengtegraad van het bestemmingspunt oost- of westelijk is. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Krijgt of stelt een GPS-waarde in die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Krijgt of stelt de GPS-richting van de afbeelding in op het moment van opname. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Krijgt of stelt de GPS-referentie in voor het aangeven van de richting van de afbeelding bij opname. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Krijgt of stelt de GPS-breedtegraad in. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Krijgt of stelt in of de GPS-breedtegraad noord- of zuiderbreedte is. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Krijgt of stelt de GPS-lengtegraad in. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Krijgt of stelt in of de GPS-lengtegraad oost- of westelijk is. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Krijgt of stelt de GPS-geodetische surveygegevens in die door de GPS-ontvanger worden gebruikt. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Krijgt of stelt de GPS-meetmodus in. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Krijgt of stelt de GPS-tekenreeks in die de naam van de methode voor locatiebepaling registreert. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Krijgt of stelt de GPS-satellieten in die voor metingen worden gebruikt. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Krijgt of stelt de snelheid van de GPS-ontvangerbeweging in. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Krijgt of stelt de eenheid in die wordt gebruikt om de snelheid van de GPS-ontvangerbeweging uit te drukken. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Krijgt of stelt de status van de GPS-ontvanger in wanneer de afbeelding wordt vastgelegd. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Krijgt of stelt tags in die alleen tot de GPS-sectie behoren. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Krijgt of stelt de GPS-tijd in als UTC (gecoördineerde wereldtijd). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Krijgt of stelt de richting van de GPS-ontvangerbeweging in. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Krijgt of stelt de referentie in voor het aangeven van de richting van de GPS-ontvangerbeweging. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Haalt op of stelt de GPS-versie‑identificatie in. |
| [setGainControl(int value)](#setGainControl-int-) | Haalt op of stelt de graad van algemene beeldversterkingsaanpassing in. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt op of stelt de gamma in. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Haalt op of stelt de ISO-snelheid in. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Haalt op of stelt de ISO-snelheidsbreedte yyy‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Haalt op of stelt de ISO-snelheidsbreedte zzz‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Haalt op of stelt de unieke afbeelding‑identificatie in. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Haalt op of stelt de fabrikant van het objectief in. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Haalt op of stelt het objectiefmodel in. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Haalt op of stelt het serienummer van het objectief in. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Haalt op of stelt de objectiefspecificatie in. |
| [setLightSource(int value)](#setLightSource-int-) | Haalt op of stelt de lichtbron in. |
| [setMake(String value)](#setMake-java.lang.String-) | Stelt de fabrikant van de opnameapparatuur in. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Haalt op of stelt de ruwe maker‑notitiegegevens in. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt op of stelt de maximale diafragmawaarde in. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Haalt op of stelt de meetmodus in. |
| [setOECF(byte[] value)](#setOECF-byte---) | Haalt op of stelt de Opto‑elektrische conversiefunctie (OECF) gespecificeerd in ISO 14524 in. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Haalt op of stelt de fotografische gevoeligheid in. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Haalt op of stelt de pixel‑x‑dimensie in. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Haalt op of stelt de pixel‑y‑dimensie in. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Haalt op of stelt alle EXIF‑tags in (inclusief algemene en GPS‑tags). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Haalt op of stelt de aanbevolen belichtingsindex in. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Haalt op of stelt het gerelateerde geluidsbestand in. |
| [setSaturation(int value)](#setSaturation-int-) | Haalt de verzadiging op of stelt deze in. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Haalt het type scène‑opname op of stelt dit in. |
| [setSceneType(byte value)](#setSceneType-byte-) | Haalt het type scène op of stelt dit in. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Haalt de detectiemethode op of stelt deze in. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Haalt het type gevoeligheid op of stelt dit in. |
| [setSharpness(int value)](#setSharpness-int-) | Haalt de scherpte op of stelt deze in. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Haalt de sluitertijdwaarde op of stelt deze in. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Haalt de ruimtelijke frequentierespons op of stelt deze in. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Haalt de spectrale gevoeligheid op of stelt deze in. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Stelt de standaard uitgangsgevoeligheid in |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Haalt het onderwerpgebied op of stelt dit in. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt de onderwerpafstand op of stelt deze in. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Haalt het bereik van de onderwerpafstand op of stelt dit in. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Haalt de locatie van het onderwerp op of stelt deze in. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Haalt de fracties van seconden voor de DateTime-tag op of stelt deze in. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Haalt de fracties van seconden voor de DateTimeDigitized-tag op of stelt deze in. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Haalt de fracties van seconden voor de DateTimeOriginal-tag op of stelt deze in. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Haalt de gebruikersopmerking op of stelt deze in. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Haalt de witbalans op of stelt deze in. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Haalt de chromaticiteit van het witpunt van de afbeelding op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


Initialiseert een nieuw exemplaar van de  ExifData  klasse.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Initialiseert een nieuw exemplaar van de  ExifData  klasse met gegevens uit een array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Array van EXIF-tags samen met algemene en GPS-tags. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialiseert een nieuw exemplaar van de  ExifData  klasse met gegevens uit een array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De algemene tags. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De EXIF-tags. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De GPS-tags. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Haalt de diafragmawaarde op of stelt deze in.

Waarde: de diafragmawaarde.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Haalt het serienummer van de camerabehuizing op of stelt dit in.

Waarde: het serienummer van de body.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Haalt de helderheidswaarde op of stelt deze in.

Waarde: de helderheidswaarde.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Haalt het CFA-patroon op of stelt dit in.

Waarde: het CFA-patroon.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Haalt de naam van de camerabezitter op of stelt deze in

Waarde: de naam van de camerabezitter.

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


Haalt de kleurruimte op of stelt deze in.

Waarde: de kleurenruimte.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Haalt tags op of stelt ze in die tot de algemene sectie behoren. Dit geldt alleen voor jpeg-afbeeldingen; in tiff-formaat worden in plaats daarvan tiffOptions gebruikt.

Waarde: de tags van de algemene sectie.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Haalt de componentconfiguratie op of stelt deze in.

Waarde: de componentconfiguratie.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Haalt het aantal gecomprimeerde bits per pixel op of stelt dit in.

Waarde: het aantal gecomprimeerde bits per pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


Haalt het contrast op of stelt dit in.

Waarde: het contrast.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Haalt de aangepaste rendering op of stelt deze in.

Waarde: de aangepaste rendering.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Haalt de gedigitaliseerde datum/tijd op of stelt deze in.

Waarde: de gedigitaliseerde datum en tijd.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Haalt de oorspronkelijke datum/tijd op of stelt deze in.

Waarde: de oorspronkelijke datum en tijd.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Geeft of stelt de beschrijving van de apparaatinstellingen in

Waarde: de beschrijving van de apparaatinstellingen.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Geeft of stelt de digitale zoomverhouding in.

Waarde: de digitale zoomverhouding.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Geeft of stelt tags in die alleen tot de EXIF‑sectie behoren.

Waarde: de EXIF-sectietags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Geeft of stelt de EXIF‑versie in.

Waarde: de EXIF-versie.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Geeft of stelt de belichtingsbiaswaarde in.

Waarde: de belichtingsbiaswaarde.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Geeft of stelt de belichtingsindex in.

Waarde: de index van de belichting.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Geeft of stelt de belichtingsmodus in.

Waarde: de belichtingsmodus.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Geeft of stelt het belichtingsprogramma in.

Waarde: Het belichtingsprogramma.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Geeft of stelt de belichtingstijd in.

Waarde: De belichtingstijd.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Geeft of stelt het F‑getal in.

Waarde: Het F-getal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Geeft of stelt het type bestandbron in.

Waarde: Het type bestandbron.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Geeft of stelt de flits in.

Waarde: De flits.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Geeft of stelt de flitsenergie in.

Waarde: De flitsenergie.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Geeft of stelt de flash‑pix‑versie in.

Waarde: De flash-pix versie.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Geeft of stelt de brandpuntsafstand in.

Waarde: De lengte van de brandpuntsafstand.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Geeft of stelt de brandpuntsafstand in 35 mm film in.

Waarde: De brandpuntsafstand in 35 mm film.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Geeft of stelt de resolutie‑eenheid van het brandpuntvlak in.

Waarde: De resolutie-eenheid van het brandvlak.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Geeft of stelt de X‑resolutie van het brandpuntvlak in.

Waarde: De x-resolutie van het brandvlak.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Geeft of stelt de Y‑resolutie van het brandpuntvlak in.

Waarde: De y-resolutie van het brandvlak.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Geeft of stelt de GPS‑hoogte in.

Waarde: De GPS-hoogte.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Geeft of stelt de GPS‑hoogte die als referentiehoogte wordt gebruikt in.

Waarde: De GPS-hoogte gebruikt als referentiehoogte.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Geeft of stelt de GPS‑gebiedsinformatie in.

Waarde: De GPS-gebiedsinformatie.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Geeft of stelt de GPS‑DOP (data‑graad van precisie) in.

Waarde: De GPS DOP (datadegraad van precisie).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Geeft of stelt de GPS‑karakterreeks die datum‑ en tijdinformatie registreert ten opzichte van UTC (gecoördineerde wereldtijd) in.

Waarde: De GPS-tekenreeks die datum- en tijdinformatie registreert ten opzichte van UTC (Coördineerde Universele Tijd).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Geeft of stelt de GPS‑richting naar het bestemmingspunt in.

Waarde: De GPS-richting naar het bestemmingspunt.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Krijgt of stelt de GPS-referentie in die wordt gebruikt om de koers naar het bestemmingspunt te geven.

Waarde: De GPS-referentie die wordt gebruikt om de richting naar het bestemmingspunt te geven.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Krijgt of stelt de GPS-afstand tot het bestemmingspunt in.

Waarde: De GPS-afstand naar het bestemmingspunt.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Krijgt of stelt de GPS-eenheid in die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken.

Waarde: De GPS-eenheid die wordt gebruikt om de afstand naar het bestemmingspunt uit te drukken.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Krijgt of stelt de GPS-breedtegraad van het bestemmingspunt in.

Waarde: De GPS-breedtegraad van het bestemmingspunt.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Krijgt of stelt de GPS-waarde in die aangeeft of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is.

Waarde: De GPS-waarde die aangeeft of de breedtegraad van het bestemmingspunt noordelijk of zuidelijk is.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Krijgt of stelt de GPS-lengtegraad van het bestemmingspunt in.

Waarde: De GPS-longitude van het bestemmingspunt.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Krijgt of stelt de GPS-waarde in die aangeeft of de lengtegraad van het bestemmingspunt oost- of westelijk is.

Waarde: De GPS-waarde die aangeeft of de lengtegraad van het bestemmingspunt oost- of westelijk is.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Krijgt of stelt een GPS-waarde in die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger.

Waarde: De GPS-waarde die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Krijgt of stelt de GPS-richting van de afbeelding in op het moment van opname.

Waarde: De GPS-richting van de afbeelding toen deze werd vastgelegd.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Krijgt of stelt de GPS-referentie in voor het aangeven van de richting van de afbeelding bij opname.

Waarde: De GPS-referentie voor het aangeven van de richting van de afbeelding wanneer deze wordt vastgelegd.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Krijgt of stelt de GPS-breedtegraad in.

Waarde: De GPS-breedtegraad.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Krijgt of stelt in of de GPS-breedtegraad noord- of zuiderbreedte is.

Waarde: De GPS-breedtegraad is noord- of zuiderbreedte.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Krijgt of stelt de GPS-lengtegraad in.

Waarde: De GPS-lengtegraad.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Krijgt of stelt in of de GPS-lengtegraad oost- of westelijk is.

Waarde: De GPS-lengtegraad is oost- of westelijk.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Krijgt of stelt de GPS-geodetische surveygegevens in die door de GPS-ontvanger worden gebruikt.

Waarde: De GPS-geodetische surveygegevens die door de GPS-ontvanger worden gebruikt.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Krijgt of stelt de GPS-meetmodus in.

Waarde: De GPS-meetmodus.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Krijgt of stelt de GPS-tekenreeks in die de naam van de methode voor locatiebepaling registreert.

Waarde: De GPS-tekenreeks die de naam van de gebruikte methode voor locatiebepaling registreert.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Krijgt of stelt de GPS-satellieten in die voor metingen worden gebruikt.

Waarde: De GPS-satellieten die voor metingen worden gebruikt.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Krijgt of stelt de snelheid van de GPS-ontvangerbeweging in.

Waarde: De snelheid van de beweging van de GPS-ontvanger.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Krijgt of stelt de eenheid in die wordt gebruikt om de snelheid van de GPS-ontvangerbeweging uit te drukken.

Waarde: De eenheid die wordt gebruikt om de snelheid van de GPS-ontvanger uit te drukken.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Krijgt of stelt de status van de GPS-ontvanger in wanneer de afbeelding wordt vastgelegd.

Waarde: De status van de GPS-ontvanger wanneer de afbeelding wordt vastgelegd.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Krijgt of stelt tags in die alleen tot de GPS-sectie behoren.

Waarde: De GPS-tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Krijgt of stelt de GPS-tijd in als UTC (gecoördineerde wereldtijd).

Waarde: De GPS-tijd als UTC (gecoördineerde universele tijd).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Krijgt of stelt de richting van de GPS-ontvangerbeweging in.

Waarde: De richting van de beweging van de GPS-ontvanger.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Krijgt of stelt de referentie in voor het aangeven van de richting van de GPS-ontvangerbeweging.

Waarde: De referentie voor het aangeven van de richting van de beweging van de GPS-ontvanger.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Haalt op of stelt de GPS-versie‑identificatie in.

Waarde: De GPS-versie‑identificatie.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Haalt op of stelt de graad van algemene beeldversterkingsaanpassing in.

Waarde: De graad van algemene afbeeldingversterkingsaanpassing.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Haalt op of stelt de gamma in.

Waarde: De gamma‑waarde.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Haalt op of stelt de ISO-snelheid in.

Waarde: De ISO-snelheid.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Haalt op of stelt de ISO-snelheidsbreedte yyy‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232.

Waarde: De ISO-snelheidsbreedtegraad yyy‑waarde van een camera of invoerapparaat die is gedefinieerd in ISO 12232.

Deze tag mag niet worden vastgelegd zonder ISOSpeed en ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Haalt op of stelt de ISO-snelheidsbreedte zzz‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232.

Waarde: De ISO-snelheidsbreedte zzz-waarde van een camera of invoerapparaat die is gedefinieerd in ISO 12232.

Deze tag mag niet worden vastgelegd zonder ISOSpeed en ISOSpeedLatitudeyyy

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Haalt op of stelt de unieke afbeelding‑identificatie in.

Waarde: De unieke identificatie van de afbeelding.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Haalt op of stelt de fabrikant van het objectief in.

Waarde: De lensfabrikant.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Haalt op of stelt het objectiefmodel in.

Waarde: Het lensmodel.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Haalt op of stelt het serienummer van het objectief in.

Waarde: Het serienummer van de lens.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Haalt op of stelt de objectiefspecificatie in.

Waarde: De lensspecificatie.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Haalt op of stelt de lichtbron in.

Waarde: De lichtbron.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Haalt de fabrikant van de opname‑apparatuur op.

Waarde: De fabrikant van de opnameapparatuur.

**Returns:**
java.lang.String - de fabrikant van de opnameapparatuur.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Haalt de maker‑notitiegegevens op.

Waarde: De maker note-gegevens.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Haalt op of stelt de ruwe maker‑notitiegegevens in.

Waarde: De ruwe maker note-gegevens.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Haalt de maker‑notities op.

Waarde: De maker notes.

**Returns:**
com.aspose.psd.exif.MakerNote[] - de maker notes.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Haalt op of stelt de maximale diafragmawaarde in.

Waarde: De maximale diafragmawaarde.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Haalt op of stelt de meetmodus in.

Waarde: De meetmodus.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Haalt op of stelt de Opto‑elektrische conversiefunctie (OECF) gespecificeerd in ISO 14524 in.

Waarde: De Opto-Electrische Conversiefunctie (OECF) gespecificeerd in ISO 14524.

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Haalt op of stelt de fotografische gevoeligheid in.

Waarde: De fotografische gevoeligheid.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Haalt op of stelt de pixel‑x‑dimensie in.

Waarde: De pixel x-dimensie.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Haalt op of stelt de pixel‑y‑dimensie in.

Waarde: De pixel y-dimensie.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Haalt op of stelt alle EXIF‑tags in (inclusief algemene en GPS‑tags).

Waarde: De EXIF-tags (inclusief algemene en GPS-tags).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Haalt op of stelt de aanbevolen belichtingsindex in.

Waarde: De aanbevolen belichtingsindex.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Haalt op of stelt het gerelateerde geluidsbestand in.

Waarde: Het gerelateerde geluidsbestand.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Haalt de verzadiging op of stelt deze in.

Waarde: De verzadiging.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Haalt het type scène‑opname op of stelt dit in.

Waarde: Het type van de scène-opname.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Haalt het type scène op of stelt dit in.

Waarde: Het type van de scène.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Haalt de detectiemethode op of stelt deze in.

Waarde: De detectiemethode.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Haalt het type gevoeligheid op of stelt dit in.

Waarde: Het type van de gevoeligheid.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Haalt de scherpte op of stelt deze in.

Waarde: De scherpte.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Haalt de sluitertijdwaarde op of stelt deze in.

Waarde: De sluitertijdwaarde.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Haalt de ruimtelijke frequentierespons op of stelt deze in.

Waarde: De ruimtelijke frequentierespons.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Haalt de spectrale gevoeligheid op of stelt deze in.

Waarde: De spectrale gevoeligheid.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Haalt de standaard uitgangsgevoeligheid op

Waarde: De standaard uitgangsgevoeligheid.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Haalt het onderwerpgebied op of stelt dit in.

Waarde: Het onderwerpgebied.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Haalt de onderwerpafstand op of stelt deze in.

Waarde: De onderwerpafstand.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Haalt het bereik van de onderwerpafstand op of stelt dit in.

Waarde: Het bereik van de onderwerpafstand.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Haalt de locatie van het onderwerp op of stelt deze in.

Waarde: De onderwerplocatie.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Haalt de fracties van seconden voor de DateTime-tag op of stelt deze in.

Waarde: De fracties van seconden voor de DateTime-tag.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Haalt de fracties van seconden voor de DateTimeDigitized-tag op of stelt deze in.

Waarde: De fracties van seconden voor de DateTimeDigitized-tag.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Haalt de fracties van seconden voor de DateTimeOriginal-tag op of stelt deze in.

Waarde: De fracties van seconden voor de DateTimeOriginal-tag.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Haalt de gebruikersopmerking op of stelt deze in.

Waarde: De gebruikersopmerking.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Haalt de witbalans op of stelt deze in.

Waarde: De witbalans.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Haalt de chromaticiteit van het witpunt van de afbeelding op of stelt deze in.

Waarde: De chromaticiteit van het witpunt van de afbeelding.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
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


Haalt een waarde op of stelt deze in die aangeeft of de EXIF‑gegevensstroom die is gemaakt van big‑endian is.

Waarde:  true  als de EXIF-gegevensstroom waaruit is gemaakt big endian is; anders,  false .

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


Verwijder tag uit container

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tagId | int | De tagidentificatie om te verwijderen. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Haalt de diafragmawaarde op of stelt deze in.

Waarde: de diafragmawaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de EXIF‑gegevensstroom die is gemaakt van big‑endian is.

Waarde:  true  als de EXIF-gegevensstroom waaruit is gemaakt big endian is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Haalt het serienummer van de camerabehuizing op of stelt dit in.

Waarde: het serienummer van de body.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Haalt de helderheidswaarde op of stelt deze in.

Waarde: de helderheidswaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Haalt het CFA-patroon op of stelt dit in.

Waarde: het CFA-patroon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Haalt de naam van de camerabezitter op of stelt deze in

Waarde: de naam van de camerabezitter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Haalt de kleurruimte op of stelt deze in.

Waarde: de kleurenruimte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Haalt tags op of stelt ze in die tot de algemene sectie behoren. Dit geldt alleen voor jpeg-afbeeldingen; in tiff-formaat worden in plaats daarvan tiffOptions gebruikt.

Waarde: de tags van de algemene sectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Haalt de componentconfiguratie op of stelt deze in.

Waarde: de componentconfiguratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Haalt het aantal gecomprimeerde bits per pixel op of stelt dit in.

Waarde: het aantal gecomprimeerde bits per pixel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Haalt het contrast op of stelt dit in.

Waarde: het contrast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Haalt de aangepaste rendering op of stelt deze in.

Waarde: de aangepaste rendering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Haalt de gedigitaliseerde datum/tijd op of stelt deze in.

Waarde: de gedigitaliseerde datum en tijd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Haalt de oorspronkelijke datum/tijd op of stelt deze in.

Waarde: de oorspronkelijke datum en tijd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Geeft of stelt de beschrijving van de apparaatinstellingen in

Waarde: de beschrijving van de apparaatinstellingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Geeft of stelt de digitale zoomverhouding in.

Waarde: de digitale zoomverhouding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Geeft of stelt tags in die alleen tot de EXIF‑sectie behoren.

Waarde: de EXIF-sectietags.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Geeft of stelt de EXIF‑versie in.

Waarde: de EXIF-versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Geeft of stelt de belichtingsbiaswaarde in.

Waarde: de belichtingsbiaswaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Geeft of stelt de belichtingsindex in.

Waarde: de index van de belichting.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Geeft of stelt de belichtingsmodus in.

Waarde: de belichtingsmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Geeft of stelt het belichtingsprogramma in.

Waarde: Het belichtingsprogramma.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Geeft of stelt de belichtingstijd in.

Waarde: De belichtingstijd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Geeft of stelt het F‑getal in.

Waarde: Het F-getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Geeft of stelt het type bestandbron in.

Waarde: Het type bestandbron.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Geeft of stelt de flits in.

Waarde: De flits.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Geeft of stelt de flitsenergie in.

Waarde: De flitsenergie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Geeft of stelt de flash‑pix‑versie in.

Waarde: De flash-pix versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Geeft of stelt de brandpuntsafstand in.

Waarde: De lengte van de brandpuntsafstand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Geeft of stelt de brandpuntsafstand in 35 mm film in.

Waarde: De brandpuntsafstand in 35 mm film.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Geeft of stelt de resolutie‑eenheid van het brandpuntvlak in.

Waarde: De resolutie-eenheid van het brandvlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Geeft of stelt de X‑resolutie van het brandpuntvlak in.

Waarde: De x-resolutie van het brandvlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Geeft of stelt de Y‑resolutie van het brandpuntvlak in.

Waarde: De y-resolutie van het brandvlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Geeft of stelt de GPS‑hoogte in.

Waarde: De GPS-hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Geeft of stelt de GPS‑hoogte die als referentiehoogte wordt gebruikt in.

Waarde: De GPS-hoogte gebruikt als referentiehoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Geeft of stelt de GPS‑gebiedsinformatie in.

Waarde: De GPS-gebiedsinformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Geeft of stelt de GPS‑DOP (data‑graad van precisie) in.

Waarde: De GPS DOP (datadegraad van precisie).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Geeft of stelt de GPS‑karakterreeks die datum‑ en tijdinformatie registreert ten opzichte van UTC (gecoördineerde wereldtijd) in.

Waarde: De GPS-tekenreeks die datum- en tijdinformatie registreert ten opzichte van UTC (Coördineerde Universele Tijd).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Geeft of stelt de GPS‑richting naar het bestemmingspunt in.

Waarde: De GPS-richting naar het bestemmingspunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Krijgt of stelt de GPS-referentie in die wordt gebruikt om de koers naar het bestemmingspunt te geven.

Waarde: De GPS-referentie die wordt gebruikt om de richting naar het bestemmingspunt te geven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Krijgt of stelt de GPS-afstand tot het bestemmingspunt in.

Waarde: De GPS-afstand naar het bestemmingspunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Krijgt of stelt de GPS-eenheid in die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken.

Waarde: De GPS-eenheid die wordt gebruikt om de afstand naar het bestemmingspunt uit te drukken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Krijgt of stelt de GPS-breedtegraad van het bestemmingspunt in.

Waarde: De GPS-breedtegraad van het bestemmingspunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Krijgt of stelt de GPS-waarde in die aangeeft of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is.

Waarde: De GPS-waarde die aangeeft of de breedtegraad van het bestemmingspunt noordelijk of zuidelijk is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Krijgt of stelt de GPS-lengtegraad van het bestemmingspunt in.

Waarde: De GPS-longitude van het bestemmingspunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Krijgt of stelt de GPS-waarde in die aangeeft of de lengtegraad van het bestemmingspunt oost- of westelijk is.

Waarde: De GPS-waarde die aangeeft of de lengtegraad van het bestemmingspunt oost- of westelijk is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Krijgt of stelt een GPS-waarde in die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger.

Waarde: De GPS-waarde die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Krijgt of stelt de GPS-richting van de afbeelding in op het moment van opname.

Waarde: De GPS-richting van de afbeelding toen deze werd vastgelegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Krijgt of stelt de GPS-referentie in voor het aangeven van de richting van de afbeelding bij opname.

Waarde: De GPS-referentie voor het aangeven van de richting van de afbeelding wanneer deze wordt vastgelegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Krijgt of stelt de GPS-breedtegraad in.

Waarde: De GPS-breedtegraad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Krijgt of stelt in of de GPS-breedtegraad noord- of zuiderbreedte is.

Waarde: De GPS-breedtegraad is noord- of zuiderbreedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Krijgt of stelt de GPS-lengtegraad in.

Waarde: De GPS-lengtegraad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Krijgt of stelt in of de GPS-lengtegraad oost- of westelijk is.

Waarde: De GPS-lengtegraad is oost- of westelijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Krijgt of stelt de GPS-geodetische surveygegevens in die door de GPS-ontvanger worden gebruikt.

Waarde: De GPS-geodetische surveygegevens die door de GPS-ontvanger worden gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Krijgt of stelt de GPS-meetmodus in.

Waarde: De GPS-meetmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Krijgt of stelt de GPS-tekenreeks in die de naam van de methode voor locatiebepaling registreert.

Waarde: De GPS-tekenreeks die de naam van de gebruikte methode voor locatiebepaling registreert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Krijgt of stelt de GPS-satellieten in die voor metingen worden gebruikt.

Waarde: De GPS-satellieten die voor metingen worden gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Krijgt of stelt de snelheid van de GPS-ontvangerbeweging in.

Waarde: De snelheid van de beweging van de GPS-ontvanger.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Krijgt of stelt de eenheid in die wordt gebruikt om de snelheid van de GPS-ontvangerbeweging uit te drukken.

Waarde: De eenheid die wordt gebruikt om de snelheid van de GPS-ontvanger uit te drukken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Krijgt of stelt de status van de GPS-ontvanger in wanneer de afbeelding wordt vastgelegd.

Waarde: De status van de GPS-ontvanger wanneer de afbeelding wordt vastgelegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Krijgt of stelt tags in die alleen tot de GPS-sectie behoren.

Waarde: De GPS-tags.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Krijgt of stelt de GPS-tijd in als UTC (gecoördineerde wereldtijd).

Waarde: De GPS-tijd als UTC (gecoördineerde universele tijd).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Krijgt of stelt de richting van de GPS-ontvangerbeweging in.

Waarde: De richting van de beweging van de GPS-ontvanger.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Krijgt of stelt de referentie in voor het aangeven van de richting van de GPS-ontvangerbeweging.

Waarde: De referentie voor het aangeven van de richting van de beweging van de GPS-ontvanger.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Haalt op of stelt de GPS-versie‑identificatie in.

Waarde: De GPS-versie‑identificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Haalt op of stelt de graad van algemene beeldversterkingsaanpassing in.

Waarde: De graad van algemene afbeeldingversterkingsaanpassing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Haalt op of stelt de gamma in.

Waarde: De gamma‑waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Haalt op of stelt de ISO-snelheid in.

Waarde: De ISO-snelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Haalt op of stelt de ISO-snelheidsbreedte yyy‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232.

Waarde: De ISO-snelheidsbreedtegraad yyy‑waarde van een camera of invoerapparaat die is gedefinieerd in ISO 12232.

Deze tag mag niet worden vastgelegd zonder ISOSpeed en ISOSpeedLatitudezzz

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Haalt op of stelt de ISO-snelheidsbreedte zzz‑waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232.

Waarde: De ISO-snelheidsbreedte zzz-waarde van een camera of invoerapparaat die is gedefinieerd in ISO 12232.

Deze tag mag niet worden vastgelegd zonder ISOSpeed en ISOSpeedLatitudeyyy

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Haalt op of stelt de unieke afbeelding‑identificatie in.

Waarde: De unieke identificatie van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Haalt op of stelt de fabrikant van het objectief in.

Waarde: De lensfabrikant.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Haalt op of stelt het objectiefmodel in.

Waarde: Het lensmodel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Haalt op of stelt het serienummer van het objectief in.

Waarde: Het serienummer van de lens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Haalt op of stelt de objectiefspecificatie in.

Waarde: De lensspecificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Haalt op of stelt de lichtbron in.

Waarde: De lichtbron.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Stelt de fabrikant van de opnameapparatuur in.

Waarde: De fabrikant van de opnameapparatuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | de fabrikant van de opnameapparatuur. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Haalt op of stelt de ruwe maker‑notitiegegevens in.

Waarde: De ruwe maker note-gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Haalt op of stelt de maximale diafragmawaarde in.

Waarde: De maximale diafragmawaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Haalt op of stelt de meetmodus in.

Waarde: De meetmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Haalt op of stelt de Opto‑elektrische conversiefunctie (OECF) gespecificeerd in ISO 14524 in.

Waarde: De Opto-Electrische Conversiefunctie (OECF) gespecificeerd in ISO 14524.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Haalt op of stelt de fotografische gevoeligheid in.

Waarde: De fotografische gevoeligheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Haalt op of stelt de pixel‑x‑dimensie in.

Waarde: De pixel x-dimensie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Haalt op of stelt de pixel‑y‑dimensie in.

Waarde: De pixel y-dimensie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Haalt op of stelt alle EXIF‑tags in (inclusief algemene en GPS‑tags).

Waarde: De EXIF-tags (inclusief algemene en GPS-tags).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Haalt op of stelt de aanbevolen belichtingsindex in.

Waarde: De aanbevolen belichtingsindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Haalt op of stelt het gerelateerde geluidsbestand in.

Waarde: Het gerelateerde geluidsbestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Haalt de verzadiging op of stelt deze in.

Waarde: De verzadiging.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Haalt het type scène‑opname op of stelt dit in.

Waarde: Het type van de scène-opname.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Haalt het type scène op of stelt dit in.

Waarde: Het type van de scène.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Haalt de detectiemethode op of stelt deze in.

Waarde: De detectiemethode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Haalt het type gevoeligheid op of stelt dit in.

Waarde: Het type van de gevoeligheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Haalt de scherpte op of stelt deze in.

Waarde: De scherpte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Haalt de sluitertijdwaarde op of stelt deze in.

Waarde: De sluitertijdwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Haalt de ruimtelijke frequentierespons op of stelt deze in.

Waarde: De ruimtelijke frequentierespons.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Haalt de spectrale gevoeligheid op of stelt deze in.

Waarde: De spectrale gevoeligheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Stelt de standaard uitgangsgevoeligheid in

Waarde: De standaard uitgangsgevoeligheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Haalt het onderwerpgebied op of stelt dit in.

Waarde: Het onderwerpgebied.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Haalt de onderwerpafstand op of stelt deze in.

Waarde: De onderwerpafstand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Haalt het bereik van de onderwerpafstand op of stelt dit in.

Waarde: Het bereik van de onderwerpafstand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Haalt de locatie van het onderwerp op of stelt deze in.

Waarde: De onderwerplocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Haalt de fracties van seconden voor de DateTime-tag op of stelt deze in.

Waarde: De fracties van seconden voor de DateTime-tag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Haalt de fracties van seconden voor de DateTimeDigitized-tag op of stelt deze in.

Waarde: De fracties van seconden voor de DateTimeDigitized-tag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Haalt de fracties van seconden voor de DateTimeOriginal-tag op of stelt deze in.

Waarde: De fracties van seconden voor de DateTimeOriginal-tag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Haalt de gebruikersopmerking op of stelt deze in.

Waarde: De gebruikersopmerking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Haalt de witbalans op of stelt deze in.

Waarde: De witbalans.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Haalt de chromaticiteit van het witpunt van de afbeelding op of stelt deze in.

Waarde: De chromaticiteit van het witpunt van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

