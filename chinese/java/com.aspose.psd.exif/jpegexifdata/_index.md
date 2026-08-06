---
title: "JpegExifData"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于 JPEG 文件的 EXIF 数据容器。"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

用于 JPEG 文件的 EXIF 数据容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | 初始化 JpegExifData 类的新实例。 |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | 使用数组中的数据初始化 JpegExifData 类的新实例。 |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | 使用数组中的数据初始化 JpegExifData 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | 允许的最大 EXIF 段大小（字节）。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | 获取或设置光圈值。 |
| [getArtist()](#getArtist--) | 获取或设置艺术家。 |
| [getBitsPerSample()](#getBitsPerSample--) | 获取或设置每个样本的位数。 |
| [getBodySerialNumber()](#getBodySerialNumber--) | 获取或设置相机机身序列号。 |
| [getBrightnessValue()](#getBrightnessValue--) | 获取或设置亮度值。 |
| [getCFAPattern()](#getCFAPattern--) | 获取或设置 CFA 模式。 |
| [getCameraOwnerName()](#getCameraOwnerName--) | 获取或设置相机所有者名称 |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | 获取或设置色彩空间。 |
| [getCommonTags()](#getCommonTags--) | 获取或设置属于通用部分的标签。 |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | 获取或设置组件配置。 |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | 获取或设置每像素压缩位数。 |
| [getCompression()](#getCompression--) | 获取或设置压缩方式。 |
| [getContrast()](#getContrast--) | 获取或设置对比度。 |
| [getCopyright()](#getCopyright--) | 获取或设置版权信息。 |
| [getCustomRendered()](#getCustomRendered--) | 获取或设置自定义渲染。 |
| [getDateTime()](#getDateTime--) | 获取或设置日期时间。 |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | 获取或设置数字化日期时间。 |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | 获取或设置原始日期时间。 |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | 获取或设置设备设置描述 |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | 获取或设置数码变焦比例。 |
| [getExifTags()](#getExifTags--) | 获取或设置仅属于 EXIF 部分的标签。 |
| [getExifVersion()](#getExifVersion--) | 获取或设置 EXIF 版本。 |
| [getExposureBiasValue()](#getExposureBiasValue--) | 获取或设置曝光偏差值。 |
| [getExposureIndex()](#getExposureIndex--) | 获取或设置曝光指数。 |
| [getExposureMode()](#getExposureMode--) | 获取或设置曝光模式。 |
| [getExposureProgram()](#getExposureProgram--) | 获取或设置曝光程序。 |
| [getExposureTime()](#getExposureTime--) | 获取或设置曝光时间。 |
| [getFNumber()](#getFNumber--) | 获取或设置光圈数。 |
| [getFileSource()](#getFileSource--) | 获取或设置文件源类型。 |
| [getFlash()](#getFlash--) | 获取或设置闪光灯。 |
| [getFlashEnergy()](#getFlashEnergy--) | 获取或设置闪光能量。 |
| [getFlashpixVersion()](#getFlashpixVersion--) | 获取或设置闪光像素版本。 |
| [getFocalLength()](#getFocalLength--) | 获取或设置焦距。 |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 获取或设置 35 mm 胶片的焦距。 |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | 获取或设置焦平面分辨率单位。 |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | 获取或设置焦平面 X 方向分辨率。 |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | 获取或设置焦平面 Y 方向分辨率。 |
| [getGPSAltitude()](#getGPSAltitude--) | 获取或设置 GPS 海拔。 |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | 获取或设置用作参考海拔的 GPS 海拔。 |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | 获取或设置 GPS 区域信息。 |
| [getGPSDOP()](#getGPSDOP--) | 获取或设置 GPS DOP（数据精度等级）。 |
| [getGPSDateStamp()](#getGPSDateStamp--) | 获取或设置相对于 UTC（协调世界时）的 GPS 字符串记录日期和时间信息。 |
| [getGPSDestBearing()](#getGPSDestBearing--) | 获取或设置指向目的地点的 GPS 方位角。 |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | 获取或设置用于提供指向目的地点方位角的 GPS 参考。 |
| [getGPSDestDistance()](#getGPSDestDistance--) | 获取或设置到目的地点的 GPS 距离。 |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | 获取或设置用于表示到目的地点距离的 GPS 单位。 |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | 获取或设置目的地点的 GPS 纬度。 |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | 获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。 |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | 获取或设置目的地点的 GPS 经度。 |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | 获取或设置指示目的地点经度是东经还是西经的 GPS 值。 |
| [getGPSDifferential()](#getGPSDifferential--) | 获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。 |
| [getGPSImgDirection()](#getGPSImgDirection--) | 获取或设置图像拍摄时的 GPS 方向。 |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | 获取或设置图像拍摄时提供方向的 GPS 参考。 |
| [getGPSLatitude()](#getGPSLatitude--) | 获取或设置 GPS 纬度。 |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | 获取或设置 GPS 纬度是北纬还是南纬。 |
| [getGPSLongitude()](#getGPSLongitude--) | 获取或设置 GPS 经度。 |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | 获取或设置 GPS 经度是东经还是西经。 |
| [getGPSMapDatum()](#getGPSMapDatum--) | 获取或设置 GPS 接收器使用的 GPS 大地测量数据。 |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | 获取或设置 GPS 测量模式。 |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | 获取或设置记录用于定位方法名称的 GPS 字符串。 |
| [getGPSSatellites()](#getGPSSatellites--) | 获取或设置用于测量的 GPS 卫星。 |
| [getGPSSpeed()](#getGPSSpeed--) | 获取或设置 GPS 接收器移动的速度。 |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | 获取或设置用于表示 GPS 接收器移动速度的单位。 |
| [getGPSStatus()](#getGPSStatus--) | 获取或设置记录图像时 GPS 接收器的状态。 |
| [getGPSTags()](#getGPSTags--) | 获取或设置仅属于 GPS 部分的标签。 |
| [getGPSTimestamp()](#getGPSTimestamp--) | 获取或设置 GPS 时间（UTC，协调世界时）。 |
| [getGPSTrack()](#getGPSTrack--) | 获取或设置 GPS 接收器移动的方向。 |
| [getGPSTrackRef()](#getGPSTrackRef--) | 获取或设置提供 GPS 接收器移动方向的参考。 |
| [getGPSVersionID()](#getGPSVersionID--) | 获取或设置 GPS 版本标识符。 |
| [getGainControl()](#getGainControl--) | 获取或设置整体图像增益调整的程度。 |
| [getGamma()](#getGamma--) | 获取或设置伽马值。 |
| [getISOSpeed()](#getISOSpeed--) | 获取或设置 ISO 速度。 |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。 |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。 |
| [getImageDescription()](#getImageDescription--) | 获取或设置图像描述。 |
| [getImageLength()](#getImageLength--) | 获取或设置图像长度。 |
| [getImageUniqueID()](#getImageUniqueID--) | 获取或设置图像唯一标识符。 |
| [getImageWidth()](#getImageWidth--) | 获取或设置图像宽度。 |
| [getLensMake()](#getLensMake--) | 获取或设置镜头制造商。 |
| [getLensModel()](#getLensModel--) | 获取或设置镜头型号。 |
| [getLensSerialNumber()](#getLensSerialNumber--) | 获取或设置镜头序列号。 |
| [getLensSpecification()](#getLensSpecification--) | 获取或设置镜头规格 |
| [getLightSource()](#getLightSource--) | 获取或设置光源。 |
| [getMake()](#getMake--) | 获取录制设备的制造商。 |
| [getMakerNoteData()](#getMakerNoteData--) | 获取制造商注释数据。 |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | 获取或设置制造商注释原始数据。 |
| [getMakerNotes()](#getMakerNotes--) | 获取制造商注释。 |
| [getMaxApertureValue()](#getMaxApertureValue--) | 获取或设置最大光圈值。 |
| [getMeteringMode()](#getMeteringMode--) | 获取或设置测光模式。 |
| [getModel()](#getModel--) | 获取或设置模型。 |
| [getOECF()](#getOECF--) | 获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。 |
| [getOrientation()](#getOrientation--) | 获取或设置方向。 |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | 获取或设置感光度。 |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | 获取或设置光度解释。 |
| [getPixelXDimension()](#getPixelXDimension--) | 获取或设置像素 X 维度。 |
| [getPixelYDimension()](#getPixelYDimension--) | 获取或设置像素 Y 维度。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 获取或设置平面配置。 |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | 获取或设置图像三原色的色度。 |
| [getProperties()](#getProperties--) | 获取或设置所有 EXIF 标签（包括通用标签和 GPS 标签）。 |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | 获取或设置推荐曝光指数。 |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | 获取或设置参考黑白。 |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | 获取或设置相关音频文件。 |
| [getResolutionUnit()](#getResolutionUnit--) | 获取或设置分辨率单位。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | 获取或设置每像素采样数。 |
| [getSaturation()](#getSaturation--) | 获取或设置饱和度。 |
| [getSceneCaptureType()](#getSceneCaptureType--) | 获取或设置场景捕获类型。 |
| [getSceneType()](#getSceneType--) | 获取或设置场景类型。 |
| [getSensingMethod()](#getSensingMethod--) | 获取或设置感应方法。 |
| [getSensitivityType()](#getSensitivityType--) | 获取或设置灵敏度类型。 |
| [getSharpness()](#getSharpness--) | 获取或设置锐度。 |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | 获取或设置快门速度值。 |
| [getSoftware()](#getSoftware--) | 获取或设置软件。 |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | 获取或设置空间频率响应。 |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | 获取或设置光谱灵敏度。 |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | 获取标准输出灵敏度 |
| [getSubjectArea()](#getSubjectArea--) | 获取或设置主体区域。 |
| [getSubjectDistance()](#getSubjectDistance--) | 获取或设置主体距离。 |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | 获取或设置主体距离范围。 |
| [getSubjectLocation()](#getSubjectLocation--) | 获取或设置主体位置。 |
| [getSubsecTime()](#getSubsecTime--) | 获取或设置 DateTime 标记的秒分数。 |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | 获取或设置 DateTimeDigitized 标记的秒分数。 |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | 获取或设置 DateTimeOriginal 标记的秒分数。 |
| [getThumbnail()](#getThumbnail--) | 获取或设置缩略图。 |
| [getTransferFunction()](#getTransferFunction--) | 获取或设置传输函数。 |
| [getUserComment()](#getUserComment--) | 获取或设置用户评论。 |
| [getWhiteBalance()](#getWhiteBalance--) | 获取或设置白平衡。 |
| [getWhitePoint()](#getWhitePoint--) | 获取或设置图像白点的色度。 |
| [getXResolution()](#getXResolution--) | 获取或设置 X 分辨率。 |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | 获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | 获取或设置色度分量相对于亮度分量的位置。 |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | 获取或设置色度分量相对于亮度分量的采样比率。 |
| [getYResolution()](#getYResolution--) | 获取或设置 Y 分辨率。 |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | 获取或设置一个值，以指示从中创建的流 EXIF 数据是否为大端序。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | 从容器中移除标签 |
| [serializeExifData()](#serializeExifData--) | 序列化 EXIF 数据。 |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置光圈值。 |
| [setArtist(String value)](#setArtist-java.lang.String-) | 获取或设置艺术家。 |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | 获取或设置一个值，以指示从中创建的流 EXIF 数据是否为大端序。 |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | 获取或设置每个样本的位数。 |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | 获取或设置相机机身序列号。 |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 获取或设置亮度值。 |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | 获取或设置 CFA 模式。 |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | 获取或设置相机所有者名称 |
| [setColorSpace(int value)](#setColorSpace-int-) | 获取或设置色彩空间。 |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 获取或设置属于通用部分的标签。 |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | 获取或设置组件配置。 |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置每像素压缩位数。 |
| [setCompression(int value)](#setCompression-int-) | 获取或设置压缩方式。 |
| [setContrast(int value)](#setContrast-int-) | 获取或设置对比度。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 获取或设置版权信息。 |
| [setCustomRendered(int value)](#setCustomRendered-int-) | 获取或设置自定义渲染。 |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 获取或设置日期时间。 |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | 获取或设置数字化日期时间。 |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | 获取或设置原始日期时间。 |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | 获取或设置设备设置描述 |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置数码变焦比例。 |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 获取或设置仅属于 EXIF 部分的标签。 |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | 获取或设置 EXIF 版本。 |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 获取或设置曝光偏差值。 |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置曝光指数。 |
| [setExposureMode(int value)](#setExposureMode-int-) | 获取或设置曝光模式。 |
| [setExposureProgram(int value)](#setExposureProgram-int-) | 获取或设置曝光程序。 |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置曝光时间。 |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置光圈数。 |
| [setFileSource(byte value)](#setFileSource-byte-) | 获取或设置文件源类型。 |
| [setFlash(int value)](#setFlash-int-) | 获取或设置闪光灯。 |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置闪光能量。 |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | 获取或设置闪光像素版本。 |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置焦距。 |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 获取或设置 35 mm 胶片的焦距。 |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | 获取或设置焦平面分辨率单位。 |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置焦平面 X 方向分辨率。 |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置焦平面 Y 方向分辨率。 |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 GPS 海拔。 |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | 获取或设置用作参考海拔的 GPS 海拔。 |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | 获取或设置 GPS 区域信息。 |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 GPS DOP（数据精度等级）。 |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | 获取或设置相对于 UTC（协调世界时）的 GPS 字符串记录日期和时间信息。 |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置指向目的地点的 GPS 方位角。 |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | 获取或设置用于提供指向目的地点方位角的 GPS 参考。 |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置到目的地点的 GPS 距离。 |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | 获取或设置用于表示到目的地点距离的 GPS 单位。 |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置目的地点的 GPS 纬度。 |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | 获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。 |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置目的地点的 GPS 经度。 |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | 获取或设置指示目的地点经度是东经还是西经的 GPS 值。 |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | 获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。 |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置图像拍摄时的 GPS 方向。 |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | 获取或设置图像拍摄时提供方向的 GPS 参考。 |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置 GPS 纬度。 |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | 获取或设置 GPS 纬度是北纬还是南纬。 |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置 GPS 经度。 |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | 获取或设置 GPS 经度是东经还是西经。 |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | 获取或设置 GPS 接收器使用的 GPS 大地测量数据。 |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | 获取或设置 GPS 测量模式。 |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | 获取或设置记录用于定位方法名称的 GPS 字符串。 |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | 获取或设置用于测量的 GPS 卫星。 |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 GPS 接收器移动的速度。 |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | 获取或设置用于表示 GPS 接收器移动速度的单位。 |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | 获取或设置记录图像时 GPS 接收器的状态。 |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 获取或设置仅属于 GPS 部分的标签。 |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置 GPS 时间（UTC，协调世界时）。 |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | 获取或设置 GPS 接收器移动的方向。 |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | 获取或设置提供 GPS 接收器移动方向的参考。 |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | 获取或设置 GPS 版本标识符。 |
| [setGainControl(int value)](#setGainControl-int-) | 获取或设置整体图像增益调整的程度。 |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置伽马值。 |
| [setISOSpeed(long value)](#setISOSpeed-long-) | 获取或设置 ISO 速度。 |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。 |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。 |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 获取或设置图像描述。 |
| [setImageLength(long value)](#setImageLength-long-) | 获取或设置图像长度。 |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | 获取或设置图像唯一标识符。 |
| [setImageWidth(long value)](#setImageWidth-long-) | 获取或设置图像宽度。 |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | 获取或设置镜头制造商。 |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | 获取或设置镜头型号。 |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | 获取或设置镜头序列号。 |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置镜头规格 |
| [setLightSource(int value)](#setLightSource-int-) | 获取或设置光源。 |
| [setMake(String value)](#setMake-java.lang.String-) | 设置录音设备的制造商。 |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | 获取或设置制造商注释原始数据。 |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置最大光圈值。 |
| [setMeteringMode(int value)](#setMeteringMode-int-) | 获取或设置测光模式。 |
| [setModel(String value)](#setModel-java.lang.String-) | 获取或设置模型。 |
| [setOECF(byte[] value)](#setOECF-byte---) | 获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。 |
| [setOrientation(int value)](#setOrientation-int-) | 获取或设置方向。 |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | 获取或设置感光度。 |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | 获取或设置光度解释。 |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | 获取或设置像素 X 维度。 |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | 获取或设置像素 Y 维度。 |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 获取或设置平面配置。 |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置图像三原色的色度。 |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | 获取或设置所有 EXIF 标签（包括通用标签和 GPS 标签）。 |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | 获取或设置推荐曝光指数。 |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置参考黑白。 |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | 获取或设置相关音频文件。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 获取或设置分辨率单位。 |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | 获取或设置每像素采样数。 |
| [setSaturation(int value)](#setSaturation-int-) | 获取或设置饱和度。 |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | 获取或设置场景捕获类型。 |
| [setSceneType(byte value)](#setSceneType-byte-) | 获取或设置场景类型。 |
| [setSensingMethod(int value)](#setSensingMethod-int-) | 获取或设置感应方法。 |
| [setSensitivityType(int value)](#setSensitivityType-int-) | 获取或设置灵敏度类型。 |
| [setSharpness(int value)](#setSharpness-int-) | 获取或设置锐度。 |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 获取或设置快门速度值。 |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | 获取或设置软件。 |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | 获取或设置空间频率响应。 |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | 获取或设置光谱灵敏度。 |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | 设置标准输出灵敏度 |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | 获取或设置主体区域。 |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置主体距离。 |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | 获取或设置主体距离范围。 |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | 获取或设置主体位置。 |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | 获取或设置 DateTime 标记的秒分数。 |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | 获取或设置 DateTimeDigitized 标记的秒分数。 |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | 获取或设置 DateTimeOriginal 标记的秒分数。 |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | 获取或设置缩略图。 |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | 获取或设置传输函数。 |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | 获取或设置用户评论。 |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | 获取或设置白平衡。 |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置图像白点的色度。 |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 X 分辨率。 |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | 获取或设置色度分量相对于亮度分量的位置。 |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | 获取或设置色度分量相对于亮度分量的采样比率。 |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 Y 分辨率。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


初始化 JpegExifData 类的新实例。

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


使用数组中的数据初始化 JpegExifData 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 包含通用和 GPS 标签的 EXIF 标签数组。 |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


使用数组中的数据初始化 JpegExifData 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 通用标签。 |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | EXIF 标签。 |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | GPS 标签。 |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


允许的最大 EXIF 段大小（字节）。

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
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


获取或设置光圈值。

值：光圈值。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


获取或设置艺术家。

值：艺术家。

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


获取或设置每个样本的位数。

值：每样本位数。

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


获取或设置相机机身序列号。

值：机身序列号。

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


获取或设置亮度值。

值：亮度值。

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


获取或设置 CFA 模式。

值：CFA 模式。

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


获取或设置相机所有者名称

值：相机所有者的名称。

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


获取或设置色彩空间。

值：颜色空间。

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


获取或设置标签，这些标签属于公共部分。仅适用于 jpeg 图像，在 tiff 格式中使用 tiffOptions 替代。

值：公共部分标签。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


获取或设置组件配置。

值：组件配置。

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


获取或设置每像素压缩位数。

值：每像素压缩位数。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


获取或设置压缩方式。

值：压缩方式。

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


获取或设置对比度。

值：对比度。

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


获取或设置版权信息。

值：版权信息。

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


获取或设置自定义渲染。

值：自定义渲染。

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


获取或设置日期时间。

值：日期时间。

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


获取或设置数字化日期时间。

值：数字化日期时间。

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


获取或设置原始日期时间。

值：原始日期时间。

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


获取或设置设备设置描述

值：设备设置描述。

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


获取或设置数码变焦比例。

值：数字变焦比例。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


获取或设置仅属于 EXIF 部分的标签。

值：EXIF 部分标签。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


获取或设置 EXIF 版本。

值：EXIF 版本。

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


获取或设置曝光偏差值。

值：曝光偏差值。

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


获取或设置曝光指数。

值：曝光指数。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


获取或设置曝光模式。

值：曝光模式。

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


获取或设置曝光程序。

值：曝光程序。

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


获取或设置曝光时间。

值：曝光时间。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


获取或设置光圈数。

值：光圈值。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


获取或设置文件源类型。

值：文件来源类型。

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


获取或设置闪光灯。

值：闪光灯。

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


获取或设置闪光能量。

值：闪光能量。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


获取或设置闪光像素版本。

值：闪光像素版本。

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


获取或设置焦距。

值：焦距长度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


获取或设置 35 mm 胶片的焦距。

值：以 35 mm 胶片为基准的焦距。

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


获取或设置焦平面分辨率单位。

值：焦平面分辨率单位。

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


获取或设置焦平面 X 方向分辨率。

值：焦平面 X 方向分辨率。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


获取或设置焦平面 Y 方向分辨率。

值：焦平面 Y 方向分辨率。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


获取或设置 GPS 海拔。

值：GPS 海拔。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


获取或设置用作参考海拔的 GPS 海拔。

值：用作参考海拔的 GPS 海拔。

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


获取或设置 GPS 区域信息。

值：GPS 区域信息。

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


获取或设置 GPS DOP（数据精度等级）。

值：GPS DOP（数据精度等级）。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


获取或设置相对于 UTC（协调世界时）的 GPS 字符串记录日期和时间信息。

值：相对于 UTC（协调世界时）的 GPS 字符串记录的日期和时间信息。

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


获取或设置指向目的地点的 GPS 方位角。

值：指向目标点的 GPS 方位角。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


获取或设置用于提供指向目的地点方位角的 GPS 参考。

值：用于给出指向目标点的方位角的 GPS 参考。

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


获取或设置到目的地点的 GPS 距离。

值：到目标点的 GPS 距离。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


获取或设置用于表示到目的地点距离的 GPS 单位。

值：用于表示到目标点距离的 GPS 单位。

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


获取或设置目的地点的 GPS 纬度。

值：目标点的 GPS 纬度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。

值：指示目标点纬度是北纬还是南纬的 GPS 值。

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


获取或设置目的地点的 GPS 经度。

值：目标点的 GPS 经度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


获取或设置指示目的地点经度是东经还是西经的 GPS 值。

值：指示目标点经度是东经还是西经的 GPS 值。

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。

值：指示是否对 GPS 接收机应用差分校正的 GPS 值。

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


获取或设置图像拍摄时的 GPS 方向。

值：拍摄时图像的 GPS 方向。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


获取或设置图像拍摄时提供方向的 GPS 参考。

值：用于给出拍摄时图像方向的 GPS 参考。

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


获取或设置 GPS 纬度。

值：GPS 纬度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


获取或设置 GPS 纬度是北纬还是南纬。

值：GPS 纬度为北纬或南纬。

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


获取或设置 GPS 经度。

值：GPS 经度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


获取或设置 GPS 经度是东经还是西经。

值：GPS 经度为东经或西经。

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


获取或设置 GPS 接收器使用的 GPS 大地测量数据。

值：GPS 接收器使用的 GPS 大地测量数据。

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


获取或设置 GPS 测量模式。

值：GPS 测量模式。

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


获取或设置记录用于定位方法名称的 GPS 字符串。

值：记录用于定位的方法名称的 GPS 字符串。

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


获取或设置用于测量的 GPS 卫星。

值：用于测量的 GPS 卫星。

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


获取或设置 GPS 接收器移动的速度。

值：GPS 接收器移动的速度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


获取或设置用于表示 GPS 接收器移动速度的单位。

值：用于表示 GPS 接收器移动速度的单位。

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


获取或设置记录图像时 GPS 接收器的状态。

值：记录图像时 GPS 接收器的状态。

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


获取或设置仅属于 GPS 部分的标签。

值：GPS 标签。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


获取或设置 GPS 时间（UTC，协调世界时）。

值：UTC（协调世界时）形式的 GPS 时间。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


获取或设置 GPS 接收器移动的方向。

值：GPS 接收器移动的方向。

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


获取或设置提供 GPS 接收器移动方向的参考。

值：给出 GPS 接收器移动方向的参考。

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


获取或设置 GPS 版本标识符。

值：GPS 版本标识符。

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


获取或设置整体图像增益调整的程度。

值：整体图像增益调整的程度。

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


获取或设置伽马值。

值：伽马值。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


获取或设置 ISO 速度。

值：ISO 速度。

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。

值：ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 yyy 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudezzz，则不应记录此标签。

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。

值：ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 zzz 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudeyyy，则不应记录此标签。

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


获取或设置图像描述。

值：图像描述。

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


获取或设置图像长度。

值：图像的长度。

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


获取或设置图像唯一标识符。

值：图像唯一标识符。

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


获取或设置图像宽度。

值：图像的宽度。

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


获取或设置镜头制造商。

值：镜头制造商。

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


获取或设置镜头型号。

值：镜头型号。

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


获取或设置镜头序列号。

值：镜头序列号。

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


获取或设置镜头规格

值：镜头规格。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


获取或设置光源。

值：光源。

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


获取录制设备的制造商。

值：录音设备的制造商。

**Returns:**
java.lang.String - 录音设备的制造商。
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


获取制造商注释数据。

值：制造商注释数据。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


获取或设置制造商注释原始数据。

值：制造商注释原始数据。

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


获取制造商注释。

值：制造商注释。

**Returns:**
com.aspose.psd.exif.MakerNote[] - 制造商注释。
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


获取或设置最大光圈值。

值：最大光圈值。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


获取或设置测光模式。

值：测光模式。

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


获取或设置模型。

值：模型。

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。

值：ISO 14524 中指定的光电转换函数 (OECF)。

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


获取或设置方向。

值：方向。

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


获取或设置感光度。

值：感光度。

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


获取或设置光度解释。

值：光度解释。

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


获取或设置像素 X 维度。

值：像素 X 维度。

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


获取或设置像素 Y 维度。

值：像素 Y 维度。

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


获取或设置平面配置。

值：平面配置。

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


获取或设置图像三原色的色度。

值：图像三原色的色度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


获取或设置所有 EXIF 标签（包括通用标签和 GPS 标签）。

值：EXIF 标签（包括通用标签和 GPS 标签）。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


获取或设置推荐曝光指数。

值：推荐曝光指数。

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


获取或设置参考黑白。

值：参考黑白。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


获取或设置相关音频文件。

值：相关的声音文件。

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


获取或设置分辨率单位。

值：分辨率单位。

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


获取或设置每像素采样数。

值：每像素样本数。

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


获取或设置饱和度。

值：饱和度。

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


获取或设置场景捕获类型。

值：场景捕获类型。

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


获取或设置场景类型。

值：场景类型。

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


获取或设置感应方法。

值：感测方法。

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


获取或设置灵敏度类型。

值：灵敏度类型。

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


获取或设置锐度。

值：锐度。

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


获取或设置快门速度值。

值：快门速度值。

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


获取或设置软件。

值：软件。

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


获取或设置空间频率响应。

值：空间频率响应。

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


获取或设置光谱灵敏度。

值：光谱灵敏度。

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


获取标准输出灵敏度

值：标准输出灵敏度。

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


获取或设置主体区域。

值：主题区域。

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


获取或设置主体距离。

值：主题距离。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


获取或设置主体距离范围。

值：主题距离范围。

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


获取或设置主体位置。

值：主题位置。

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


获取或设置 DateTime 标记的秒分数。

值：DateTime 标签的秒分数。

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


获取或设置 DateTimeDigitized 标记的秒分数。

值：DateTimeDigitized 标签的秒分数。

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


获取或设置 DateTimeOriginal 标记的秒分数。

值：DateTimeOriginal 标签的秒分数。

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


获取或设置缩略图。

值：缩略图。

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


获取或设置传输函数。

值：传输函数。

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


获取或设置用户评论。

值：用户评论。

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


获取或设置白平衡。

值：白平衡。

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


获取或设置图像白点的色度。

值：图像白点的色度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


获取或设置 X 分辨率。

值：X 方向分辨率。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。

值：从 RGB 到 YCbCr 图像数据转换的矩阵系数。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


获取或设置色度分量相对于亮度分量的位置。

值：色度分量相对于亮度分量的位置。

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


获取或设置色度分量相对于亮度分量的采样比率。

值：色度分量相对于亮度分量的采样比率。

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


获取或设置 Y 分辨率。

值：Y 方向分辨率。

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


获取或设置一个值，以指示从中创建的流 EXIF 数据是否为大端序。

值：如果从中创建的流 EXIF 数据是大端序，则为 true；否则为 false。

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


从容器中移除标签

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tagId | int | 要删除的标签标识符。 |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


序列化 EXIF 数据。写入标签值和内容。最影响大小的标签是缩略图标签内容。

**Returns:**
byte[] - 序列化的 EXIF 数据。

整个段的大小必须小于或等于 MaxExifSegmentSize 字节，以生成正确的 jpeg 图像。提示：如果 EXIF 部分大小过大，请尝试减小缩略图尺寸或更改其压缩方式。
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


获取或设置光圈值。

值：光圈值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


获取或设置艺术家。

值：艺术家。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


获取或设置一个值，以指示从中创建的流 EXIF 数据是否为大端序。

值：如果从中创建的流 EXIF 数据是大端序，则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


获取或设置每个样本的位数。

值：每样本位数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


获取或设置相机机身序列号。

值：机身序列号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


获取或设置亮度值。

值：亮度值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


获取或设置 CFA 模式。

值：CFA 模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


获取或设置相机所有者名称

值：相机所有者的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


获取或设置色彩空间。

值：颜色空间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


获取或设置标签，这些标签属于公共部分。仅适用于 jpeg 图像，在 tiff 格式中使用 tiffOptions 替代。

值：公共部分标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


获取或设置组件配置。

值：组件配置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


获取或设置每像素压缩位数。

值：每像素压缩位数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


获取或设置压缩方式。

值：压缩方式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


获取或设置对比度。

值：对比度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


获取或设置版权信息。

值：版权信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


获取或设置自定义渲染。

值：自定义渲染。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


获取或设置日期时间。

值：日期时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


获取或设置数字化日期时间。

值：数字化日期时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


获取或设置原始日期时间。

值：原始日期时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


获取或设置设备设置描述

值：设备设置描述。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


获取或设置数码变焦比例。

值：数字变焦比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


获取或设置仅属于 EXIF 部分的标签。

值：EXIF 部分标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


获取或设置 EXIF 版本。

值：EXIF 版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


获取或设置曝光偏差值。

值：曝光偏差值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


获取或设置曝光指数。

值：曝光指数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


获取或设置曝光模式。

值：曝光模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


获取或设置曝光程序。

值：曝光程序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


获取或设置曝光时间。

值：曝光时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


获取或设置光圈数。

值：光圈值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


获取或设置文件源类型。

值：文件来源类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


获取或设置闪光灯。

值：闪光灯。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


获取或设置闪光能量。

值：闪光能量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


获取或设置闪光像素版本。

值：闪光像素版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


获取或设置焦距。

值：焦距长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


获取或设置 35 mm 胶片的焦距。

值：以 35 mm 胶片为基准的焦距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


获取或设置焦平面分辨率单位。

值：焦平面分辨率单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


获取或设置焦平面 X 方向分辨率。

值：焦平面 X 方向分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


获取或设置焦平面 Y 方向分辨率。

值：焦平面 Y 方向分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


获取或设置 GPS 海拔。

值：GPS 海拔。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


获取或设置用作参考海拔的 GPS 海拔。

值：用作参考海拔的 GPS 海拔。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


获取或设置 GPS 区域信息。

值：GPS 区域信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


获取或设置 GPS DOP（数据精度等级）。

值：GPS DOP（数据精度等级）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


获取或设置相对于 UTC（协调世界时）的 GPS 字符串记录日期和时间信息。

值：相对于 UTC（协调世界时）的 GPS 字符串记录的日期和时间信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


获取或设置指向目的地点的 GPS 方位角。

值：指向目标点的 GPS 方位角。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


获取或设置用于提供指向目的地点方位角的 GPS 参考。

值：用于给出指向目标点的方位角的 GPS 参考。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


获取或设置到目的地点的 GPS 距离。

值：到目标点的 GPS 距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


获取或设置用于表示到目的地点距离的 GPS 单位。

值：用于表示到目标点距离的 GPS 单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


获取或设置目的地点的 GPS 纬度。

值：目标点的 GPS 纬度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。

值：指示目标点纬度是北纬还是南纬的 GPS 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


获取或设置目的地点的 GPS 经度。

值：目标点的 GPS 经度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


获取或设置指示目的地点经度是东经还是西经的 GPS 值。

值：指示目标点经度是东经还是西经的 GPS 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。

值：指示是否对 GPS 接收机应用差分校正的 GPS 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


获取或设置图像拍摄时的 GPS 方向。

值：拍摄时图像的 GPS 方向。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


获取或设置图像拍摄时提供方向的 GPS 参考。

值：用于给出拍摄时图像方向的 GPS 参考。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


获取或设置 GPS 纬度。

值：GPS 纬度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


获取或设置 GPS 纬度是北纬还是南纬。

值：GPS 纬度为北纬或南纬。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


获取或设置 GPS 经度。

值：GPS 经度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


获取或设置 GPS 经度是东经还是西经。

值：GPS 经度为东经或西经。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


获取或设置 GPS 接收器使用的 GPS 大地测量数据。

值：GPS 接收器使用的 GPS 大地测量数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


获取或设置 GPS 测量模式。

值：GPS 测量模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


获取或设置记录用于定位方法名称的 GPS 字符串。

值：记录用于定位的方法名称的 GPS 字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


获取或设置用于测量的 GPS 卫星。

值：用于测量的 GPS 卫星。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


获取或设置 GPS 接收器移动的速度。

值：GPS 接收器移动的速度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


获取或设置用于表示 GPS 接收器移动速度的单位。

值：用于表示 GPS 接收器移动速度的单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


获取或设置记录图像时 GPS 接收器的状态。

值：记录图像时 GPS 接收器的状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


获取或设置仅属于 GPS 部分的标签。

值：GPS 标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


获取或设置 GPS 时间（UTC，协调世界时）。

值：UTC（协调世界时）形式的 GPS 时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


获取或设置 GPS 接收器移动的方向。

值：GPS 接收器移动的方向。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


获取或设置提供 GPS 接收器移动方向的参考。

值：给出 GPS 接收器移动方向的参考。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


获取或设置 GPS 版本标识符。

值：GPS 版本标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


获取或设置整体图像增益调整的程度。

值：整体图像增益调整的程度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


获取或设置伽马值。

值：伽马值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


获取或设置 ISO 速度。

值：ISO 速度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。

值：ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 yyy 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudezzz，则不应记录此标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。

值：ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 zzz 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudeyyy，则不应记录此标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


获取或设置图像描述。

值：图像描述。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


获取或设置图像长度。

值：图像的长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


获取或设置图像唯一标识符。

值：图像唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


获取或设置图像宽度。

值：图像的宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


获取或设置镜头制造商。

值：镜头制造商。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


获取或设置镜头型号。

值：镜头型号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


获取或设置镜头序列号。

值：镜头序列号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


获取或设置镜头规格

值：镜头规格。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


获取或设置光源。

值：光源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


设置录音设备的制造商。

值：录音设备的制造商。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 记录设备的制造商。 |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


获取或设置制造商注释原始数据。

值：制造商注释原始数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


获取或设置最大光圈值。

值：最大光圈值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


获取或设置测光模式。

值：测光模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


获取或设置模型。

值：模型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。

值：ISO 14524 中指定的光电转换函数 (OECF)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


获取或设置方向。

值：方向。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


获取或设置感光度。

值：感光度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


获取或设置光度解释。

值：光度解释。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


获取或设置像素 X 维度。

值：像素 X 维度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


获取或设置像素 Y 维度。

值：像素 Y 维度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


获取或设置平面配置。

值：平面配置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


获取或设置图像三原色的色度。

值：图像三原色的色度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


获取或设置所有 EXIF 标签（包括通用标签和 GPS 标签）。

值：EXIF 标签（包括通用标签和 GPS 标签）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


获取或设置推荐曝光指数。

值：推荐曝光指数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


获取或设置参考黑白。

值：参考黑白。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


获取或设置相关音频文件。

值：相关的声音文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


获取或设置分辨率单位。

值：分辨率单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


获取或设置每像素采样数。

值：每像素样本数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


获取或设置饱和度。

值：饱和度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


获取或设置场景捕获类型。

值：场景捕获类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


获取或设置场景类型。

值：场景类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


获取或设置感应方法。

值：感测方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


获取或设置灵敏度类型。

值：灵敏度类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


获取或设置锐度。

值：锐度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


获取或设置快门速度值。

值：快门速度值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


获取或设置软件。

值：软件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


获取或设置空间频率响应。

值：空间频率响应。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


获取或设置光谱灵敏度。

值：光谱灵敏度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


设置标准输出灵敏度

值：标准输出灵敏度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


获取或设置主体区域。

值：主题区域。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


获取或设置主体距离。

值：主题距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


获取或设置主体距离范围。

值：主题距离范围。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


获取或设置主体位置。

值：主题位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


获取或设置 DateTime 标记的秒分数。

值：DateTime 标签的秒分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


获取或设置 DateTimeDigitized 标记的秒分数。

值：DateTimeDigitized 标签的秒分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


获取或设置 DateTimeOriginal 标记的秒分数。

值：DateTimeOriginal 标签的秒分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


获取或设置缩略图。

值：缩略图。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


获取或设置传输函数。

值：传输函数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


获取或设置用户评论。

值：用户评论。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


获取或设置白平衡。

值：白平衡。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


获取或设置图像白点的色度。

值：图像白点的色度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


获取或设置 X 分辨率。

值：X 方向分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。

值：从 RGB 到 YCbCr 图像数据转换的矩阵系数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


获取或设置色度分量相对于亮度分量的位置。

值：色度分量相对于亮度分量的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


获取或设置色度分量相对于亮度分量的采样比率。

值：色度分量相对于亮度分量的采样比率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


获取或设置 Y 分辨率。

值：Y 方向分辨率。

**Parameters:**
| Parameter | Type | 描述 |
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

