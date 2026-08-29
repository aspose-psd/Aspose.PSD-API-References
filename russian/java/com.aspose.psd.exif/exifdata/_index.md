---
title: "ExifData"
second_title: "Aspose.PSD for Java API Справочник"
description: "Контейнер данных EXIF."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

Контейнер данных EXIF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExifData()](#ExifData--) | Инициализирует новый экземпляр класса  ExifData . |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса  ExifData  данными из массива. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса  ExifData  данными из массива. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Получает или задаёт значение диафрагмы. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Получает или задаёт серийный номер корпуса камеры. |
| [getBrightnessValue()](#getBrightnessValue--) | Получает или задаёт значение яркости. |
| [getCFAPattern()](#getCFAPattern--) | Получает или задаёт шаблон CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Получает или задаёт имя владельца камеры |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Получает или задаёт цветовое пространство. |
| [getCommonTags()](#getCommonTags--) | Получает или задаёт теги, принадлежащие общей секции. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Получает или задаёт конфигурацию компонентов. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Получает или задаёт сжатые биты на пиксель. |
| [getContrast()](#getContrast--) | Получает или задаёт контраст. |
| [getCustomRendered()](#getCustomRendered--) | Получает или задаёт пользовательскую отрисовку. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Получает или задаёт дату и время оцифровки. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Получает или задаёт оригинальную дату и время. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Получает или задает описание настроек устройства |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Получает или задает коэффициент цифрового увеличения. |
| [getExifTags()](#getExifTags--) | Получает или задает теги, которые относятся только к разделу EXIF. |
| [getExifVersion()](#getExifVersion--) | Получает или задает версию EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Получает или задает значение смещения экспозиции. |
| [getExposureIndex()](#getExposureIndex--) | Получает или задает индекс экспозиции. |
| [getExposureMode()](#getExposureMode--) | Получает или задает режим экспозиции. |
| [getExposureProgram()](#getExposureProgram--) | Получает или задает программу экспозиции. |
| [getExposureTime()](#getExposureTime--) | Получает или задает время экспозиции. |
| [getFNumber()](#getFNumber--) | Получает или задает значение F-number. |
| [getFileSource()](#getFileSource--) | Получает или задает тип источника файла. |
| [getFlash()](#getFlash--) | Получает или задает вспышку. |
| [getFlashEnergy()](#getFlashEnergy--) | Получает или задает энергию вспышки. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Получает или задает версию flash pix. |
| [getFocalLength()](#getFocalLength--) | Получает или задает фокусное расстояние. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Получает или задает фокусное расстояние в 35‑мм пленке. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Получает или задает единицу разрешения фокальной плоскости. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Получает или задает разрешение по оси X фокальной плоскости. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Получает или задает разрешение по оси Y фокальной плоскости. |
| [getGPSAltitude()](#getGPSAltitude--) | Получает или задает высоту GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Получает или задает высоту GPS, используемую в качестве эталонной высоты. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Получает или задает информацию о области GPS. |
| [getGPSDOP()](#getGPSDOP--) | Получает или задает GPS DOP (степень точности данных). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Получает или задает строку GPS, записывающую дату и время относительно UTC (координированного всемирного времени). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Получает или задает азимут GPS к целевой точке. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Получает или задаёт GPS‑ссылку, используемую для указания направления к целевой точке. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Получает или задает расстояние GPS до конечной точки. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Получает или задает единицу GPS, используемую для выражения расстояния до конечной точки. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Получает или задает широту GPS конечной точки. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Получает или задает значение GPS, указывающее, является ли широта конечной точки северной или южной. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Получает или задает долготу GPS конечной точки. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Получает или задает значение GPS, указывающее, является ли долгота конечной точки восточной или западной. |
| [getGPSDifferential()](#getGPSDifferential--) | Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS‑приемнику. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Получает или задает направление GPS изображения при его захвате. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Получает или задает ссылку GPS, указывающую направление изображения при его захвате. |
| [getGPSLatitude()](#getGPSLatitude--) | Получает или задает широту GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Получает или задает, является ли широта GPS северной или южной. |
| [getGPSLongitude()](#getGPSLongitude--) | Получает или задает долготу GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Получает или задает, является ли долгота GPS восточной или западной. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Получает или задает геодезические данные GPS, используемые GPS‑приемником. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Получает или задает режим измерения GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Получает или задает строку GPS, содержащую название метода, используемого для определения местоположения. |
| [getGPSSatellites()](#getGPSSatellites--) | Получает или задает спутники GPS, используемые для измерений. |
| [getGPSSpeed()](#getGPSSpeed--) | Получает или задает скорость перемещения GPS‑приемника. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Получает или задает единицу, используемую для выражения скорости перемещения GPS‑приемника. |
| [getGPSStatus()](#getGPSStatus--) | Получает или задает статус GPS‑приемника при записи изображения. |
| [getGPSTags()](#getGPSTags--) | Получает или задает теги, которые относятся только к разделу GPS. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Получает или задает время GPS в формате UTC (координированное всемирное время). |
| [getGPSTrack()](#getGPSTrack--) | Получает или задает направление перемещения GPS‑приемника. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Получает или задает ссылку, указывающую направление перемещения GPS‑приемника. |
| [getGPSVersionID()](#getGPSVersionID--) | Получает или задает идентификатор версии GPS. |
| [getGainControl()](#getGainControl--) | Получает или задает степень общей регулировки усиления изображения. |
| [getGamma()](#getGamma--) | Получает или задает гамму. |
| [getISOSpeed()](#getISOSpeed--) | Получает или задает скорость ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Получает или задает значение yyy широты скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Получает или задает значение zzz широты скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [getImageUniqueID()](#getImageUniqueID--) | Получает или задает уникальный идентификатор изображения. |
| [getLensMake()](#getLensMake--) | Получает или задает производителя объектива. |
| [getLensModel()](#getLensModel--) | Получает или задает модель объектива. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Получает или задает серийный номер объектива. |
| [getLensSpecification()](#getLensSpecification--) | Получает или задает спецификацию объектива. |
| [getLightSource()](#getLightSource--) | Получает или задает источник света. |
| [getMake()](#getMake--) | Получает производителя записывающего оборудования. |
| [getMakerNoteData()](#getMakerNoteData--) | Получает данные примечаний производителя. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Получает или задает необработанные данные примечаний производителя. |
| [getMakerNotes()](#getMakerNotes--) | Получает примечания производителя. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Получает или задает значение максимальной диафрагмы. |
| [getMeteringMode()](#getMeteringMode--) | Получает или задает режим измерения экспозиции. |
| [getOECF()](#getOECF--) | Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Получает или задает фоточувствительность. |
| [getPixelXDimension()](#getPixelXDimension--) | Получает или задает размер пикселя по оси X. |
| [getPixelYDimension()](#getPixelYDimension--) | Получает или задает размер пикселя по оси Y. |
| [getProperties()](#getProperties--) | Получает или задает все теги EXIF (включая общие и GPS-теги). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Получает или задает рекомендованный индекс экспозиции. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Получает или задает связанный звуковой файл. |
| [getSaturation()](#getSaturation--) | Получает или задает насыщенность. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Получает или задает тип захвата сцены. |
| [getSceneType()](#getSceneType--) | Получает или задает тип сцены. |
| [getSensingMethod()](#getSensingMethod--) | Получает или задает метод измерения. |
| [getSensitivityType()](#getSensitivityType--) | Получает или задает тип чувствительности. |
| [getSharpness()](#getSharpness--) | Получает или задает резкость. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Получает или задает значение скорости затвора. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Получает или задает отклик пространственной частоты. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Получает или задает спектральную чувствительность. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Получает стандартную чувствительность вывода |
| [getSubjectArea()](#getSubjectArea--) | Получает или задает область объекта. |
| [getSubjectDistance()](#getSubjectDistance--) | Получает или задает расстояние до объекта. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Получает или задает диапазон расстояний до объекта. |
| [getSubjectLocation()](#getSubjectLocation--) | Получает или задает расположение объекта. |
| [getSubsecTime()](#getSubsecTime--) | Получает или задает доли секунды для тега DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Получает или задает доли секунды для тега DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Получает или задает доли секунды для тега DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Получает или задает комментарий пользователя. |
| [getWhiteBalance()](#getWhiteBalance--) | Получает или задает баланс белого. |
| [getWhitePoint()](#getWhitePoint--) | Получает или задает хроматичность белой точки изображения. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Получает или задает значение, указывающее, является ли поток данных EXIF, созданный из, big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Удалить тег из контейнера |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задаёт значение диафрагмы. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Получает или задает значение, указывающее, является ли поток данных EXIF, созданный из, big endian. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Получает или задаёт серийный номер корпуса камеры. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Получает или задаёт значение яркости. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Получает или задаёт шаблон CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Получает или задаёт имя владельца камеры |
| [setColorSpace(int value)](#setColorSpace-int-) | Получает или задаёт цветовое пространство. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Получает или задаёт теги, принадлежащие общей секции. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Получает или задаёт конфигурацию компонентов. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задаёт сжатые биты на пиксель. |
| [setContrast(int value)](#setContrast-int-) | Получает или задаёт контраст. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Получает или задаёт пользовательскую отрисовку. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Получает или задаёт дату и время оцифровки. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Получает или задаёт оригинальную дату и время. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Получает или задает описание настроек устройства |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает коэффициент цифрового увеличения. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Получает или задает теги, которые относятся только к разделу EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Получает или задает версию EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Получает или задает значение смещения экспозиции. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает индекс экспозиции. |
| [setExposureMode(int value)](#setExposureMode-int-) | Получает или задает режим экспозиции. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Получает или задает программу экспозиции. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает время экспозиции. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает значение F-number. |
| [setFileSource(byte value)](#setFileSource-byte-) | Получает или задает тип источника файла. |
| [setFlash(int value)](#setFlash-int-) | Получает или задает вспышку. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает энергию вспышки. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Получает или задает версию flash pix. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает фокусное расстояние. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Получает или задает фокусное расстояние в 35‑мм пленке. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Получает или задает единицу разрешения фокальной плоскости. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси X фокальной плоскости. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси Y фокальной плоскости. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает высоту GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Получает или задает высоту GPS, используемую в качестве эталонной высоты. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Получает или задает информацию о области GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает GPS DOP (степень точности данных). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Получает или задает строку GPS, записывающую дату и время относительно UTC (координированного всемирного времени). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает азимут GPS к целевой точке. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Получает или задаёт GPS‑ссылку, используемую для указания направления к целевой точке. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает расстояние GPS до конечной точки. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Получает или задает единицу GPS, используемую для выражения расстояния до конечной точки. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает широту GPS конечной точки. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Получает или задает значение GPS, указывающее, является ли широта конечной точки северной или южной. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает долготу GPS конечной точки. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Получает или задает значение GPS, указывающее, является ли долгота конечной точки восточной или западной. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS‑приемнику. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает направление GPS изображения при его захвате. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Получает или задает ссылку GPS, указывающую направление изображения при его захвате. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает широту GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Получает или задает, является ли широта GPS северной или южной. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает долготу GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Получает или задает, является ли долгота GPS восточной или западной. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Получает или задает геодезические данные GPS, используемые GPS‑приемником. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Получает или задает режим измерения GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Получает или задает строку GPS, содержащую название метода, используемого для определения местоположения. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Получает или задает спутники GPS, используемые для измерений. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает скорость перемещения GPS‑приемника. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Получает или задает единицу, используемую для выражения скорости перемещения GPS‑приемника. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Получает или задает статус GPS‑приемника при записи изображения. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Получает или задает теги, которые относятся только к разделу GPS. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает время GPS в формате UTC (координированное всемирное время). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Получает или задает направление перемещения GPS‑приемника. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Получает или задает ссылку, указывающую направление перемещения GPS‑приемника. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Получает или задает идентификатор версии GPS. |
| [setGainControl(int value)](#setGainControl-int-) | Получает или задает степень общей регулировки усиления изображения. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает гамму. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Получает или задает скорость ISO. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Получает или задает значение yyy широты скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Получает или задает значение zzz широты скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Получает или задает уникальный идентификатор изображения. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Получает или задает производителя объектива. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Получает или задает модель объектива. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Получает или задает серийный номер объектива. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает спецификацию объектива. |
| [setLightSource(int value)](#setLightSource-int-) | Получает или задает источник света. |
| [setMake(String value)](#setMake-java.lang.String-) | Задает производителя записывающего оборудования. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Получает или задает необработанные данные примечаний производителя. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает значение максимальной диафрагмы. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Получает или задает режим измерения экспозиции. |
| [setOECF(byte[] value)](#setOECF-byte---) | Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Получает или задает фоточувствительность. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Получает или задает размер пикселя по оси X. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Получает или задает размер пикселя по оси Y. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Получает или задает все теги EXIF (включая общие и GPS-теги). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Получает или задает рекомендованный индекс экспозиции. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Получает или задает связанный звуковой файл. |
| [setSaturation(int value)](#setSaturation-int-) | Получает или задает насыщенность. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Получает или задает тип захвата сцены. |
| [setSceneType(byte value)](#setSceneType-byte-) | Получает или задает тип сцены. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Получает или задает метод измерения. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Получает или задает тип чувствительности. |
| [setSharpness(int value)](#setSharpness-int-) | Получает или задает резкость. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Получает или задает значение скорости затвора. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Получает или задает отклик пространственной частоты. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Получает или задает спектральную чувствительность. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Задает стандартную чувствительность вывода |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Получает или задает область объекта. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает расстояние до объекта. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Получает или задает диапазон расстояний до объекта. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Получает или задает расположение объекта. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Получает или задает доли секунды для тега DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Получает или задает доли секунды для тега DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Получает или задает доли секунды для тега DateTimeOriginal. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Получает или задает комментарий пользователя. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Получает или задает баланс белого. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает хроматичность белой точки изображения. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


Инициализирует новый экземпляр класса  ExifData .

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Инициализирует новый экземпляр класса  ExifData  данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Массив тегов EXIF вместе с общими и GPS‑тегами. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Инициализирует новый экземпляр класса  ExifData  данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Общие теги. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Теги EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Теги GPS. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Получает или задаёт значение диафрагмы.

Значение: значение диафрагмы.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Получает или задаёт серийный номер корпуса камеры.

Значение: серийный номер корпуса.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Получает или задаёт значение яркости.

Значение: значение яркости.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Получает или задаёт шаблон CFA.

Значение: шаблон CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Получает или задаёт имя владельца камеры

Значение: имя владельца камеры.

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


Получает или задаёт цветовое пространство.

Значение: цветовое пространство.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Получает или задает теги, принадлежащие общей секции. Это применимо только к изображениям JPEG, в формате TIFF вместо этого используются tiffOptions.

Значение: теги общей секции.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Получает или задаёт конфигурацию компонентов.

Значение: конфигурация компонентов.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Получает или задаёт сжатые биты на пиксель.

Значение: сжатые биты на пиксель.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


Получает или задаёт контраст.

Значение: контраст.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Получает или задаёт пользовательскую отрисовку.

Значение: пользовательская отрисовка.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Получает или задаёт дату и время оцифровки.

Значение: дата и время оцифровки.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Получает или задаёт оригинальную дату и время.

Значение: оригинальная дата и время.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Получает или задает описание настроек устройства

Значение: описание настроек устройства.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Получает или задает коэффициент цифрового увеличения.

Значение: коэффициент цифрового зума.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Получает или задает теги, которые относятся только к разделу EXIF.

Значение: теги раздела EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Получает или задает версию EXIF.

Значение: версия EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Получает или задает значение смещения экспозиции.

Значение: значение смещения экспозиции.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Получает или задает индекс экспозиции.

Значение: индекс экспозиции.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Получает или задает режим экспозиции.

Значение: режим экспозиции.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Получает или задает программу экспозиции.

Значение: программа экспозиции.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Получает или задает время экспозиции.

Значение: Время экспозиции.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Получает или задает значение F-number.

Значение: F-число.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Получает или задает тип источника файла.

Значение: Тип источника файла.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Получает или задает вспышку.

Значение: Вспышка.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Получает или задает энергию вспышки.

Значение: Энергия вспышки.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Получает или задает версию flash pix.

Значение: Версия flash pix.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Получает или задает фокусное расстояние.

Значение: Длина фокуса.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Получает или задает фокусное расстояние в 35‑мм пленке.

Значение: Фокусное расстояние в 35‑мм пленке.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Получает или задает единицу разрешения фокальной плоскости.

Значение: Единица разрешения плоскости фокуса.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Получает или задает разрешение по оси X фокальной плоскости.

Значение: Разрешение плоскости фокуса по X.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Получает или задает разрешение по оси Y фокальной плоскости.

Значение: Разрешение плоскости фокуса по Y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Получает или задает высоту GPS.

Значение: Высота GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Получает или задает высоту GPS, используемую в качестве эталонной высоты.

Значение: Высота GPS, используемая в качестве эталонной высоты.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Получает или задает информацию о области GPS.

Значение: Информация о области GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Получает или задает GPS DOP (степень точности данных).

Значение: GPS DOP (степень точности данных).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Получает или задает строку GPS, записывающую дату и время относительно UTC (координированного всемирного времени).

Значение: Строка GPS, записывающая дату и время относительно UTC (координированное всемирное время).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Получает или задает азимут GPS к целевой точке.

Значение: Азимут GPS к целевой точке.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Получает или задаёт GPS‑ссылку, используемую для указания направления к целевой точке.

Значение: GPS‑ссылка, используемая для определения азимута к целевой точке.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Получает или задает расстояние GPS до конечной точки.

Значение: Расстояние GPS до целевой точки.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Получает или задает единицу GPS, используемую для выражения расстояния до конечной точки.

Значение: Единица GPS, используемая для выражения расстояния до целевой точки.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Получает или задает широту GPS конечной точки.

Значение: Широта GPS целевой точки.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Получает или задает значение GPS, указывающее, является ли широта конечной точки северной или южной.

Значение: Значение GPS, указывающее, находится ли широта целевой точки в северном или южном полушарии.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Получает или задает долготу GPS конечной точки.

Значение: Долгота GPS целевой точки.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Получает или задает значение GPS, указывающее, является ли долгота конечной точки восточной или западной.

Значение: Значение GPS, указывающее, находится ли долгота целевой точки в восточном или западном полушарии.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS‑приемнику.

Значение: GPS‑значение, указывающее, применяется ли дифференциальная коррекция к GPS‑приёмнику.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Получает или задает направление GPS изображения при его захвате.

Значение: GPS‑направление изображения при его захвате.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Получает или задает ссылку GPS, указывающую направление изображения при его захвате.

Значение: GPS‑ссылка, указывающая направление изображения при его захвате.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Получает или задает широту GPS.

Значение: GPS‑широта.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Получает или задает, является ли широта GPS северной или южной.

Значение: GPS‑широта — северная или южная широта.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Получает или задает долготу GPS.

Значение: GPS‑долгота.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Получает или задает, является ли долгота GPS восточной или западной.

Значение: GPS‑долгота — восточная или западная долгота.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Получает или задает геодезические данные GPS, используемые GPS‑приемником.

Значение: GPS‑геодезические данные, используемые GPS‑приёмником.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Получает или задает режим измерения GPS.

Значение: GPS‑режим измерения.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Получает или задает строку GPS, содержащую название метода, используемого для определения местоположения.

Значение: GPS‑строка, содержащая название метода, используемого для определения местоположения.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Получает или задает спутники GPS, используемые для измерений.

Значение: GPS‑спутники, используемые для измерений.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Получает или задает скорость перемещения GPS‑приемника.

Значение: Скорость перемещения GPS‑приёмника.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Получает или задает единицу, используемую для выражения скорости перемещения GPS‑приемника.

Значение: Единица измерения скорости перемещения GPS‑приёмника.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Получает или задает статус GPS‑приемника при записи изображения.

Значение: Состояние GPS‑приёмника при записи изображения.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Получает или задает теги, которые относятся только к разделу GPS.

Значение: GPS‑теги.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Получает или задает время GPS в формате UTC (координированное всемирное время).

Значение: GPS‑время в формате UTC (координированное всемирное время).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Получает или задает направление перемещения GPS‑приемника.

Значение: Направление перемещения GPS‑приёмника.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Получает или задает ссылку, указывающую направление перемещения GPS‑приемника.

Значение: Ссылка, указывающая направление перемещения GPS‑приёмника.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Получает или задает идентификатор версии GPS.

Значение: Идентификатор версии GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Получает или задает степень общей регулировки усиления изображения.

Значение: Степень общей регулировки усиления изображения.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Получает или задает гамму.

Значение: Значение гаммы.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Получает или задает скорость ISO.

Значение: ISO‑скорость.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Получает или задает значение yyy широты скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: Значение ISO‑speed latitude yyy камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен быть записан без ISOSpeed и ISOSpeedLatitudezzz.

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Получает или задает значение zzz широты скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: Значение ISO‑speed latitude zzz камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен записываться без ISOSpeed и ISOSpeedLatitudeyyy

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Получает или задает уникальный идентификатор изображения.

Значение: Уникальный идентификатор изображения.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Получает или задает производителя объектива.

Значение: Производитель объектива.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Получает или задает модель объектива.

Значение: Модель объектива.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Получает или задает серийный номер объектива.

Значение: Серийный номер объектива.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Получает или задает спецификацию объектива.

Значение: Спецификация объектива.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Получает или задает источник света.

Значение: Источник света.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Получает производителя записывающего оборудования.

Значение: Производитель записывающего оборудования.

**Returns:**
java.lang.String - производитель записывающего оборудования.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Получает данные примечаний производителя.

Значение: Данные MakerNote.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Получает или задает необработанные данные примечаний производителя.

Значение: Необработанные данные MakerNote.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Получает примечания производителя.

Значение: MakerNote.

**Returns:**
com.aspose.psd.exif.MakerNote[] - MakerNote.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Получает или задает значение максимальной диафрагмы.

Значение: Максимальное значение диафрагмы.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Получает или задает режим измерения экспозиции.

Значение: Режим измерения экспозиции.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524.

Значение: Опто-электрическая функция преобразования (OECF), указанная в ISO 14524.

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Получает или задает фоточувствительность.

Значение: Фотографическая чувствительность.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Получает или задает размер пикселя по оси X.

Значение: Размер пикселя по оси X.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Получает или задает размер пикселя по оси Y.

Значение: Размер пикселя по оси Y.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Получает или задает все теги EXIF (включая общие и GPS-теги).

Значение: Теги EXIF (включая общие и GPS-теги).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Получает или задает рекомендованный индекс экспозиции.

Значение: Рекомендованный индекс экспозиции.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Получает или задает связанный звуковой файл.

Значение: Связанный звуковой файл.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Получает или задает насыщенность.

Значение: Насыщенность.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Получает или задает тип захвата сцены.

Значение: Тип захвата сцены.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Получает или задает тип сцены.

Значение: Тип сцены.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Получает или задает метод измерения.

Значение: Метод измерения.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Получает или задает тип чувствительности.

Значение: Тип чувствительности.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Получает или задает резкость.

Значение: Резкость.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Получает или задает значение скорости затвора.

Значение: Значение скорости затвора.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Получает или задает отклик пространственной частоты.

Значение: Пространственная частотная характеристика.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Получает или задает спектральную чувствительность.

Значение: Спектральная чувствительность.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Получает стандартную чувствительность вывода

Значение: Стандартная выходная чувствительность.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Получает или задает область объекта.

Значение: Область объекта.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Получает или задает расстояние до объекта.

Значение: Расстояние до объекта.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Получает или задает диапазон расстояний до объекта.

Значение: Диапазон расстояний до объекта.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Получает или задает расположение объекта.

Значение: Положение объекта.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Получает или задает доли секунды для тега DateTime.

Значение: Доли секунды для тега DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Получает или задает доли секунды для тега DateTimeDigitized.

Значение: Доли секунды для тега DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Получает или задает доли секунды для тега DateTimeOriginal.

Значение: Доли секунды для тега DateTimeOriginal.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Получает или задает комментарий пользователя.

Значение: Комментарий пользователя.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Получает или задает баланс белого.

Значение: Баланс белого.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Получает или задает хроматичность белой точки изображения.

Значение: Хроматичность белой точки изображения.

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


Получает или задает значение, указывающее, является ли поток данных EXIF, созданный из, big endian.

Значение:  true  если поток EXIF данных, из которого создано, имеет порядок байтов big endian; иначе,  false .

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


Удалить тег из контейнера

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега для удаления. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Получает или задаёт значение диафрагмы.

Значение: значение диафрагмы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Получает или задает значение, указывающее, является ли поток данных EXIF, созданный из, big endian.

Значение:  true  если поток EXIF данных, из которого создано, имеет порядок байтов big endian; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Получает или задаёт серийный номер корпуса камеры.

Значение: серийный номер корпуса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Получает или задаёт значение яркости.

Значение: значение яркости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Получает или задаёт шаблон CFA.

Значение: шаблон CFA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Получает или задаёт имя владельца камеры

Значение: имя владельца камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Получает или задаёт цветовое пространство.

Значение: цветовое пространство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Получает или задает теги, принадлежащие общей секции. Это применимо только к изображениям JPEG, в формате TIFF вместо этого используются tiffOptions.

Значение: теги общей секции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Получает или задаёт конфигурацию компонентов.

Значение: конфигурация компонентов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Получает или задаёт сжатые биты на пиксель.

Значение: сжатые биты на пиксель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Получает или задаёт контраст.

Значение: контраст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Получает или задаёт пользовательскую отрисовку.

Значение: пользовательская отрисовка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Получает или задаёт дату и время оцифровки.

Значение: дата и время оцифровки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Получает или задаёт оригинальную дату и время.

Значение: оригинальная дата и время.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Получает или задает описание настроек устройства

Значение: описание настроек устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Получает или задает коэффициент цифрового увеличения.

Значение: коэффициент цифрового зума.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Получает или задает теги, которые относятся только к разделу EXIF.

Значение: теги раздела EXIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Получает или задает версию EXIF.

Значение: версия EXIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Получает или задает значение смещения экспозиции.

Значение: значение смещения экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Получает или задает индекс экспозиции.

Значение: индекс экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Получает или задает режим экспозиции.

Значение: режим экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Получает или задает программу экспозиции.

Значение: программа экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Получает или задает время экспозиции.

Значение: Время экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Получает или задает значение F-number.

Значение: F-число.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Получает или задает тип источника файла.

Значение: Тип источника файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Получает или задает вспышку.

Значение: Вспышка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Получает или задает энергию вспышки.

Значение: Энергия вспышки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Получает или задает версию flash pix.

Значение: Версия flash pix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Получает или задает фокусное расстояние.

Значение: Длина фокуса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Получает или задает фокусное расстояние в 35‑мм пленке.

Значение: Фокусное расстояние в 35‑мм пленке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Получает или задает единицу разрешения фокальной плоскости.

Значение: Единица разрешения плоскости фокуса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Получает или задает разрешение по оси X фокальной плоскости.

Значение: Разрешение плоскости фокуса по X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Получает или задает разрешение по оси Y фокальной плоскости.

Значение: Разрешение плоскости фокуса по Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Получает или задает высоту GPS.

Значение: Высота GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Получает или задает высоту GPS, используемую в качестве эталонной высоты.

Значение: Высота GPS, используемая в качестве эталонной высоты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Получает или задает информацию о области GPS.

Значение: Информация о области GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Получает или задает GPS DOP (степень точности данных).

Значение: GPS DOP (степень точности данных).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Получает или задает строку GPS, записывающую дату и время относительно UTC (координированного всемирного времени).

Значение: Строка GPS, записывающая дату и время относительно UTC (координированное всемирное время).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Получает или задает азимут GPS к целевой точке.

Значение: Азимут GPS к целевой точке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Получает или задаёт GPS‑ссылку, используемую для указания направления к целевой точке.

Значение: GPS‑ссылка, используемая для определения азимута к целевой точке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Получает или задает расстояние GPS до конечной точки.

Значение: Расстояние GPS до целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Получает или задает единицу GPS, используемую для выражения расстояния до конечной точки.

Значение: Единица GPS, используемая для выражения расстояния до целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Получает или задает широту GPS конечной точки.

Значение: Широта GPS целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Получает или задает значение GPS, указывающее, является ли широта конечной точки северной или южной.

Значение: Значение GPS, указывающее, находится ли широта целевой точки в северном или южном полушарии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Получает или задает долготу GPS конечной точки.

Значение: Долгота GPS целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Получает или задает значение GPS, указывающее, является ли долгота конечной точки восточной или западной.

Значение: Значение GPS, указывающее, находится ли долгота целевой точки в восточном или западном полушарии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS‑приемнику.

Значение: GPS‑значение, указывающее, применяется ли дифференциальная коррекция к GPS‑приёмнику.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Получает или задает направление GPS изображения при его захвате.

Значение: GPS‑направление изображения при его захвате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Получает или задает ссылку GPS, указывающую направление изображения при его захвате.

Значение: GPS‑ссылка, указывающая направление изображения при его захвате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Получает или задает широту GPS.

Значение: GPS‑широта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Получает или задает, является ли широта GPS северной или южной.

Значение: GPS‑широта — северная или южная широта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Получает или задает долготу GPS.

Значение: GPS‑долгота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Получает или задает, является ли долгота GPS восточной или западной.

Значение: GPS‑долгота — восточная или западная долгота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Получает или задает геодезические данные GPS, используемые GPS‑приемником.

Значение: GPS‑геодезические данные, используемые GPS‑приёмником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Получает или задает режим измерения GPS.

Значение: GPS‑режим измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Получает или задает строку GPS, содержащую название метода, используемого для определения местоположения.

Значение: GPS‑строка, содержащая название метода, используемого для определения местоположения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Получает или задает спутники GPS, используемые для измерений.

Значение: GPS‑спутники, используемые для измерений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Получает или задает скорость перемещения GPS‑приемника.

Значение: Скорость перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Получает или задает единицу, используемую для выражения скорости перемещения GPS‑приемника.

Значение: Единица измерения скорости перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Получает или задает статус GPS‑приемника при записи изображения.

Значение: Состояние GPS‑приёмника при записи изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Получает или задает теги, которые относятся только к разделу GPS.

Значение: GPS‑теги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Получает или задает время GPS в формате UTC (координированное всемирное время).

Значение: GPS‑время в формате UTC (координированное всемирное время).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Получает или задает направление перемещения GPS‑приемника.

Значение: Направление перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Получает или задает ссылку, указывающую направление перемещения GPS‑приемника.

Значение: Ссылка, указывающая направление перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Получает или задает идентификатор версии GPS.

Значение: Идентификатор версии GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Получает или задает степень общей регулировки усиления изображения.

Значение: Степень общей регулировки усиления изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Получает или задает гамму.

Значение: Значение гаммы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Получает или задает скорость ISO.

Значение: ISO‑скорость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Получает или задает значение yyy широты скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: Значение ISO‑speed latitude yyy камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен быть записан без ISOSpeed и ISOSpeedLatitudezzz.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Получает или задает значение zzz широты скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: Значение ISO‑speed latitude zzz камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен записываться без ISOSpeed и ISOSpeedLatitudeyyy

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Получает или задает уникальный идентификатор изображения.

Значение: Уникальный идентификатор изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Получает или задает производителя объектива.

Значение: Производитель объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Получает или задает модель объектива.

Значение: Модель объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Получает или задает серийный номер объектива.

Значение: Серийный номер объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Получает или задает спецификацию объектива.

Значение: Спецификация объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Получает или задает источник света.

Значение: Источник света.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Задает производителя записывающего оборудования.

Значение: Производитель записывающего оборудования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | производитель записывающего оборудования. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Получает или задает необработанные данные примечаний производителя.

Значение: Необработанные данные MakerNote.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Получает или задает значение максимальной диафрагмы.

Значение: Максимальное значение диафрагмы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Получает или задает режим измерения экспозиции.

Значение: Режим измерения экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524.

Значение: Опто-электрическая функция преобразования (OECF), указанная в ISO 14524.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Получает или задает фоточувствительность.

Значение: Фотографическая чувствительность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Получает или задает размер пикселя по оси X.

Значение: Размер пикселя по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Получает или задает размер пикселя по оси Y.

Значение: Размер пикселя по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Получает или задает все теги EXIF (включая общие и GPS-теги).

Значение: Теги EXIF (включая общие и GPS-теги).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Получает или задает рекомендованный индекс экспозиции.

Значение: Рекомендованный индекс экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Получает или задает связанный звуковой файл.

Значение: Связанный звуковой файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Получает или задает насыщенность.

Значение: Насыщенность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Получает или задает тип захвата сцены.

Значение: Тип захвата сцены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Получает или задает тип сцены.

Значение: Тип сцены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Получает или задает метод измерения.

Значение: Метод измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Получает или задает тип чувствительности.

Значение: Тип чувствительности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Получает или задает резкость.

Значение: Резкость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Получает или задает значение скорости затвора.

Значение: Значение скорости затвора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Получает или задает отклик пространственной частоты.

Значение: Пространственная частотная характеристика.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Получает или задает спектральную чувствительность.

Значение: Спектральная чувствительность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Задает стандартную чувствительность вывода

Значение: Стандартная выходная чувствительность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Получает или задает область объекта.

Значение: Область объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Получает или задает расстояние до объекта.

Значение: Расстояние до объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Получает или задает диапазон расстояний до объекта.

Значение: Диапазон расстояний до объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Получает или задает расположение объекта.

Значение: Положение объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Получает или задает доли секунды для тега DateTime.

Значение: Доли секунды для тега DateTime.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Получает или задает доли секунды для тега DateTimeDigitized.

Значение: Доли секунды для тега DateTimeDigitized.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Получает или задает доли секунды для тега DateTimeOriginal.

Значение: Доли секунды для тега DateTimeOriginal.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Получает или задает комментарий пользователя.

Значение: Комментарий пользователя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Получает или задает баланс белого.

Значение: Баланс белого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Получает или задает хроматичность белой точки изображения.

Значение: Хроматичность белой точки изображения.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

