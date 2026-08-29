---
title: "ExifData"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Contenedor de datos EXIF."
type: docs
weight: 10
url: /es/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

Contenedor de datos EXIF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExifData()](#ExifData--) | Inicializa una nueva instancia de la  ExifData  clase. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la  ExifData  clase con datos de una matriz. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la  ExifData  clase con datos de una matriz. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Obtiene o establece el valor de la apertura. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Obtiene o establece el número de serie del cuerpo de la cámara. |
| [getBrightnessValue()](#getBrightnessValue--) | Obtiene o establece el valor de brillo. |
| [getCFAPattern()](#getCFAPattern--) | Obtiene o establece el patrón CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Obtiene o establece el nombre del propietario de la cámara |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Obtiene o establece el espacio de color. |
| [getCommonTags()](#getCommonTags--) | Obtiene o establece las etiquetas, que pertenecen a la sección común. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Obtiene o establece la configuración de componentes. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Obtiene o establece los bits comprimidos por píxel. |
| [getContrast()](#getContrast--) | Obtiene o establece el contraste. |
| [getCustomRendered()](#getCustomRendered--) | Obtiene o establece el renderizado personalizado. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Obtiene o establece la fecha y hora de digitalización. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Obtiene o establece la fecha y hora original. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Obtiene o establece la descripción de la configuración del dispositivo |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Obtiene o establece la relación de zoom digital. |
| [getExifTags()](#getExifTags--) | Obtiene o establece las etiquetas que pertenecen solo a la sección EXIF. |
| [getExifVersion()](#getExifVersion--) | Obtiene o establece la versión EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Obtiene o establece el valor de compensación de exposición. |
| [getExposureIndex()](#getExposureIndex--) | Obtiene o establece el índice de exposición. |
| [getExposureMode()](#getExposureMode--) | Obtiene o establece el modo de exposición. |
| [getExposureProgram()](#getExposureProgram--) | Obtiene o establece el programa de exposición. |
| [getExposureTime()](#getExposureTime--) | Obtiene o establece el tiempo de exposición. |
| [getFNumber()](#getFNumber--) | Obtiene o establece el número F. |
| [getFileSource()](#getFileSource--) | Obtiene o establece el tipo de origen del archivo. |
| [getFlash()](#getFlash--) | Obtiene o establece el flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Obtiene o establece la energía del flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Obtiene o establece la versión pix del flash. |
| [getFocalLength()](#getFocalLength--) | Obtiene o establece la distancia focal. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Obtiene o establece la distancia focal en película de 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Obtiene o establece la unidad de resolución del plano focal. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Obtiene o establece la resolución X del plano focal. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Obtiene o establece la resolución Y del plano focal. |
| [getGPSAltitude()](#getGPSAltitude--) | Obtiene o establece la altitud GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Obtiene o establece la altitud GPS utilizada como altitud de referencia. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Obtiene o establece la información del área GPS. |
| [getGPSDOP()](#getGPSDOP--) | Obtiene o establece el DOP GPS (grado de precisión de los datos). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Obtiene o establece la dirección GPS hacia el punto de destino. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Obtiene o establece la distancia GPS al punto de destino. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Obtiene o establece la latitud GPS del punto de destino. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Obtiene o establece la longitud GPS del punto de destino. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste. |
| [getGPSDifferential()](#getGPSDifferential--) | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Obtiene o establece la dirección GPS de la imagen cuando se capturó. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura. |
| [getGPSLatitude()](#getGPSLatitude--) | Obtiene o establece la latitud GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Obtiene o establece si la latitud GPS es norte o sur. |
| [getGPSLongitude()](#getGPSLongitude--) | Obtiene o establece la longitud GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Obtiene o establece si la longitud GPS es este u oeste. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Obtiene o establece el modo de medición GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización. |
| [getGPSSatellites()](#getGPSSatellites--) | Obtiene o establece los satélites GPS utilizados para las mediciones. |
| [getGPSSpeed()](#getGPSSpeed--) | Obtiene o establece la velocidad del movimiento del receptor GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. |
| [getGPSStatus()](#getGPSStatus--) | Obtiene o establece el estado del receptor GPS cuando se registra la imagen. |
| [getGPSTags()](#getGPSTags--) | Obtiene o establece etiquetas, que pertenecen solo a la sección GPS. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado). |
| [getGPSTrack()](#getGPSTrack--) | Obtiene o establece la dirección del movimiento del receptor GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Obtiene o establece la referencia para proporcionar la dirección del movimiento del receptor GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Obtiene o establece el identificador de versión GPS. |
| [getGainControl()](#getGainControl--) | Obtiene o establece el grado de ajuste general de ganancia de la imagen. |
| [getGamma()](#getGamma--) | Obtiene o establece la gamma. |
| [getISOSpeed()](#getISOSpeed--) | Obtiene o establece la velocidad ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Obtiene o establece el valor yyy de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Obtiene o establece el valor zzz de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232. |
| [getImageUniqueID()](#getImageUniqueID--) | Obtiene o establece el identificador único de la imagen. |
| [getLensMake()](#getLensMake--) | Obtiene o establece el fabricante del objetivo. |
| [getLensModel()](#getLensModel--) | Obtiene o establece el modelo del objetivo. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Obtiene o establece el número de serie del objetivo. |
| [getLensSpecification()](#getLensSpecification--) | Obtiene o establece la especificación del objetivo. |
| [getLightSource()](#getLightSource--) | Obtiene o establece la fuente de luz. |
| [getMake()](#getMake--) | Obtiene el fabricante del equipo de grabación. |
| [getMakerNoteData()](#getMakerNoteData--) | Obtiene los datos de la nota del fabricante. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Obtiene o establece los datos sin procesar de la nota del fabricante. |
| [getMakerNotes()](#getMakerNotes--) | Obtiene las notas del fabricante. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Obtiene o establece el valor máximo de apertura. |
| [getMeteringMode()](#getMeteringMode--) | Obtiene o establece el modo de medición. |
| [getOECF()](#getOECF--) | Obtiene o establece la Función de Conversión Opto‑Eléctrica (OECF) especificada en la ISO 14524. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Obtiene o establece la sensibilidad fotográfica. |
| [getPixelXDimension()](#getPixelXDimension--) | Obtiene o establece la dimensión x del píxel. |
| [getPixelYDimension()](#getPixelYDimension--) | Obtiene o establece la dimensión y del píxel. |
| [getProperties()](#getProperties--) | Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Obtiene o establece el índice de exposición recomendado. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Obtiene o establece el archivo de sonido relacionado. |
| [getSaturation()](#getSaturation--) | Obtiene o establece la saturación. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Obtiene o establece el tipo de captura de escena. |
| [getSceneType()](#getSceneType--) | Obtiene o establece el tipo de escena. |
| [getSensingMethod()](#getSensingMethod--) | Obtiene o establece el método de detección. |
| [getSensitivityType()](#getSensitivityType--) | Obtiene o establece el tipo de sensibilidad. |
| [getSharpness()](#getSharpness--) | Obtiene o establece la nitidez. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Obtiene o establece el valor de la velocidad de obturación. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Obtiene o establece la respuesta de frecuencia espacial. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Obtiene o establece la sensibilidad espectral. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Obtiene la sensibilidad de salida estándar |
| [getSubjectArea()](#getSubjectArea--) | Obtiene o establece el área del sujeto. |
| [getSubjectDistance()](#getSubjectDistance--) | Obtiene o establece la distancia del sujeto. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Obtiene o establece el rango de distancia del sujeto. |
| [getSubjectLocation()](#getSubjectLocation--) | Obtiene o establece la ubicación del sujeto. |
| [getSubsecTime()](#getSubsecTime--) | Obtiene o establece las fracciones de segundo para la etiqueta DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Obtiene o establece el comentario del usuario. |
| [getWhiteBalance()](#getWhiteBalance--) | Obtiene o establece el balance de blancos. |
| [getWhitePoint()](#getWhitePoint--) | Obtiene o establece la cromaticidad del punto blanco de la imagen. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Obtiene o establece un valor que indica si los datos EXIF del flujo creados son big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Eliminar etiqueta del contenedor |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece el valor de la apertura. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Obtiene o establece un valor que indica si los datos EXIF del flujo creados son big endian. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Obtiene o establece el número de serie del cuerpo de la cámara. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Obtiene o establece el valor de brillo. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Obtiene o establece el patrón CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Obtiene o establece el nombre del propietario de la cámara |
| [setColorSpace(int value)](#setColorSpace-int-) | Obtiene o establece el espacio de color. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtiene o establece las etiquetas, que pertenecen a la sección común. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Obtiene o establece la configuración de componentes. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece los bits comprimidos por píxel. |
| [setContrast(int value)](#setContrast-int-) | Obtiene o establece el contraste. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Obtiene o establece el renderizado personalizado. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Obtiene o establece la fecha y hora de digitalización. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Obtiene o establece la fecha y hora original. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Obtiene o establece la descripción de la configuración del dispositivo |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la relación de zoom digital. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtiene o establece las etiquetas que pertenecen solo a la sección EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Obtiene o establece la versión EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Obtiene o establece el valor de compensación de exposición. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece el índice de exposición. |
| [setExposureMode(int value)](#setExposureMode-int-) | Obtiene o establece el modo de exposición. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Obtiene o establece el programa de exposición. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece el tiempo de exposición. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece el número F. |
| [setFileSource(byte value)](#setFileSource-byte-) | Obtiene o establece el tipo de origen del archivo. |
| [setFlash(int value)](#setFlash-int-) | Obtiene o establece el flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la energía del flash. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Obtiene o establece la versión pix del flash. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la distancia focal. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Obtiene o establece la distancia focal en película de 35 mm. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Obtiene o establece la unidad de resolución del plano focal. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución X del plano focal. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución Y del plano focal. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la altitud GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Obtiene o establece la altitud GPS utilizada como altitud de referencia. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Obtiene o establece la información del área GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece el DOP GPS (grado de precisión de los datos). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la dirección GPS hacia el punto de destino. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la distancia GPS al punto de destino. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la latitud GPS del punto de destino. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la longitud GPS del punto de destino. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la dirección GPS de la imagen cuando se capturó. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la latitud GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Obtiene o establece si la latitud GPS es norte o sur. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la longitud GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Obtiene o establece si la longitud GPS es este u oeste. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Obtiene o establece el modo de medición GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Obtiene o establece los satélites GPS utilizados para las mediciones. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la velocidad del movimiento del receptor GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Obtiene o establece el estado del receptor GPS cuando se registra la imagen. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtiene o establece etiquetas, que pertenecen solo a la sección GPS. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Obtiene o establece la dirección del movimiento del receptor GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Obtiene o establece la referencia para proporcionar la dirección del movimiento del receptor GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Obtiene o establece el identificador de versión GPS. |
| [setGainControl(int value)](#setGainControl-int-) | Obtiene o establece el grado de ajuste general de ganancia de la imagen. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Obtiene o establece la velocidad ISO. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Obtiene o establece el valor yyy de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Obtiene o establece el valor zzz de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Obtiene o establece el identificador único de la imagen. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Obtiene o establece el fabricante del objetivo. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Obtiene o establece el modelo del objetivo. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Obtiene o establece el número de serie del objetivo. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la especificación del objetivo. |
| [setLightSource(int value)](#setLightSource-int-) | Obtiene o establece la fuente de luz. |
| [setMake(String value)](#setMake-java.lang.String-) | Establece el fabricante del equipo de grabación. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Obtiene o establece los datos sin procesar de la nota del fabricante. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece el valor máximo de apertura. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Obtiene o establece el modo de medición. |
| [setOECF(byte[] value)](#setOECF-byte---) | Obtiene o establece la Función de Conversión Opto‑Eléctrica (OECF) especificada en la ISO 14524. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Obtiene o establece la sensibilidad fotográfica. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Obtiene o establece la dimensión x del píxel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Obtiene o establece la dimensión y del píxel. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Obtiene o establece el índice de exposición recomendado. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Obtiene o establece el archivo de sonido relacionado. |
| [setSaturation(int value)](#setSaturation-int-) | Obtiene o establece la saturación. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Obtiene o establece el tipo de captura de escena. |
| [setSceneType(byte value)](#setSceneType-byte-) | Obtiene o establece el tipo de escena. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Obtiene o establece el método de detección. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Obtiene o establece el tipo de sensibilidad. |
| [setSharpness(int value)](#setSharpness-int-) | Obtiene o establece la nitidez. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Obtiene o establece el valor de la velocidad de obturación. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Obtiene o establece la respuesta de frecuencia espacial. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Obtiene o establece la sensibilidad espectral. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Establece la sensibilidad de salida estándar |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Obtiene o establece el área del sujeto. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la distancia del sujeto. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Obtiene o establece el rango de distancia del sujeto. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Obtiene o establece la ubicación del sujeto. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Obtiene o establece las fracciones de segundo para la etiqueta DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Obtiene o establece el comentario del usuario. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Obtiene o establece el balance de blancos. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece la cromaticidad del punto blanco de la imagen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


Inicializa una nueva instancia de la  ExifData  clase.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Inicializa una nueva instancia de la  ExifData  clase con datos de una matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Matriz de etiquetas EXIF junto con etiquetas comunes y GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Inicializa una nueva instancia de la  ExifData  clase con datos de una matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas comunes. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas GPS. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Obtiene o establece el valor de la apertura.

Valor: El valor de apertura.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Obtiene o establece el número de serie del cuerpo de la cámara.

Valor: El número de serie del cuerpo.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Obtiene o establece el valor de brillo.

Valor: El valor de brillo.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Obtiene o establece el patrón CFA.

Valor: El patrón CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Obtiene o establece el nombre del propietario de la cámara

Valor: El nombre del propietario de la cámara.

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


Obtiene o establece el espacio de color.

Valor: El espacio de color.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Obtiene o establece etiquetas que pertenecen a la sección común. Esto se aplica solo a imágenes jpeg; en formato tiff se utilizan tiffOptions en su lugar

Valor: Las etiquetas de la sección común.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Obtiene o establece la configuración de componentes.

Valor: La configuración de componentes.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Obtiene o establece los bits comprimidos por píxel.

Valor: Los bits comprimidos por píxel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


Obtiene o establece el contraste.

Valor: El contraste.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Obtiene o establece el renderizado personalizado.

Valor: El renderizado personalizado.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Obtiene o establece la fecha y hora de digitalización.

Valor: La fecha y hora de digitalización.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Obtiene o establece la fecha y hora original.

Valor: La fecha y hora original.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Obtiene o establece la descripción de la configuración del dispositivo

Valor: La descripción de la configuración del dispositivo.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Obtiene o establece la relación de zoom digital.

Valor: La relación de zoom digital.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Obtiene o establece las etiquetas que pertenecen solo a la sección EXIF.

Valor: Las etiquetas de la sección EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Obtiene o establece la versión EXIF.

Valor: La versión EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Obtiene o establece el valor de compensación de exposición.

Valor: El valor de compensación de exposición.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Obtiene o establece el índice de exposición.

Valor: El índice de exposición.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Obtiene o establece el modo de exposición.

Valor: El modo de exposición.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Obtiene o establece el programa de exposición.

Valor: El programa de exposición.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Obtiene o establece el tiempo de exposición.

Valor: El tiempo de exposición.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Obtiene o establece el número F.

Valor: El número F.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Obtiene o establece el tipo de origen del archivo.

Valor: El tipo de origen del archivo.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Obtiene o establece el flash.

Valor: El flash.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Obtiene o establece la energía del flash.

Valor: La energía del flash.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Obtiene o establece la versión pix del flash.

Valor: La versión de pix del flash.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Obtiene o establece la distancia focal.

Valor: La longitud del focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Obtiene o establece la distancia focal en película de 35 mm.

Valor: La distancia focal en película de 35 mm.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Obtiene o establece la unidad de resolución del plano focal.

Valor: La unidad de resolución del plano focal.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Obtiene o establece la resolución X del plano focal.

Valor: La resolución X del plano focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Obtiene o establece la resolución Y del plano focal.

Valor: La resolución Y del plano focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Obtiene o establece la altitud GPS.

Valor: La altitud GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Obtiene o establece la altitud GPS utilizada como altitud de referencia.

Valor: La altitud GPS utilizada como altitud de referencia.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Obtiene o establece la información del área GPS.

Valor: La información de área GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Obtiene o establece el DOP GPS (grado de precisión de los datos).

Valor: El DOP GPS (grado de precisión de los datos).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

Valor: La cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Obtiene o establece la dirección GPS hacia el punto de destino.

Valor: La dirección GPS al punto de destino.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino.

Valor: La referencia GPS utilizada para dar la dirección al punto de destino.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Obtiene o establece la distancia GPS al punto de destino.

Valor: La distancia GPS al punto de destino.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino.

Valor: La unidad GPS utilizada para expresar la distancia al punto de destino.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Obtiene o establece la latitud GPS del punto de destino.

Valor: La latitud GPS del punto de destino.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur.

Valor: El valor GPS que indica si la latitud del punto de destino es norte o sur.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Obtiene o establece la longitud GPS del punto de destino.

Valor: La longitud GPS del punto de destino.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste.

Valor: El valor GPS que indica si la longitud del punto de destino es longitud este u oeste.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS.

Valor: El valor GPS que indica si se aplica corrección diferencial al receptor GPS.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Obtiene o establece la dirección GPS de la imagen cuando se capturó.

Valor: La dirección GPS de la imagen cuando fue capturada.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura.

Valor: La referencia GPS para indicar la dirección de la imagen cuando se captura.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Obtiene o establece la latitud GPS.

Valor: La latitud GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Obtiene o establece si la latitud GPS es norte o sur.

Valor: La latitud GPS es latitud norte o sur.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Obtiene o establece la longitud GPS.

Valor: La longitud GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Obtiene o establece si la longitud GPS es este u oeste.

Valor: La longitud GPS es longitud este u oeste.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

Valor: Los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Obtiene o establece el modo de medición GPS.

Valor: El modo de medición GPS.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

Valor: La cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Obtiene o establece los satélites GPS utilizados para las mediciones.

Valor: Los satélites GPS utilizados para las mediciones.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Obtiene o establece la velocidad del movimiento del receptor GPS.

Valor: La velocidad del movimiento del receptor GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

Valor: La unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Obtiene o establece el estado del receptor GPS cuando se registra la imagen.

Valor: El estado del receptor GPS cuando se registra la imagen.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Obtiene o establece etiquetas, que pertenecen solo a la sección GPS.

Valor: Las etiquetas GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado).

Valor: La hora GPS como UTC (Tiempo Universal Coordinado).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Obtiene o establece la dirección del movimiento del receptor GPS.

Valor: La dirección del movimiento del receptor GPS.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Obtiene o establece la referencia para proporcionar la dirección del movimiento del receptor GPS.

Valor: La referencia para indicar la dirección del movimiento del receptor GPS.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Obtiene o establece el identificador de versión GPS.

Valor: El identificador de versión GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Obtiene o establece el grado de ajuste general de ganancia de la imagen.

Valor: El grado de ajuste general de ganancia de la imagen.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Obtiene o establece la gamma.

Valor: El valor gamma.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Obtiene o establece la velocidad ISO.

Valor: La velocidad ISO.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Obtiene o establece el valor yyy de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232.

Valor: El valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed e ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Obtiene o establece el valor zzz de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232.

Valor: El valor de latitud de velocidad ISO zzz de una cámara o dispositivo de entrada que está definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed y ISOSpeedLatitudeyyy

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Obtiene o establece el identificador único de la imagen.

Valor: El identificador único de la imagen.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Obtiene o establece el fabricante del objetivo.

Valor: El fabricante del objetivo.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Obtiene o establece el modelo del objetivo.

Valor: El modelo del objetivo.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Obtiene o establece el número de serie del objetivo.

Valor: El número de serie del objetivo.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Obtiene o establece la especificación del objetivo.

Valor: La especificación del objetivo.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Obtiene o establece la fuente de luz.

Valor: La fuente de luz.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Obtiene el fabricante del equipo de grabación.

Valor: El fabricante del equipo de grabación.

**Returns:**
java.lang.String - el fabricante del equipo de grabación.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Obtiene los datos de la nota del fabricante.

Valor: Los datos de la nota del fabricante.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Obtiene o establece los datos sin procesar de la nota del fabricante.

Valor: Los datos sin procesar de la nota del fabricante.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Obtiene las notas del fabricante.

Valor: Las notas del fabricante.

**Returns:**
com.aspose.psd.exif.MakerNote[] - las notas del fabricante.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Obtiene o establece el valor máximo de apertura.

Valor: El valor de apertura máxima.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Obtiene o establece el modo de medición.

Valor: El modo de medición.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Obtiene o establece la Función de Conversión Opto‑Eléctrica (OECF) especificada en la ISO 14524.

Valor: La Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524.

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Obtiene o establece la sensibilidad fotográfica.

Valor: La sensibilidad fotográfica.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Obtiene o establece la dimensión x del píxel.

Valor: La dimensión x del píxel.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Obtiene o establece la dimensión y del píxel.

Valor: La dimensión y del píxel.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

Valor: Las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Obtiene o establece el índice de exposición recomendado.

Valor: El índice de exposición recomendado.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Obtiene o establece el archivo de sonido relacionado.

Valor: El archivo de sonido relacionado.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Obtiene o establece la saturación.

Valor: La saturación.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Obtiene o establece el tipo de captura de escena.

Valor: El tipo de captura de escena.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Obtiene o establece el tipo de escena.

Valor: El tipo de la escena.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Obtiene o establece el método de detección.

Valor: El método de detección.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Obtiene o establece el tipo de sensibilidad.

Valor: El tipo de sensibilidad.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Obtiene o establece la nitidez.

Valor: La nitidez.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Obtiene o establece el valor de la velocidad de obturación.

Valor: El valor de la velocidad de obturación.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Obtiene o establece la respuesta de frecuencia espacial.

Valor: La respuesta de frecuencia espacial.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Obtiene o establece la sensibilidad espectral.

Valor: La sensibilidad espectral.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Obtiene la sensibilidad de salida estándar

Valor: La sensibilidad de salida estándar.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Obtiene o establece el área del sujeto.

Valor: El área del sujeto.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Obtiene o establece la distancia del sujeto.

Valor: La distancia del sujeto.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Obtiene o establece el rango de distancia del sujeto.

Valor: El rango de distancia del sujeto.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Obtiene o establece la ubicación del sujeto.

Valor: La ubicación del sujeto.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTime.

Valor: Las fracciones de segundo para la etiqueta DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized.

Valor: Las fracciones de segundo para la etiqueta DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal.

Valor: Las fracciones de segundo para la etiqueta DateTimeOriginal.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Obtiene o establece el comentario del usuario.

Valor: El comentario del usuario.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Obtiene o establece el balance de blancos.

Valor: El balance de blancos.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Obtiene o establece la cromaticidad del punto blanco de la imagen.

Valor: La cromaticidad del punto blanco de la imagen.

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


Obtiene o establece un valor que indica si los datos EXIF del flujo creados son big endian.

Valor:  true  si los datos EXIF del flujo creados a partir de son big endian; de lo contrario,  false .

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


Eliminar etiqueta del contenedor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de la etiqueta a eliminar. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Obtiene o establece el valor de la apertura.

Valor: El valor de apertura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Obtiene o establece un valor que indica si los datos EXIF del flujo creados son big endian.

Valor:  true  si los datos EXIF del flujo creados a partir de son big endian; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Obtiene o establece el número de serie del cuerpo de la cámara.

Valor: El número de serie del cuerpo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Obtiene o establece el valor de brillo.

Valor: El valor de brillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Obtiene o establece el patrón CFA.

Valor: El patrón CFA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Obtiene o establece el nombre del propietario de la cámara

Valor: El nombre del propietario de la cámara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Obtiene o establece el espacio de color.

Valor: El espacio de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Obtiene o establece etiquetas que pertenecen a la sección común. Esto se aplica solo a imágenes jpeg; en formato tiff se utilizan tiffOptions en su lugar

Valor: Las etiquetas de la sección común.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Obtiene o establece la configuración de componentes.

Valor: La configuración de componentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Obtiene o establece los bits comprimidos por píxel.

Valor: Los bits comprimidos por píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Obtiene o establece el contraste.

Valor: El contraste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Obtiene o establece el renderizado personalizado.

Valor: El renderizado personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Obtiene o establece la fecha y hora de digitalización.

Valor: La fecha y hora de digitalización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Obtiene o establece la fecha y hora original.

Valor: La fecha y hora original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Obtiene o establece la descripción de la configuración del dispositivo

Valor: La descripción de la configuración del dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Obtiene o establece la relación de zoom digital.

Valor: La relación de zoom digital.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Obtiene o establece las etiquetas que pertenecen solo a la sección EXIF.

Valor: Las etiquetas de la sección EXIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Obtiene o establece la versión EXIF.

Valor: La versión EXIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Obtiene o establece el valor de compensación de exposición.

Valor: El valor de compensación de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Obtiene o establece el índice de exposición.

Valor: El índice de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Obtiene o establece el modo de exposición.

Valor: El modo de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Obtiene o establece el programa de exposición.

Valor: El programa de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Obtiene o establece el tiempo de exposición.

Valor: El tiempo de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Obtiene o establece el número F.

Valor: El número F.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Obtiene o establece el tipo de origen del archivo.

Valor: El tipo de origen del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Obtiene o establece el flash.

Valor: El flash.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Obtiene o establece la energía del flash.

Valor: La energía del flash.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Obtiene o establece la versión pix del flash.

Valor: La versión de pix del flash.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Obtiene o establece la distancia focal.

Valor: La longitud del focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Obtiene o establece la distancia focal en película de 35 mm.

Valor: La distancia focal en película de 35 mm.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Obtiene o establece la unidad de resolución del plano focal.

Valor: La unidad de resolución del plano focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Obtiene o establece la resolución X del plano focal.

Valor: La resolución X del plano focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Obtiene o establece la resolución Y del plano focal.

Valor: La resolución Y del plano focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Obtiene o establece la altitud GPS.

Valor: La altitud GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Obtiene o establece la altitud GPS utilizada como altitud de referencia.

Valor: La altitud GPS utilizada como altitud de referencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Obtiene o establece la información del área GPS.

Valor: La información de área GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Obtiene o establece el DOP GPS (grado de precisión de los datos).

Valor: El DOP GPS (grado de precisión de los datos).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

Valor: La cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Obtiene o establece la dirección GPS hacia el punto de destino.

Valor: La dirección GPS al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino.

Valor: La referencia GPS utilizada para dar la dirección al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Obtiene o establece la distancia GPS al punto de destino.

Valor: La distancia GPS al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino.

Valor: La unidad GPS utilizada para expresar la distancia al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Obtiene o establece la latitud GPS del punto de destino.

Valor: La latitud GPS del punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur.

Valor: El valor GPS que indica si la latitud del punto de destino es norte o sur.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Obtiene o establece la longitud GPS del punto de destino.

Valor: La longitud GPS del punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste.

Valor: El valor GPS que indica si la longitud del punto de destino es longitud este u oeste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS.

Valor: El valor GPS que indica si se aplica corrección diferencial al receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Obtiene o establece la dirección GPS de la imagen cuando se capturó.

Valor: La dirección GPS de la imagen cuando fue capturada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura.

Valor: La referencia GPS para indicar la dirección de la imagen cuando se captura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Obtiene o establece la latitud GPS.

Valor: La latitud GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Obtiene o establece si la latitud GPS es norte o sur.

Valor: La latitud GPS es latitud norte o sur.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Obtiene o establece la longitud GPS.

Valor: La longitud GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Obtiene o establece si la longitud GPS es este u oeste.

Valor: La longitud GPS es longitud este u oeste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

Valor: Los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Obtiene o establece el modo de medición GPS.

Valor: El modo de medición GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

Valor: La cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Obtiene o establece los satélites GPS utilizados para las mediciones.

Valor: Los satélites GPS utilizados para las mediciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Obtiene o establece la velocidad del movimiento del receptor GPS.

Valor: La velocidad del movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

Valor: La unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Obtiene o establece el estado del receptor GPS cuando se registra la imagen.

Valor: El estado del receptor GPS cuando se registra la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Obtiene o establece etiquetas, que pertenecen solo a la sección GPS.

Valor: Las etiquetas GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado).

Valor: La hora GPS como UTC (Tiempo Universal Coordinado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Obtiene o establece la dirección del movimiento del receptor GPS.

Valor: La dirección del movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Obtiene o establece la referencia para proporcionar la dirección del movimiento del receptor GPS.

Valor: La referencia para indicar la dirección del movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Obtiene o establece el identificador de versión GPS.

Valor: El identificador de versión GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Obtiene o establece el grado de ajuste general de ganancia de la imagen.

Valor: El grado de ajuste general de ganancia de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Obtiene o establece la gamma.

Valor: El valor gamma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Obtiene o establece la velocidad ISO.

Valor: La velocidad ISO.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Obtiene o establece el valor yyy de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232.

Valor: El valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed e ISOSpeedLatitudezzz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Obtiene o establece el valor zzz de latitud de velocidad ISO de una cámara o dispositivo de entrada que está definido en la ISO 12232.

Valor: El valor de latitud de velocidad ISO zzz de una cámara o dispositivo de entrada que está definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed y ISOSpeedLatitudeyyy

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Obtiene o establece el identificador único de la imagen.

Valor: El identificador único de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Obtiene o establece el fabricante del objetivo.

Valor: El fabricante del objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Obtiene o establece el modelo del objetivo.

Valor: El modelo del objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Obtiene o establece el número de serie del objetivo.

Valor: El número de serie del objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Obtiene o establece la especificación del objetivo.

Valor: La especificación del objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Obtiene o establece la fuente de luz.

Valor: La fuente de luz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Establece el fabricante del equipo de grabación.

Valor: El fabricante del equipo de grabación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el fabricante del equipo de grabación. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Obtiene o establece los datos sin procesar de la nota del fabricante.

Valor: Los datos sin procesar de la nota del fabricante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Obtiene o establece el valor máximo de apertura.

Valor: El valor de apertura máxima.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Obtiene o establece el modo de medición.

Valor: El modo de medición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Obtiene o establece la Función de Conversión Opto‑Eléctrica (OECF) especificada en la ISO 14524.

Valor: La Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Obtiene o establece la sensibilidad fotográfica.

Valor: La sensibilidad fotográfica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Obtiene o establece la dimensión x del píxel.

Valor: La dimensión x del píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Obtiene o establece la dimensión y del píxel.

Valor: La dimensión y del píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

Valor: Las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Obtiene o establece el índice de exposición recomendado.

Valor: El índice de exposición recomendado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Obtiene o establece el archivo de sonido relacionado.

Valor: El archivo de sonido relacionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Obtiene o establece la saturación.

Valor: La saturación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Obtiene o establece el tipo de captura de escena.

Valor: El tipo de captura de escena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Obtiene o establece el tipo de escena.

Valor: El tipo de la escena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Obtiene o establece el método de detección.

Valor: El método de detección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Obtiene o establece el tipo de sensibilidad.

Valor: El tipo de sensibilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Obtiene o establece la nitidez.

Valor: La nitidez.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Obtiene o establece el valor de la velocidad de obturación.

Valor: El valor de la velocidad de obturación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Obtiene o establece la respuesta de frecuencia espacial.

Valor: La respuesta de frecuencia espacial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Obtiene o establece la sensibilidad espectral.

Valor: La sensibilidad espectral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Establece la sensibilidad de salida estándar

Valor: La sensibilidad de salida estándar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Obtiene o establece el área del sujeto.

Valor: El área del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Obtiene o establece la distancia del sujeto.

Valor: La distancia del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Obtiene o establece el rango de distancia del sujeto.

Valor: El rango de distancia del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Obtiene o establece la ubicación del sujeto.

Valor: La ubicación del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTime.

Valor: Las fracciones de segundo para la etiqueta DateTime.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized.

Valor: Las fracciones de segundo para la etiqueta DateTimeDigitized.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal.

Valor: Las fracciones de segundo para la etiqueta DateTimeOriginal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Obtiene o establece el comentario del usuario.

Valor: El comentario del usuario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Obtiene o establece el balance de blancos.

Valor: El balance de blancos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Obtiene o establece la cromaticidad del punto blanco de la imagen.

Valor: La cromaticidad del punto blanco de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

