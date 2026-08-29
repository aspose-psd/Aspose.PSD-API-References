---
title: "ExifProperties"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Exif 标签列表"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif 标签列表
## 字段

| 字段 | 描述 |
| --- | --- |
| [ApertureValue](#ApertureValue) | 镜头光圈值。 |
| [Artist](#Artist) | 此标签记录相机所有者、摄影师或图像创建者的名称。 |
| [BitsPerSample](#BitsPerSample) | 每个图像组件的位数。 |
| [BodySerialNumber](#BodySerialNumber) | 包含相机机身序列号 |
| [BrightnessValue](#BrightnessValue) | 亮度值。 |
| [CFAPattern](#CFAPattern) | 指示在使用单芯片彩色区域传感器时，图像传感器的彩色滤光阵列 (CFA) 几何图案。 |
| [CameraOwnerName](#CameraOwnerName) | 包含相机所有者名称 |
| [ColorSpace](#ColorSpace) | 颜色空间信息标签 (ColorSpace) 始终记录为颜色空间指定符。 |
| [ComponentsConfiguration](#ComponentsConfiguration) | 组件配置。 |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | 特定于压缩数据；说明每像素的压缩位数。 |
| [Compression](#Compression) | 用于图像数据的压缩方案。 |
| [Contrast](#Contrast) | 此标签指示拍摄时相机所应用的对比度处理方向。 |
| [Copyright](#Copyright) | 版权信息。 |
| [CustomRendered](#CustomRendered) | 此标签指示对图像数据使用的特殊处理，例如面向输出的渲染。 |
| [DateTime](#DateTime) | 图像创建的日期和时间。 |
| [DateTimeDigitized](#DateTimeDigitized) | 数字化的日期时间。 |
| [DateTimeOriginal](#DateTimeOriginal) | 原始图像数据生成的日期和时间。 |
| [DeviceSettingDescription](#DeviceSettingDescription) | 此标签指示特定相机型号的拍摄条件信息。 |
| [DigitalZoomRatio](#DigitalZoomRatio) | 此标签指示拍摄图像时的数字变焦比例。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | 指向 Exif IFD 的指针。 |
| [ExifVersion](#ExifVersion) | Exif 版本。 |
| [ExposureBiasValue](#ExposureBiasValue) | 曝光补偿值。 |
| [ExposureIndex](#ExposureIndex) | 指示在捕获图像时相机或输入设备选择的曝光指数。 |
| [ExposureMode](#ExposureMode) | 此标签指示拍摄图像时设置的曝光模式。 |
| [ExposureProgram](#ExposureProgram) | 相机在拍摄时用于设置曝光的程序类。 |
| [ExposureTime](#ExposureTime) | 曝光时间，以秒为单位。 |
| [FNumber](#FNumber) | 光圈值（F 值）。 |
| [FileSource](#FileSource) | 文件来源。 |
| [Flash](#Flash) | 指示拍摄图像时闪光灯的状态。 |
| [FlashEnergy](#FlashEnergy) | 指示捕获图像时的闪光能量，单位为光束烛光功率秒（BCPS）。 |
| [FlashpixVersion](#FlashpixVersion) | FPXR 文件支持的 Flashpix 格式版本。 |
| [FocalLength](#FocalLength) | 镜头的实际焦距，单位为毫米。 |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | 此标签指示在假设 35mm 胶片相机的情况下的等效焦距，单位为毫米。 |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | 指示用于测量 FocalPlaneXResolution 和 FocalPlaneYResolution 的单位。 |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | 指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像宽度（X）方向的像素数量。 |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | 指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像高度（Y）方向的像素数量。 |
| [GPSAltitude](#GPSAltitude) | 根据 GPSAltitudeRef 中的参考指示海拔高度。 |
| [GPSAltitudeRef](#GPSAltitudeRef) | 指示用作参考的海拔高度。 |
| [GPSAreaInformation](#GPSAreaInformation) | 记录 GPS 区域名称的字符字符串。 |
| [GPSDOP](#GPSDOP) | 指示 GPS DOP（数据精度等级）。 |
| [GPSDateStamp](#GPSDateStamp) | 记录相对于 UTC（协调世界时）的日期和时间信息的字符字符串。 |
| [GPSDestBearing](#GPSDestBearing) | 指示到达目的地点的方位。 |
| [GPSDestBearingRef](#GPSDestBearingRef) | 指示用于给出到达目的地点方位的参考。 |
| [GPSDestDistance](#GPSDestDistance) | 指示到达目的地点的距离。 |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | 指示用于表示到达目的地点距离的单位。 |
| [GPSDestLatitude](#GPSDestLatitude) | 指示目的地点的纬度。 |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | 指示目的地点的纬度是北纬还是南纬。 |
| [GPSDestLongitude](#GPSDestLongitude) | 指示目的地点的经度。 |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | 指示目的地点的经度是东经还是西经。 |
| [GPSDifferential](#GPSDifferential) | 指示是否对 GPS 接收机应用差分校正。 |
| [GPSIfdPointer](#GPSIfdPointer) | 该 gps ifd 指针。 |
| [GPSImgDirection](#GPSImgDirection) | 指示图像拍摄时的方向。 |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | 指示用于给出图像拍摄时方向的参考。 |
| [GPSLatitude](#GPSLatitude) | 指示纬度。 |
| [GPSLatitudeRef](#GPSLatitudeRef) | 指示纬度是北纬还是南纬。 |
| [GPSLongitude](#GPSLongitude) | 指示经度。 |
| [GPSLongitudeRef](#GPSLongitudeRef) | 指示经度是东经还是西经。 |
| [GPSMapDatum](#GPSMapDatum) | 指示 GPS 接收机使用的大地测量数据。 |
| [GPSMeasureMode](#GPSMeasureMode) | 指示 GPS 测量模式。 |
| [GPSProcessingMethod](#GPSProcessingMethod) | 记录用于定位的方法名称的字符字符串。 |
| [GPSSatellites](#GPSSatellites) | 指示用于测量的 GPS 卫星。 |
| [GPSSpeed](#GPSSpeed) | 指示 GPS 接收机移动的速度。 |
| [GPSSpeedRef](#GPSSpeedRef) | 指示用于表示 GPS 接收机移动速度的单位。 |
| [GPSStatus](#GPSStatus) | 指示记录图像时 GPS 接收机的状态。 |
| [GPSTimestamp](#GPSTimestamp) | 指示时间为 UTC（协调世界时）。 |
| [GPSTrack](#GPSTrack) | 指示 GPS 接收机移动的方向。 |
| [GPSTrackRef](#GPSTrackRef) | 指示用于给出 GPS 接收器移动方向的参考。 |
| [GPSVersionID](#GPSVersionID) | 指示 GPSInfoIFD 的版本。 |
| [GainControl](#GainControl) | 此标签指示整体图像增益调整的程度。 |
| [Gamma](#Gamma) | 伽马值 |
| [ISOSpeed](#ISOSpeed) | 关于 ISO 12232 中定义的 ISO 速度值的信息 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 yyy 值 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 zzz 值 |
| [ImageDescription](#ImageDescription) | 提供图像标题的字符字符串。 |
| [ImageLength](#ImageLength) | 图像数据的行数。 |
| [ImageUniqueID](#ImageUniqueID) | 图像唯一标识符。 |
| [ImageWidth](#ImageWidth) | 图像数据的列数，等于每行的像素数。 |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | 指向 JPEG 压缩缩略图数据起始字节 (SOI) 的偏移量。 |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | JPEG 压缩缩略图数据的字节数。 |
| [LensMake](#LensMake) | 此标签记录镜头制造商 |
| [LensModel](#LensModel) | 此标签记录镜头的型号名称和型号编号 |
| [LensSerialNumber](#LensSerialNumber) | 此标签记录可互换镜头的序列号 |
| [LensSpecification](#LensSpecification) | 此标签记录最小焦距、最大焦距、最小焦距对应的最小光圈值以及最大焦距对应的最小光圈值 |
| [LightSource](#LightSource) | 光源类型。 |
| [Make](#Make) | 记录设备的制造商。 |
| [MakerNote](#MakerNote) | 供 Exif 编写器制造商记录任意所需信息的标签。 |
| [MaxApertureValue](#MaxApertureValue) | 最大光圈值。 |
| [MeteringMode](#MeteringMode) | 测光模式。 |
| [Model](#Model) | 设备的型号名称或型号编号。 |
| [OECF](#OECF) | 指示 ISO 14524 中规定的光电转换函数 (OECF)。 |
| [Orientation](#Orientation) | 以行列方式查看的图像方向。 |
| [PhotographicSensitivity](#PhotographicSensitivity) | 指示相机或输入设备的 ISO 速度和 ISO 纬度（如 ISO 12232 所规定）。 |
| [PhotometricInterpretation](#PhotometricInterpretation) | 像素组成。 |
| [PixelXDimension](#PixelXDimension) | 特定于压缩数据的信息。 |
| [PixelYDimension](#PixelYDimension) | 特定于压缩数据的信息。 |
| [PlanarConfiguration](#PlanarConfiguration) | 指示像素组件是以块状还是平面格式记录。 |
| [PrimaryChromaticities](#PrimaryChromaticities) | 图像三原色的色度。 |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | 指示推荐的曝光指数 |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | 参考黑点值和参考白点值。 |
| [RelatedSoundFile](#RelatedSoundFile) | 相关的声音文件。 |
| [ResolutionUnit](#ResolutionUnit) | 用于测量 XResolution 和 YResolution 的单位。 |
| [RowsPerStrip](#RowsPerStrip) | 每条带的行数。 |
| [SamplesPerPixel](#SamplesPerPixel) | 每个像素的组件数量。 |
| [Saturation](#Saturation) | 此标签指示相机拍摄图像时所应用的饱和度处理方向。 |
| [SceneCaptureType](#SceneCaptureType) | 此标签指示拍摄的场景类型。 |
| [SceneType](#SceneType) | 指示场景类型。 |
| [SensingMethod](#SensingMethod) | 指示相机或输入设备的图像传感器类型。 |
| [SensitivityType](#SensitivityType) | 摄影感光度类型 |
| [Sharpness](#Sharpness) | 此标签指示相机拍摄图像时所应用的锐度处理方向 |
| [ShutterSpeedValue](#ShutterSpeedValue) | 快门速度值。 |
| [Software](#Software) | 此标签记录用于生成图像的相机或图像输入设备的软件或固件的名称和版本。 |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | 此标签记录相机或输入设备的空间频率表以及在图像宽度、图像高度和对角方向上的 SFR 值，依据 ISO 12233。 |
| [SpectralSensitivity](#SpectralSensitivity) | 指示所使用相机每个通道的光谱灵敏度。 |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | 指示相机的标准输出灵敏度 |
| [StripByteCounts](#StripByteCounts) | 每条带的总字节数。 |
| [StripOffsets](#StripOffsets) | 对于每条带，给出该带的字节偏移量。 |
| [SubjectArea](#SubjectArea) | 此标签指示整体场景中主体的位置信息和区域。 |
| [SubjectDistance](#SubjectDistance) | 以米为单位的主体距离。 |
| [SubjectDistanceRange](#SubjectDistanceRange) | 此标签指示主体的距离。 |
| [SubjectLocation](#SubjectLocation) | 指示场景中主要主体的位置。 |
| [SubsecTime](#SubsecTime) | 用于记录 DateTime 标签的秒分数的标签。 |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | 用于记录 DateTimeDigitized 标签的秒分数的标签。 |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | 用于记录 DateTimeOriginal 标签的秒分数的标签。 |
| [TransferFunction](#TransferFunction) | 图像的传输函数，以表格形式描述。 |
| [UserComment](#UserComment) | 供 Exif 用户在图像上写入关键字或注释的标签，除了 ImageDescription 中的内容，并且不受 ImageDescription 标签字符编码限制。 |
| [WhiteBalance](#WhiteBalance) | 此标签指示拍摄图像时设置的白平衡模式。 |
| [WhitePoint](#WhitePoint) | 图像白点的色度。 |
| [XResolution](#XResolution) | ImageWidth 方向上每个 ResolutionUnit 的像素数。 |
| [YCbCrCoefficients](#YCbCrCoefficients) | 从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| [YCbCrPositioning](#YCbCrPositioning) | 色度分量相对于亮度分量的位置。 |
| [YCbCrSubSampling](#YCbCrSubSampling) | 色度分量相对于亮度分量的采样比率。 |
| [YResolution](#YResolution) | ImageLength 方向上每个 ResolutionUnit 的像素数。 |
## Methods

| Method | 描述 |
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


镜头光圈值。

### Artist {#Artist}
```
public static final int Artist
```


此标签记录相机所有者、摄影师或图像创建者的名称。未指定详细格式，但建议按以下示例编写信息，以便于互操作性。字段留空时视为未知。示例）"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


每个图像组件的位数。根据本标准，图像的每个组件为 8 位，因此此标签的值为 8。

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


包含相机机身序列号

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


亮度值。

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


指示在使用单芯片彩色区域传感器时图像传感器的颜色滤光阵列 (CFA) 几何图案。该描述并不适用于所有感测方法。

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


包含相机所有者名称

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


颜色空间信息标签 (ColorSpace) 始终记录为颜色空间指定符。

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


组件配置。

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


特定于压缩数据；说明每像素的压缩位数。

### Compression {#Compression}
```
public static final int Compression
```


用于图像数据的压缩方案。当主图像采用 JPEG 压缩时，此标识不是必需的，会被省略。

### Contrast {#Contrast}
```
public static final int Contrast
```


此标签指示拍摄时相机所应用的对比度处理方向。

### Copyright {#Copyright}
```
public static final int Copyright
```


版权信息。根据本标准，此标签用于指示摄影师和编辑的版权。它是对声称拥有图像权利的个人或组织的版权声明。互操作性版权声明应包括日期和权利，并写入此字段；例如，"Copyright, John Smith, 19xx. All rights reserved."。在本标准中，该字段记录摄影师和编辑的版权，分别写在声明的不同部分。当摄影师和编辑的版权有明确区分时，按摄影师在前、编辑在后的顺序写入，并以 NULL 分隔（由于声明也以 NULL 结束，此情况下有两个 NULL 代码）。仅提供摄影师版权时，以一个 NULL 代码结束。仅提供编辑版权时，摄影师版权部分为一个空格加终止的 NULL 代码，然后写入编辑版权。字段留空时视为未知。

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


此标签指示对图像数据使用特殊处理，例如面向输出的渲染。执行特殊处理时，读取器应禁用或尽量减少后续处理。

### DateTime {#DateTime}
```
public static final int DateTime
```


图像创建的日期和时间。根据 Exif 标准，它是文件被修改的日期和时间。

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


数字化的日期时间。

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


原始图像数据生成的日期和时间。

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


此标签指示特定相机型号的拍摄条件信息。该标签仅用于在读取器中指示拍摄条件。

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


此标签指示拍摄图像时的数码变焦比例。如果记录值的分子为 0，则表示未使用数码变焦。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


指向 Exif IFD 的指针。互操作性方面，Exif IFD 与 TIFF 中指定的 IFD 结构相同。但通常情况下，它不像 TIFF 那样包含图像数据。

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif 版本。

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


曝光补偿值。

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


指示在捕获图像时相机或输入设备选择的曝光指数。

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


此标签指示拍摄图像时设置的曝光模式。在自动包围模式下，摄像机会以不同的曝光设置拍摄同一场景的一系列帧。

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


相机在拍摄时用于设置曝光的程序类。

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


曝光时间，以秒为单位。

### FNumber {#FNumber}
```
public static final int FNumber
```


光圈值（F 值）。

### FileSource {#FileSource}
```
public static final int FileSource
```


文件来源。

### Flash {#Flash}
```
public static final int Flash
```


指示拍摄图像时闪光灯的状态。

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


指示捕获图像时的闪光能量，单位为光束烛光功率秒（BCPS）。

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


FPXR 文件支持的 Flashpix 格式版本。

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


镜头的实际焦距，单位为毫米。

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


此标签指示在假设为35mm胶片相机时的等效焦距，单位为毫米。值为0表示焦距未知。请注意，此标签与FocalLength标签不同。

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


指示用于测量FocalPlaneXResolution和FocalPlaneYResolution的单位。该值与ResolutionUnit相同。

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像宽度（X）方向的像素数量。

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像高度（Y）方向的像素数量。

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


指示基于GPSAltitudeRef参考的海拔。海拔以一个RATIONAL值表示。参考单位为米。

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


指示用作参考海拔的海拔。如果参考为海平面且海拔高于海平面，则给出0。如果海拔低于海平面，则给出1，并在GPSAltitude标签中以绝对值表示海拔。

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


记录GPS区域名称的字符字符串。第一个字节指示使用的字符编码，随后是GPS区域的名称。

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


指示GPS DOP（数据精度）。在二维测量时写入HDOP值，三维测量时写入PDOP值。

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


记录相对于UTC（协调世界时）的日期和时间信息的字符字符串。格式为YYYY:MM:DD。

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


指示到目的地点的方位。取值范围为0.00至359.99。

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


指示用于给出到目的地点方位的参考。'T'表示真方向，'M'表示磁方向。

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


指示到达目的地点的距离。

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


指示用于表示到目的地点距离的单位。'K'、'M'和'N'分别代表公里、英里和节。

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


指示目的地点的纬度。纬度以三个RATIONAL值表示，分别为度、分、秒。如果纬度以度、分、秒表示，典型格式为dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为dd/1,mmmm/100,0/1。

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


指示目的地点的纬度是北纬还是南纬。ASCII值'N'表示北纬，'S'表示南纬。

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


指示目的地点的经度。经度以三个RATIONAL值表示，分别为度、分、秒。如果经度以度、分、秒表示，典型格式为ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为ddd/1,mmmm/100,0/1。

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


指示目的地点的经度是东经还是西经。ASCII'E'表示东经，'W'表示西经。

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


指示是否对 GPS 接收机应用差分校正。

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


该 gps ifd 指针。

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


指示拍摄图像时的方向。取值范围为0.00至359.99。

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


指示用于给出拍摄图像方向的参考。'T'表示真方向，'M'表示磁方向。

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


指示纬度。纬度以三个RATIONAL值表示，分别为度、分、秒。如果纬度以度、分、秒表示，典型格式为dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为dd/1,mmmm/100,0/1。

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


指示纬度是北纬还是南纬。

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


指示经度。经度以三个RATIONAL值表示，分别为度、分、秒。如果经度以度、分、秒表示，典型格式为ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为ddd/1,mmmm/100,0/1。

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


指示经度是东经还是西经。

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


指示 GPS 接收机使用的大地测量数据。

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


指示GPS测量模式。- 2维或3维。

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


记录用于定位的方式名称的字符字符串。第一个字节指示使用的字符编码，随后是该方式的名称。

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


指示用于测量的GPS卫星。此标签可用于描述卫星数量、其ID号、仰角、方位角、信噪比及其他ASCII表示的信息。格式未指定。如果GPS接收器无法进行测量，则该标签的值应设为NULL。

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


指示 GPS 接收机移动的速度。

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


指示用于表示GPS接收器移动速度的单位。'K'、'M'和'N'分别代表公里每小时、英里每小时和节。

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


指示记录图像时 GPS 接收机的状态。

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


指示时间为UTC（协调世界时）。TimeStamp以三个RATIONAL值表示，分别为小时、分钟和秒。

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


指示GPS接收器移动的方向。取值范围为0.00至359.99。

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


指示用于给出 GPS 接收机移动方向的参考。'T' 表示真北方向，'M' 表示磁北方向。

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


指示 GPSInfoIFD 的版本。

### GainControl {#GainControl}
```
public static final int GainControl
```


此标签指示整体图像增益调整的程度。

### Gamma {#Gamma}
```
public static final int Gamma
```


伽马值

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


关于 ISO 12232 中定义的 ISO 速度值的信息

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


此标签指示 ISO 12232 中定义的 ISO 速度纬度 yyy 值

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


此标签指示 ISO 12232 中定义的 ISO 速度纬度 zzz 值

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


提供图像标题的字符字符串。它可以是诸如 "1988 company picnic" 之类的注释。

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


图像数据的行数。

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


图像唯一标识符。

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


图像数据的列数，等于每行的像素数。

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


JPEG 压缩缩略图数据的起始字节 (SOI) 的偏移量。此字段不用于主图像的 JPEG 数据。

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


JPEG 压缩缩略图数据的字节数。此字段不用于主图像的 JPEG 数据。JPEG 缩略图不被分割，而是从 SOI 到 EOI 作为连续的 JPEG 位流记录。Appn 和 COM 标记不应被记录。压缩缩略图的记录不得超过 64 Kbytes，包括在 APP1 中记录的所有其他数据。

### LensMake {#LensMake}
```
public static final int LensMake
```


此标签记录镜头制造商

### LensModel {#LensModel}
```
public static final int LensModel
```


此标签记录镜头的型号名称和型号编号

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


此标签记录可互换镜头的序列号

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


此标签记录最小焦距、最大焦距、最小焦距对应的最小光圈值以及最大焦距对应的最小光圈值

### LightSource {#LightSource}
```
public static final int LightSource
```


光源类型。

### Make {#Make}
```
public static final int Make
```


记录设备的制造商。指生成图像的 DSC、扫描仪、视频数字化仪或其他设备的制造商。若该字段留空，则视为未知。

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


供 Exif 编写器制造商记录任意信息的标签。内容由制造商自行决定，但此标签不应用于其预定用途之外的任何目的。

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


最大光圈值。

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


测光模式。

### Model {#Model}
```
public static final int Model
```


设备的型号名称或型号编号。指生成图像的 DSC、扫描仪、视频数字化仪或其他设备的型号名称或编号。若该字段留空，则视为未知。

### OECF {#OECF}
```
public static final int OECF
```


指示 ISO 14524 中规定的光电转换函数 (OECF)。

### Orientation {#Orientation}
```
public static final int Orientation
```


以行列方式查看的图像方向。

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


指示相机或输入设备的 ISO 速度和 ISO 纬度（如 ISO 12232 所规定）。

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


像素组成。

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


特定于压缩数据的信息。记录压缩文件时，应在此标签中记录有效图像的宽度，无论是否存在填充数据或重启标记。

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


特定于压缩数据的信息。记录压缩文件时，应在此标签中记录有效图像的高度。

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


指示像素分量是以块状（chunky）还是平面（planar）格式记录。如果该字段不存在，则假定 TIFF 默认值 1（块状）。

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


图像三原色的色度。通常此标签不是必需的，因为颜色空间已在 ColorSpace 信息标签中指定。

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


指示推荐的曝光指数

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


参考黑点值和参考白点值。TIFF 未提供默认值，但此处给出了以下默认值。颜色空间在颜色空间信息标签中声明，默认值为在这些条件下提供最佳图像特性的值。

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


相关的声音文件。

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


用于测量 XResolution 和 YResolution 的单位。XResolution 与 YResolution 使用相同的单位。如果图像分辨率未知，则指定为 2（英寸）。

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


每条带的行数。当图像被划分为条带时，这指单个条带在图像中的行数。

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


每像素的分量数。由于本标准适用于 RGB 和 YCbCr 图像，此标签的取值为 3。

### Saturation {#Saturation}
```
public static final int Saturation
```


此标签指示相机拍摄图像时所应用的饱和度处理方向。

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


此标签指示拍摄场景的类型。它也可用于记录图像拍摄的模式。

### SceneType {#SceneType}
```
public static final int SceneType
```


指示场景类型。如果是 DSC 记录的图像，则此标签值应始终设为 1，表示图像为直接拍摄。

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


指示相机或输入设备的图像传感器类型。

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


摄影感光度类型

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


此标签指示相机拍摄图像时所应用的锐度处理方向

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


快门速度值。

### Software {#Software}
```
public static final int Software
```


此标签记录用于生成图像的相机或图像输入设备的软件或固件的名称和版本。未指定详细格式，但建议遵循下方示例。若该字段留空，则视为未知。

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


此标签记录相机或输入设备的空间频率表以及在图像宽度、图像高度和对角方向上的 SFR 值，依据 ISO 12233。

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


指示所使用相机每个通道的光谱灵敏度。

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


指示相机的标准输出灵敏度

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


每条带的总字节数。

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


对于每个条带，记录该条带的字节偏移量。建议选择使条带字节数不超过 64 Kbytes。辅助标签。

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


此标签指示整体场景中主体的位置信息和区域。

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


以米为单位的主体距离。

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


此标签指示主体的距离。

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


指示场景中主体的位置信息。此标签的值表示相对于左边缘、在旋转处理（依据 Rotation 标签）之前，主体中心像素的位置。

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


用于记录 DateTime 标签的秒分数的标签。

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


用于记录 DateTimeDigitized 标签的秒分数的标签。

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


用于记录 DateTimeOriginal 标签的秒分数的标签。

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


图像的传递函数，以表格形式描述。通常此标签不是必需的，因为颜色空间已在 ColorSpace 信息标签中指定。

### UserComment {#UserComment}
```
public static final int UserComment
```


供 Exif 用户在图像上写入关键字或注释的标签，除了 ImageDescription 中的内容，并且不受 ImageDescription 标签字符编码限制。

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


此标签指示拍摄图像时设置的白平衡模式。

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


图像白点的色度。通常此标签不是必需的，因为颜色空间已在 ColorSpace 信息标签中指定。

### XResolution {#XResolution}
```
public static final int XResolution
```


在 ImageWidth 方向上，每个 ResolutionUnit 的像素数。当图像分辨率未知时，指定为 72 [dpi]。

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


从 RGB 到 YCbCr 图像数据转换的矩阵系数。

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


色度分量相对于亮度分量的位置。此字段仅用于 JPEG 压缩数据或未压缩的 YCbCr 数据。TIFF 默认值为 1（居中）；但当 Y:Cb:Cr = 4:2:2 时，本标准建议使用 2（并列）来记录数据，以提升在电视系统上观看时的图像质量。当此字段不存在时，读取器应假定 TIFF 默认值。对于 Y:Cb:Cr = 4:2:0，推荐使用 TIFF 默认值（居中）。如果读取器不具备支持两种 YCbCrPositioning 的能力，则应无论该字段的值如何都遵循 TIFF 默认值。最好读取器 \" 能够支持居中和并列定位。

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


色度分量相对于亮度分量的采样比率。

### YResolution {#YResolution}
```
public static final int YResolution
```


在 ImageLength 方向上，每个 ResolutionUnit 的像素数。指定的值与 XResolution 相同。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

