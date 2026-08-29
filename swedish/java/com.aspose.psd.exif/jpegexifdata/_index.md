---
title: "JpegExifData"
second_title: "Aspose.PSD för Java API-referens"
description: "EXIF-datakontainer för jpeg-filer."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

EXIF-datakontainer för jpeg-filer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initierar en ny instans av klassen  JpegExifData  . |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen  JpegExifData  med data från en array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen  JpegExifData  med data från en array. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | Den maximala EXIF-segmentsstorleken i byte som är tillåten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Hämtar eller anger bländarvärdet. |
| [getArtist()](#getArtist--) | Hämtar eller anger artisten. |
| [getBitsPerSample()](#getBitsPerSample--) | Hämtar eller anger bitar per prov. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Hämtar eller anger kamerahusets serienummer. |
| [getBrightnessValue()](#getBrightnessValue--) | Hämtar eller anger ljusstyrkevärdet. |
| [getCFAPattern()](#getCFAPattern--) | Hämtar eller anger CFA‑mönstret. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Hämtar eller anger kamerans ägarnamn |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Hämtar eller anger färgrymden. |
| [getCommonTags()](#getCommonTags--) | Hämtar eller anger taggar som tillhör den gemensamma sektionen. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Hämtar eller anger komponentkonfigurationen. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Hämtar eller anger komprimerade bitar per pixel. |
| [getCompression()](#getCompression--) | Hämtar eller anger komprimeringen. |
| [getContrast()](#getContrast--) | Hämtar eller anger kontrasten. |
| [getCopyright()](#getCopyright--) | Hämtar eller anger upphovsrätten. |
| [getCustomRendered()](#getCustomRendered--) | Hämtar eller anger den anpassade rendering. |
| [getDateTime()](#getDateTime--) | Hämtar eller anger datum och tid. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Hämtar eller anger datum och tid för digitalisering. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Hämtar eller anger datum och tid för originalet. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Hämtar eller anger beskrivning av enhetens inställningar |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Hämtar eller anger den digitala zoomförhållandet. |
| [getExifTags()](#getExifTags--) | Hämtar eller anger taggar som endast tillhör EXIF‑avsnittet. |
| [getExifVersion()](#getExifVersion--) | Hämtar eller anger EXIF‑versionen. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Hämtar eller anger exponeringsförskjutningsvärdet. |
| [getExposureIndex()](#getExposureIndex--) | Hämtar eller anger exponeringsindexet. |
| [getExposureMode()](#getExposureMode--) | Hämtar eller anger exponeringsläget. |
| [getExposureProgram()](#getExposureProgram--) | Hämtar eller anger exponeringsprogrammet. |
| [getExposureTime()](#getExposureTime--) | Hämtar eller anger exponeringstiden. |
| [getFNumber()](#getFNumber--) | Hämtar eller anger F‑numret. |
| [getFileSource()](#getFileSource--) | Hämtar eller anger filkällans typ. |
| [getFlash()](#getFlash--) | Hämtar eller anger blixten. |
| [getFlashEnergy()](#getFlashEnergy--) | Hämtar eller anger blixtenergin. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Hämtar eller anger flash‑pix‑versionen. |
| [getFocalLength()](#getFocalLength--) | Hämtar eller anger brännvidden. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Hämtar eller anger brännvidden i 35 mm‑film. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Hämtar eller anger upplösningsenheten för fokalplanet. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Hämtar eller anger fokalplanets x‑upplösning. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Hämtar eller anger fokalplanets y‑upplösning. |
| [getGPSAltitude()](#getGPSAltitude--) | Hämtar eller anger GPS‑höjden. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Hämtar eller anger GPS‑höjden som används som referenshöjd. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Hämtar eller anger GPS‑områdesinformation. |
| [getGPSDOP()](#getGPSDOP--) | Hämtar eller anger GPS‑DOP (dataprecisionsgrad). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Hämtar eller anger GPS‑teckensträng som spelar in datum‑ och tidsinformation relativt UTC (Coordinated Universal Time). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Hämtar eller anger GPS‑riktning mot destinationspunkten. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Hämtar eller anger GPS‑referensen som används för att ange riktning mot destinationspunkten. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Hämtar eller anger GPS‑avståndet till destinationspunkten. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Hämtar eller anger GPS‑enheten som används för att uttrycka avståndet till destinationspunkten. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Hämtar eller anger GPS‑latituden för destinationspunkten. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Hämtar eller anger GPS‑värdet som visar om latituden för destinationspunkten är norr eller söder. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Hämtar eller anger GPS‑longituden för destinationspunkten. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Hämtar eller anger GPS‑värdet som visar om longituden för destinationspunkten är östlig eller västlig. |
| [getGPSDifferential()](#getGPSDifferential--) | Hämtar eller anger ett GPS‑värde som visar om differentialkorrigering tillämpas på GPS‑mottagaren. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Hämtar eller anger GPS‑riktningen för bilden när den togs. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Hämtar eller anger GPS‑referensen för att ange bildens riktning när den tas. |
| [getGPSLatitude()](#getGPSLatitude--) | Hämtar eller anger GPS‑latituden. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Hämtar eller anger om GPS‑latituden är norr eller söder. |
| [getGPSLongitude()](#getGPSLongitude--) | Hämtar eller anger GPS‑longituden. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Hämtar eller anger om GPS‑longituden är östlig eller västlig. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Hämtar eller anger de GPS‑geodetiska undersökningsdata som används av GPS‑mottagaren. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Hämtar eller anger GPS‑mätningsläget. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Hämtar eller anger GPS‑teckensträngen som registrerar namnet på metoden som används för positionsbestämning. |
| [getGPSSatellites()](#getGPSSatellites--) | Hämtar eller anger GPS‑satelliterna som används för mätningar. |
| [getGPSSpeed()](#getGPSSpeed--) | Hämtar eller anger hastigheten för GPS‑mottagarens rörelse. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Hämtar eller anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet. |
| [getGPSStatus()](#getGPSStatus--) | Hämtar eller anger statusen för GPS‑mottagaren när bilden registreras. |
| [getGPSTags()](#getGPSTags--) | Hämtar eller anger taggar som endast tillhör GPS‑avsnittet. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Hämtar eller anger GPS‑tiden som UTC (Coordinated Universal Time). |
| [getGPSTrack()](#getGPSTrack--) | Hämtar eller anger riktningen för GPS‑mottagarens rörelse. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Hämtar eller anger referensen för att ange riktningen för GPS‑mottagarens rörelse. |
| [getGPSVersionID()](#getGPSVersionID--) | Hämtar eller anger GPS‑versionsidentifieraren. |
| [getGainControl()](#getGainControl--) | Hämtar eller anger graden av total bildförstärkningsjustering. |
| [getGamma()](#getGamma--) | Hämtar eller anger gamma. |
| [getISOSpeed()](#getISOSpeed--) | Hämtar eller anger ISO-hastighet |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Hämtar eller anger ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Hämtar eller anger ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [getImageDescription()](#getImageDescription--) | Hämtar eller anger bildbeskrivning. |
| [getImageLength()](#getImageLength--) | Hämtar eller anger bildlängd. |
| [getImageUniqueID()](#getImageUniqueID--) | Hämtar eller anger bildens unika identifierare. |
| [getImageWidth()](#getImageWidth--) | Hämtar eller anger bildbredd. |
| [getLensMake()](#getLensMake--) | Hämtar eller anger linsens tillverkare. |
| [getLensModel()](#getLensModel--) | Hämtar eller anger linsmodellen. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Hämtar eller anger linsens serienummer. |
| [getLensSpecification()](#getLensSpecification--) | Hämtar eller anger linsens specifikation |
| [getLightSource()](#getLightSource--) | Hämtar eller anger ljuskällan. |
| [getMake()](#getMake--) | Hämtar tillverkaren av inspelningsutrustningen. |
| [getMakerNoteData()](#getMakerNoteData--) | Hämtar tillverkarens noteringsdata. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Hämtar eller anger tillverkarens noteringsrådata. |
| [getMakerNotes()](#getMakerNotes--) | Hämtar tillverkarens anteckningar. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Hämtar eller anger maximalt bländarvärde. |
| [getMeteringMode()](#getMeteringMode--) | Hämtar eller anger mätarläget. |
| [getModel()](#getModel--) | Hämtar eller anger modellen. |
| [getOECF()](#getOECF--) | Hämtar eller anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| [getOrientation()](#getOrientation--) | Hämtar eller anger orienteringen. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Hämtar eller anger fotografisk känslighet. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Hämtar eller anger fotometrisk tolkning. |
| [getPixelXDimension()](#getPixelXDimension--) | Hämtar eller anger pixelns x-dimension. |
| [getPixelYDimension()](#getPixelYDimension--) | Hämtar eller anger pixelns y-dimension. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Hämtar eller anger planär konfiguration. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Hämtar eller anger kromaticiteten för bildens tre primära färger. |
| [getProperties()](#getProperties--) | Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Hämtar eller anger rekommenderat exponeringsindex. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Hämtar eller anger referenssvartvitt. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Hämtar eller anger den relaterade ljudfilen. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar eller anger upplösningsenhet. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Hämtar eller anger prover per pixel. |
| [getSaturation()](#getSaturation--) | Hämtar eller anger mättnad. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Hämtar eller anger sceninspelningstyp. |
| [getSceneType()](#getSceneType--) | Hämtar eller anger scenens typ. |
| [getSensingMethod()](#getSensingMethod--) | Hämtar eller anger avkänningsmetoden. |
| [getSensitivityType()](#getSensitivityType--) | Hämtar eller anger känslighetstypen. |
| [getSharpness()](#getSharpness--) | Hämtar eller anger skärpan. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Hämtar eller anger slutartidens värde. |
| [getSoftware()](#getSoftware--) | Hämtar eller anger programvaran. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Hämtar eller anger det rumsliga frekvenssvaret. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Hämtar eller anger spektralkänsligheten. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Hämtar standardutgångskänsligheten |
| [getSubjectArea()](#getSubjectArea--) | Hämtar eller anger motivområdet. |
| [getSubjectDistance()](#getSubjectDistance--) | Hämtar eller anger motivavståndet. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Hämtar eller anger intervallet för motivavståndet. |
| [getSubjectLocation()](#getSubjectLocation--) | Hämtar eller anger motivets plats. |
| [getSubsecTime()](#getSubsecTime--) | Hämtar eller anger bråkdelen av sekunder för DateTime-taggen. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen. |
| [getThumbnail()](#getThumbnail--) | Hämtar eller anger miniatyrbilden. |
| [getTransferFunction()](#getTransferFunction--) | Hämtar eller anger överföringsfunktionen. |
| [getUserComment()](#getUserComment--) | Hämtar eller anger användarkommentaren. |
| [getWhiteBalance()](#getWhiteBalance--) | Hämtar eller anger vitbalansen. |
| [getWhitePoint()](#getWhitePoint--) | Hämtar eller anger kromaticiteten för bildens vita punkt. |
| [getXResolution()](#getXResolution--) | Hämtar eller anger x-upplösning. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Hämtar eller anger positionen för krominanskomponenter i förhållande till luminanskomponenten. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Hämtar eller anger samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten. |
| [getYResolution()](#getYResolution--) | Hämtar eller anger y-upplösning. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Ta bort tagg från behållare |
| [serializeExifData()](#serializeExifData--) | Serialiserar EXIF-data. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger bländarvärdet. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Hämtar eller anger artisten. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Hämtar eller anger bitar per prov. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Hämtar eller anger kamerahusets serienummer. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Hämtar eller anger ljusstyrkevärdet. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Hämtar eller anger CFA‑mönstret. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Hämtar eller anger kamerans ägarnamn |
| [setColorSpace(int value)](#setColorSpace-int-) | Hämtar eller anger färgrymden. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggar som tillhör den gemensamma sektionen. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Hämtar eller anger komponentkonfigurationen. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger komprimerade bitar per pixel. |
| [setCompression(int value)](#setCompression-int-) | Hämtar eller anger komprimeringen. |
| [setContrast(int value)](#setContrast-int-) | Hämtar eller anger kontrasten. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Hämtar eller anger upphovsrätten. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Hämtar eller anger den anpassade rendering. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Hämtar eller anger datum och tid. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Hämtar eller anger datum och tid för digitalisering. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Hämtar eller anger datum och tid för originalet. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Hämtar eller anger beskrivning av enhetens inställningar |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger den digitala zoomförhållandet. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggar som endast tillhör EXIF‑avsnittet. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Hämtar eller anger EXIF‑versionen. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Hämtar eller anger exponeringsförskjutningsvärdet. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger exponeringsindexet. |
| [setExposureMode(int value)](#setExposureMode-int-) | Hämtar eller anger exponeringsläget. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Hämtar eller anger exponeringsprogrammet. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger exponeringstiden. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger F‑numret. |
| [setFileSource(byte value)](#setFileSource-byte-) | Hämtar eller anger filkällans typ. |
| [setFlash(int value)](#setFlash-int-) | Hämtar eller anger blixten. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger blixtenergin. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Hämtar eller anger flash‑pix‑versionen. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger brännvidden. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Hämtar eller anger brännvidden i 35 mm‑film. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Hämtar eller anger upplösningsenheten för fokalplanet. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger fokalplanets x‑upplösning. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger fokalplanets y‑upplösning. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS‑höjden. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Hämtar eller anger GPS‑höjden som används som referenshöjd. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Hämtar eller anger GPS‑områdesinformation. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS‑DOP (dataprecisionsgrad). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Hämtar eller anger GPS‑teckensträng som spelar in datum‑ och tidsinformation relativt UTC (Coordinated Universal Time). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS‑riktning mot destinationspunkten. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Hämtar eller anger GPS‑referensen som används för att ange riktning mot destinationspunkten. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS‑avståndet till destinationspunkten. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Hämtar eller anger GPS‑enheten som används för att uttrycka avståndet till destinationspunkten. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS‑latituden för destinationspunkten. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Hämtar eller anger GPS‑värdet som visar om latituden för destinationspunkten är norr eller söder. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS‑longituden för destinationspunkten. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Hämtar eller anger GPS‑värdet som visar om longituden för destinationspunkten är östlig eller västlig. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Hämtar eller anger ett GPS‑värde som visar om differentialkorrigering tillämpas på GPS‑mottagaren. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS‑riktningen för bilden när den togs. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Hämtar eller anger GPS‑referensen för att ange bildens riktning när den tas. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS‑latituden. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Hämtar eller anger om GPS‑latituden är norr eller söder. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS‑longituden. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Hämtar eller anger om GPS‑longituden är östlig eller västlig. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Hämtar eller anger de GPS‑geodetiska undersökningsdata som används av GPS‑mottagaren. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Hämtar eller anger GPS‑mätningsläget. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Hämtar eller anger GPS‑teckensträngen som registrerar namnet på metoden som används för positionsbestämning. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Hämtar eller anger GPS‑satelliterna som används för mätningar. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger hastigheten för GPS‑mottagarens rörelse. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Hämtar eller anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Hämtar eller anger statusen för GPS‑mottagaren när bilden registreras. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggar som endast tillhör GPS‑avsnittet. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS‑tiden som UTC (Coordinated Universal Time). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Hämtar eller anger riktningen för GPS‑mottagarens rörelse. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Hämtar eller anger referensen för att ange riktningen för GPS‑mottagarens rörelse. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Hämtar eller anger GPS‑versionsidentifieraren. |
| [setGainControl(int value)](#setGainControl-int-) | Hämtar eller anger graden av total bildförstärkningsjustering. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Hämtar eller anger ISO-hastighet |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Hämtar eller anger ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Hämtar eller anger ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Hämtar eller anger bildbeskrivning. |
| [setImageLength(long value)](#setImageLength-long-) | Hämtar eller anger bildlängd. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Hämtar eller anger bildens unika identifierare. |
| [setImageWidth(long value)](#setImageWidth-long-) | Hämtar eller anger bildbredd. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Hämtar eller anger linsens tillverkare. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Hämtar eller anger linsmodellen. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Hämtar eller anger linsens serienummer. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger linsens specifikation |
| [setLightSource(int value)](#setLightSource-int-) | Hämtar eller anger ljuskällan. |
| [setMake(String value)](#setMake-java.lang.String-) | Anger tillverkaren av inspelningsutrustningen. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Hämtar eller anger tillverkarens noteringsrådata. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger maximalt bländarvärde. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Hämtar eller anger mätarläget. |
| [setModel(String value)](#setModel-java.lang.String-) | Hämtar eller anger modellen. |
| [setOECF(byte[] value)](#setOECF-byte---) | Hämtar eller anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger orienteringen. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Hämtar eller anger fotografisk känslighet. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Hämtar eller anger fotometrisk tolkning. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Hämtar eller anger pixelns x-dimension. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Hämtar eller anger pixelns y-dimension. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Hämtar eller anger planär konfiguration. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger kromaticiteten för bildens tre primära färger. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Hämtar eller anger rekommenderat exponeringsindex. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger referenssvartvitt. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Hämtar eller anger den relaterade ljudfilen. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Hämtar eller anger upplösningsenhet. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Hämtar eller anger prover per pixel. |
| [setSaturation(int value)](#setSaturation-int-) | Hämtar eller anger mättnad. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Hämtar eller anger sceninspelningstyp. |
| [setSceneType(byte value)](#setSceneType-byte-) | Hämtar eller anger scenens typ. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Hämtar eller anger avkänningsmetoden. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Hämtar eller anger känslighetstypen. |
| [setSharpness(int value)](#setSharpness-int-) | Hämtar eller anger skärpan. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Hämtar eller anger slutartidens värde. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Hämtar eller anger programvaran. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Hämtar eller anger det rumsliga frekvenssvaret. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Hämtar eller anger spektralkänsligheten. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Anger standardutgångskänsligheten |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Hämtar eller anger motivområdet. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger motivavståndet. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Hämtar eller anger intervallet för motivavståndet. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Hämtar eller anger motivets plats. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Hämtar eller anger bråkdelen av sekunder för DateTime-taggen. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | Hämtar eller anger miniatyrbilden. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Hämtar eller anger överföringsfunktionen. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Hämtar eller anger användarkommentaren. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Hämtar eller anger vitbalansen. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger kromaticiteten för bildens vita punkt. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger x-upplösning. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Hämtar eller anger positionen för krominanskomponenter i förhållande till luminanskomponenten. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Hämtar eller anger samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger y-upplösning. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initierar en ny instans av klassen  JpegExifData  .

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


Initierar en ny instans av klassen  JpegExifData  med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Array av EXIF-taggar tillsammans med vanliga taggar och GPS-taggar. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initierar en ny instans av klassen  JpegExifData  med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De vanliga taggarna. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | EXIF-taggarna. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | GPS-taggarna. |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


Den maximala EXIF-segmentsstorleken i byte som är tillåten.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Hämtar eller anger bländarvärdet.

Värde: bländarvärdet.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


Hämtar eller anger artisten.

Värde: Konstnären.

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Hämtar eller anger bitar per prov.

Värde: Bitar per prov.

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Hämtar eller anger kamerahusets serienummer.

Värde: kroppsserienumret.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Hämtar eller anger ljusstyrkevärdet.

Värde: ljusstyrkevärdet.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Hämtar eller anger CFA‑mönstret.

Värde: CFA-mönstret.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Hämtar eller anger kamerans ägarnamn

Värde: namnet på kamerans ägare.

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


Hämtar eller anger färgrymden.

Värde: färgrymden.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Hämtar eller anger taggar som tillhör den gemensamma sektionen. Detta gäller endast jpeg-bilder, i tiff-format används tiffOptions istället

Värde: de gemensamma sektionstaggarna.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Hämtar eller anger komponentkonfigurationen.

Värde: komponentkonfigurationen.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Hämtar eller anger komprimerade bitar per pixel.

Värde: komprimerade bitar per pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


Hämtar eller anger komprimeringen.

Värde: Komprimeringen.

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


Hämtar eller anger kontrasten.

Värde: kontrasten.

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Hämtar eller anger upphovsrätten.

Värde: Upphovsrätten.

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Hämtar eller anger den anpassade rendering.

Värde: anpassad återgivning.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Hämtar eller anger datum och tid.

Värde: Datum och tid.

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Hämtar eller anger datum och tid för digitalisering.

Värde: digitaliseringsdatum och tid.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Hämtar eller anger datum och tid för originalet.

Värde: originaldatum och tid.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Hämtar eller anger beskrivning av enhetens inställningar

Värde: enhetsinställningsbeskrivning.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Hämtar eller anger den digitala zoomförhållandet.

Värde: digitala zoomförhållandet.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Hämtar eller anger taggar som endast tillhör EXIF‑avsnittet.

Värde: EXIF-sektions-taggarna.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Hämtar eller anger EXIF‑versionen.

Värde: EXIF-versionen.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Hämtar eller anger exponeringsförskjutningsvärdet.

Värde: exponeringskompensationsvärdet.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Hämtar eller anger exponeringsindexet.

Värde: exponeringsindexet.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Hämtar eller anger exponeringsläget.

Värde: exponeringsläget.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Hämtar eller anger exponeringsprogrammet.

Värde: exponeringsprogrammet.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Hämtar eller anger exponeringstiden.

Värde: exponeringstiden.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Hämtar eller anger F‑numret.

Värde: F-numret.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Hämtar eller anger filkällans typ.

Värde: Filkällans typ.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Hämtar eller anger blixten.

Värde: Blixten.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Hämtar eller anger blixtenergin.

Värde: Blixtenergi.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Hämtar eller anger flash‑pix‑versionen.

Värde: Blixt pix-version.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Hämtar eller anger brännvidden.

Värde: Fokallängden.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Hämtar eller anger brännvidden i 35 mm‑film.

Värde: Brännvidden i 35 mm film.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Hämtar eller anger upplösningsenheten för fokalplanet.

Värde: Upplösningsenhet för fokalplanet.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Hämtar eller anger fokalplanets x‑upplösning.

Värde: Fokalplanets x-upplösning.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Hämtar eller anger fokalplanets y‑upplösning.

Värde: Fokalplanets y-upplösning.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Hämtar eller anger GPS‑höjden.

Värde: GPS-höjd.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Hämtar eller anger GPS‑höjden som används som referenshöjd.

Värde: GPS-höjd som används som referenshöjd.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Hämtar eller anger GPS‑områdesinformation.

Värde: GPS-områdesinformation.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Hämtar eller anger GPS‑DOP (dataprecisionsgrad).

Värde: GPS DOP (dataprecisionsgrad).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Hämtar eller anger GPS‑teckensträng som spelar in datum‑ och tidsinformation relativt UTC (Coordinated Universal Time).

Värde: GPS-teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Hämtar eller anger GPS‑riktning mot destinationspunkten.

Värde: GPS-riktning mot destinationspunkten.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Hämtar eller anger GPS‑referensen som används för att ange riktning mot destinationspunkten.

Värde: GPS-referens som används för att ange riktning mot destinationspunkten.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Hämtar eller anger GPS‑avståndet till destinationspunkten.

Värde: GPS-avstånd till destinationspunkten.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Hämtar eller anger GPS‑enheten som används för att uttrycka avståndet till destinationspunkten.

Värde: GPS-enhet som används för att uttrycka avståndet till destinationspunkten.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Hämtar eller anger GPS‑latituden för destinationspunkten.

Värde: GPS-latitud för destinationspunkten.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Hämtar eller anger GPS‑värdet som visar om latituden för destinationspunkten är norr eller söder.

Värde: GPS-värdet som indikerar om destinationspunktens latitud är nordlig eller sydlig.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Hämtar eller anger GPS‑longituden för destinationspunkten.

Värde: GPS-longitud för destinationspunkten.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Hämtar eller anger GPS‑värdet som visar om longituden för destinationspunkten är östlig eller västlig.

Värde: GPS-värdet som indikerar om destinationspunktens longitud är östlig eller västlig.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Hämtar eller anger ett GPS‑värde som visar om differentialkorrigering tillämpas på GPS‑mottagaren.

Värde: GPS-värdet som indikerar om differentialkorrigering tillämpas på GPS-mottagaren.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Hämtar eller anger GPS‑riktningen för bilden när den togs.

Värde: GPS-riktningen för bilden när den togs.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Hämtar eller anger GPS‑referensen för att ange bildens riktning när den tas.

Värde: GPS-referensen för att ange bildens riktning när den tas.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Hämtar eller anger GPS‑latituden.

Värde: GPS-latituden.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Hämtar eller anger om GPS‑latituden är norr eller söder.

Värde: GPS-latituden är nordlig eller sydlig latitud.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Hämtar eller anger GPS‑longituden.

Värde: GPS-longituden.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Hämtar eller anger om GPS‑longituden är östlig eller västlig.

Värde: GPS-longituden är östlig eller västlig longitud.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Hämtar eller anger de GPS‑geodetiska undersökningsdata som används av GPS‑mottagaren.

Värde: GPS:s geodetiska undersökningsdata som används av GPS-mottagaren.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Hämtar eller anger GPS‑mätningsläget.

Värde: GPS-mätningsläget.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Hämtar eller anger GPS‑teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

Värde: GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Hämtar eller anger GPS‑satelliterna som används för mätningar.

Värde: GPS-satelliterna som används för mätningar.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Hämtar eller anger hastigheten för GPS‑mottagarens rörelse.

Värde: Hastigheten för GPS-mottagarens rörelse.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Hämtar eller anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet.

Värde: Enheten som används för att uttrycka GPS-mottagarens rörelseshastighet.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Hämtar eller anger statusen för GPS‑mottagaren när bilden registreras.

Värde: Statusen för GPS-mottagaren när bilden spelas in.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Hämtar eller anger taggar som endast tillhör GPS‑avsnittet.

Värde: GPS-taggarna.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Hämtar eller anger GPS‑tiden som UTC (Coordinated Universal Time).

Värde: GPS-tiden som UTC (Coordinated Universal Time).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Hämtar eller anger riktningen för GPS‑mottagarens rörelse.

Värde: Riktningen för GPS-mottagarens rörelse.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Hämtar eller anger referensen för att ange riktningen för GPS‑mottagarens rörelse.

Värde: Referensen för att ange riktningen för GPS-mottagarens rörelse.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Hämtar eller anger GPS‑versionsidentifieraren.

Värde: GPS-versionens identifierare.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Hämtar eller anger graden av total bildförstärkningsjustering.

Värde: Graden av total bildförstärkningsjustering.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Hämtar eller anger gamma.

Värde: Gamma-värdet.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Hämtar eller anger ISO-hastighet

Värde: ISO-hastigheten.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Hämtar eller anger ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Hämtar eller anger ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudeyyy

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Hämtar eller anger bildbeskrivning.

Värde: Bildbeskrivning.

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Hämtar eller anger bildlängd.

Värde: Bildens längd.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Hämtar eller anger bildens unika identifierare.

Värde: Den unika bildidentifieraren.

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Hämtar eller anger bildbredd.

Värde: Bildens bredd.

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Hämtar eller anger linsens tillverkare.

Värde: Linsens tillverkare.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Hämtar eller anger linsmodellen.

Värde: Linsmodellen.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Hämtar eller anger linsens serienummer.

Värde: Linsens serienummer.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Hämtar eller anger linsens specifikation

Värde: Linsens specifikation.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Hämtar eller anger ljuskällan.

Värde: Ljuskällan.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Hämtar tillverkaren av inspelningsutrustningen.

Värde: Tillverkaren av inspelningsutrustningen.

**Returns:**
java.lang.String - tillverkaren av inspelningsutrustningen.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Hämtar tillverkarens noteringsdata.

Värde: Maker note-data.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Hämtar eller anger tillverkarens noteringsrådata.

Värde: Maker note rådata.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Hämtar tillverkarens anteckningar.

Värde: Maker notes.

**Returns:**
com.aspose.psd.exif.MakerNote[] - tillverkaranteckningarna.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Hämtar eller anger maximalt bländarvärde.

Värde: Maximalt bländarvärde.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Hämtar eller anger mätarläget.

Värde: Mätläget.

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


Hämtar eller anger modellen.

Värde: Modellen.

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Hämtar eller anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524.

Värde: Den optoelektriska konverteringsfunktionen (OECF) specificerad i ISO 14524.

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Hämtar eller anger orienteringen.

Värde: Orienteringen.

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Hämtar eller anger fotografisk känslighet.

Värde: Den fotografiska känsligheten.

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Hämtar eller anger fotometrisk tolkning.

Värde: Fotometrisk tolkning.

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Hämtar eller anger pixelns x-dimension.

Värde: Pixelns x-dimension.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Hämtar eller anger pixelns y-dimension.

Värde: Pixelns y-dimension.

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Hämtar eller anger planär konfiguration.

Värde: Planär konfiguration.

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Hämtar eller anger kromaticiteten för bildens tre primära färger.

Värde: Bildens tre primära färgers kromaticitet.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar).

Värde: EXIF-taggarna (inklusive vanliga och GPS-taggar).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Hämtar eller anger rekommenderat exponeringsindex.

Värde: Rekommenderat exponeringsindex.

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Hämtar eller anger referenssvartvitt.

Värde: Referens svart vit.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Hämtar eller anger den relaterade ljudfilen.

Värde: Den relaterade ljudfilen.

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Hämtar eller anger upplösningsenhet.

Värde: Upplösningsenhet.

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Hämtar eller anger prover per pixel.

Värde: Prover per pixel.

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Hämtar eller anger mättnad.

Värde: Mättnaden.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Hämtar eller anger sceninspelningstyp.

Värde: Typen av scenupptagning.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Hämtar eller anger scenens typ.

Värde: Typen av scenen.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Hämtar eller anger avkänningsmetoden.

Värde: Avkänningsmetoden.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Hämtar eller anger känslighetstypen.

Värde: Typen av känsligheten.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Hämtar eller anger skärpan.

Värde: Skärpan.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Hämtar eller anger slutartidens värde.

Värde: Slutartidsvärdet.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Hämtar eller anger programvaran.

Värde: Mjukvaran.

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Hämtar eller anger det rumsliga frekvenssvaret.

Värde: Det rumsliga frekvenssvaret.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Hämtar eller anger spektralkänsligheten.

Värde: Spektralkänsligheten.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Hämtar standardutgångskänsligheten

Värde: Standardutgångskänsligheten.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Hämtar eller anger motivområdet.

Värde: Objektområdet.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Hämtar eller anger motivavståndet.

Värde: Objektavståndet.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Hämtar eller anger intervallet för motivavståndet.

Värde: Objektavståndsområdet.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Hämtar eller anger motivets plats.

Värde: Objektplatsen.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Hämtar eller anger bråkdelen av sekunder för DateTime-taggen.

Värde: Bråkdelen av sekunder för DateTime-taggen.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen.

Värde: Bråkdelen av sekunder för DateTimeDigitized-taggen.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen.

Värde: Bråkdelen av sekunder för DateTimeOriginal-taggen.

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


Hämtar eller anger miniatyrbilden.

Värde: Miniatyrbilden.

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Hämtar eller anger överföringsfunktionen.

Värde: Överföringsfunktion.

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Hämtar eller anger användarkommentaren.

Värde: Användarkommentaren.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Hämtar eller anger vitbalansen.

Värde: Vitbalansen.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Hämtar eller anger kromaticiteten för bildens vita punkt.

Värde: Bildens vita punkts kromaticitet.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Hämtar eller anger x-upplösning.

Värde: X-upplösning.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

Värde: Matriskoefficienter för transformation från RGB till YCbCr bilddata.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Hämtar eller anger positionen för krominanskomponenter i förhållande till luminanskomponenten.

Värde: Positionen för krominanskomponenter i förhållande till luminanskomponenten.

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Hämtar eller anger samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten.

Värde: Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten.

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Hämtar eller anger y-upplösning.

Värde: Y-upplösning.

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


Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian.

Värde:  true  om EXIF-data från strömmen är big endian; annars,  false .

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


Ta bort tagg från behållare

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Taggidentifieraren att ta bort. |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serialiserar EXIF-data. Skriver taggvärden och innehåll. Den mest påverkande storlekstaggen är miniatyrbildens tagg-innehåll.

**Returns:**
byte[] - De serialiserade EXIF‑data.

Den totala segmentstorleken måste vara mindre än eller lika med MaxExifSegmentSize byte för att producera en korrekt jpeg‑bild. Tips: försök minska miniatyrbildens storlek eller ändra dess kompression om du har en för stor EXIF‑sektion.
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Hämtar eller anger bländarvärdet.

Värde: bländarvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Hämtar eller anger artisten.

Värde: Konstnären.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian.

Värde:  true  om EXIF-data från strömmen är big endian; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Hämtar eller anger bitar per prov.

Värde: Bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Hämtar eller anger kamerahusets serienummer.

Värde: kroppsserienumret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Hämtar eller anger ljusstyrkevärdet.

Värde: ljusstyrkevärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Hämtar eller anger CFA‑mönstret.

Värde: CFA-mönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Hämtar eller anger kamerans ägarnamn

Värde: namnet på kamerans ägare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Hämtar eller anger färgrymden.

Värde: färgrymden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Hämtar eller anger taggar som tillhör den gemensamma sektionen. Detta gäller endast jpeg-bilder, i tiff-format används tiffOptions istället

Värde: de gemensamma sektionstaggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Hämtar eller anger komponentkonfigurationen.

Värde: komponentkonfigurationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Hämtar eller anger komprimerade bitar per pixel.

Värde: komprimerade bitar per pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Hämtar eller anger komprimeringen.

Värde: Komprimeringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Hämtar eller anger kontrasten.

Värde: kontrasten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Hämtar eller anger upphovsrätten.

Värde: Upphovsrätten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Hämtar eller anger den anpassade rendering.

Värde: anpassad återgivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Hämtar eller anger datum och tid.

Värde: Datum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Hämtar eller anger datum och tid för digitalisering.

Värde: digitaliseringsdatum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Hämtar eller anger datum och tid för originalet.

Värde: originaldatum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Hämtar eller anger beskrivning av enhetens inställningar

Värde: enhetsinställningsbeskrivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Hämtar eller anger den digitala zoomförhållandet.

Värde: digitala zoomförhållandet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Hämtar eller anger taggar som endast tillhör EXIF‑avsnittet.

Värde: EXIF-sektions-taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Hämtar eller anger EXIF‑versionen.

Värde: EXIF-versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Hämtar eller anger exponeringsförskjutningsvärdet.

Värde: exponeringskompensationsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Hämtar eller anger exponeringsindexet.

Värde: exponeringsindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Hämtar eller anger exponeringsläget.

Värde: exponeringsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Hämtar eller anger exponeringsprogrammet.

Värde: exponeringsprogrammet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Hämtar eller anger exponeringstiden.

Värde: exponeringstiden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Hämtar eller anger F‑numret.

Värde: F-numret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Hämtar eller anger filkällans typ.

Värde: Filkällans typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Hämtar eller anger blixten.

Värde: Blixten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Hämtar eller anger blixtenergin.

Värde: Blixtenergi.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Hämtar eller anger flash‑pix‑versionen.

Värde: Blixt pix-version.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Hämtar eller anger brännvidden.

Värde: Fokallängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Hämtar eller anger brännvidden i 35 mm‑film.

Värde: Brännvidden i 35 mm film.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Hämtar eller anger upplösningsenheten för fokalplanet.

Värde: Upplösningsenhet för fokalplanet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Hämtar eller anger fokalplanets x‑upplösning.

Värde: Fokalplanets x-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Hämtar eller anger fokalplanets y‑upplösning.

Värde: Fokalplanets y-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Hämtar eller anger GPS‑höjden.

Värde: GPS-höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Hämtar eller anger GPS‑höjden som används som referenshöjd.

Värde: GPS-höjd som används som referenshöjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Hämtar eller anger GPS‑områdesinformation.

Värde: GPS-områdesinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Hämtar eller anger GPS‑DOP (dataprecisionsgrad).

Värde: GPS DOP (dataprecisionsgrad).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Hämtar eller anger GPS‑teckensträng som spelar in datum‑ och tidsinformation relativt UTC (Coordinated Universal Time).

Värde: GPS-teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Hämtar eller anger GPS‑riktning mot destinationspunkten.

Värde: GPS-riktning mot destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Hämtar eller anger GPS‑referensen som används för att ange riktning mot destinationspunkten.

Värde: GPS-referens som används för att ange riktning mot destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Hämtar eller anger GPS‑avståndet till destinationspunkten.

Värde: GPS-avstånd till destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Hämtar eller anger GPS‑enheten som används för att uttrycka avståndet till destinationspunkten.

Värde: GPS-enhet som används för att uttrycka avståndet till destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Hämtar eller anger GPS‑latituden för destinationspunkten.

Värde: GPS-latitud för destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Hämtar eller anger GPS‑värdet som visar om latituden för destinationspunkten är norr eller söder.

Värde: GPS-värdet som indikerar om destinationspunktens latitud är nordlig eller sydlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Hämtar eller anger GPS‑longituden för destinationspunkten.

Värde: GPS-longitud för destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Hämtar eller anger GPS‑värdet som visar om longituden för destinationspunkten är östlig eller västlig.

Värde: GPS-värdet som indikerar om destinationspunktens longitud är östlig eller västlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Hämtar eller anger ett GPS‑värde som visar om differentialkorrigering tillämpas på GPS‑mottagaren.

Värde: GPS-värdet som indikerar om differentialkorrigering tillämpas på GPS-mottagaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Hämtar eller anger GPS‑riktningen för bilden när den togs.

Värde: GPS-riktningen för bilden när den togs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Hämtar eller anger GPS‑referensen för att ange bildens riktning när den tas.

Värde: GPS-referensen för att ange bildens riktning när den tas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Hämtar eller anger GPS‑latituden.

Värde: GPS-latituden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Hämtar eller anger om GPS‑latituden är norr eller söder.

Värde: GPS-latituden är nordlig eller sydlig latitud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Hämtar eller anger GPS‑longituden.

Värde: GPS-longituden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Hämtar eller anger om GPS‑longituden är östlig eller västlig.

Värde: GPS-longituden är östlig eller västlig longitud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Hämtar eller anger de GPS‑geodetiska undersökningsdata som används av GPS‑mottagaren.

Värde: GPS:s geodetiska undersökningsdata som används av GPS-mottagaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Hämtar eller anger GPS‑mätningsläget.

Värde: GPS-mätningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Hämtar eller anger GPS‑teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

Värde: GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Hämtar eller anger GPS‑satelliterna som används för mätningar.

Värde: GPS-satelliterna som används för mätningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Hämtar eller anger hastigheten för GPS‑mottagarens rörelse.

Värde: Hastigheten för GPS-mottagarens rörelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Hämtar eller anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet.

Värde: Enheten som används för att uttrycka GPS-mottagarens rörelseshastighet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Hämtar eller anger statusen för GPS‑mottagaren när bilden registreras.

Värde: Statusen för GPS-mottagaren när bilden spelas in.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Hämtar eller anger taggar som endast tillhör GPS‑avsnittet.

Värde: GPS-taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Hämtar eller anger GPS‑tiden som UTC (Coordinated Universal Time).

Värde: GPS-tiden som UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Hämtar eller anger riktningen för GPS‑mottagarens rörelse.

Värde: Riktningen för GPS-mottagarens rörelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Hämtar eller anger referensen för att ange riktningen för GPS‑mottagarens rörelse.

Värde: Referensen för att ange riktningen för GPS-mottagarens rörelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Hämtar eller anger GPS‑versionsidentifieraren.

Värde: GPS-versionens identifierare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Hämtar eller anger graden av total bildförstärkningsjustering.

Värde: Graden av total bildförstärkningsjustering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Hämtar eller anger gamma.

Värde: Gamma-värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Hämtar eller anger ISO-hastighet

Värde: ISO-hastigheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Hämtar eller anger ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudezzz

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Hämtar eller anger ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudeyyy

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Hämtar eller anger bildbeskrivning.

Värde: Bildbeskrivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Hämtar eller anger bildlängd.

Värde: Bildens längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Hämtar eller anger bildens unika identifierare.

Värde: Den unika bildidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Hämtar eller anger bildbredd.

Värde: Bildens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Hämtar eller anger linsens tillverkare.

Värde: Linsens tillverkare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Hämtar eller anger linsmodellen.

Värde: Linsmodellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Hämtar eller anger linsens serienummer.

Värde: Linsens serienummer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Hämtar eller anger linsens specifikation

Värde: Linsens specifikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Hämtar eller anger ljuskällan.

Värde: Ljuskällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Anger tillverkaren av inspelningsutrustningen.

Värde: Tillverkaren av inspelningsutrustningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | tillverkaren av inspelningsutrustningen. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Hämtar eller anger tillverkarens noteringsrådata.

Värde: Maker note rådata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Hämtar eller anger maximalt bländarvärde.

Värde: Maximalt bländarvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Hämtar eller anger mätarläget.

Värde: Mätläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Hämtar eller anger modellen.

Värde: Modellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Hämtar eller anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524.

Värde: Den optoelektriska konverteringsfunktionen (OECF) specificerad i ISO 14524.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Hämtar eller anger orienteringen.

Värde: Orienteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Hämtar eller anger fotografisk känslighet.

Värde: Den fotografiska känsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Hämtar eller anger fotometrisk tolkning.

Värde: Fotometrisk tolkning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Hämtar eller anger pixelns x-dimension.

Värde: Pixelns x-dimension.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Hämtar eller anger pixelns y-dimension.

Värde: Pixelns y-dimension.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Hämtar eller anger planär konfiguration.

Värde: Planär konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Hämtar eller anger kromaticiteten för bildens tre primära färger.

Värde: Bildens tre primära färgers kromaticitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar).

Värde: EXIF-taggarna (inklusive vanliga och GPS-taggar).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Hämtar eller anger rekommenderat exponeringsindex.

Värde: Rekommenderat exponeringsindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Hämtar eller anger referenssvartvitt.

Värde: Referens svart vit.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Hämtar eller anger den relaterade ljudfilen.

Värde: Den relaterade ljudfilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Hämtar eller anger upplösningsenhet.

Värde: Upplösningsenhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Hämtar eller anger prover per pixel.

Värde: Prover per pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Hämtar eller anger mättnad.

Värde: Mättnaden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Hämtar eller anger sceninspelningstyp.

Värde: Typen av scenupptagning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Hämtar eller anger scenens typ.

Värde: Typen av scenen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Hämtar eller anger avkänningsmetoden.

Värde: Avkänningsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Hämtar eller anger känslighetstypen.

Värde: Typen av känsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Hämtar eller anger skärpan.

Värde: Skärpan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Hämtar eller anger slutartidens värde.

Värde: Slutartidsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Hämtar eller anger programvaran.

Värde: Mjukvaran.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Hämtar eller anger det rumsliga frekvenssvaret.

Värde: Det rumsliga frekvenssvaret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Hämtar eller anger spektralkänsligheten.

Värde: Spektralkänsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Anger standardutgångskänsligheten

Värde: Standardutgångskänsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Hämtar eller anger motivområdet.

Värde: Objektområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Hämtar eller anger motivavståndet.

Värde: Objektavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Hämtar eller anger intervallet för motivavståndet.

Värde: Objektavståndsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Hämtar eller anger motivets plats.

Värde: Objektplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Hämtar eller anger bråkdelen av sekunder för DateTime-taggen.

Värde: Bråkdelen av sekunder för DateTime-taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen.

Värde: Bråkdelen av sekunder för DateTimeDigitized-taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen.

Värde: Bråkdelen av sekunder för DateTimeOriginal-taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


Hämtar eller anger miniatyrbilden.

Värde: Miniatyrbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Hämtar eller anger överföringsfunktionen.

Värde: Överföringsfunktion.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Hämtar eller anger användarkommentaren.

Värde: Användarkommentaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Hämtar eller anger vitbalansen.

Värde: Vitbalansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Hämtar eller anger kromaticiteten för bildens vita punkt.

Värde: Bildens vita punkts kromaticitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Hämtar eller anger x-upplösning.

Värde: X-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

Värde: Matriskoefficienter för transformation från RGB till YCbCr bilddata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Hämtar eller anger positionen för krominanskomponenter i förhållande till luminanskomponenten.

Värde: Positionen för krominanskomponenter i förhållande till luminanskomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Hämtar eller anger samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten.

Värde: Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Hämtar eller anger y-upplösning.

Värde: Y-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

