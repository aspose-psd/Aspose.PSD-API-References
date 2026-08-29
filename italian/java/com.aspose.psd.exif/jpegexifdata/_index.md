---
title: "JpegExifData"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Contenitore di dati EXIF per file JPEG."
type: docs
weight: 12
url: /it/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Contenitore di dati EXIF per file JPEG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Inizializza una nuova istanza della classe  JpegExifData  . |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe  JpegExifData  con dati da array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe  JpegExifData  con dati da array. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | La dimensione massima del segmento EXIF in byte consentita. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Ottiene o imposta il valore dell'apertura. |
| [getArtist()](#getArtist--) | Ottiene o imposta l'artista. |
| [getBitsPerSample()](#getBitsPerSample--) | Ottiene o imposta i bit per campione. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Ottiene o imposta il numero di serie del corpo della fotocamera. |
| [getBrightnessValue()](#getBrightnessValue--) | Ottiene o imposta il valore della luminosità. |
| [getCFAPattern()](#getCFAPattern--) | Ottiene o imposta il pattern CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Ottiene o imposta il nome del proprietario della fotocamera |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Ottiene o imposta lo spazio colore. |
| [getCommonTags()](#getCommonTags--) | Ottiene o imposta i tag, che appartengono alla sezione comune. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Ottiene o imposta la configurazione dei componenti. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Ottiene o imposta i bit compressi per pixel. |
| [getCompression()](#getCompression--) | Ottiene o imposta la compressione. |
| [getContrast()](#getContrast--) | Ottiene o imposta il contrasto. |
| [getCopyright()](#getCopyright--) | Ottiene o imposta il copyright. |
| [getCustomRendered()](#getCustomRendered--) | Ottiene o imposta il rendering personalizzato. |
| [getDateTime()](#getDateTime--) | Ottiene o imposta la data e ora. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Ottiene o imposta la data e ora di digitalizzazione. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Ottiene o imposta la data e ora originale. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Ottiene o imposta la descrizione delle impostazioni del dispositivo |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Ottiene o imposta il rapporto di zoom digitale. |
| [getExifTags()](#getExifTags--) | Ottiene o imposta i tag che appartengono solo alla sezione EXIF. |
| [getExifVersion()](#getExifVersion--) | Ottiene o imposta la versione EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Ottiene o imposta il valore di compensazione dell'esposizione. |
| [getExposureIndex()](#getExposureIndex--) | Ottiene o imposta l'indice di esposizione. |
| [getExposureMode()](#getExposureMode--) | Ottiene o imposta la modalità di esposizione. |
| [getExposureProgram()](#getExposureProgram--) | Ottiene o imposta il programma di esposizione. |
| [getExposureTime()](#getExposureTime--) | Ottiene o imposta il tempo di esposizione. |
| [getFNumber()](#getFNumber--) | Ottiene o imposta il numero F. |
| [getFileSource()](#getFileSource--) | Ottiene o imposta il tipo di origine del file. |
| [getFlash()](#getFlash--) | Ottiene o imposta il flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Ottiene o imposta l'energia del flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Ottiene o imposta la versione flash pix. |
| [getFocalLength()](#getFocalLength--) | Ottiene o imposta la lunghezza focale. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Ottiene o imposta la lunghezza focale nel film da 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Ottiene o imposta l'unità di risoluzione del piano focale. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Ottiene o imposta la risoluzione X del piano focale. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Ottiene o imposta la risoluzione Y del piano focale. |
| [getGPSAltitude()](#getGPSAltitude--) | Ottiene o imposta l'altitudine GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Ottiene o imposta l'altitudine GPS utilizzata come altitudine di riferimento. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Ottiene o imposta le informazioni sull'area GPS. |
| [getGPSDOP()](#getGPSDOP--) | Ottiene o imposta il DOP GPS (grado di precisione dei dati). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Ottiene o imposta l'orientamento GPS verso il punto di destinazione. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Ottiene o imposta il riferimento GPS utilizzato per fornire la direzione al punto di destinazione. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Ottiene o imposta la distanza GPS dal punto di destinazione. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Ottiene o imposta l'unità GPS utilizzata per esprimere la distanza dal punto di destinazione. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. |
| [getGPSDifferential()](#getGPSDifferential--) | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Ottiene o imposta la direzione GPS dell'immagine al momento della cattura. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura. |
| [getGPSLatitude()](#getGPSLatitude--) | Ottiene o imposta la latitudine GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Ottiene o imposta se la latitudine GPS è nord o sud. |
| [getGPSLongitude()](#getGPSLongitude--) | Ottiene o imposta la longitudine GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Ottiene o imposta se la longitudine GPS è est o ovest. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Ottiene o imposta i dati di rilievo geodetico GPS utilizzati dal ricevitore GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Ottiene o imposta la modalità di misurazione GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo utilizzato per la ricerca della posizione. |
| [getGPSSatellites()](#getGPSSatellites--) | Ottiene o imposta i satelliti GPS utilizzati per le misurazioni. |
| [getGPSSpeed()](#getGPSSpeed--) | Ottiene o imposta la velocità del movimento del ricevitore GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Ottiene o imposta l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS. |
| [getGPSStatus()](#getGPSStatus--) | Ottiene o imposta lo stato del ricevitore GPS quando l'immagine è registrata. |
| [getGPSTags()](#getGPSTags--) | Ottiene o imposta i tag, che appartengono solo alla sezione GPS. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale). |
| [getGPSTrack()](#getGPSTrack--) | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Ottiene o imposta l'identificatore di versione GPS. |
| [getGainControl()](#getGainControl--) | Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine. |
| [getGamma()](#getGamma--) | Ottiene o imposta la gamma. |
| [getISOSpeed()](#getISOSpeed--) | Ottiene o imposta la velocità ISO |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Ottiene o imposta il valore yyy della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Ottiene o imposta il valore zzz della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [getImageDescription()](#getImageDescription--) | Ottiene o imposta la descrizione dell'immagine. |
| [getImageLength()](#getImageLength--) | Ottiene o imposta la lunghezza dell'immagine. |
| [getImageUniqueID()](#getImageUniqueID--) | Ottiene o imposta l'identificatore univoco dell'immagine. |
| [getImageWidth()](#getImageWidth--) | Ottiene o imposta la larghezza dell'immagine. |
| [getLensMake()](#getLensMake--) | Ottiene o imposta il produttore dell'obiettivo. |
| [getLensModel()](#getLensModel--) | Ottiene o imposta il modello dell'obiettivo. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Ottiene o imposta il numero di serie dell'obiettivo. |
| [getLensSpecification()](#getLensSpecification--) | Ottiene o imposta le specifiche dell'obiettivo |
| [getLightSource()](#getLightSource--) | Ottiene o imposta la sorgente luminosa. |
| [getMake()](#getMake--) | Ottiene il produttore dell'attrezzatura di registrazione. |
| [getMakerNoteData()](#getMakerNoteData--) | Ottiene i dati delle note del produttore. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Ottiene o imposta i dati grezzi delle note del produttore. |
| [getMakerNotes()](#getMakerNotes--) | Ottiene le note del produttore. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Ottiene o imposta il valore dell'apertura massima. |
| [getMeteringMode()](#getMeteringMode--) | Ottiene o imposta la modalità di misurazione. |
| [getModel()](#getModel--) | Ottiene o imposta il modello. |
| [getOECF()](#getOECF--) | Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| [getOrientation()](#getOrientation--) | Ottiene o imposta l'orientamento. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Ottiene o imposta la sensibilità fotografica. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Ottiene o imposta l'interpretazione fotometrica. |
| [getPixelXDimension()](#getPixelXDimension--) | Ottiene o imposta la dimensione x del pixel. |
| [getPixelYDimension()](#getPixelYDimension--) | Ottiene o imposta la dimensione y del pixel. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Ottiene o imposta la configurazione planare. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Ottiene o imposta la cromaticità dei tre colori primari dell'immagine. |
| [getProperties()](#getProperties--) | Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Ottiene o imposta l'indice di esposizione consigliato. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Ottiene o imposta il riferimento nero bianco. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Ottiene o imposta il file audio correlato. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene o imposta l'unità di risoluzione. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Ottiene o imposta i campioni per pixel. |
| [getSaturation()](#getSaturation--) | Ottiene o imposta la saturazione. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Ottiene o imposta il tipo di acquisizione della scena. |
| [getSceneType()](#getSceneType--) | Ottiene o imposta il tipo di scena. |
| [getSensingMethod()](#getSensingMethod--) | Ottiene o imposta il metodo di rilevamento. |
| [getSensitivityType()](#getSensitivityType--) | Ottiene o imposta il tipo di sensibilità. |
| [getSharpness()](#getSharpness--) | Ottiene o imposta la nitidezza. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Ottiene o imposta il valore della velocità dell'otturatore. |
| [getSoftware()](#getSoftware--) | Ottiene o imposta il software. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Ottiene o imposta la risposta in frequenza spaziale. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Ottiene o imposta la sensibilità spettrale. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Ottiene la sensibilità di uscita standard |
| [getSubjectArea()](#getSubjectArea--) | Ottiene o imposta l'area del soggetto. |
| [getSubjectDistance()](#getSubjectDistance--) | Ottiene o imposta la distanza del soggetto. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Ottiene o imposta l'intervallo di distanza del soggetto. |
| [getSubjectLocation()](#getSubjectLocation--) | Ottiene o imposta la posizione del soggetto. |
| [getSubsecTime()](#getSubsecTime--) | Ottiene o imposta le frazioni di secondo per il tag DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal. |
| [getThumbnail()](#getThumbnail--) | Ottiene o imposta l'immagine miniatura. |
| [getTransferFunction()](#getTransferFunction--) | Ottiene o imposta la funzione di trasferimento. |
| [getUserComment()](#getUserComment--) | Ottiene o imposta il commento dell'utente. |
| [getWhiteBalance()](#getWhiteBalance--) | Ottiene o imposta il bilanciamento del bianco. |
| [getWhitePoint()](#getWhitePoint--) | Ottiene o imposta la cromaticità del punto bianco dell'immagine. |
| [getXResolution()](#getXResolution--) | Ottiene o imposta la risoluzione x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Ottiene o imposta i coefficienti della matrice per la trasformazione da RGB a dati immagine YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| [getYResolution()](#getYResolution--) | Ottiene o imposta la risoluzione y. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Ottiene o imposta un valore che indica se i dati EXIF del flusso creati da è big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Rimuovi il tag dal contenitore |
| [serializeExifData()](#serializeExifData--) | Serializza i dati EXIF. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta il valore dell'apertura. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Ottiene o imposta l'artista. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Ottiene o imposta un valore che indica se i dati EXIF del flusso creati da è big endian. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Ottiene o imposta i bit per campione. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Ottiene o imposta il numero di serie del corpo della fotocamera. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Ottiene o imposta il valore della luminosità. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Ottiene o imposta il pattern CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Ottiene o imposta il nome del proprietario della fotocamera |
| [setColorSpace(int value)](#setColorSpace-int-) | Ottiene o imposta lo spazio colore. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag, che appartengono alla sezione comune. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Ottiene o imposta la configurazione dei componenti. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta i bit compressi per pixel. |
| [setCompression(int value)](#setCompression-int-) | Ottiene o imposta la compressione. |
| [setContrast(int value)](#setContrast-int-) | Ottiene o imposta il contrasto. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Ottiene o imposta il copyright. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Ottiene o imposta il rendering personalizzato. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Ottiene o imposta la data e ora. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Ottiene o imposta la data e ora di digitalizzazione. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Ottiene o imposta la data e ora originale. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Ottiene o imposta la descrizione delle impostazioni del dispositivo |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta il rapporto di zoom digitale. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag che appartengono solo alla sezione EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Ottiene o imposta la versione EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Ottiene o imposta il valore di compensazione dell'esposizione. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta l'indice di esposizione. |
| [setExposureMode(int value)](#setExposureMode-int-) | Ottiene o imposta la modalità di esposizione. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Ottiene o imposta il programma di esposizione. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta il tempo di esposizione. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta il numero F. |
| [setFileSource(byte value)](#setFileSource-byte-) | Ottiene o imposta il tipo di origine del file. |
| [setFlash(int value)](#setFlash-int-) | Ottiene o imposta il flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta l'energia del flash. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Ottiene o imposta la versione flash pix. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la lunghezza focale. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Ottiene o imposta la lunghezza focale nel film da 35 mm. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Ottiene o imposta l'unità di risoluzione del piano focale. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione X del piano focale. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione Y del piano focale. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta l'altitudine GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Ottiene o imposta l'altitudine GPS utilizzata come altitudine di riferimento. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Ottiene o imposta le informazioni sull'area GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta il DOP GPS (grado di precisione dei dati). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta l'orientamento GPS verso il punto di destinazione. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Ottiene o imposta il riferimento GPS utilizzato per fornire la direzione al punto di destinazione. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la distanza GPS dal punto di destinazione. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Ottiene o imposta l'unità GPS utilizzata per esprimere la distanza dal punto di destinazione. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la direzione GPS dell'immagine al momento della cattura. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta la latitudine GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Ottiene o imposta se la latitudine GPS è nord o sud. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta la longitudine GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Ottiene o imposta se la longitudine GPS è est o ovest. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Ottiene o imposta i dati di rilievo geodetico GPS utilizzati dal ricevitore GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Ottiene o imposta la modalità di misurazione GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo utilizzato per la ricerca della posizione. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Ottiene o imposta i satelliti GPS utilizzati per le misurazioni. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la velocità del movimento del ricevitore GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Ottiene o imposta l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Ottiene o imposta lo stato del ricevitore GPS quando l'immagine è registrata. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag, che appartengono solo alla sezione GPS. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Ottiene o imposta l'identificatore di versione GPS. |
| [setGainControl(int value)](#setGainControl-int-) | Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Ottiene o imposta la velocità ISO |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Ottiene o imposta il valore yyy della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Ottiene o imposta il valore zzz della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Ottiene o imposta la descrizione dell'immagine. |
| [setImageLength(long value)](#setImageLength-long-) | Ottiene o imposta la lunghezza dell'immagine. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Ottiene o imposta l'identificatore univoco dell'immagine. |
| [setImageWidth(long value)](#setImageWidth-long-) | Ottiene o imposta la larghezza dell'immagine. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Ottiene o imposta il produttore dell'obiettivo. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Ottiene o imposta il modello dell'obiettivo. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Ottiene o imposta il numero di serie dell'obiettivo. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta le specifiche dell'obiettivo |
| [setLightSource(int value)](#setLightSource-int-) | Ottiene o imposta la sorgente luminosa. |
| [setMake(String value)](#setMake-java.lang.String-) | Imposta il produttore dell'attrezzatura di registrazione. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Ottiene o imposta i dati grezzi delle note del produttore. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta il valore dell'apertura massima. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Ottiene o imposta la modalità di misurazione. |
| [setModel(String value)](#setModel-java.lang.String-) | Ottiene o imposta il modello. |
| [setOECF(byte[] value)](#setOECF-byte---) | Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| [setOrientation(int value)](#setOrientation-int-) | Ottiene o imposta l'orientamento. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Ottiene o imposta la sensibilità fotografica. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Ottiene o imposta l'interpretazione fotometrica. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Ottiene o imposta la dimensione x del pixel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Ottiene o imposta la dimensione y del pixel. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Ottiene o imposta la configurazione planare. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta la cromaticità dei tre colori primari dell'immagine. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Ottiene o imposta l'indice di esposizione consigliato. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta il riferimento nero bianco. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Ottiene o imposta il file audio correlato. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Ottiene o imposta l'unità di risoluzione. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Ottiene o imposta i campioni per pixel. |
| [setSaturation(int value)](#setSaturation-int-) | Ottiene o imposta la saturazione. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Ottiene o imposta il tipo di acquisizione della scena. |
| [setSceneType(byte value)](#setSceneType-byte-) | Ottiene o imposta il tipo di scena. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Ottiene o imposta il metodo di rilevamento. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Ottiene o imposta il tipo di sensibilità. |
| [setSharpness(int value)](#setSharpness-int-) | Ottiene o imposta la nitidezza. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Ottiene o imposta il valore della velocità dell'otturatore. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Ottiene o imposta il software. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Ottiene o imposta la risposta in frequenza spaziale. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Ottiene o imposta la sensibilità spettrale. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Imposta la sensibilità di uscita standard |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Ottiene o imposta l'area del soggetto. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la distanza del soggetto. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Ottiene o imposta l'intervallo di distanza del soggetto. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Ottiene o imposta la posizione del soggetto. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Ottiene o imposta le frazioni di secondo per il tag DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | Ottiene o imposta l'immagine miniatura. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Ottiene o imposta la funzione di trasferimento. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Ottiene o imposta il commento dell'utente. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Ottiene o imposta il bilanciamento del bianco. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta la cromaticità del punto bianco dell'immagine. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta i coefficienti della matrice per la trasformazione da RGB a dati immagine YCbCr. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione y. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Inizializza una nuova istanza della classe  JpegExifData  .

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


Inizializza una nuova istanza della classe  JpegExifData  con dati da array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Array di tag EXIF insieme a tag comuni e GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Inizializza una nuova istanza della classe  JpegExifData  con dati da array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag comuni. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag GPS. |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


La dimensione massima del segmento EXIF in byte consentita.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Ottiene o imposta il valore dell'apertura.

Valore: Il valore di apertura.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


Ottiene o imposta l'artista.

Valore: L'artista.

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Ottiene o imposta i bit per campione.

Valore: I bit per campione.

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Ottiene o imposta il numero di serie del corpo della fotocamera.

Valore: Il numero di serie del corpo.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Ottiene o imposta il valore della luminosità.

Valore: Il valore di luminosità.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Ottiene o imposta il pattern CFA.

Valore: Il modello CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Ottiene o imposta il nome del proprietario della fotocamera

Valore: Il nome del proprietario della fotocamera.

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


Ottiene o imposta lo spazio colore.

Valore: Lo spazio colore.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Ottiene o imposta i tag, che appartengono alla sezione comune. Questo si applica solo alle immagini jpeg, nel formato tiff vengono utilizzate tiffOptions.

Valore: I tag della sezione comune.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Ottiene o imposta la configurazione dei componenti.

Valore: La configurazione dei componenti.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Ottiene o imposta i bit compressi per pixel.

Valore: I bit compressi per pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


Ottiene o imposta la compressione.

Valore: La compressione.

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


Ottiene o imposta il contrasto.

Valore: Il contrasto.

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Ottiene o imposta il copyright.

Valore: Il copyright.

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Ottiene o imposta il rendering personalizzato.

Valore: Il rendering personalizzato.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Ottiene o imposta la data e ora.

Valore: La data e ora.

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Ottiene o imposta la data e ora di digitalizzazione.

Valore: La data e ora di digitalizzazione.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Ottiene o imposta la data e ora originale.

Valore: La data e ora originale.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Ottiene o imposta la descrizione delle impostazioni del dispositivo

Valore: La descrizione delle impostazioni del dispositivo.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Ottiene o imposta il rapporto di zoom digitale.

Valore: Il rapporto di zoom digitale.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Ottiene o imposta i tag che appartengono solo alla sezione EXIF.

Valore: I tag della sezione EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Ottiene o imposta la versione EXIF.

Valore: La versione EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Ottiene o imposta il valore di compensazione dell'esposizione.

Valore: Il valore di compensazione dell'esposizione.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Ottiene o imposta l'indice di esposizione.

Valore: L'indice dell'esposizione.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Ottiene o imposta la modalità di esposizione.

Valore: La modalità di esposizione.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Ottiene o imposta il programma di esposizione.

Valore: Il programma di esposizione.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Ottiene o imposta il tempo di esposizione.

Valore: Il tempo di esposizione.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Ottiene o imposta il numero F.

Valore: Il numero F.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Ottiene o imposta il tipo di origine del file.

Valore: Il tipo di sorgente del file.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Ottiene o imposta il flash.

Valore: Il flash.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Ottiene o imposta l'energia del flash.

Valore: L'energia del flash.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Ottiene o imposta la versione flash pix.

Valore: La versione del flash pix.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Ottiene o imposta la lunghezza focale.

Valore: La lunghezza del focale.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Ottiene o imposta la lunghezza focale nel film da 35 mm.

Valore: La lunghezza focale in pellicola da 35 mm.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Ottiene o imposta l'unità di risoluzione del piano focale.

Valore: L'unità di risoluzione del piano focale.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Ottiene o imposta la risoluzione X del piano focale.

Valore: La risoluzione x del piano focale.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Ottiene o imposta la risoluzione Y del piano focale.

Valore: La risoluzione y del piano focale.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Ottiene o imposta l'altitudine GPS.

Valore: L'altitudine GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Ottiene o imposta l'altitudine GPS utilizzata come altitudine di riferimento.

Valore: L'altitudine GPS usata come altitudine di riferimento.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Ottiene o imposta le informazioni sull'area GPS.

Valore: Le informazioni sull'area GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Ottiene o imposta il DOP GPS (grado di precisione dei dati).

Valore: Il DOP GPS (grado di precisione dei dati).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale).

Valore: La stringa di caratteri GPS che registra data e ora relative a UTC (Tempo Coordinato Universale).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Ottiene o imposta l'orientamento GPS verso il punto di destinazione.

Valore: L'orientamento GPS verso il punto di destinazione.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Ottiene o imposta il riferimento GPS utilizzato per fornire la direzione al punto di destinazione.

Valore: Il riferimento GPS usato per fornire l'orientamento verso il punto di destinazione.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Ottiene o imposta la distanza GPS dal punto di destinazione.

Valore: La distanza GPS al punto di destinazione.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Ottiene o imposta l'unità GPS utilizzata per esprimere la distanza dal punto di destinazione.

Valore: L'unità GPS usata per esprimere la distanza al punto di destinazione.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Ottiene o imposta la latitudine GPS del punto di destinazione.

Valore: La latitudine GPS del punto di destinazione.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud.

Valore: Il valore GPS che indica se la latitudine del punto di destinazione è a nord o a sud.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Ottiene o imposta la longitudine GPS del punto di destinazione.

Valore: La longitudine GPS del punto di destinazione.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest.

Valore: Il valore GPS che indica se la longitudine del punto di destinazione è a est o a ovest.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS.

Valore: Il valore GPS che indica se è applicata la correzione differenziale al ricevitore GPS.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Ottiene o imposta la direzione GPS dell'immagine al momento della cattura.

Valore: La direzione GPS dell'immagine al momento della cattura.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

Valore: Il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Ottiene o imposta la latitudine GPS.

Valore: La latitudine GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Ottiene o imposta se la latitudine GPS è nord o sud.

Valore: La latitudine GPS è latitudine nord o sud.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Ottiene o imposta la longitudine GPS.

Valore: La longitudine GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Ottiene o imposta se la longitudine GPS è est o ovest.

Valore: La longitudine GPS è longitudine est o ovest.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Ottiene o imposta i dati di rilievo geodetico GPS utilizzati dal ricevitore GPS.

Valore: I dati di rilievo geodetico GPS utilizzati dal ricevitore GPS.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Ottiene o imposta la modalità di misurazione GPS.

Valore: La modalità di misurazione GPS.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo utilizzato per la ricerca della posizione.

Valore: La stringa di caratteri GPS che registra il nome del metodo utilizzato per la localizzazione.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Ottiene o imposta i satelliti GPS utilizzati per le misurazioni.

Valore: I satelliti GPS utilizzati per le misurazioni.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Ottiene o imposta la velocità del movimento del ricevitore GPS.

Valore: La velocità di movimento del ricevitore GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Ottiene o imposta l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS.

Valore: L'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Ottiene o imposta lo stato del ricevitore GPS quando l'immagine è registrata.

Valore: Lo stato del ricevitore GPS quando l'immagine è registrata.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Ottiene o imposta i tag, che appartengono solo alla sezione GPS.

Valore: I tag GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale).

Valore: L'ora GPS come UTC (Tempo Coordinato Universale).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Ottiene o imposta la direzione del movimento del ricevitore GPS.

Valore: La direzione del movimento del ricevitore GPS.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS.

Valore: Il riferimento per fornire la direzione del movimento del ricevitore GPS.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Ottiene o imposta l'identificatore di versione GPS.

Valore: L'identificatore di versione GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine.

Valore: Il grado di regolazione complessiva del guadagno dell'immagine.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Ottiene o imposta la gamma.

Valore: Il valore gamma.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Ottiene o imposta la velocità ISO

Valore: La velocità ISO.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Ottiene o imposta il valore yyy della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di ingresso definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Ottiene o imposta il valore zzz della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine della velocità ISO zzz di una fotocamera o dispositivo di input definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudeyyy

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Ottiene o imposta la descrizione dell'immagine.

Valore: La descrizione dell'immagine.

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Ottiene o imposta la lunghezza dell'immagine.

Valore: La lunghezza dell'immagine.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Ottiene o imposta l'identificatore univoco dell'immagine.

Valore: L'identificatore univoco dell'immagine.

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Ottiene o imposta la larghezza dell'immagine.

Valore: La larghezza dell'immagine.

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Ottiene o imposta il produttore dell'obiettivo.

Valore: Il produttore dell'obiettivo.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Ottiene o imposta il modello dell'obiettivo.

Valore: Il modello dell'obiettivo.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Ottiene o imposta il numero di serie dell'obiettivo.

Valore: Il numero di serie dell'obiettivo.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Ottiene o imposta le specifiche dell'obiettivo

Valore: La specifica dell'obiettivo.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Ottiene o imposta la sorgente luminosa.

Valore: La sorgente luminosa.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Ottiene il produttore dell'attrezzatura di registrazione.

Valore: Il produttore dell'attrezzatura di registrazione.

**Returns:**
java.lang.String - il produttore dell'attrezzatura di registrazione.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Ottiene i dati delle note del produttore.

Valore: I dati della nota del produttore.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Ottiene o imposta i dati grezzi delle note del produttore.

Valore: I dati grezzi della nota del produttore.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Ottiene le note del produttore.

Valore: Le note del produttore.

**Returns:**
com.aspose.psd.exif.MakerNote[] - le note del produttore.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Ottiene o imposta il valore dell'apertura massima.

Valore: Il valore dell'apertura massima.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Ottiene o imposta la modalità di misurazione.

Valore: La modalità di misurazione.

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


Ottiene o imposta il modello.

Valore: Il modello.

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

Valore: La Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Ottiene o imposta l'orientamento.

Valore: L'orientamento.

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Ottiene o imposta la sensibilità fotografica.

Valore: La sensibilità fotografica.

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Ottiene o imposta l'interpretazione fotometrica.

Valore: L'interpretazione fotometrica.

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Ottiene o imposta la dimensione x del pixel.

Valore: La dimensione x del pixel.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Ottiene o imposta la dimensione y del pixel.

Valore: La dimensione y del pixel.

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Ottiene o imposta la configurazione planare.

Valore: La configurazione planare.

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Ottiene o imposta la cromaticità dei tre colori primari dell'immagine.

Valore: La cromaticità dei tre colori primari dell'immagine.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS).

Valore: I tag EXIF (inclusi i tag comuni e GPS).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Ottiene o imposta l'indice di esposizione consigliato.

Valore: L'indice di esposizione consigliato.

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Ottiene o imposta il riferimento nero bianco.

Valore: Il riferimento bianco e nero.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Ottiene o imposta il file audio correlato.

Valore: Il file audio correlato.

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Ottiene o imposta l'unità di risoluzione.

Valore: L'unità di risoluzione.

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ottiene o imposta i campioni per pixel.

Valore: I campioni per pixel.

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Ottiene o imposta la saturazione.

Valore: La saturazione.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Ottiene o imposta il tipo di acquisizione della scena.

Valore: Il tipo di acquisizione della scena.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Ottiene o imposta il tipo di scena.

Valore: Il tipo della scena.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Ottiene o imposta il metodo di rilevamento.

Valore: Il metodo di rilevamento.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Ottiene o imposta il tipo di sensibilità.

Valore: Il tipo di sensibilità.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Ottiene o imposta la nitidezza.

Valore: La nitidezza.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Ottiene o imposta il valore della velocità dell'otturatore.

Valore: Il valore della velocità dell'otturatore.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Ottiene o imposta il software.

Valore: Il software.

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Ottiene o imposta la risposta in frequenza spaziale.

Valore: La risposta in frequenza spaziale.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Ottiene o imposta la sensibilità spettrale.

Valore: La sensibilità spettrale.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Ottiene la sensibilità di uscita standard

Valore: La sensibilità di uscita standard.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Ottiene o imposta l'area del soggetto.

Valore: L'area del soggetto.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Ottiene o imposta la distanza del soggetto.

Valore: La distanza del soggetto.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Ottiene o imposta l'intervallo di distanza del soggetto.

Valore: L'intervallo di distanza del soggetto.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Ottiene o imposta la posizione del soggetto.

Valore: La posizione del soggetto.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Ottiene o imposta le frazioni di secondo per il tag DateTime.

Valore: Le frazioni di secondo per il tag DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized.

Valore: Le frazioni di secondo per il tag DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal.

Valore: Le frazioni di secondo per il tag DateTimeOriginal.

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


Ottiene o imposta l'immagine miniatura.

Valore: La miniatura.

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Ottiene o imposta la funzione di trasferimento.

Valore: La funzione di trasferimento.

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Ottiene o imposta il commento dell'utente.

Valore: Il commento dell'utente.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Ottiene o imposta il bilanciamento del bianco.

Valore: Il bilanciamento del bianco.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Ottiene o imposta la cromaticità del punto bianco dell'immagine.

Valore: La cromaticità del punto bianco dell'immagine.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Ottiene o imposta la risoluzione x.

Valore: La risoluzione x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Ottiene o imposta i coefficienti della matrice per la trasformazione da RGB a dati immagine YCbCr.

Valore: I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza.

Valore: La posizione dei componenti di crominanza rispetto al componente di luminanza.

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

Valore: Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Ottiene o imposta la risoluzione y.

Valore: La risoluzione y.

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


Ottiene o imposta un valore che indica se i dati EXIF del flusso creati da è big endian.

Valore:  true  se il flusso di dati EXIF creato da è big endian; altrimenti,  false .

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


Rimuovi il tag dal contenitore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'identificatore del tag da rimuovere. |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serializza i dati EXIF. Scrive i valori e i contenuti dei tag. Il tag di dimensione più influente è il contenuto del tag Thumbnail.

**Returns:**
byte[] - I dati EXIF serializzati.

La dimensione complessiva del segmento deve essere minore o uguale a MaxExifSegmentSize byte per produrre un'immagine jpeg corretta. Suggerimento: prova a ridurre la dimensione della miniatura o a modificare la sua compressione nel caso in cui la sezione EXIF sia troppo grande.
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Ottiene o imposta il valore dell'apertura.

Valore: Il valore di apertura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Ottiene o imposta l'artista.

Valore: L'artista.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Ottiene o imposta un valore che indica se i dati EXIF del flusso creati da è big endian.

Valore:  true  se il flusso di dati EXIF creato da è big endian; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Ottiene o imposta i bit per campione.

Valore: I bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Ottiene o imposta il numero di serie del corpo della fotocamera.

Valore: Il numero di serie del corpo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Ottiene o imposta il valore della luminosità.

Valore: Il valore di luminosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Ottiene o imposta il pattern CFA.

Valore: Il modello CFA.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Ottiene o imposta il nome del proprietario della fotocamera

Valore: Il nome del proprietario della fotocamera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Ottiene o imposta lo spazio colore.

Valore: Lo spazio colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Ottiene o imposta i tag, che appartengono alla sezione comune. Questo si applica solo alle immagini jpeg, nel formato tiff vengono utilizzate tiffOptions.

Valore: I tag della sezione comune.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Ottiene o imposta la configurazione dei componenti.

Valore: La configurazione dei componenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Ottiene o imposta i bit compressi per pixel.

Valore: I bit compressi per pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Ottiene o imposta la compressione.

Valore: La compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Ottiene o imposta il contrasto.

Valore: Il contrasto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Ottiene o imposta il copyright.

Valore: Il copyright.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Ottiene o imposta il rendering personalizzato.

Valore: Il rendering personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Ottiene o imposta la data e ora.

Valore: La data e ora.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Ottiene o imposta la data e ora di digitalizzazione.

Valore: La data e ora di digitalizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Ottiene o imposta la data e ora originale.

Valore: La data e ora originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Ottiene o imposta la descrizione delle impostazioni del dispositivo

Valore: La descrizione delle impostazioni del dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Ottiene o imposta il rapporto di zoom digitale.

Valore: Il rapporto di zoom digitale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Ottiene o imposta i tag che appartengono solo alla sezione EXIF.

Valore: I tag della sezione EXIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Ottiene o imposta la versione EXIF.

Valore: La versione EXIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Ottiene o imposta il valore di compensazione dell'esposizione.

Valore: Il valore di compensazione dell'esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Ottiene o imposta l'indice di esposizione.

Valore: L'indice dell'esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Ottiene o imposta la modalità di esposizione.

Valore: La modalità di esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Ottiene o imposta il programma di esposizione.

Valore: Il programma di esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Ottiene o imposta il tempo di esposizione.

Valore: Il tempo di esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Ottiene o imposta il numero F.

Valore: Il numero F.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Ottiene o imposta il tipo di origine del file.

Valore: Il tipo di sorgente del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Ottiene o imposta il flash.

Valore: Il flash.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Ottiene o imposta l'energia del flash.

Valore: L'energia del flash.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Ottiene o imposta la versione flash pix.

Valore: La versione del flash pix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Ottiene o imposta la lunghezza focale.

Valore: La lunghezza del focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Ottiene o imposta la lunghezza focale nel film da 35 mm.

Valore: La lunghezza focale in pellicola da 35 mm.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Ottiene o imposta l'unità di risoluzione del piano focale.

Valore: L'unità di risoluzione del piano focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Ottiene o imposta la risoluzione X del piano focale.

Valore: La risoluzione x del piano focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Ottiene o imposta la risoluzione Y del piano focale.

Valore: La risoluzione y del piano focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Ottiene o imposta l'altitudine GPS.

Valore: L'altitudine GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Ottiene o imposta l'altitudine GPS utilizzata come altitudine di riferimento.

Valore: L'altitudine GPS usata come altitudine di riferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Ottiene o imposta le informazioni sull'area GPS.

Valore: Le informazioni sull'area GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Ottiene o imposta il DOP GPS (grado di precisione dei dati).

Valore: Il DOP GPS (grado di precisione dei dati).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale).

Valore: La stringa di caratteri GPS che registra data e ora relative a UTC (Tempo Coordinato Universale).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Ottiene o imposta l'orientamento GPS verso il punto di destinazione.

Valore: L'orientamento GPS verso il punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Ottiene o imposta il riferimento GPS utilizzato per fornire la direzione al punto di destinazione.

Valore: Il riferimento GPS usato per fornire l'orientamento verso il punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Ottiene o imposta la distanza GPS dal punto di destinazione.

Valore: La distanza GPS al punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Ottiene o imposta l'unità GPS utilizzata per esprimere la distanza dal punto di destinazione.

Valore: L'unità GPS usata per esprimere la distanza al punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Ottiene o imposta la latitudine GPS del punto di destinazione.

Valore: La latitudine GPS del punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud.

Valore: Il valore GPS che indica se la latitudine del punto di destinazione è a nord o a sud.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Ottiene o imposta la longitudine GPS del punto di destinazione.

Valore: La longitudine GPS del punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest.

Valore: Il valore GPS che indica se la longitudine del punto di destinazione è a est o a ovest.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS.

Valore: Il valore GPS che indica se è applicata la correzione differenziale al ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Ottiene o imposta la direzione GPS dell'immagine al momento della cattura.

Valore: La direzione GPS dell'immagine al momento della cattura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

Valore: Il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Ottiene o imposta la latitudine GPS.

Valore: La latitudine GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Ottiene o imposta se la latitudine GPS è nord o sud.

Valore: La latitudine GPS è latitudine nord o sud.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Ottiene o imposta la longitudine GPS.

Valore: La longitudine GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Ottiene o imposta se la longitudine GPS è est o ovest.

Valore: La longitudine GPS è longitudine est o ovest.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Ottiene o imposta i dati di rilievo geodetico GPS utilizzati dal ricevitore GPS.

Valore: I dati di rilievo geodetico GPS utilizzati dal ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Ottiene o imposta la modalità di misurazione GPS.

Valore: La modalità di misurazione GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo utilizzato per la ricerca della posizione.

Valore: La stringa di caratteri GPS che registra il nome del metodo utilizzato per la localizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Ottiene o imposta i satelliti GPS utilizzati per le misurazioni.

Valore: I satelliti GPS utilizzati per le misurazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Ottiene o imposta la velocità del movimento del ricevitore GPS.

Valore: La velocità di movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Ottiene o imposta l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS.

Valore: L'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Ottiene o imposta lo stato del ricevitore GPS quando l'immagine è registrata.

Valore: Lo stato del ricevitore GPS quando l'immagine è registrata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Ottiene o imposta i tag, che appartengono solo alla sezione GPS.

Valore: I tag GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale).

Valore: L'ora GPS come UTC (Tempo Coordinato Universale).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Ottiene o imposta la direzione del movimento del ricevitore GPS.

Valore: La direzione del movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS.

Valore: Il riferimento per fornire la direzione del movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Ottiene o imposta l'identificatore di versione GPS.

Valore: L'identificatore di versione GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine.

Valore: Il grado di regolazione complessiva del guadagno dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Ottiene o imposta la gamma.

Valore: Il valore gamma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Ottiene o imposta la velocità ISO

Valore: La velocità ISO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Ottiene o imposta il valore yyy della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di ingresso definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudezzz

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Ottiene o imposta il valore zzz della latitudine della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine della velocità ISO zzz di una fotocamera o dispositivo di input definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudeyyy

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Ottiene o imposta la descrizione dell'immagine.

Valore: La descrizione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Ottiene o imposta la lunghezza dell'immagine.

Valore: La lunghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Ottiene o imposta l'identificatore univoco dell'immagine.

Valore: L'identificatore univoco dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Ottiene o imposta la larghezza dell'immagine.

Valore: La larghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Ottiene o imposta il produttore dell'obiettivo.

Valore: Il produttore dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Ottiene o imposta il modello dell'obiettivo.

Valore: Il modello dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Ottiene o imposta il numero di serie dell'obiettivo.

Valore: Il numero di serie dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Ottiene o imposta le specifiche dell'obiettivo

Valore: La specifica dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Ottiene o imposta la sorgente luminosa.

Valore: La sorgente luminosa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Imposta il produttore dell'attrezzatura di registrazione.

Valore: Il produttore dell'attrezzatura di registrazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il produttore dell'attrezzatura di registrazione. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Ottiene o imposta i dati grezzi delle note del produttore.

Valore: I dati grezzi della nota del produttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Ottiene o imposta il valore dell'apertura massima.

Valore: Il valore dell'apertura massima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Ottiene o imposta la modalità di misurazione.

Valore: La modalità di misurazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Ottiene o imposta il modello.

Valore: Il modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

Valore: La Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Ottiene o imposta l'orientamento.

Valore: L'orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Ottiene o imposta la sensibilità fotografica.

Valore: La sensibilità fotografica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Ottiene o imposta l'interpretazione fotometrica.

Valore: L'interpretazione fotometrica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Ottiene o imposta la dimensione x del pixel.

Valore: La dimensione x del pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Ottiene o imposta la dimensione y del pixel.

Valore: La dimensione y del pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Ottiene o imposta la configurazione planare.

Valore: La configurazione planare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Ottiene o imposta la cromaticità dei tre colori primari dell'immagine.

Valore: La cromaticità dei tre colori primari dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS).

Valore: I tag EXIF (inclusi i tag comuni e GPS).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Ottiene o imposta l'indice di esposizione consigliato.

Valore: L'indice di esposizione consigliato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Ottiene o imposta il riferimento nero bianco.

Valore: Il riferimento bianco e nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Ottiene o imposta il file audio correlato.

Valore: Il file audio correlato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Ottiene o imposta l'unità di risoluzione.

Valore: L'unità di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Ottiene o imposta i campioni per pixel.

Valore: I campioni per pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Ottiene o imposta la saturazione.

Valore: La saturazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Ottiene o imposta il tipo di acquisizione della scena.

Valore: Il tipo di acquisizione della scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Ottiene o imposta il tipo di scena.

Valore: Il tipo della scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Ottiene o imposta il metodo di rilevamento.

Valore: Il metodo di rilevamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Ottiene o imposta il tipo di sensibilità.

Valore: Il tipo di sensibilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Ottiene o imposta la nitidezza.

Valore: La nitidezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Ottiene o imposta il valore della velocità dell'otturatore.

Valore: Il valore della velocità dell'otturatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Ottiene o imposta il software.

Valore: Il software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Ottiene o imposta la risposta in frequenza spaziale.

Valore: La risposta in frequenza spaziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Ottiene o imposta la sensibilità spettrale.

Valore: La sensibilità spettrale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Imposta la sensibilità di uscita standard

Valore: La sensibilità di uscita standard.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Ottiene o imposta l'area del soggetto.

Valore: L'area del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Ottiene o imposta la distanza del soggetto.

Valore: La distanza del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Ottiene o imposta l'intervallo di distanza del soggetto.

Valore: L'intervallo di distanza del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Ottiene o imposta la posizione del soggetto.

Valore: La posizione del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Ottiene o imposta le frazioni di secondo per il tag DateTime.

Valore: Le frazioni di secondo per il tag DateTime.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized.

Valore: Le frazioni di secondo per il tag DateTimeDigitized.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal.

Valore: Le frazioni di secondo per il tag DateTimeOriginal.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


Ottiene o imposta l'immagine miniatura.

Valore: La miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Ottiene o imposta la funzione di trasferimento.

Valore: La funzione di trasferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Ottiene o imposta il commento dell'utente.

Valore: Il commento dell'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Ottiene o imposta il bilanciamento del bianco.

Valore: Il bilanciamento del bianco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Ottiene o imposta la cromaticità del punto bianco dell'immagine.

Valore: La cromaticità del punto bianco dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Ottiene o imposta la risoluzione x.

Valore: La risoluzione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Ottiene o imposta i coefficienti della matrice per la trasformazione da RGB a dati immagine YCbCr.

Valore: I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza.

Valore: La posizione dei componenti di crominanza rispetto al componente di luminanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

Valore: Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Ottiene o imposta la risoluzione y.

Valore: La risoluzione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

