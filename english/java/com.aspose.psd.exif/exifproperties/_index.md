---
title: ExifProperties
second_title: Aspose.PSD for Java API Reference
description: Exif tags list
type: docs
weight: 11
url: /java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif tags list
## Fields

| Field | Description |
| --- | --- |
| [ApertureValue](#ApertureValue) | The lens aperture value. |
| [Artist](#Artist) | This tag records the name of the camera owner, photographer or image creator. |
| [BitsPerSample](#BitsPerSample) | The number of bits per image component. |
| [BodySerialNumber](#BodySerialNumber) | Contains camera body serial number |
| [BrightnessValue](#BrightnessValue) | The brightness value. |
| [CFAPattern](#CFAPattern) | Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. |
| [CameraOwnerName](#CameraOwnerName) | Contains camera owner name |
| [ColorSpace](#ColorSpace) | The color space information tag (ColorSpace) is always recorded as the color space specifier. |
| [ComponentsConfiguration](#ComponentsConfiguration) | The components configuration. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Specific to compressed data; states the compressed bits per pixel. |
| [Compression](#Compression) | The compression scheme used for the image data. |
| [Contrast](#Contrast) | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| [Copyright](#Copyright) | Copyright information. |
| [CustomRendered](#CustomRendered) | This tag indicates the use of special processing on image data, such as rendering geared to output. |
| [DateTime](#DateTime) | The date and time of image creation. |
| [DateTimeDigitized](#DateTimeDigitized) | The date time digitized. |
| [DateTimeOriginal](#DateTimeOriginal) | The date and time when the original image data was generated. |
| [DeviceSettingDescription](#DeviceSettingDescription) | This tag indicates information on the picture-taking conditions of a particular camera model. |
| [DigitalZoomRatio](#DigitalZoomRatio) | This tag indicates the digital zoom ratio when the image was shot. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | A pointer to the Exif IFD. |
| [ExifVersion](#ExifVersion) | The exif version. |
| [ExposureBiasValue](#ExposureBiasValue) | The exposure bias value. |
| [ExposureIndex](#ExposureIndex) | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| [ExposureMode](#ExposureMode) | This tag indicates the exposure mode set when the image was shot. |
| [ExposureProgram](#ExposureProgram) | The class of the program used by the camera to set exposure when the picture is taken. |
| [ExposureTime](#ExposureTime) | Exposure time, given in seconds. |
| [FNumber](#FNumber) | The F number. |
| [FileSource](#FileSource) | The file source. |
| [Flash](#Flash) | Indicates the status of flash when the image was shot. |
| [FlashEnergy](#FlashEnergy) | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds(BCPS). |
| [FlashpixVersion](#FlashpixVersion) | The Flashpix format version supported by a FPXR file. |
| [FocalLength](#FocalLength) | The actual focal length of the lens, in mm. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| [GPSAltitude](#GPSAltitude) | Indicates the altitude based on the reference in GPSAltitudeRef. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indicates the altitude used as the reference altitude. |
| [GPSAreaInformation](#GPSAreaInformation) | A character string recording the name of the GPS area. |
| [GPSDOP](#GPSDOP) | Indicates the GPS DOP (data degree of precision). |
| [GPSDateStamp](#GPSDateStamp) | A character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [GPSDestBearing](#GPSDestBearing) | Indicates the bearing to the destination point. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indicates the reference used for giving the bearing to the destination point. |
| [GPSDestDistance](#GPSDestDistance) | Indicates the distance to the destination point. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indicates the unit used to express the distance to the destination point. |
| [GPSDestLatitude](#GPSDestLatitude) | Indicates the latitude of the destination point. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indicates whether the latitude of the destination point is north or south latitude. |
| [GPSDestLongitude](#GPSDestLongitude) | Indicates the longitude of the destination point. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indicates whether the longitude of the destination point is east or west longitude. |
| [GPSDifferential](#GPSDifferential) | Indicates whether differential correction is applied to the GPS receiver. |
| [GPSIfdPointer](#GPSIfdPointer) | The gps ifd pointer. |
| [GPSImgDirection](#GPSImgDirection) | Indicates the direction of the image when it was captured. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indicates the reference for giving the direction of the image when it is captured. |
| [GPSLatitude](#GPSLatitude) | Indicates the latitude. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indicates whether the latitude is north or south latitude. |
| [GPSLongitude](#GPSLongitude) | Indicates the longitude. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indicates whether the longitude is east or west longitude. |
| [GPSMapDatum](#GPSMapDatum) | Indicates the geodetic survey data used by the GPS receiver. |
| [GPSMeasureMode](#GPSMeasureMode) | Indicates the GPS measurement mode. |
| [GPSProcessingMethod](#GPSProcessingMethod) | A character string recording the name of the method used for location finding. |
| [GPSSatellites](#GPSSatellites) | Indicates the GPS satellites used for measurements. |
| [GPSSpeed](#GPSSpeed) | Indicates the speed of GPS receiver movement. |
| [GPSSpeedRef](#GPSSpeedRef) | Indicates the unit used to express the GPS receiver speed of movement. |
| [GPSStatus](#GPSStatus) | Indicates the status of the GPS receiver when the image is recorded. |
| [GPSTimestamp](#GPSTimestamp) | Indicates the time as UTC (Coordinated Universal Time). |
| [GPSTrack](#GPSTrack) | Indicates the direction of GPS receiver movement. |
| [GPSTrackRef](#GPSTrackRef) | Indicates the reference for giving the direction of GPS receiver movement. |
| [GPSVersionID](#GPSVersionID) | Indicates the version of GPSInfoIFD. |
| [GainControl](#GainControl) | This tag indicates the degree of overall image gain adjustment. |
| [Gamma](#Gamma) | Gamma value |
| [ISOSpeed](#ISOSpeed) | Information about iso speed value as defined in ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | This tag indicates ISO speed latitude yyy value as defined in ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | This tag indicates ISO speed latitude zzz value as defined in ISO 12232 |
| [ImageDescription](#ImageDescription) | A character string giving the title of the image. |
| [ImageLength](#ImageLength) | The number of rows of image data. |
| [ImageUniqueID](#ImageUniqueID) | The image unique id. |
| [ImageWidth](#ImageWidth) | The number of columns of image data, equal to the number of pixels per row. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | The offset to the start byte (SOI) of JPEG compressed thumbnail data. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | The number of bytes of JPEG compressed thumbnail data. |
| [LensMake](#LensMake) | This tag records lens manufacturer |
| [LensModel](#LensModel) | This tag records lenss model name and model number |
| [LensSerialNumber](#LensSerialNumber) | This tag records the serial number of interchangable lens |
| [LensSpecification](#LensSpecification) | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length and minimum F number in maximum focal length |
| [LightSource](#LightSource) | The kind light source. |
| [Make](#Make) | The manufacturer of the recording equipment. |
| [MakerNote](#MakerNote) | A tag for manufacturers of Exif writers to record any desired information. |
| [MaxApertureValue](#MaxApertureValue) | The max aperture value. |
| [MeteringMode](#MeteringMode) | The metering mode. |
| [Model](#Model) | The model name or model number of the equipment. |
| [OECF](#OECF) | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| [Orientation](#Orientation) | The image orientation viewed in terms of rows and columns. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indicates the ISO Speed and ISO Latitude of the camera or input device as specified in ISO 12232. |
| [PhotometricInterpretation](#PhotometricInterpretation) | The pixel composition. |
| [PixelXDimension](#PixelXDimension) | Information specific to compressed data. |
| [PixelYDimension](#PixelYDimension) | Information specific to compressed data. |
| [PlanarConfiguration](#PlanarConfiguration) | Indicates whether pixel components are recorded in a chunky or planar format. |
| [PrimaryChromaticities](#PrimaryChromaticities) | The chromaticity of the three primary colors of the image. |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indicates recommended exposure index |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | The reference black point value and reference white point value. |
| [RelatedSoundFile](#RelatedSoundFile) | The related sound file. |
| [ResolutionUnit](#ResolutionUnit) | The unit for measuring XResolution and YResolution. |
| [RowsPerStrip](#RowsPerStrip) | The number of rows per strip. |
| [SamplesPerPixel](#SamplesPerPixel) | The number of components per pixel. |
| [Saturation](#Saturation) | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| [SceneCaptureType](#SceneCaptureType) | This tag indicates the type of scene that was shot. |
| [SceneType](#SceneType) | Indicates the type of scene. |
| [SensingMethod](#SensingMethod) | Indicates the image sensor type on the camera or input device. |
| [SensitivityType](#SensitivityType) | Type of photographic sensitivity |
| [Sharpness](#Sharpness) | This tag indicates the direction of sharpness processing applied by the camera when the image was shot |
| [ShutterSpeedValue](#ShutterSpeedValue) | The shutter speed value. |
| [Software](#Software) | This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233. |
| [SpectralSensitivity](#SpectralSensitivity) | Indicates the spectral sensitivity of each channel of the camera used. |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indicates standard output sensitivity of camera |
| [StripByteCounts](#StripByteCounts) | The total number of bytes in each strip. |
| [StripOffsets](#StripOffsets) | For each strip, the byte offset of that strip. |
| [SubjectArea](#SubjectArea) | This tag indicates the location and area of the main subject in the overall scene. |
| [SubjectDistance](#SubjectDistance) | The distance to the subject, given in meters. |
| [SubjectDistanceRange](#SubjectDistanceRange) | This tag indicates the distance to the subject. |
| [SubjectLocation](#SubjectLocation) | Indicates the location of the main subject in the scene. |
| [SubsecTime](#SubsecTime) | A tag used to record fractions of seconds for the DateTime tag. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| [TransferFunction](#TransferFunction) | A transfer function for the image, described in tabular style. |
| [UserComment](#UserComment) | A tag for Exif users to write keywords or comments on the image besides those in ImageDescription, and without the character code limitations of the ImageDescription tag. |
| [WhiteBalance](#WhiteBalance) | This tag indicates the white balance mode set when the image was shot. |
| [WhitePoint](#WhitePoint) | The chromaticity of the white point of the image. |
| [XResolution](#XResolution) | The number of pixels per ResolutionUnit in the ImageWidth direction. |
| [YCbCrCoefficients](#YCbCrCoefficients) | The matrix coefficients for transformation from RGB to YCbCr image data. |
| [YCbCrPositioning](#YCbCrPositioning) | The position of chrominance components in relation to the luminance component. |
| [YCbCrSubSampling](#YCbCrSubSampling) | The sampling ratio of chrominance components in relation to the luminance component. |
| [YResolution](#YResolution) | The number of pixels per ResolutionUnit in the ImageLength direction. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames()](#getNames--) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues()](#getValues--) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [getValues(Class<?> arg0)](#getValues-java.lang.Class----) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, String arg1)](#isDefined-java.lang.Class----java.lang.String-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [toString(long arg0)](#toString-long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


The lens aperture value.

### Artist {#Artist}
```
public static final int Artist
```


This tag records the name of the camera owner, photographer or image creator. The detailed format is not specified, but it is recommended that the information be written as in the example below for ease of Interoperability. When the field is left blank, it is treated as unknown. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


The number of bits per image component. In this standard each component of the image is 8 bits, so the value for this tag is 8.

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contains camera body serial number

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


The brightness value.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods.

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contains camera owner name

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


The color space information tag (ColorSpace) is always recorded as the color space specifier.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


The components configuration.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Specific to compressed data; states the compressed bits per pixel.

### Compression {#Compression}
```
public static final int Compression
```


The compression scheme used for the image data. When a primary image is JPEG compressed, this designation is not necessary and is omitted.

### Contrast {#Contrast}
```
public static final int Contrast
```


This tag indicates the direction of contrast processing applied by the camera when the image was shot.

### Copyright {#Copyright}
```
public static final int Copyright
```


Copyright information. In this standard the tag is used to indicate both the photographer and editor copyrights. It is the copyright notice of the person or organization claiming rights to the image. The Interoperability copyright statement including date and rights should be written in this field; e.g., "Copyright, John Smith, 19xx. All rights reserved.". In this standard the field records both the photographer and editor copyrights, with each recorded in a separate part of the statement. When there is a clear distinction between the photographer and editor copyrights, these are to be written in the order of photographer followed by editor copyright, separated by NULL (in this case since the statement also ends with a NULL, there are two NULL codes). When only the photographer copyright is given, it is terminated by one NULL code . When only the editor copyright is given, the photographer copyright part consists of one space followed by a terminating NULL code, then the editor copyright is given. When the field is left blank, it is treated as unknown.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


This tag indicates the use of special processing on image data, such as rendering geared to output. When special processing is performed, the reader is expected to disable or minimize any further processing.

### DateTime {#DateTime}
```
public static final int DateTime
```


The date and time of image creation. In Exif standard, it is the date and time the file was changed.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


The date time digitized.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


The date and time when the original image data was generated.

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


This tag indicates information on the picture-taking conditions of a particular camera model. The tag is used only to indicate the picture-taking conditions in the reader.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


A pointer to the Exif IFD. Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


The exif version.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


The exposure bias value.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indicates the exposure index selected on the camera or input device at the time the image is captured.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


The class of the program used by the camera to set exposure when the picture is taken.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Exposure time, given in seconds.

### FNumber {#FNumber}
```
public static final int FNumber
```


The F number.

### FileSource {#FileSource}
```
public static final int FileSource
```


The file source.

### Flash {#Flash}
```
public static final int Flash
```


Indicates the status of flash when the image was shot.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds(BCPS).

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


The Flashpix format version supported by a FPXR file.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


The actual focal length of the lens, in mm.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indicates the altitude based on the reference in GPSAltitudeRef. Altitude is expressed as one RATIONAL value. The reference unit is meters.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indicates the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the GPSAltitude tag.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


A character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indicates the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


A character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indicates the bearing to the destination point. The range of values is from 0.00 to 359.99.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indicates the reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is magnetic direction.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indicates the distance to the destination point.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indicates the unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles and knots.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indicates the latitude of the destination point. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north latitude, and 'S' is south latitude.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indicates the longitude of the destination point. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude, and 'W' is west longitude.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indicates whether differential correction is applied to the GPS receiver.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


The gps ifd pointer.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indicates the direction of the image when it was captured. The range of values is from 0.00 to 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indicates the reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is magnetic direction.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indicates the latitude. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indicates whether the latitude is north or south latitude.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indicates the longitude. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indicates whether the longitude is east or west longitude.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indicates the geodetic survey data used by the GPS receiver.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indicates the GPS measurement mode. - 2- or 3- dimensional.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


A character string recording the name of the method used for location finding. The first byte indicates the character code used, and this is followed by the name of the method.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indicates the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indicates the speed of GPS receiver movement.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indicates the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indicates the status of the GPS receiver when the image is recorded.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indicates the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indicates the direction of GPS receiver movement. The range of values is from 0.00 to 359.99.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indicates the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is magnetic direction.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indicates the version of GPSInfoIFD.

### GainControl {#GainControl}
```
public static final int GainControl
```


This tag indicates the degree of overall image gain adjustment.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma value

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Information about iso speed value as defined in ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


This tag indicates ISO speed latitude yyy value as defined in ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


This tag indicates ISO speed latitude zzz value as defined in ISO 12232

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


A character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


The number of rows of image data.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


The image unique id.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


The number of columns of image data, equal to the number of pixels per row.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


The offset to the start byte (SOI) of JPEG compressed thumbnail data. This is not used for primary image JPEG data.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


The number of bytes of JPEG compressed thumbnail data. This is not used for primary image JPEG data. JPEG thumbnails are not divided but are recorded as a continuous JPEG bitstream from SOI to EOI. Appn and COM markers should not be recorded. Compressed thumbnails must be recorded in no more than 64 Kbytes, including all other data to be recorded in APP1.

### LensMake {#LensMake}
```
public static final int LensMake
```


This tag records lens manufacturer

### LensModel {#LensModel}
```
public static final int LensModel
```


This tag records lenss model name and model number

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


This tag records the serial number of interchangable lens

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length and minimum F number in maximum focal length

### LightSource {#LightSource}
```
public static final int LightSource
```


The kind light source.

### Make {#Make}
```
public static final int Make
```


The manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


A tag for manufacturers of Exif writers to record any desired information. The contents are up to the manufacturer, but this tag should not be used for any other than its intended purpose.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


The max aperture value.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


The metering mode.

### Model {#Model}
```
public static final int Model
```


The model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown.

### OECF {#OECF}
```
public static final int OECF
```


Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524.

### Orientation {#Orientation}
```
public static final int Orientation
```


The image orientation viewed in terms of rows and columns.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indicates the ISO Speed and ISO Latitude of the camera or input device as specified in ISO 12232.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


The pixel composition.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Information specific to compressed data. When a compressed file is recorded, the valid width of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Information specific to compressed data. When a compressed file is recorded, the valid height of the meaningful image shall be recorded in this tag

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indicates whether pixel components are recorded in a chunky or planar format. If this field does not exist, the TIFF default of 1 (chunky) is assumed.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


The chromaticity of the three primary colors of the image. Normally this tag is not necessary, since colorspace is specified in the colorspace information ColorSpace tag.

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indicates recommended exposure index

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


The reference black point value and reference white point value. No defaults are given in TIFF, but the values below are given as defaults here. The color space is declared in a color space information tag, with the default being the value that gives the optimal image characteristics Interoperability these conditions

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


The related sound file.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


The unit for measuring XResolution and YResolution. The same unit is used for both XResolution and YResolution. If the image resolution is unknown, 2 (inches) is designated.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


The number of rows per strip. This is the number of rows in the image of one strip when an image is divided into strips.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


The number of components per pixel. Since this standard applies to RGB and YCbCr images, the value set for this tag is 3.

### Saturation {#Saturation}
```
public static final int Saturation
```


This tag indicates the direction of saturation processing applied by the camera when the image was shot.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


This tag indicates the type of scene that was shot. It can also be used to record the mode in which the image was shot.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indicates the image sensor type on the camera or input device.

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Type of photographic sensitivity

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


This tag indicates the direction of sharpness processing applied by the camera when the image was shot

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


The shutter speed value.

### Software {#Software}
```
public static final int Software
```


This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. The detailed format is not specified, but it is recommended that the example shown below be followed. When the field is left blank, it is treated as unknown.

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indicates the spectral sensitivity of each channel of the camera used.

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indicates standard output sensitivity of camera

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


The total number of bytes in each strip.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


For each strip, the byte offset of that strip. It is recommended that this be selected so the number of strip bytes does not exceed 64 Kbytes. Aux tag.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


This tag indicates the location and area of the main subject in the overall scene.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


The distance to the subject, given in meters.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


This tag indicates the distance to the subject.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


A tag used to record fractions of seconds for the DateTime tag.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


A tag used to record fractions of seconds for the DateTimeDigitized tag.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


A tag used to record fractions of seconds for the DateTimeOriginal tag.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


A transfer function for the image, described in tabular style. Normally this tag is not necessary, since color space is specified in the color space information ColorSpace tag.

### UserComment {#UserComment}
```
public static final int UserComment
```


A tag for Exif users to write keywords or comments on the image besides those in ImageDescription, and without the character code limitations of the ImageDescription tag.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


This tag indicates the white balance mode set when the image was shot.

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


The chromaticity of the white point of the image. Normally this tag is not necessary, since color space is specified in the colorspace information ColorSpace tag.

### XResolution {#XResolution}
```
public static final int XResolution
```


The number of pixels per ResolutionUnit in the ImageWidth direction. When the image resolution is unknown, 72 [dpi] is designated.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


The matrix coefficients for transformation from RGB to YCbCr image data.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


The position of chrominance components in relation to the luminance component. This field is designated only for JPEG compressed data or uncompressed YCbCr data. The TIFF default is 1 (centered); but when Y:Cb:Cr = 4:2:2 it is recommended in this standard that 2 (co-sited) be used to record data, in order to improve the image quality when viewed on TV systems. When this field does not exist, the reader shall assume the TIFF default. In the case of Y:Cb:Cr = 4:2:0, the TIFF default (centered) is recommended. If the reader does not have the capability of supporting both kinds of YCbCrPositioning, it shall follow the TIFF default regardless of the value in this field. It is preferable that readers " be able to support both centered and co-sited positioning.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


The sampling ratio of chrominance components in relation to the luminance component.

### YResolution {#YResolution}
```
public static final int YResolution
```


The number of pixels per ResolutionUnit in the ImageLength direction. The same value as XResolution is designated.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames() {#getNames--}
```
public String[] getNames()
```




**Returns:**
java.lang.String[]
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues() {#getValues--}
```
public Long[] getValues()
```




**Returns:**
java.lang.Long[]
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Long[]
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, String arg1) {#isDefined-java.lang.Class----java.lang.String-}
```
public static boolean isDefined(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### toString(long arg0) {#toString-long-}
```
public String toString(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

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

