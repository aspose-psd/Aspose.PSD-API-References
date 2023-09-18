---
title: ExifData
second_title: Aspose.PSD for Java API Reference
description: EXIF data container.
type: docs
weight: 10
url: /java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

EXIF data container.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExifData()](#ExifData--) | Initializes a new instance of the  ExifData  class. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initializes a new instance of the  ExifData  class with data from array. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Initializes a new instance of the  ExifData  class with data from array. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Gets or sets the aperture value. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Gets or sets camera body serial number. |
| [getBrightnessValue()](#getBrightnessValue--) | Gets or sets the brightness value. |
| [getCFAPattern()](#getCFAPattern--) | Gets or sets the CFA pattern. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Gets or sets camera owner name |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Gets or sets the color space. |
| [getCommonTags()](#getCommonTags--) | Gets or sets tags, which belong to common section. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Gets or sets the components configuration. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Gets or sets the compressed bits per pixel. |
| [getContrast()](#getContrast--) | Gets or sets the contrast. |
| [getCustomRendered()](#getCustomRendered--) | Gets or sets the custom rendered. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Gets or sets the date time digitized. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Gets or sets the date time original. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Gets or sets device settings description |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Gets or sets the digital zoom ratio. |
| [getExifTags()](#getExifTags--) | Gets or sets tags which belong to EXIF section only. |
| [getExifVersion()](#getExifVersion--) | Gets or sets the EXIF version. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Gets or sets the exposure bias value. |
| [getExposureIndex()](#getExposureIndex--) | Gets or sets the exposure index. |
| [getExposureMode()](#getExposureMode--) | Gets or sets the exposure mode. |
| [getExposureProgram()](#getExposureProgram--) | Gets or sets the exposure program. |
| [getExposureTime()](#getExposureTime--) | Gets or sets the exposure time. |
| [getFNumber()](#getFNumber--) | Gets or sets the F-number. |
| [getFileSource()](#getFileSource--) | Gets or sets the file source type. |
| [getFlash()](#getFlash--) | Gets or sets the flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Gets or sets the flash energy. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Gets or sets the flash pix version. |
| [getFocalLength()](#getFocalLength--) | Gets or sets the focal length. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Gets or sets the focal length in 35 mm film. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Gets or sets the focal plane resolution unit. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Gets or sets the focal plane x resolution. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Gets or sets the focal plane y resolution. |
| [getGPSAltitude()](#getGPSAltitude--) | Gets or sets the GPS altitude. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Gets or sets the GPS altitude used as the reference altitude. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Gets or sets the GPS area information. |
| [getGPSDOP()](#getGPSDOP--) | Gets or sets the GPS DOP (data degree of precision). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Gets or sets the GPS character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Gets or sets the GPS bearing to the destination point. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Gets or sets the GPS reference used for giving the bearing to the destination point. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Gets or sets the GPS distance to the destination point. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Gets or sets the GPS unit used to express the distance to the destination point. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Gets or sets the GPS latitude of the destination point. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Gets or sets the GPS longitude of the destination point. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude. |
| [getGPSDifferential()](#getGPSDifferential--) | Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Gets or sets the GPS direction of the image when it was captured. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Gets or sets the GPS reference for giving the direction of the image when it is captured. |
| [getGPSLatitude()](#getGPSLatitude--) | Gets or sets the GPS latitude. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Gets or sets the GPS latitude is north or south latitude. |
| [getGPSLongitude()](#getGPSLongitude--) | Gets or sets the GPS longitude. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Gets or sets the GPS longitude is east or west longitude. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Gets or sets the GPS geodetic survey data used by the GPS receiver. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Gets or sets the GPS measurement mode. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Gets or sets the GPS character string recording the name of the method used for location finding. |
| [getGPSSatellites()](#getGPSSatellites--) | Gets or sets the GPS satellites used for measurements. |
| [getGPSSpeed()](#getGPSSpeed--) | Gets or sets the speed of GPS receiver movement. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Gets or sets the unit used to express the GPS receiver speed of movement. |
| [getGPSStatus()](#getGPSStatus--) | Gets or sets the status of the GPS receiver when the image is recorded. |
| [getGPSTags()](#getGPSTags--) | Gets or sets tags, which belong to GPS section only. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Gets or sets the GPS time as UTC (Coordinated Universal Time). |
| [getGPSTrack()](#getGPSTrack--) | Gets or sets direction of GPS receiver movement. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Gets or sets the reference for giving the direction of GPS receiver movement. |
| [getGPSVersionID()](#getGPSVersionID--) | Gets or sets the GPS version identifier. |
| [getGainControl()](#getGainControl--) | Gets or sets the degree of overall image gain adjustment. |
| [getGamma()](#getGamma--) | Gets or sets the gamma. |
| [getISOSpeed()](#getISOSpeed--) | Gets or sets ISO speed |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Gets or sets the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Gets or sets the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232. |
| [getImageUniqueID()](#getImageUniqueID--) | Gets or sets the image unique identifier. |
| [getLensMake()](#getLensMake--) | Gets or sets the maker of lens. |
| [getLensModel()](#getLensModel--) | Gets or sets the lens model. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Gets or sets the lens serial number. |
| [getLensSpecification()](#getLensSpecification--) | Gets or sets the lens specification |
| [getLightSource()](#getLightSource--) | Gets or sets the light source. |
| [getMake()](#getMake--) | Gets the manufacturer of the recording equipment. |
| [getMakerNoteData()](#getMakerNoteData--) | Gets the maker note data. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Gets or sets the maker note raw data. |
| [getMakerNotes()](#getMakerNotes--) | Gets the maker notes. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Gets or sets the maximum aperture value. |
| [getMeteringMode()](#getMeteringMode--) | Gets or sets the metering mode. |
| [getOECF()](#getOECF--) | Gets or sets the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Gets or sets the photographic sensitivity. |
| [getPixelXDimension()](#getPixelXDimension--) | Gets or sets the pixel x dimension. |
| [getPixelYDimension()](#getPixelYDimension--) | Gets or sets the pixel y dimension. |
| [getProperties()](#getProperties--) | Gets or sets all the EXIF tags (including common and GPS tags). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Gets or sets the recommended exposure index. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Gets or sets the related sound file. |
| [getSaturation()](#getSaturation--) | Gets or sets the saturation. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Gets or sets the scene capture type. |
| [getSceneType()](#getSceneType--) | Gets or sets the scene type. |
| [getSensingMethod()](#getSensingMethod--) | Gets or sets the sensing method. |
| [getSensitivityType()](#getSensitivityType--) | Gets or sets the sensitivity type. |
| [getSharpness()](#getSharpness--) | Gets or sets the sharpness. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Gets or sets the shutter speed value. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Gets or sets the spatial frequency response. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Gets or sets the spectral sensitivity. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Gets standard output sensitivity |
| [getSubjectArea()](#getSubjectArea--) | Gets or sets the subject area. |
| [getSubjectDistance()](#getSubjectDistance--) | Gets or sets the subject distance. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Gets or sets the subject distance range. |
| [getSubjectLocation()](#getSubjectLocation--) | Gets or sets the subject location. |
| [getSubsecTime()](#getSubsecTime--) | Gets or sets the fractions of seconds for the DateTime tag. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Gets or sets the fractions of seconds for the DateTimeDigitized tag. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Gets or sets the fractions of seconds for the DateTimeOriginal tag. |
| [getUserComment()](#getUserComment--) | Gets or sets the user comment. |
| [getWhiteBalance()](#getWhiteBalance--) | Gets or sets the white balance. |
| [getWhitePoint()](#getWhitePoint--) | Gets or sets the chromaticity of the white point of the image. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Gets or sets a value indicating whether the stream EXIF data created from is big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Remove tag from container |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the aperture value. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Gets or sets a value indicating whether the stream EXIF data created from is big endian. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Gets or sets camera body serial number. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Gets or sets the brightness value. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Gets or sets the CFA pattern. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Gets or sets camera owner name |
| [setColorSpace(int value)](#setColorSpace-int-) | Gets or sets the color space. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gets or sets tags, which belong to common section. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Gets or sets the components configuration. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the compressed bits per pixel. |
| [setContrast(int value)](#setContrast-int-) | Gets or sets the contrast. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Gets or sets the custom rendered. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Gets or sets the date time digitized. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Gets or sets the date time original. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Gets or sets device settings description |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the digital zoom ratio. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gets or sets tags which belong to EXIF section only. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Gets or sets the EXIF version. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Gets or sets the exposure bias value. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the exposure index. |
| [setExposureMode(int value)](#setExposureMode-int-) | Gets or sets the exposure mode. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Gets or sets the exposure program. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the exposure time. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the F-number. |
| [setFileSource(byte value)](#setFileSource-byte-) | Gets or sets the file source type. |
| [setFlash(int value)](#setFlash-int-) | Gets or sets the flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the flash energy. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Gets or sets the flash pix version. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the focal length. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Gets or sets the focal length in 35 mm film. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Gets or sets the focal plane resolution unit. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the focal plane x resolution. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the focal plane y resolution. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the GPS altitude. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Gets or sets the GPS altitude used as the reference altitude. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Gets or sets the GPS area information. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the GPS DOP (data degree of precision). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Gets or sets the GPS character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the GPS bearing to the destination point. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Gets or sets the GPS reference used for giving the bearing to the destination point. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the GPS distance to the destination point. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Gets or sets the GPS unit used to express the distance to the destination point. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the GPS latitude of the destination point. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the GPS longitude of the destination point. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the GPS direction of the image when it was captured. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Gets or sets the GPS reference for giving the direction of the image when it is captured. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the GPS latitude. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Gets or sets the GPS latitude is north or south latitude. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the GPS longitude. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Gets or sets the GPS longitude is east or west longitude. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Gets or sets the GPS geodetic survey data used by the GPS receiver. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Gets or sets the GPS measurement mode. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Gets or sets the GPS character string recording the name of the method used for location finding. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Gets or sets the GPS satellites used for measurements. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the speed of GPS receiver movement. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Gets or sets the unit used to express the GPS receiver speed of movement. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Gets or sets the status of the GPS receiver when the image is recorded. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gets or sets tags, which belong to GPS section only. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the GPS time as UTC (Coordinated Universal Time). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Gets or sets direction of GPS receiver movement. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Gets or sets the reference for giving the direction of GPS receiver movement. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Gets or sets the GPS version identifier. |
| [setGainControl(int value)](#setGainControl-int-) | Gets or sets the degree of overall image gain adjustment. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Gets or sets ISO speed |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Gets or sets the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Gets or sets the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Gets or sets the image unique identifier. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Gets or sets the maker of lens. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Gets or sets the lens model. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Gets or sets the lens serial number. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the lens specification |
| [setLightSource(int value)](#setLightSource-int-) | Gets or sets the light source. |
| [setMake(String value)](#setMake-java.lang.String-) | Sets the manufacturer of the recording equipment. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Gets or sets the maker note raw data. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the maximum aperture value. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Gets or sets the metering mode. |
| [setOECF(byte[] value)](#setOECF-byte---) | Gets or sets the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Gets or sets the photographic sensitivity. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Gets or sets the pixel x dimension. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Gets or sets the pixel y dimension. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gets or sets all the EXIF tags (including common and GPS tags). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Gets or sets the recommended exposure index. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Gets or sets the related sound file. |
| [setSaturation(int value)](#setSaturation-int-) | Gets or sets the saturation. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Gets or sets the scene capture type. |
| [setSceneType(byte value)](#setSceneType-byte-) | Gets or sets the scene type. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Gets or sets the sensing method. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Gets or sets the sensitivity type. |
| [setSharpness(int value)](#setSharpness-int-) | Gets or sets the sharpness. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Gets or sets the shutter speed value. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Gets or sets the spatial frequency response. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Gets or sets the spectral sensitivity. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Sets standard output sensitivity |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Gets or sets the subject area. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the subject distance. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Gets or sets the subject distance range. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Gets or sets the subject location. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Gets or sets the fractions of seconds for the DateTime tag. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Gets or sets the fractions of seconds for the DateTimeDigitized tag. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Gets or sets the fractions of seconds for the DateTimeOriginal tag. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Gets or sets the user comment. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Gets or sets the white balance. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the chromaticity of the white point of the image. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


Initializes a new instance of the  ExifData  class.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Initializes a new instance of the  ExifData  class with data from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Array of EXIF tags together with common and GPS tags. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initializes a new instance of the  ExifData  class with data from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The common tags. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The EXIF tags. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The GPS tags. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Gets or sets the aperture value.

Value: The aperture value.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Gets or sets camera body serial number.

Value: The body serial number.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Gets or sets the brightness value.

Value: The brightness value.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Gets or sets the CFA pattern.

Value: The CFA pattern.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Gets or sets camera owner name

Value: The name of the camera owner.

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


Gets or sets the color space.

Value: The color space.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Gets or sets tags, which belong to common section. This applies only to jpeg images, in tiff format tiffOptions are being used instead

Value: The common section tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Gets or sets the components configuration.

Value: The components configuration.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Gets or sets the compressed bits per pixel.

Value: The compressed bits per pixel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


Gets or sets the contrast.

Value: The contrast.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Gets or sets the custom rendered.

Value: The custom rendered.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Gets or sets the date time digitized.

Value: The date time digitized.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Gets or sets the date time original.

Value: The date time original.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Gets or sets device settings description

Value: The device setting description.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Gets or sets the digital zoom ratio.

Value: The digital zoom ratio.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Gets or sets tags which belong to EXIF section only.

Value: The EXIF section tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Gets or sets the EXIF version.

Value: The EXIF version.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Gets or sets the exposure bias value.

Value: The exposure bias value.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Gets or sets the exposure index.

Value: The index of the exposure.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Gets or sets the exposure mode.

Value: The exposure mode.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Gets or sets the exposure program.

Value: The exposure program.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Gets or sets the exposure time.

Value: The exposure time.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Gets or sets the F-number.

Value: The F-number.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Gets or sets the file source type.

Value: The file source type.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Gets or sets the flash.

Value: The flash.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Gets or sets the flash energy.

Value: The flash energy.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Gets or sets the flash pix version.

Value: The flash pix version.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Gets or sets the focal length.

Value: The length of the focal.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Gets or sets the focal length in 35 mm film.

Value: The focal length in35 mm film.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Gets or sets the focal plane resolution unit.

Value: The focal plane resolution unit.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Gets or sets the focal plane x resolution.

Value: The focal plane x resolution.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Gets or sets the focal plane y resolution.

Value: The focal plane y resolution.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Gets or sets the GPS altitude.

Value: The GPS altitude.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Gets or sets the GPS altitude used as the reference altitude.

Value: The GPS altitude used as the reference altitude.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Gets or sets the GPS area information.

Value: The GPS area information.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Gets or sets the GPS DOP (data degree of precision).

Value: The GPS DOP (data degree of precision).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Gets or sets the GPS character string recording date and time information relative to UTC (Coordinated Universal Time).

Value: The GPS character string recording date and time information relative to UTC (Coordinated Universal Time).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Gets or sets the GPS bearing to the destination point.

Value: The GPS bearing to the destination point.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Gets or sets the GPS reference used for giving the bearing to the destination point.

Value: The GPS reference used for giving the bearing to the destination point.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Gets or sets the GPS distance to the destination point.

Value: The GPS distance to the destination point.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Gets or sets the GPS unit used to express the distance to the destination point.

Value: The GPS unit used to express the distance to the destination point.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Gets or sets the GPS latitude of the destination point.

Value: The GPS latitude of the destination point.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude.

Value: The GPS value which indicates whether the latitude of the destination point is north or south latitude.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Gets or sets the GPS longitude of the destination point.

Value: The GPS longitude of the destination point.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude.

Value: The GPS value which indicates whether the longitude of the destination point is east or west longitude.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver.

Value: The GPS value which indicates whether differential correction is applied to the GPS receiver.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Gets or sets the GPS direction of the image when it was captured.

Value: The GPS direction of the image when it was captured.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Gets or sets the GPS reference for giving the direction of the image when it is captured.

Value: The GPS reference for giving the direction of the image when it is captured.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Gets or sets the GPS latitude.

Value: The GPS latitude.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Gets or sets the GPS latitude is north or south latitude.

Value: The GPS latitude is north or south latitude.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Gets or sets the GPS longitude.

Value: The GPS longitude.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Gets or sets the GPS longitude is east or west longitude.

Value: The GPS longitude is east or west longitude.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Gets or sets the GPS geodetic survey data used by the GPS receiver.

Value: The GPS geodetic survey data used by the GPS receiver.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Gets or sets the GPS measurement mode.

Value: The GPS measurement mode.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Gets or sets the GPS character string recording the name of the method used for location finding.

Value: The GPS character string recording the name of the method used for location finding.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Gets or sets the GPS satellites used for measurements.

Value: The GPS satellites used for measurements.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Gets or sets the speed of GPS receiver movement.

Value: The speed of GPS receiver movement.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Gets or sets the unit used to express the GPS receiver speed of movement.

Value: The unit used to express the GPS receiver speed of movement.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Gets or sets the status of the GPS receiver when the image is recorded.

Value: The status of the GPS receiver when the image is recorded.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Gets or sets tags, which belong to GPS section only.

Value: The GPS tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Gets or sets the GPS time as UTC (Coordinated Universal Time).

Value: The GPS time as UTC (Coordinated Universal Time).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Gets or sets direction of GPS receiver movement.

Value: The direction of GPS receiver movement.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Gets or sets the reference for giving the direction of GPS receiver movement.

Value: The reference for giving the direction of GPS receiver movement.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Gets or sets the GPS version identifier.

Value: The GPS version identifier.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Gets or sets the degree of overall image gain adjustment.

Value: The degree of overall image gain adjustment.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Gets or sets the gamma.

Value: The gamma value.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Gets or sets ISO speed

Value: The ISO speed.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Gets or sets the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232.

Value: The ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232.

This tag shall not be recorded without ISOSpeed and ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Gets or sets the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232.

Value: The ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232.

This tag shall not be recorded without ISOSpeed and ISOSpeedLatitudeyyy

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Gets or sets the image unique identifier.

Value: The image unique identifier.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Gets or sets the maker of lens.

Value: The lens maker.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Gets or sets the lens model.

Value: The lens model.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Gets or sets the lens serial number.

Value: The lens serial number.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Gets or sets the lens specification

Value: The lens specification.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Gets or sets the light source.

Value: The light source.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Gets the manufacturer of the recording equipment.

Value: The manufacturer of the recording equipment.

**Returns:**
java.lang.String - the manufacturer of the recording equipment.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Gets the maker note data.

Value: The maker note data.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Gets or sets the maker note raw data.

Value: The maker note raw data.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Gets the maker notes.

Value: The maker notes.

**Returns:**
com.aspose.psd.exif.MakerNote[] - the maker notes.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Gets or sets the maximum aperture value.

Value: The maximum aperture value.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Gets or sets the metering mode.

Value: The metering mode.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Gets or sets the Opto-Electric Conversion Function (OECF) specified in ISO 14524.

Value: The Opto-Electric Conversion Function (OECF) specified in ISO 14524.

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Gets or sets the photographic sensitivity.

Value: The photographic sensitivity.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Gets or sets the pixel x dimension.

Value: The pixel x dimension.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Gets or sets the pixel y dimension.

Value: The pixel y dimension.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Gets or sets all the EXIF tags (including common and GPS tags).

Value: The EXIF tags (including common and GPS tags).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Gets or sets the recommended exposure index.

Value: The recommended exposure index.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Gets or sets the related sound file.

Value: The related sound file.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Gets or sets the saturation.

Value: The saturation.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Gets or sets the scene capture type.

Value: The type of the scene capture.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Gets or sets the scene type.

Value: The type of the scene.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Gets or sets the sensing method.

Value: The sensing method.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Gets or sets the sensitivity type.

Value: The type of the sensitivity.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Gets or sets the sharpness.

Value: The sharpness.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Gets or sets the shutter speed value.

Value: The shutter speed value.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Gets or sets the spatial frequency response.

Value: The spatial frequency response.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Gets or sets the spectral sensitivity.

Value: The spectral sensitivity.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Gets standard output sensitivity

Value: The standard output sensitivity.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Gets or sets the subject area.

Value: The subject area.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Gets or sets the subject distance.

Value: The subject distance.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Gets or sets the subject distance range.

Value: The subject distance range.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Gets or sets the subject location.

Value: The subject location.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Gets or sets the fractions of seconds for the DateTime tag.

Value: The fractions of seconds for the DateTime tag.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Gets or sets the fractions of seconds for the DateTimeDigitized tag.

Value: The fractions of seconds for the DateTimeDigitized tag.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Gets or sets the fractions of seconds for the DateTimeOriginal tag.

Value: The fractions of seconds for the DateTimeOriginal tag.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Gets or sets the user comment.

Value: The user comment.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Gets or sets the white balance.

Value: The white balance.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Gets or sets the chromaticity of the white point of the image.

Value: The chromaticity of the white point of the image.

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


Gets or sets a value indicating whether the stream EXIF data created from is big endian.

Value:  true  if the stream EXIF data created from is big endian; otherwise,  false .

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


Remove tag from container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag identifier to remove. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Gets or sets the aperture value.

Value: The aperture value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Gets or sets a value indicating whether the stream EXIF data created from is big endian.

Value:  true  if the stream EXIF data created from is big endian; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Gets or sets camera body serial number.

Value: The body serial number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Gets or sets the brightness value.

Value: The brightness value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Gets or sets the CFA pattern.

Value: The CFA pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Gets or sets camera owner name

Value: The name of the camera owner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Gets or sets the color space.

Value: The color space.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Gets or sets tags, which belong to common section. This applies only to jpeg images, in tiff format tiffOptions are being used instead

Value: The common section tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Gets or sets the components configuration.

Value: The components configuration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Gets or sets the compressed bits per pixel.

Value: The compressed bits per pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Gets or sets the contrast.

Value: The contrast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Gets or sets the custom rendered.

Value: The custom rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Gets or sets the date time digitized.

Value: The date time digitized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Gets or sets the date time original.

Value: The date time original.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Gets or sets device settings description

Value: The device setting description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Gets or sets the digital zoom ratio.

Value: The digital zoom ratio.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Gets or sets tags which belong to EXIF section only.

Value: The EXIF section tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Gets or sets the EXIF version.

Value: The EXIF version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Gets or sets the exposure bias value.

Value: The exposure bias value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Gets or sets the exposure index.

Value: The index of the exposure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Gets or sets the exposure mode.

Value: The exposure mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Gets or sets the exposure program.

Value: The exposure program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Gets or sets the exposure time.

Value: The exposure time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Gets or sets the F-number.

Value: The F-number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Gets or sets the file source type.

Value: The file source type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Gets or sets the flash.

Value: The flash.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Gets or sets the flash energy.

Value: The flash energy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Gets or sets the flash pix version.

Value: The flash pix version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Gets or sets the focal length.

Value: The length of the focal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Gets or sets the focal length in 35 mm film.

Value: The focal length in35 mm film.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Gets or sets the focal plane resolution unit.

Value: The focal plane resolution unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Gets or sets the focal plane x resolution.

Value: The focal plane x resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Gets or sets the focal plane y resolution.

Value: The focal plane y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Gets or sets the GPS altitude.

Value: The GPS altitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Gets or sets the GPS altitude used as the reference altitude.

Value: The GPS altitude used as the reference altitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Gets or sets the GPS area information.

Value: The GPS area information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Gets or sets the GPS DOP (data degree of precision).

Value: The GPS DOP (data degree of precision).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Gets or sets the GPS character string recording date and time information relative to UTC (Coordinated Universal Time).

Value: The GPS character string recording date and time information relative to UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Gets or sets the GPS bearing to the destination point.

Value: The GPS bearing to the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Gets or sets the GPS reference used for giving the bearing to the destination point.

Value: The GPS reference used for giving the bearing to the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Gets or sets the GPS distance to the destination point.

Value: The GPS distance to the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Gets or sets the GPS unit used to express the distance to the destination point.

Value: The GPS unit used to express the distance to the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Gets or sets the GPS latitude of the destination point.

Value: The GPS latitude of the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude.

Value: The GPS value which indicates whether the latitude of the destination point is north or south latitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Gets or sets the GPS longitude of the destination point.

Value: The GPS longitude of the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude.

Value: The GPS value which indicates whether the longitude of the destination point is east or west longitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver.

Value: The GPS value which indicates whether differential correction is applied to the GPS receiver.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Gets or sets the GPS direction of the image when it was captured.

Value: The GPS direction of the image when it was captured.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Gets or sets the GPS reference for giving the direction of the image when it is captured.

Value: The GPS reference for giving the direction of the image when it is captured.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Gets or sets the GPS latitude.

Value: The GPS latitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Gets or sets the GPS latitude is north or south latitude.

Value: The GPS latitude is north or south latitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Gets or sets the GPS longitude.

Value: The GPS longitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Gets or sets the GPS longitude is east or west longitude.

Value: The GPS longitude is east or west longitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Gets or sets the GPS geodetic survey data used by the GPS receiver.

Value: The GPS geodetic survey data used by the GPS receiver.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Gets or sets the GPS measurement mode.

Value: The GPS measurement mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Gets or sets the GPS character string recording the name of the method used for location finding.

Value: The GPS character string recording the name of the method used for location finding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Gets or sets the GPS satellites used for measurements.

Value: The GPS satellites used for measurements.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Gets or sets the speed of GPS receiver movement.

Value: The speed of GPS receiver movement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Gets or sets the unit used to express the GPS receiver speed of movement.

Value: The unit used to express the GPS receiver speed of movement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Gets or sets the status of the GPS receiver when the image is recorded.

Value: The status of the GPS receiver when the image is recorded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Gets or sets tags, which belong to GPS section only.

Value: The GPS tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Gets or sets the GPS time as UTC (Coordinated Universal Time).

Value: The GPS time as UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Gets or sets direction of GPS receiver movement.

Value: The direction of GPS receiver movement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Gets or sets the reference for giving the direction of GPS receiver movement.

Value: The reference for giving the direction of GPS receiver movement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Gets or sets the GPS version identifier.

Value: The GPS version identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Gets or sets the degree of overall image gain adjustment.

Value: The degree of overall image gain adjustment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Gets or sets the gamma.

Value: The gamma value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Gets or sets ISO speed

Value: The ISO speed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Gets or sets the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232.

Value: The ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232.

This tag shall not be recorded without ISOSpeed and ISOSpeedLatitudezzz

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Gets or sets the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232.

Value: The ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232.

This tag shall not be recorded without ISOSpeed and ISOSpeedLatitudeyyy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Gets or sets the image unique identifier.

Value: The image unique identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Gets or sets the maker of lens.

Value: The lens maker.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Gets or sets the lens model.

Value: The lens model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Gets or sets the lens serial number.

Value: The lens serial number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Gets or sets the lens specification

Value: The lens specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Gets or sets the light source.

Value: The light source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Sets the manufacturer of the recording equipment.

Value: The manufacturer of the recording equipment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the manufacturer of the recording equipment. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Gets or sets the maker note raw data.

Value: The maker note raw data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Gets or sets the maximum aperture value.

Value: The maximum aperture value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Gets or sets the metering mode.

Value: The metering mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Gets or sets the Opto-Electric Conversion Function (OECF) specified in ISO 14524.

Value: The Opto-Electric Conversion Function (OECF) specified in ISO 14524.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Gets or sets the photographic sensitivity.

Value: The photographic sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Gets or sets the pixel x dimension.

Value: The pixel x dimension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Gets or sets the pixel y dimension.

Value: The pixel y dimension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Gets or sets all the EXIF tags (including common and GPS tags).

Value: The EXIF tags (including common and GPS tags).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Gets or sets the recommended exposure index.

Value: The recommended exposure index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Gets or sets the related sound file.

Value: The related sound file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Gets or sets the saturation.

Value: The saturation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Gets or sets the scene capture type.

Value: The type of the scene capture.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Gets or sets the scene type.

Value: The type of the scene.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Gets or sets the sensing method.

Value: The sensing method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Gets or sets the sensitivity type.

Value: The type of the sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Gets or sets the sharpness.

Value: The sharpness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Gets or sets the shutter speed value.

Value: The shutter speed value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Gets or sets the spatial frequency response.

Value: The spatial frequency response.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Gets or sets the spectral sensitivity.

Value: The spectral sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Sets standard output sensitivity

Value: The standard output sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Gets or sets the subject area.

Value: The subject area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Gets or sets the subject distance.

Value: The subject distance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Gets or sets the subject distance range.

Value: The subject distance range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Gets or sets the subject location.

Value: The subject location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Gets or sets the fractions of seconds for the DateTime tag.

Value: The fractions of seconds for the DateTime tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Gets or sets the fractions of seconds for the DateTimeDigitized tag.

Value: The fractions of seconds for the DateTimeDigitized tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Gets or sets the fractions of seconds for the DateTimeOriginal tag.

Value: The fractions of seconds for the DateTimeOriginal tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Gets or sets the user comment.

Value: The user comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Gets or sets the white balance.

Value: The white balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Gets or sets the chromaticity of the white point of the image.

Value: The chromaticity of the white point of the image.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

