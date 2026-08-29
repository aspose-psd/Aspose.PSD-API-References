---
title: "JpegExifData"
second_title: "Aspose.PSD für Java API-Referenz"
description: "EXIF-Datencontainer für JPEG-Dateien."
type: docs
weight: 12
url: /de/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

EXIF-Datencontainer für JPEG-Dateien.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initialisiert eine neue Instanz der  JpegExifData  Klasse. |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der  JpegExifData  Klasse mit Daten aus einem Array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der  JpegExifData  Klasse mit Daten aus einem Array. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | Die maximal zulässige EXIF‑Segmentgröße in Bytes. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Liest oder setzt den Blendenwert. |
| [getArtist()](#getArtist--) | Liest oder setzt den Künstler. |
| [getBitsPerSample()](#getBitsPerSample--) | Liest oder setzt die Bits pro Probe. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Liest oder setzt die Seriennummer des Kameragehäuses. |
| [getBrightnessValue()](#getBrightnessValue--) | Liest oder setzt den Helligkeitswert. |
| [getCFAPattern()](#getCFAPattern--) | Liest oder setzt das CFA‑Muster. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Liest oder setzt den Namen des Kamerabesitzers |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Liest oder setzt den Farbraum. |
| [getCommonTags()](#getCommonTags--) | Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Liest oder setzt die Komponenten‑Konfiguration. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Liest oder setzt die komprimierten Bits pro Pixel. |
| [getCompression()](#getCompression--) | Liest oder setzt die Kompression. |
| [getContrast()](#getContrast--) | Liest oder setzt den Kontrast. |
| [getCopyright()](#getCopyright--) | Liest oder setzt das Urheberrecht. |
| [getCustomRendered()](#getCustomRendered--) | Liest oder setzt die benutzerdefinierte Darstellung. |
| [getDateTime()](#getDateTime--) | Liest oder setzt das Datum und die Uhrzeit. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Liest oder setzt das Digitalisierungsdatum und die -uhrzeit. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Liest oder setzt das Originaldatum und die -uhrzeit. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Liest oder setzt die Geräte­einstellungsbeschreibung |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Liest oder setzt das digitale Zoom‑Verhältnis. |
| [getExifTags()](#getExifTags--) | Liest oder setzt Tags, die ausschließlich zum EXIF‑Abschnitt gehören. |
| [getExifVersion()](#getExifVersion--) | Liest oder setzt die EXIF‑Version. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Liest oder setzt den Belichtungswert. |
| [getExposureIndex()](#getExposureIndex--) | Liest oder setzt den Belichtungsindex. |
| [getExposureMode()](#getExposureMode--) | Liest oder setzt den Belichtungsmodus. |
| [getExposureProgram()](#getExposureProgram--) | Liest oder setzt das Belichtungsprogramm. |
| [getExposureTime()](#getExposureTime--) | Liest oder setzt die Belichtungszeit. |
| [getFNumber()](#getFNumber--) | Liest oder setzt die F‑Zahl. |
| [getFileSource()](#getFileSource--) | Liest oder setzt den Dateiquellentyp. |
| [getFlash()](#getFlash--) | Liest oder setzt den Blitz. |
| [getFlashEnergy()](#getFlashEnergy--) | Liest oder setzt die Blitzenergie. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Liest oder setzt die Flash‑Pix-Version. |
| [getFocalLength()](#getFocalLength--) | Liest oder setzt die Brennweite. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Liest oder setzt die Brennweite in 35‑mm-Film. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Liest oder setzt die Auflösungseinheit der Bildebene. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Liest oder setzt die X‑Auflösung der Bildebene. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Liest oder setzt die Y‑Auflösung der Bildebene. |
| [getGPSAltitude()](#getGPSAltitude--) | Liest oder setzt die GPS‑Höhe. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Liest oder setzt die GPS‑Höhe, die als Referenzhöhe verwendet wird. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Liest oder setzt die GPS‑Gebietsinformationen. |
| [getGPSDOP()](#getGPSDOP--) | Liest oder setzt den GPS‑DOP (Datenpräzisionsgrad). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Liest oder setzt die GPS‑Zeichenkette, die Datum‑ und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. |
| [getGPSDestBearing()](#getGPSDestBearing--) | Liest oder setzt die GPS‑Richtung zum Zielpunkt. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Liest oder setzt die GPS‑Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Liest oder setzt die GPS‑Entfernung zum Zielpunkt. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Liest oder setzt die GPS‑Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Liest oder setzt den GPS‑Breitengrad des Zielpunkts. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Liest oder setzt den GPS‑Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Liest oder setzt den GPS-Längengrad des Zielpunkts. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist. |
| [getGPSDifferential()](#getGPSDifferential--) | Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme. |
| [getGPSLatitude()](#getGPSLatitude--) | Liest oder setzt den GPS-Breitengrad. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist. |
| [getGPSLongitude()](#getGPSLongitude--) | Liest oder setzt den GPS-Längengrad. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Liest oder setzt den GPS-Messmodus. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Standortbestimmung verwendeten Methode aufzeichnet. |
| [getGPSSatellites()](#getGPSSatellites--) | Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden. |
| [getGPSSpeed()](#getGPSSpeed--) | Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird. |
| [getGPSStatus()](#getGPSStatus--) | Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird. |
| [getGPSTags()](#getGPSTags--) | Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit). |
| [getGPSTrack()](#getGPSTrack--) | Liest oder setzt die Richtung der GPS-Empfängerbewegung. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Liest oder setzt die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung. |
| [getGPSVersionID()](#getGPSVersionID--) | Liest oder setzt den GPS-Versionsidentifikator. |
| [getGainControl()](#getGainControl--) | Liest oder setzt den Grad der Gesamtabstimmung der Bildverstärkung. |
| [getGamma()](#getGamma--) | Liest oder setzt das Gamma. |
| [getISOSpeed()](#getISOSpeed--) | Liest oder setzt die ISO-Geschwindigkeit |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Liest oder setzt den ISO-Geschwindigkeits-Breitengrad-yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Liest oder setzt den ISO‑Geschwindigkeits‑Latitude‑zzz‑Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [getImageDescription()](#getImageDescription--) | Liest oder setzt die Bildbeschreibung. |
| [getImageLength()](#getImageLength--) | Liest oder setzt die Bildlänge. |
| [getImageUniqueID()](#getImageUniqueID--) | Liest oder setzt die eindeutige Bildkennung. |
| [getImageWidth()](#getImageWidth--) | Liest oder setzt die Bildbreite. |
| [getLensMake()](#getLensMake--) | Liest oder setzt den Hersteller des Objektivs. |
| [getLensModel()](#getLensModel--) | Liest oder setzt das Objektivmodell. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Liest oder setzt die Seriennummer des Objektivs. |
| [getLensSpecification()](#getLensSpecification--) | Liest oder setzt die Objektivspezifikation |
| [getLightSource()](#getLightSource--) | Liest oder setzt die Lichtquelle. |
| [getMake()](#getMake--) | Liest den Hersteller der Aufzeichnungsgeräte. |
| [getMakerNoteData()](#getMakerNoteData--) | Liest die Herstellerhinweisdaten. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Liest oder setzt die rohen Herstellerhinweisdaten. |
| [getMakerNotes()](#getMakerNotes--) | Liest die Herstellerhinweise. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Liest oder setzt den maximalen Blendenwert. |
| [getMeteringMode()](#getMeteringMode--) | Liest oder setzt den Messmodus. |
| [getModel()](#getModel--) | Liest oder setzt das Modell. |
| [getOECF()](#getOECF--) | Liest oder setzt die in ISO 14524 spezifizierte Opto‑Elektrische Umwandlungsfunktion (OECF). |
| [getOrientation()](#getOrientation--) | Liest oder setzt die Ausrichtung. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Liest oder setzt die fotografische Empfindlichkeit. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Liest oder setzt die photometrische Interpretation. |
| [getPixelXDimension()](#getPixelXDimension--) | Liest oder setzt die Pixel‑X‑Dimension. |
| [getPixelYDimension()](#getPixelYDimension--) | Liest oder setzt die Pixel‑Y‑Dimension. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Liest oder setzt die planare Konfiguration. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Liest oder setzt die Chromatik der drei Primärfarben des Bildes. |
| [getProperties()](#getProperties--) | Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Liest oder setzt den empfohlenen Belichtungsindex. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Liest oder setzt das Referenz‑Schwarz‑Weiß. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Liest oder setzt die zugehörige Audiodatei. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest oder setzt die Auflösungseinheit. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Liest oder setzt die Proben pro Pixel. |
| [getSaturation()](#getSaturation--) | Liest oder setzt die Sättigung. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Liest oder setzt den Aufnahmetyp der Szene. |
| [getSceneType()](#getSceneType--) | Liest oder setzt den Szenentyp. |
| [getSensingMethod()](#getSensingMethod--) | Liest oder setzt die Erfassungsmethode. |
| [getSensitivityType()](#getSensitivityType--) | Liest oder setzt den Empfindlichkeitstyp. |
| [getSharpness()](#getSharpness--) | Liest oder setzt die Schärfe. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Liest oder setzt den Verschlusszeitwert. |
| [getSoftware()](#getSoftware--) | Liest oder setzt die Software. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Liest oder setzt die räumliche Frequenzantwort. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Liest oder setzt die spektrale Empfindlichkeit. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Liest die Standardausgangsempfindlichkeit |
| [getSubjectArea()](#getSubjectArea--) | Liest oder setzt den Motivbereich. |
| [getSubjectDistance()](#getSubjectDistance--) | Liest oder setzt den Motivabstand. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Liest oder setzt den Abstandbereich des Motivs. |
| [getSubjectLocation()](#getSubjectLocation--) | Liest oder setzt den Motivstandort. |
| [getSubsecTime()](#getSubsecTime--) | Liest oder setzt die Sekundenbruchteile für das DateTime-Tag. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized-Tag. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal-Tag. |
| [getThumbnail()](#getThumbnail--) | Liest oder setzt das Vorschaubild. |
| [getTransferFunction()](#getTransferFunction--) | Liest oder setzt die Transferfunktion. |
| [getUserComment()](#getUserComment--) | Liest oder setzt den Benutzerkommentar. |
| [getWhiteBalance()](#getWhiteBalance--) | Liest oder setzt den Weißabgleich. |
| [getWhitePoint()](#getWhitePoint--) | Liest oder setzt die Chromatik des Weißpunkts des Bildes. |
| [getXResolution()](#getXResolution--) | Liest oder setzt die X‑Auflösung. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [getYResolution()](#getYResolution--) | Liest oder setzt die Y‑Auflösung. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Liest oder setzt einen Wert, der angibt, ob die aus dem Stream erstellten EXIF-Daten big endian sind. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Tag aus dem Container entfernen. |
| [serializeExifData()](#serializeExifData--) | Serialisiert die EXIF‑Daten. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt den Blendenwert. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Liest oder setzt den Künstler. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Liest oder setzt einen Wert, der angibt, ob die aus dem Stream erstellten EXIF-Daten big endian sind. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Liest oder setzt die Bits pro Probe. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Liest oder setzt die Seriennummer des Kameragehäuses. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Liest oder setzt den Helligkeitswert. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Liest oder setzt das CFA‑Muster. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Liest oder setzt den Namen des Kamerabesitzers |
| [setColorSpace(int value)](#setColorSpace-int-) | Liest oder setzt den Farbraum. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Liest oder setzt die Komponenten‑Konfiguration. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die komprimierten Bits pro Pixel. |
| [setCompression(int value)](#setCompression-int-) | Liest oder setzt die Kompression. |
| [setContrast(int value)](#setContrast-int-) | Liest oder setzt den Kontrast. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Liest oder setzt das Urheberrecht. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Liest oder setzt die benutzerdefinierte Darstellung. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Liest oder setzt das Datum und die Uhrzeit. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Liest oder setzt das Digitalisierungsdatum und die -uhrzeit. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Liest oder setzt das Originaldatum und die -uhrzeit. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Liest oder setzt die Geräte­einstellungsbeschreibung |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt das digitale Zoom‑Verhältnis. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Liest oder setzt Tags, die ausschließlich zum EXIF‑Abschnitt gehören. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Liest oder setzt die EXIF‑Version. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Liest oder setzt den Belichtungswert. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt den Belichtungsindex. |
| [setExposureMode(int value)](#setExposureMode-int-) | Liest oder setzt den Belichtungsmodus. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Liest oder setzt das Belichtungsprogramm. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Belichtungszeit. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die F‑Zahl. |
| [setFileSource(byte value)](#setFileSource-byte-) | Liest oder setzt den Dateiquellentyp. |
| [setFlash(int value)](#setFlash-int-) | Liest oder setzt den Blitz. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Blitzenergie. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Liest oder setzt die Flash‑Pix-Version. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Brennweite. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Liest oder setzt die Brennweite in 35‑mm-Film. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit der Bildebene. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die X‑Auflösung der Bildebene. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Y‑Auflösung der Bildebene. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS‑Höhe. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Liest oder setzt die GPS‑Höhe, die als Referenzhöhe verwendet wird. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Liest oder setzt die GPS‑Gebietsinformationen. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt den GPS‑DOP (Datenpräzisionsgrad). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Liest oder setzt die GPS‑Zeichenkette, die Datum‑ und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS‑Richtung zum Zielpunkt. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Liest oder setzt die GPS‑Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS‑Entfernung zum Zielpunkt. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Liest oder setzt die GPS‑Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS‑Breitengrad des Zielpunkts. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Liest oder setzt den GPS‑Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Längengrad des Zielpunkts. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Breitengrad. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Längengrad. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Liest oder setzt den GPS-Messmodus. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Standortbestimmung verwendeten Methode aufzeichnet. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Liest oder setzt die Richtung der GPS-Empfängerbewegung. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Liest oder setzt die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Liest oder setzt den GPS-Versionsidentifikator. |
| [setGainControl(int value)](#setGainControl-int-) | Liest oder setzt den Grad der Gesamtabstimmung der Bildverstärkung. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt das Gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Liest oder setzt die ISO-Geschwindigkeit |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Liest oder setzt den ISO-Geschwindigkeits-Breitengrad-yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Liest oder setzt den ISO‑Geschwindigkeits‑Latitude‑zzz‑Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Liest oder setzt die Bildbeschreibung. |
| [setImageLength(long value)](#setImageLength-long-) | Liest oder setzt die Bildlänge. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Liest oder setzt die eindeutige Bildkennung. |
| [setImageWidth(long value)](#setImageWidth-long-) | Liest oder setzt die Bildbreite. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Liest oder setzt den Hersteller des Objektivs. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Liest oder setzt das Objektivmodell. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Liest oder setzt die Seriennummer des Objektivs. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt die Objektivspezifikation |
| [setLightSource(int value)](#setLightSource-int-) | Liest oder setzt die Lichtquelle. |
| [setMake(String value)](#setMake-java.lang.String-) | Legt den Hersteller der Aufzeichnungsgeräte fest. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Liest oder setzt die rohen Herstellerhinweisdaten. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt den maximalen Blendenwert. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Liest oder setzt den Messmodus. |
| [setModel(String value)](#setModel-java.lang.String-) | Liest oder setzt das Modell. |
| [setOECF(byte[] value)](#setOECF-byte---) | Liest oder setzt die in ISO 14524 spezifizierte Opto‑Elektrische Umwandlungsfunktion (OECF). |
| [setOrientation(int value)](#setOrientation-int-) | Liest oder setzt die Ausrichtung. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Liest oder setzt die fotografische Empfindlichkeit. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Liest oder setzt die photometrische Interpretation. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Liest oder setzt die Pixel‑X‑Dimension. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Liest oder setzt die Pixel‑Y‑Dimension. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Liest oder setzt die planare Konfiguration. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt die Chromatik der drei Primärfarben des Bildes. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Liest oder setzt den empfohlenen Belichtungsindex. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt das Referenz‑Schwarz‑Weiß. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Liest oder setzt die zugehörige Audiodatei. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Liest oder setzt die Proben pro Pixel. |
| [setSaturation(int value)](#setSaturation-int-) | Liest oder setzt die Sättigung. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Liest oder setzt den Aufnahmetyp der Szene. |
| [setSceneType(byte value)](#setSceneType-byte-) | Liest oder setzt den Szenentyp. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Liest oder setzt die Erfassungsmethode. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Liest oder setzt den Empfindlichkeitstyp. |
| [setSharpness(int value)](#setSharpness-int-) | Liest oder setzt die Schärfe. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Liest oder setzt den Verschlusszeitwert. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Liest oder setzt die Software. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Liest oder setzt die räumliche Frequenzantwort. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Liest oder setzt die spektrale Empfindlichkeit. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Legt die Standardausgangsempfindlichkeit fest. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Liest oder setzt den Motivbereich. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt den Motivabstand. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Liest oder setzt den Abstandbereich des Motivs. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Liest oder setzt den Motivstandort. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Liest oder setzt die Sekundenbruchteile für das DateTime-Tag. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized-Tag. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal-Tag. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | Liest oder setzt das Vorschaubild. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Liest oder setzt die Transferfunktion. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Liest oder setzt den Benutzerkommentar. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Liest oder setzt den Weißabgleich. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt die Chromatik des Weißpunkts des Bildes. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die X‑Auflösung. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Y‑Auflösung. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initialisiert eine neue Instanz der  JpegExifData  Klasse.

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


Initialisiert eine neue Instanz der  JpegExifData  Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Array von EXIF-Tags zusammen mit allgemeinen und GPS-Tags. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialisiert eine neue Instanz der  JpegExifData  Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die allgemeinen Tags. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die EXIF-Tags. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die GPS-Tags. |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


Die maximal zulässige EXIF‑Segmentgröße in Bytes.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Liest oder setzt den Blendenwert.

Wert: Der Blendenwert.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


Liest oder setzt den Künstler.

Wert: Der Künstler.

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Liest oder setzt die Bits pro Probe.

Wert: Die Bits pro Probe.

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Liest oder setzt die Seriennummer des Kameragehäuses.

Wert: Die Seriennummer des Gehäuses.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Liest oder setzt den Helligkeitswert.

Wert: Der Helligkeitswert.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Liest oder setzt das CFA‑Muster.

Wert: Das CFA-Muster.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Liest oder setzt den Namen des Kamerabesitzers

Wert: Der Name des Kamerabesitzers.

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


Liest oder setzt den Farbraum.

Wert: Der Farbraum.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Ruft Tags ab oder legt sie fest, die zum gemeinsamen Abschnitt gehören. Dies gilt nur für JPEG-Bilder; im TIFF-Format werden stattdessen tiffOptions verwendet.

Wert: Die Tags des gemeinsamen Abschnitts.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Liest oder setzt die Komponenten‑Konfiguration.

Wert: Die Komponenten-Konfiguration.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Liest oder setzt die komprimierten Bits pro Pixel.

Wert: Die komprimierten Bits pro Pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


Liest oder setzt die Kompression.

Wert: Die Kompression.

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


Liest oder setzt den Kontrast.

Wert: Der Kontrast.

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Liest oder setzt das Urheberrecht.

Wert: Das Urheberrecht.

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Liest oder setzt die benutzerdefinierte Darstellung.

Wert: Das benutzerdefinierte Rendering.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Liest oder setzt das Datum und die Uhrzeit.

Wert: Das Datum und die Uhrzeit.

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Liest oder setzt das Digitalisierungsdatum und die -uhrzeit.

Wert: Das Datum/Uhrzeit der Digitalisierung.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Liest oder setzt das Originaldatum und die -uhrzeit.

Wert: Das ursprüngliche Datum/Uhrzeit.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Liest oder setzt die Geräte­einstellungsbeschreibung

Wert: Die Geräte-Einstellungsbeschreibung.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Liest oder setzt das digitale Zoom‑Verhältnis.

Wert: Das digitale Zoom-Verhältnis.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Liest oder setzt Tags, die ausschließlich zum EXIF‑Abschnitt gehören.

Wert: Die Tags des EXIF-Abschnitts.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Liest oder setzt die EXIF‑Version.

Wert: Die EXIF-Version.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Liest oder setzt den Belichtungswert.

Wert: Der Belichtungskorrekturwert.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Liest oder setzt den Belichtungsindex.

Wert: Der Belichtungsindex.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Liest oder setzt den Belichtungsmodus.

Wert: Der Belichtungsmodus.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Liest oder setzt das Belichtungsprogramm.

Wert: Das Belichtungsprogramm.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Liest oder setzt die Belichtungszeit.

Wert: Die Belichtungszeit.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Liest oder setzt die F‑Zahl.

Wert: Die Blendenzahl.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Liest oder setzt den Dateiquellentyp.

Wert: Der Dateiquellen-Typ.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Liest oder setzt den Blitz.

Wert: Der Blitz.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Liest oder setzt die Blitzenergie.

Wert: Die Blitzenergie.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Liest oder setzt die Flash‑Pix-Version.

Wert: Die Flash-Pix-Version.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Liest oder setzt die Brennweite.

Wert: Die Länge der Brennweite.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Liest oder setzt die Brennweite in 35‑mm-Film.

Wert: Die Brennweite in 35‑mm-Film.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Liest oder setzt die Auflösungseinheit der Bildebene.

Wert: Die Auflösungseinheit der Bildebene.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Liest oder setzt die X‑Auflösung der Bildebene.

Wert: Die X‑Auflösung der Bildebene.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Liest oder setzt die Y‑Auflösung der Bildebene.

Wert: Die Y‑Auflösung der Bildebene.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Liest oder setzt die GPS‑Höhe.

Wert: Die GPS-Höhe.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Liest oder setzt die GPS‑Höhe, die als Referenzhöhe verwendet wird.

Wert: Die GPS-Höhe, die als Referenzhöhe verwendet wird.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Liest oder setzt die GPS‑Gebietsinformationen.

Wert: Die GPS-Flächeninformation.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Liest oder setzt den GPS‑DOP (Datenpräzisionsgrad).

Wert: Der GPS-DOP (Datengrad der Präzision).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Liest oder setzt die GPS‑Zeichenkette, die Datum‑ und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

Wert: Die GPS‑Zeichenkette, die Datum‑ und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Liest oder setzt die GPS‑Richtung zum Zielpunkt.

Wert: Der GPS‑Kurs zum Zielpunkt.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Liest oder setzt die GPS‑Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird.

Wert: Die GPS‑Referenz, die zur Angabe des Kurses zum Zielpunkt verwendet wird.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Liest oder setzt die GPS‑Entfernung zum Zielpunkt.

Wert: Die GPS‑Entfernung zum Zielpunkt.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Liest oder setzt die GPS‑Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

Wert: Die GPS‑Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Liest oder setzt den GPS‑Breitengrad des Zielpunkts.

Wert: Der GPS‑Breitengrad des Zielpunkts.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Liest oder setzt den GPS‑Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

Wert: Der GPS‑Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Liest oder setzt den GPS-Längengrad des Zielpunkts.

Wert: Der GPS‑Längengrad des Zielpunkts.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

Wert: Der GPS‑Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird.

Wert: Der GPS‑Wert, der angibt, ob eine differenzielle Korrektur auf den GPS‑Empfänger angewendet wird.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme.

Wert: Die GPS‑Richtung des Bildes bei der Aufnahme.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme.

Wert: Die GPS‑Referenz zur Angabe der Bildrichtung bei der Aufnahme.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Liest oder setzt den GPS-Breitengrad.

Wert: Der GPS‑Breitengrad.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist.

Wert: Der GPS-Breitengrad ist nördliche oder südliche Breite.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Liest oder setzt den GPS-Längengrad.

Wert: Der GPS-Längengrad.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist.

Wert: Der GPS-Längengrad ist östliche oder westliche Länge.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

Wert: Die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Liest oder setzt den GPS-Messmodus.

Wert: Der GPS-Messmodus.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Standortbestimmung verwendeten Methode aufzeichnet.

Wert: Die GPS-Zeichenkette, die den Namen der für die Positionsbestimmung verwendeten Methode aufzeichnet.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden.

Wert: Die für Messungen verwendeten GPS-Satelliten.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung.

Wert: Die Geschwindigkeit der GPS-Empfängerbewegung.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird.

Wert: Die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird.

Wert: Der Status des GPS-Empfängers, wenn das Bild aufgenommen wird.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören.

Wert: Die GPS-Tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit).

Wert: Die GPS-Zeit als UTC (Koordinierte Weltzeit).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Liest oder setzt die Richtung der GPS-Empfängerbewegung.

Wert: Die Richtung der GPS-Empfängerbewegung.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Liest oder setzt die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung.

Wert: Die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Liest oder setzt den GPS-Versionsidentifikator.

Wert: Der GPS-Versionsidentifikator.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Liest oder setzt den Grad der Gesamtabstimmung der Bildverstärkung.

Wert: Der Grad der Gesamten Bildverstärkungsanpassung.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Liest oder setzt das Gamma.

Wert: Der Gammawert.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Liest oder setzt die ISO-Geschwindigkeit

Wert: Die ISO-Geschwindigkeit.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Liest oder setzt den ISO-Geschwindigkeits-Breitengrad-yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO-Geschwindigkeits-Breitengrad yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudezzz aufgezeichnet werden.

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Liest oder setzt den ISO‑Geschwindigkeits‑Latitude‑zzz‑Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO-Geschwindigkeits-Breitengrad zzz-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudeyyy aufgezeichnet werden.

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Liest oder setzt die Bildbeschreibung.

Wert: Die Bildbeschreibung.

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Liest oder setzt die Bildlänge.

Wert: Die Länge des Bildes.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Liest oder setzt die eindeutige Bildkennung.

Wert: Der eindeutige Bildidentifikator.

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Liest oder setzt die Bildbreite.

Wert: Die Breite des Bildes.

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Liest oder setzt den Hersteller des Objektivs.

Wert: Der Linsenhersteller.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Liest oder setzt das Objektivmodell.

Wert: Das Linsenmodell.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Liest oder setzt die Seriennummer des Objektivs.

Wert: Die Seriennummer des Objektivs.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Liest oder setzt die Objektivspezifikation

Wert: Die Objektivspezifikation.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Liest oder setzt die Lichtquelle.

Wert: Die Lichtquelle.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Liest den Hersteller der Aufzeichnungsgeräte.

Wert: Der Hersteller der Aufzeichnungsgeräte.

**Returns:**
java.lang.String - der Hersteller der Aufzeichnungsgeräte.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Liest die Herstellerhinweisdaten.

Wert: Die Maker-Notizdaten.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Liest oder setzt die rohen Herstellerhinweisdaten.

Wert: Die rohen Maker-Notizdaten.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Liest die Herstellerhinweise.

Wert: Die Maker-Notizen.

**Returns:**
com.aspose.psd.exif.MakerNote[] - die Maker-Notizen.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Liest oder setzt den maximalen Blendenwert.

Wert: Der maximale Blendenwert.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Liest oder setzt den Messmodus.

Wert: Der Messmodus.

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


Liest oder setzt das Modell.

Wert: Das Modell.

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Liest oder setzt die in ISO 14524 spezifizierte Opto‑Elektrische Umwandlungsfunktion (OECF).

Wert: Die in ISO 14524 angegebene Opto‑elektrische Umwandlungsfunktion (OECF).

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Liest oder setzt die Ausrichtung.

Wert: Die Orientierung.

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Liest oder setzt die fotografische Empfindlichkeit.

Wert: Die fotografische Empfindlichkeit.

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Liest oder setzt die photometrische Interpretation.

Wert: Die photometrische Interpretation.

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Liest oder setzt die Pixel‑X‑Dimension.

Wert: Die Pixel‑X‑Dimension.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Liest oder setzt die Pixel‑Y‑Dimension.

Wert: Die Pixel‑Y‑Dimension.

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Liest oder setzt die planare Konfiguration.

Wert: Die planare Konfiguration.

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Liest oder setzt die Chromatik der drei Primärfarben des Bildes.

Wert: Die Chromatik der drei Primärfarben des Bildes.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags).

Wert: Die EXIF‑Tags (einschließlich gängiger und GPS‑Tags).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Liest oder setzt den empfohlenen Belichtungsindex.

Wert: Der empfohlene Belichtungsindex.

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Liest oder setzt das Referenz‑Schwarz‑Weiß.

Wert: Der Referenz‑Schwarz‑Weiß‑Wert.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Liest oder setzt die zugehörige Audiodatei.

Wert: Die zugehörige Audiodatei.

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Liest oder setzt die Auflösungseinheit.

Wert: Die Auflösungseinheit.

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Liest oder setzt die Proben pro Pixel.

Wert: Die Stichproben pro Pixel.

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Liest oder setzt die Sättigung.

Wert: Die Sättigung.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Liest oder setzt den Aufnahmetyp der Szene.

Wert: Der Typ der Szenenerfassung.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Liest oder setzt den Szenentyp.

Wert: Der Typ der Szene.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Liest oder setzt die Erfassungsmethode.

Wert: Die Erfassungsmethode.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Liest oder setzt den Empfindlichkeitstyp.

Wert: Der Typ der Empfindlichkeit.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Liest oder setzt die Schärfe.

Wert: Die Schärfe.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Liest oder setzt den Verschlusszeitwert.

Wert: Der Verschlusszeitwert.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Liest oder setzt die Software.

Wert: Die Software.

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Liest oder setzt die räumliche Frequenzantwort.

Wert: Die räumliche Frequenzantwort.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Liest oder setzt die spektrale Empfindlichkeit.

Wert: Die spektrale Empfindlichkeit.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Liest die Standardausgangsempfindlichkeit

Wert: Die Standardausgangsempfindlichkeit.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Liest oder setzt den Motivbereich.

Wert: Der Motivbereich.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Liest oder setzt den Motivabstand.

Wert: Der Motivabstand.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Liest oder setzt den Abstandbereich des Motivs.

Wert: Der Motivabstandsbereich.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Liest oder setzt den Motivstandort.

Wert: Der Motivort.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Liest oder setzt die Sekundenbruchteile für das DateTime-Tag.

Wert: Die Sekundenbruchteile für das DateTime-Tag.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized-Tag.

Wert: Die Sekundenbruchteile für das DateTimeDigitized-Tag.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal-Tag.

Wert: Die Sekundenbruchteile für das DateTimeOriginal-Tag.

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


Liest oder setzt das Vorschaubild.

Wert: Das Vorschaubild.

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Liest oder setzt die Transferfunktion.

Wert: Die Transferfunktion.

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Liest oder setzt den Benutzerkommentar.

Wert: Der Benutzerkommentar.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Liest oder setzt den Weißabgleich.

Wert: Der Weißabgleich.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Liest oder setzt die Chromatik des Weißpunkts des Bildes.

Wert: Die Chromatik des Weißpunkts des Bildes.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Liest oder setzt die X‑Auflösung.

Wert: Die X‑Auflösung.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

Wert: Die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Liest oder setzt die Y‑Auflösung.

Wert: Die Y‑Auflösung.

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


Liest oder setzt einen Wert, der angibt, ob die aus dem Stream erstellten EXIF-Daten big endian sind.

Wert:  true  wenn die aus dem Stream erstellten EXIF-Daten big endian sind; andernfalls,  false .

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


Tag aus dem Container entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Der Tag‑Bezeichner zum Entfernen. |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serialisiert die EXIF‑Daten. Schreibt die Tag‑Werte und Inhalte. Der am stärksten einflussreiche Größentag ist der Inhalt des Thumbnail‑Tags.

**Returns:**
byte[] - Die serialisierten EXIF‑Daten.

Die gesamte Segmentgröße muss kleiner oder gleich MaxExifSegmentSize Bytes sein, um ein korrektes JPEG‑Bild zu erzeugen. Hinweis: Versuchen Sie, die Größe des Vorschaubilds zu reduzieren oder dessen Kompression zu ändern, falls Sie einen zu großen EXIF‑Abschnitt haben.
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Liest oder setzt den Blendenwert.

Wert: Der Blendenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Liest oder setzt den Künstler.

Wert: Der Künstler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die aus dem Stream erstellten EXIF-Daten big endian sind.

Wert:  true  wenn die aus dem Stream erstellten EXIF-Daten big endian sind; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Liest oder setzt die Bits pro Probe.

Wert: Die Bits pro Probe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Liest oder setzt die Seriennummer des Kameragehäuses.

Wert: Die Seriennummer des Gehäuses.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Liest oder setzt den Helligkeitswert.

Wert: Der Helligkeitswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Liest oder setzt das CFA‑Muster.

Wert: Das CFA-Muster.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Liest oder setzt den Namen des Kamerabesitzers

Wert: Der Name des Kamerabesitzers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Liest oder setzt den Farbraum.

Wert: Der Farbraum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Ruft Tags ab oder legt sie fest, die zum gemeinsamen Abschnitt gehören. Dies gilt nur für JPEG-Bilder; im TIFF-Format werden stattdessen tiffOptions verwendet.

Wert: Die Tags des gemeinsamen Abschnitts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Liest oder setzt die Komponenten‑Konfiguration.

Wert: Die Komponenten-Konfiguration.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Liest oder setzt die komprimierten Bits pro Pixel.

Wert: Die komprimierten Bits pro Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Liest oder setzt die Kompression.

Wert: Die Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Liest oder setzt den Kontrast.

Wert: Der Kontrast.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Liest oder setzt das Urheberrecht.

Wert: Das Urheberrecht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Liest oder setzt die benutzerdefinierte Darstellung.

Wert: Das benutzerdefinierte Rendering.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Liest oder setzt das Datum und die Uhrzeit.

Wert: Das Datum und die Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Liest oder setzt das Digitalisierungsdatum und die -uhrzeit.

Wert: Das Datum/Uhrzeit der Digitalisierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Liest oder setzt das Originaldatum und die -uhrzeit.

Wert: Das ursprüngliche Datum/Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Liest oder setzt die Geräte­einstellungsbeschreibung

Wert: Die Geräte-Einstellungsbeschreibung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Liest oder setzt das digitale Zoom‑Verhältnis.

Wert: Das digitale Zoom-Verhältnis.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Liest oder setzt Tags, die ausschließlich zum EXIF‑Abschnitt gehören.

Wert: Die Tags des EXIF-Abschnitts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Liest oder setzt die EXIF‑Version.

Wert: Die EXIF-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Liest oder setzt den Belichtungswert.

Wert: Der Belichtungskorrekturwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Liest oder setzt den Belichtungsindex.

Wert: Der Belichtungsindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Liest oder setzt den Belichtungsmodus.

Wert: Der Belichtungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Liest oder setzt das Belichtungsprogramm.

Wert: Das Belichtungsprogramm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Liest oder setzt die Belichtungszeit.

Wert: Die Belichtungszeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Liest oder setzt die F‑Zahl.

Wert: Die Blendenzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Liest oder setzt den Dateiquellentyp.

Wert: Der Dateiquellen-Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Liest oder setzt den Blitz.

Wert: Der Blitz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Liest oder setzt die Blitzenergie.

Wert: Die Blitzenergie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Liest oder setzt die Flash‑Pix-Version.

Wert: Die Flash-Pix-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Liest oder setzt die Brennweite.

Wert: Die Länge der Brennweite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Liest oder setzt die Brennweite in 35‑mm-Film.

Wert: Die Brennweite in 35‑mm-Film.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit der Bildebene.

Wert: Die Auflösungseinheit der Bildebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Liest oder setzt die X‑Auflösung der Bildebene.

Wert: Die X‑Auflösung der Bildebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Liest oder setzt die Y‑Auflösung der Bildebene.

Wert: Die Y‑Auflösung der Bildebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Liest oder setzt die GPS‑Höhe.

Wert: Die GPS-Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Liest oder setzt die GPS‑Höhe, die als Referenzhöhe verwendet wird.

Wert: Die GPS-Höhe, die als Referenzhöhe verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Liest oder setzt die GPS‑Gebietsinformationen.

Wert: Die GPS-Flächeninformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Liest oder setzt den GPS‑DOP (Datenpräzisionsgrad).

Wert: Der GPS-DOP (Datengrad der Präzision).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Liest oder setzt die GPS‑Zeichenkette, die Datum‑ und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

Wert: Die GPS‑Zeichenkette, die Datum‑ und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Liest oder setzt die GPS‑Richtung zum Zielpunkt.

Wert: Der GPS‑Kurs zum Zielpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Liest oder setzt die GPS‑Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird.

Wert: Die GPS‑Referenz, die zur Angabe des Kurses zum Zielpunkt verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Liest oder setzt die GPS‑Entfernung zum Zielpunkt.

Wert: Die GPS‑Entfernung zum Zielpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Liest oder setzt die GPS‑Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

Wert: Die GPS‑Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Liest oder setzt den GPS‑Breitengrad des Zielpunkts.

Wert: Der GPS‑Breitengrad des Zielpunkts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Liest oder setzt den GPS‑Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

Wert: Der GPS‑Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Liest oder setzt den GPS-Längengrad des Zielpunkts.

Wert: Der GPS‑Längengrad des Zielpunkts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

Wert: Der GPS‑Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird.

Wert: Der GPS‑Wert, der angibt, ob eine differenzielle Korrektur auf den GPS‑Empfänger angewendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme.

Wert: Die GPS‑Richtung des Bildes bei der Aufnahme.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme.

Wert: Die GPS‑Referenz zur Angabe der Bildrichtung bei der Aufnahme.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Liest oder setzt den GPS-Breitengrad.

Wert: Der GPS‑Breitengrad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist.

Wert: Der GPS-Breitengrad ist nördliche oder südliche Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Liest oder setzt den GPS-Längengrad.

Wert: Der GPS-Längengrad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist.

Wert: Der GPS-Längengrad ist östliche oder westliche Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

Wert: Die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Liest oder setzt den GPS-Messmodus.

Wert: Der GPS-Messmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Standortbestimmung verwendeten Methode aufzeichnet.

Wert: Die GPS-Zeichenkette, die den Namen der für die Positionsbestimmung verwendeten Methode aufzeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden.

Wert: Die für Messungen verwendeten GPS-Satelliten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung.

Wert: Die Geschwindigkeit der GPS-Empfängerbewegung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird.

Wert: Die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird.

Wert: Der Status des GPS-Empfängers, wenn das Bild aufgenommen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören.

Wert: Die GPS-Tags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit).

Wert: Die GPS-Zeit als UTC (Koordinierte Weltzeit).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Liest oder setzt die Richtung der GPS-Empfängerbewegung.

Wert: Die Richtung der GPS-Empfängerbewegung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Liest oder setzt die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung.

Wert: Die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Liest oder setzt den GPS-Versionsidentifikator.

Wert: Der GPS-Versionsidentifikator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Liest oder setzt den Grad der Gesamtabstimmung der Bildverstärkung.

Wert: Der Grad der Gesamten Bildverstärkungsanpassung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Liest oder setzt das Gamma.

Wert: Der Gammawert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Liest oder setzt die ISO-Geschwindigkeit

Wert: Die ISO-Geschwindigkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Liest oder setzt den ISO-Geschwindigkeits-Breitengrad-yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO-Geschwindigkeits-Breitengrad yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudezzz aufgezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Liest oder setzt den ISO‑Geschwindigkeits‑Latitude‑zzz‑Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO-Geschwindigkeits-Breitengrad zzz-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudeyyy aufgezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Liest oder setzt die Bildbeschreibung.

Wert: Die Bildbeschreibung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Liest oder setzt die Bildlänge.

Wert: Die Länge des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Liest oder setzt die eindeutige Bildkennung.

Wert: Der eindeutige Bildidentifikator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Liest oder setzt die Bildbreite.

Wert: Die Breite des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Liest oder setzt den Hersteller des Objektivs.

Wert: Der Linsenhersteller.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Liest oder setzt das Objektivmodell.

Wert: Das Linsenmodell.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Liest oder setzt die Seriennummer des Objektivs.

Wert: Die Seriennummer des Objektivs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Liest oder setzt die Objektivspezifikation

Wert: Die Objektivspezifikation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Liest oder setzt die Lichtquelle.

Wert: Die Lichtquelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Legt den Hersteller der Aufzeichnungsgeräte fest.

Wert: Der Hersteller der Aufzeichnungsgeräte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | der Hersteller der Aufzeichnungsgeräte. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Liest oder setzt die rohen Herstellerhinweisdaten.

Wert: Die rohen Maker-Notizdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Liest oder setzt den maximalen Blendenwert.

Wert: Der maximale Blendenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Liest oder setzt den Messmodus.

Wert: Der Messmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Liest oder setzt das Modell.

Wert: Das Modell.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Liest oder setzt die in ISO 14524 spezifizierte Opto‑Elektrische Umwandlungsfunktion (OECF).

Wert: Die in ISO 14524 angegebene Opto‑elektrische Umwandlungsfunktion (OECF).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Liest oder setzt die Ausrichtung.

Wert: Die Orientierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Liest oder setzt die fotografische Empfindlichkeit.

Wert: Die fotografische Empfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Liest oder setzt die photometrische Interpretation.

Wert: Die photometrische Interpretation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Liest oder setzt die Pixel‑X‑Dimension.

Wert: Die Pixel‑X‑Dimension.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Liest oder setzt die Pixel‑Y‑Dimension.

Wert: Die Pixel‑Y‑Dimension.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Liest oder setzt die planare Konfiguration.

Wert: Die planare Konfiguration.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Liest oder setzt die Chromatik der drei Primärfarben des Bildes.

Wert: Die Chromatik der drei Primärfarben des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags).

Wert: Die EXIF‑Tags (einschließlich gängiger und GPS‑Tags).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Liest oder setzt den empfohlenen Belichtungsindex.

Wert: Der empfohlene Belichtungsindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Liest oder setzt das Referenz‑Schwarz‑Weiß.

Wert: Der Referenz‑Schwarz‑Weiß‑Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Liest oder setzt die zugehörige Audiodatei.

Wert: Die zugehörige Audiodatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit.

Wert: Die Auflösungseinheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Liest oder setzt die Proben pro Pixel.

Wert: Die Stichproben pro Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Liest oder setzt die Sättigung.

Wert: Die Sättigung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Liest oder setzt den Aufnahmetyp der Szene.

Wert: Der Typ der Szenenerfassung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Liest oder setzt den Szenentyp.

Wert: Der Typ der Szene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Liest oder setzt die Erfassungsmethode.

Wert: Die Erfassungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Liest oder setzt den Empfindlichkeitstyp.

Wert: Der Typ der Empfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Liest oder setzt die Schärfe.

Wert: Die Schärfe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Liest oder setzt den Verschlusszeitwert.

Wert: Der Verschlusszeitwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Liest oder setzt die Software.

Wert: Die Software.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Liest oder setzt die räumliche Frequenzantwort.

Wert: Die räumliche Frequenzantwort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Liest oder setzt die spektrale Empfindlichkeit.

Wert: Die spektrale Empfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Legt die Standardausgangsempfindlichkeit fest.

Wert: Die Standardausgangsempfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Liest oder setzt den Motivbereich.

Wert: Der Motivbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Liest oder setzt den Motivabstand.

Wert: Der Motivabstand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Liest oder setzt den Abstandbereich des Motivs.

Wert: Der Motivabstandsbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Liest oder setzt den Motivstandort.

Wert: Der Motivort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Liest oder setzt die Sekundenbruchteile für das DateTime-Tag.

Wert: Die Sekundenbruchteile für das DateTime-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized-Tag.

Wert: Die Sekundenbruchteile für das DateTimeDigitized-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal-Tag.

Wert: Die Sekundenbruchteile für das DateTimeOriginal-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


Liest oder setzt das Vorschaubild.

Wert: Das Vorschaubild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Liest oder setzt die Transferfunktion.

Wert: Die Transferfunktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Liest oder setzt den Benutzerkommentar.

Wert: Der Benutzerkommentar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Liest oder setzt den Weißabgleich.

Wert: Der Weißabgleich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Liest oder setzt die Chromatik des Weißpunkts des Bildes.

Wert: Die Chromatik des Weißpunkts des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Liest oder setzt die X‑Auflösung.

Wert: Die X‑Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

Wert: Die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Liest oder setzt die Y‑Auflösung.

Wert: Die Y‑Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

