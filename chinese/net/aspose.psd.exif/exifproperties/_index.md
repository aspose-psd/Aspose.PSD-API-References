---
title: Enum ExifProperties
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Exif.ExifProperties 枚举. Exif 标签列表
type: docs
weight: 1000
url: /zh/net/aspose.psd.exif/exifproperties/
---
## ExifProperties enumeration

Exif 标签列表

```csharp
public enum ExifProperties : ushort
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| ImageWidth | `256` | 图像数据的列数，等于每行的像素数。 |
| ImageLength | `257` | 图像数据的行数。 |
| BitsPerSample | `258` | 每个图像分量的位数。在此标准中，图像的每个分量都是 8 位，因此此标记的值为 8. |
| Compression | `259` | 用于图像数据的压缩方案。当主图像为 JPEG 压缩时，此指定不是必需的且被省略。 |
| PhotometricInterpretation | `262` | 像素组成。 |
| ImageDescription | `270` | 给出图像标题的字符串。可能是“1988公司野餐”之类的评论。 |
| Make | `271` | 录音设备的制造商。这是 DSC、扫描仪、视频数字转换器或其他生成图像的设备的制造商。当该字段留空时，它被视为未知。 |
| Model | `272` | 设备的型号名称或型号。这是生成图像的 DSC、扫描仪、视频数字转换器或其他设备的型号名称或编号。当该字段留空时，它被视为未知。 |
| Orientation | `274` | 根据行和列查看的图像方向。 |
| SamplesPerPixel | `277` | 每个像素的分量数。由于这个标准适用于RGB和YCbCr图像，所以这个标签的值设置为3. |
| XResolution | `282` | ImageWidth 方向上每个 ResolutionUnit 的像素数。当图像分辨率未知时，指定 72 [dpi]。 |
| YResolution | `283` | ImageLength 方向上每个 ResolutionUnit 的像素数。指定与 XResolution 相同的值。 |
| PlanarConfiguration | `284` | 表示像素分量是以块格式还是平面格式记录的。如果此字段不存在，则假定 TIFF 默认值为 1（矮胖）。 |
| ResolutionUnit | `296` | 测量XResolution和YResolution的单位。 XResolution 和 YResolution 使用相同的单位。如果图像分辨率未知，则指定 2（英寸）。 |
| TransferFunction | `301` | 图像的传递函数，以表格形式描述。通常这个标签不是必需的，因为颜色空间是在颜色空间信息 ColorSpace 标签中指定的。 |
| Software | `305` | 该标签记录了用于生成图像的相机或图像输入设备的软件或固件的名称和版本。未指定详细格式，但建议遵循以下示例。当该字段留空时，它被视为未知。 |
| DateTime | `306` | 创建图像的日期和时间。在 Exif 标准中，它是文件更改的日期和时间。 |
| Artist | `315` | 这个标签记录了相机所有者、摄影师或图像创作者的姓名。具体格式不详，但为了便于互操作，建议按照下面的例子来写信息。当该字段留空时，它被视为未知。例如）“相机所有者，约翰·史密斯；摄影师，迈克尔·布朗；图像创作者，肯·詹姆斯” |
| WhitePoint | `318` | 图像白点的色度。通常这个标签不是必需的，因为色彩空间是在色彩空间信息 ColorSpace 标签中指定的。 |
| PrimaryChromaticities | `319` | 图像三基色的色度。通常这个标签不是必需的，因为色彩空间是在色彩空间信息 ColorSpace 标签中指定的。 |
| YCbCrCoefficients | `529` | RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| YCbCrSubSampling | `530` | 色度分量相对于亮度分量的采样率。 |
| YCbCrPositioning | `531` | 色度分量相对于 the 亮度分量的位置。该字段仅指定用于 JPEG 压缩数据或未压缩的 YCbCr 数据。 TIFF 默认为 1（居中）；但当Y:Cb:Cr = 4:2:2时，本标准建议 使用2（co-site）来 记录数据，以提高在电视系统上观看 时的图像质量。当该字段不存在时，阅读器应 假定 TIFF 默认值。在 Y:Cb:Cr = 4:2:0 的情况下，建议使用 TIFF 默认值（居中）。如果reader 不具备同时支持两种 YCbCrPositioning的能力，则无论 该字段的值如何，它都应遵循TIFF默认值。读者最好“ 能够支持居中定位和同位定位。 |
| ReferenceBlackWhite | `532` | 参考黑点值和参考白点 值。 TIFF 中没有给出默认值，但下面的值在此处作为默认值给出。 颜色空间在颜色空间信息标记中声明 ，默认 是给出最佳图像特性的值 互操作性这些条件 |
| Copyright | `33432` | 版权信息。在此标准中，标签用于 表示摄影师和编辑的版权。它是 声称对图像拥有 权利的个人或组织的版权声明。 Interoperability copyright statement including date and rights should be written in this field;例如，“版权所有，John Smith，19xx。保留所有权利 。”。在此标准中，该字段记录了 摄影师和编辑版权，每个都记录在 a 声明的单独部分中。当摄影师和编辑版权之间有明确区分 时，这些将按照摄影师在后编辑版权的顺序写 ， 以NULL分隔（在这种情况下，由于声明也以 结尾为NULL，因此有两个NULL代码).当只给出 photographer copyright 时，它被一个 NULL code 终止。当只有 编辑版权时，摄影师版权部分 由一个空格后跟一个终止NULL代码组成，然后给予 编辑版权。当该字段留空时，它被 视为未知。 |
| ExposureTime | `33434` | 曝光时间，以秒为单位。 |
| FNumber | `33437` | F 编号。 |
| ExposureProgram | `34850` | 拍照时相机设置曝光的程序类。 |
| SpectralSensitivity | `34852` | 表示所用相机各通道的光谱灵敏度。 |
| PhotographicSensitivity | `34855` | 表示 ISO 12232. 中指定的相机或输入设备的 ISO 速度和 ISO 纬度 |
| OECF | `34856` | 表示ISO 14524. 中规定的光电转换功能（OECF） |
| ExifVersion | `36864` | exif 版本。 |
| DateTimeOriginal | `36867` | 原始图像数据生成的日期和时间。 |
| DateTimeDigitized | `36868` | 数字化的日期时间。 |
| ComponentsConfiguration | `37121` | 组件配置。 |
| CompressedBitsPerPixel | `37122` | 特定于压缩数据；说明每个像素的压缩位数。 |
| ShutterSpeedValue | `37377` | 快门速度值。 |
| ApertureValue | `37378` | 镜头光圈值。 |
| BrightnessValue | `37379` | 亮度值。 |
| ExposureBiasValue | `37380` | 曝光偏差值。 |
| MaxApertureValue | `37381` | 最大光圈值. |
| SubjectDistance | `37382` | 到主题的距离，以米为单位。 |
| MeteringMode | `37383` | 测光模式。 |
| LightSource | `37384` | 那种光源. |
| Flash | `37385` | 指示拍摄图像时闪光灯的状态。 |
| FocalLength | `37386` | 镜头实际焦距，单位mm. |
| SubjectArea | `37396` | 这个标签表示主体在整个场景中的位置和面积。 |
| MakerNote | `37500` | Exif 写入器制造商用于记录任何所需信息的标签。内容由制造商决定，但此标签不得用于其预期目的以外的任何用途。 |
| UserComment | `37510` | Exif用户在ImageDescription之外的图片上写关键字或评论的标签，没有ImageDescription标签的字符编码限制。 |
| SubsecTime | `37520` | 用于为 DateTime 标记记录小数秒的标记。 |
| SubsecTimeOriginal | `37521` | 用于记录 DateTimeOriginal 标签的小数秒的标签。 |
| SubsecTimeDigitized | `37522` | 用于为 DateTimeDigitized 标记记录小数秒的标记。 |
| FlashpixVersion | `40960` | FPXR 文件支持的 Flashpix 格式版本。 |
| ColorSpace | `40961` | 颜色空间信息标签（ColorSpace）总是被记录为颜色空间说明符。 |
| RelatedSoundFile | `40964` | 相关声音文件. |
| FlashEnergy | `41483` | 表示拍摄图像时的频闪能量，以 Beam Candle Power Seconds (BCPS) 为单位测量。 |
| SpatialFrequencyResponse | `41484` | 该标签记录相机或输入设备空间频率表和图像宽度、图像高度和对角线方向的SFR值，如ISO 12233. |
| FocalPlaneXResolution | `41486` | 表示相机焦平面上每个FocalPlaneResolutionUnit在图像宽度（X）方向的像素数。 |
| FocalPlaneYResolution | `41487` | 表示相机焦平面上每个FocalPlaneResolutionUnit在图像高度（Y）方向的像素数。 |
| FocalPlaneResolutionUnit | `41488` | 表示测量FocalPlaneXResolution和FocalPlaneYResolution的单位。此值与 ResolutionUnit. 相同 |
| SubjectLocation | `41492` | 表示场景中主体的位置。此标签的值表示在根据旋转标签进行旋转处理之前，主体中心相对于左边缘的像素。 |
| ExposureIndex | `41493` | 表示拍摄图像时在相机或输入设备上选择的曝光指数。 |
| SensingMethod | `41495` | 表示相机或输入设备上的图像传感器类型。 |
| FileSource | `41728` | 文件来源. |
| SceneType | `41729` | 表示场景类型。如果 DSC 记录了图像，则此标记值应始终设置为 1，表示图像是直接拍摄的。 |
| CFAPattern | `41730` | 指示使用单芯片彩色区域传感器时图像传感器的彩色滤光片阵列 (CFA) 几何图案。它不适用于所有传感方法。 |
| CustomRendered | `41985` | 该标签表示对图像数据进行特殊处理，例如渲染输出。执行特殊处理时，希望读者禁用或最小化任何进一步处理。 |
| ExposureMode | `41986` | 该标签表示拍摄图像时设置的曝光模式。在自动包围模式下，相机以不同的曝光设置拍摄同一场景的一系列画面。 |
| WhiteBalance | `41987` | 此标签表示拍摄图像时设置的白平衡模式。 |
| DigitalZoomRatio | `41988` | 该标签表示拍摄图像时的数码变焦倍率。如果记录值的分子为0，则表示未使用数码变焦。 |
| FocalLengthIn35MmFilm | `41989` | 该标签表示假设使用 35mm 胶片相机时的等效焦距，单位为毫米。值为 0 表示焦距未知。请注意，此标签不同于 FocalLength 标签。 |
| SceneCaptureType | `41990` | 此标签表示拍摄的场景类型。它还可用于记录拍摄图像的模式。 |
| GainControl | `41991` | 该标签表示整体图像增益调整的程度。 |
| Contrast | `41992` | 此标签表示拍摄图像时相机应用的对比度处理方向。 |
| Saturation | `41993` | 该标签表示拍摄图像时相机应用饱和度处理的方向。 |
| Sharpness | `41994` | 该标签表示拍摄图像时相机应用锐度处理的方向 |
| DeviceSettingDescription | `41995` | 该标签表示特定相机型号的拍照条件信息。该标签仅用于表明读写器中的拍照条件。 |
| SubjectDistanceRange | `41996` | 这个标签表示到主体的距离。 |
| ImageUniqueID | `42016` | 图像唯一标识。 |
| GPSVersionID | `0` | 表示GPSInfoIFD的版本。 |
| GPSLatitudeRef | `1` | 表示纬度是北纬还是南纬。 |
| GPSLatitude | `2` | 表示纬度。纬度表示为三个 RATIONAL 值，分别给出度、分和 秒。如果纬度以度、分和秒表示，则典型格式为 dd/1,mm/1,ss/1。当使用度和分时，例如，分的小数最多为 two 个小数位，格式为 dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | 表示经度是东经还是西经。 |
| GPSLongitude | `4` | 表示经度。经度表示为三个 RATIONAL 值，分别给出度、分和 秒。如果经度表示为度、分和秒，则典型格式为 ddd/1,mm/1,ss/1。当使用度和分时，例如，分的小数最多为 two 个小数位，格式为 ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | 表示用作参考高度的高度。如果参考是海平面并且高度高于海平面，则给出 0。如果高度低于海平面，则给出值 1，高度在 GPSAltitude 标签中表示为绝对值。 |
| GPSAltitude | `6` | 指示基于 GPSAltitudeRef 中参考的高度。高度表示为一个RATIONAL值。 参考单位是米。 |
| GPSTimestamp | `7` | 表示时间为 UTC（协调世界时）。 TimeStamp 表示为三个 RATIONAL 值 给出小时、分钟和秒。 |
| GPSSatellites | `8` | 指示用于测量的 GPS 卫星。这个标签可以用ASCII符号来描述卫星的数量， 它们的ID号，仰角，方位角，SNR等信息。格式未指定 。如果 GPS 接收器无法进行测量，则标签的值应设置为 NULL. |
| GPSStatus | `9` | 指示记录图像时 GPS 接收器的状态。 |
| GPSMeasureMode | `10` | 表示GPS测量模式。 - 2 维或 3 维。 |
| GPSDOP | `11` | 表示 GPS DOP（数据精度）。二维测量时写入HDOP值，三维测量时写入 和PDOP值. |
| GPSSpeedRef | `12` | 表示用于表示 GPS 接收器移动速度的单位。 'K' 'M' 和 'N' 代表公里数 per 小时、英里每小时和节。 |
| GPSSpeed | `13` | 指示GPS接收器移动的速度。 |
| GPSTrackRef | `14` | 表示给出GPS接收机运动方向的参考。 'T'表示真实方向，'M'是 磁方向. |
| GPSTrack | `15` | 指示 GPS 接收器移动的方向。值的范围是从 0.00 到 359.99. |
| GPSImgDirectionRef | `16` | 表示拍摄时给出图像方向的参考。 'T'表示真实方向，'M'是 磁方向. |
| GPSImgDirection | `17` | 表示拍摄图像时的方向。值的范围是从 0.00 到 359.99. |
| GPSMapDatum | `18` | 指示GPS接收器使用的大地测量数据。 |
| GPSDestLatitudeRef | `19` | 表示目的地点的纬度是北纬还是南纬。 ASCII 值‘N’表示北纬 ，‘S’表示南纬. |
| GPSDestLatitude | `20` | 表示目的地点的纬度。纬度表示为三个 RATIONAL 值，分别给出 度、分和秒。如果纬度以度、分和秒表示，典型的 格式将为 dd/1,mm/1,ss/1。当使用度和分时，例如，分的分数是 ，最多保留两位小数，格式为 dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | 表示目的地点的经度是东经还是西经。 ASCII 'E' 表示东经， 和 'W' 是西经. |
| GPSDestLongitude | `22` | 表示目的地点的经度。经度表示为三个 RATIONAL 值，分别给出 度、分和秒。如果经度表示为度、分和秒，则典型的 格式将为 ddd/1,mm/1,ss/1。当使用度和分时，例如，分的分数是 ，最多保留两位小数，格式为 ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | 指示用于将方位提供给目标点的参考。 'T'表示真实方向，'M'是 磁方向. |
| GPSDestBearing | `24` | 表示到目的地点的方位。值的范围是从 0.00 到 359.99. |
| GPSDestDistanceRef | `25` | 表示用来表示到目的地点的距离的单位。 'K'、'M'和'N'代表公里，miles 和knots. |
| GPSDestDistance | `26` | 表示到目标点的距离。 |
| GPSProcessingMethod | `27` | 字符串，记录用于定位的方法名称。 第一个字节表示使用的字符代码，后面是方法名称 。 |
| GPSAreaInformation | `28` | 记录GPS区域名称的字符串。第一个字节表示 使用的字符代码，后面是GPS区域的名称。 |
| GPSDateStamp | `29` | 记录相对于UTC （协调世界时）的日期和时间信息的字符串。格式为 YYYY:MM:DD. |
| GPSDifferential | `30` | 指示差分校正是否应用于 GPS 接收器。 |
| StripOffsets | `273` | 对于每个条带，该条带的字节偏移量。建议选择此项，以便条带字节数不超过 64 KB。 Aux tag. |
| JPEGInterchangeFormat | `513` | JPEG 压缩缩略图数据的起始字节 (SOI) 的偏移量。这不用于主要图像 JPEG 数据。 |
| JPEGInterchangeFormatLength | `514` | JPEG 压缩缩略图数据的字节数。这不用于主要图像 JPEG 数据。 JPEG 缩略图不被分割，而是记录为从 SOI 到 EOI 的连续 JPEG 比特流。不应记录 Appn 和 COM 标记。压缩缩略图必须记录在不超过 64 KB 的范围内，包括要记录在 APP1. 中的所有其他数据 |
| ExifIfdPointer | `34665` | 指向 Exif IFD 的指针。互操作性，Exif IFD 与 TIFF 中指定的 IFD 具有相同的结构。然而，通常它不包含图像数据，如 TIFF. |
| GPSIfdPointer | `34853` | gps ifd 指针。 |
| RowsPerStrip | `278` | 每个条带的行数。这是一个图像被分成条带时，一个条带图像的行数。 |
| StripByteCounts | `279` | 每个条带中的总字节数。 |
| PixelXDimension | `40962` | 特定于压缩数据的信息。记录压缩文件时，无论是否有填充数据或重启标记，都应在该标签中记录有意义图像的有效宽度。 |
| PixelYDimension | `40963` | 特定于压缩数据的信息。记录压缩文件时，在这个tag 中记录有意义图片的有效高度 |
| Gamma | `42240` | 伽玛值 |
| SensitivityType | `34864` | 感光度类型 |
| StandardOutputSensitivity | `34865` | 表示camera 的标准输出灵敏度 |
| RecommendedExposureIndex | `34866` | 表示推荐曝光指数 |
| ISOSpeed | `34867` | ISO 12232 中定义的有关 iso 速度值的信息 |
| ISOSpeedLatitudeYYY | `34868` | 此标签表示 ISO 速度纬度 yyy 值，如 ISO 12232 中所定义 |
| ISOSpeedLatitudeZZZ | `34869` | 此标签表示 ISO 速度纬度 zzz 值，如 ISO 12232 中所定义 |
| CameraOwnerName | `42032` | 包含相机所有者名称 |
| BodySerialNumber | `42033` | 包含相机机身序列号 |
| LensMake | `42035` | 这个标签记录了镜头制造商 |
| LensModel | `42036` | 这个标签记录了镜头的型号名称和型号 |
| LensSerialNumber | `42037` | 这个标签记录了可更换镜头的序列号 |
| LensSpecification | `42034` | 这个标签标注了最小焦距、最大焦距、最小焦距中的最小F数和最大焦距中的最小F数 |

### 也可以看看

* 命名空间 [Aspose.PSD.Exif](../../aspose.psd.exif/)
* 部件 [Aspose.PSD](../../)


