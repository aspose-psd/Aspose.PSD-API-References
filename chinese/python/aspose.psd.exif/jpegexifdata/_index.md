---
title: "JpegExifData 类"
type: docs
weight: 20
url: /zh/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | 初始化 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 类的新实例。 |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | 使用数组中的数据初始化 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 类的新实例。 |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | 使用数组中的数据初始化 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | 允许的最大 EXIF 段大小（字节）。 |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置光圈值。 |
| 艺术家 | 字符串 | 读/写 | 获取或设置艺术家。 |
| bits_per_sample | ushort | 读/写 | 获取或设置每个样本的位数。 |
| body_serial_number | 字符串 | 读/写 | 获取或设置相机机身序列号。 |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 获取或设置亮度值。 |
| camera_owner_name | 字符串 | 读/写 | 获取或设置相机所有者名称 |
| cfa_pattern | byte | 读/写 | 获取或设置 CFA 模式。 |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | 获取或设置颜色空间。 |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置属于公共部分的标签。此仅适用于 jpeg 图像，在 tiff 格式中使用 tiffOptions 替代。 |
| components_configuration | byte | 读/写 | 获取或设置组件配置。 |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置每像素压缩位数。 |
| compression | ushort | 读/写 | 获取或设置压缩方式。 |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | 获取或设置对比度。 |
| copyright | 字符串 | 读/写 | 获取或设置版权。 |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | 获取或设置自定义渲染。 |
| date_time | 字符串 | 读/写 | 获取或设置日期时间。 |
| date_time_digitized | 字符串 | 读/写 | 获取或设置数字化日期时间。 |
| date_time_original | 字符串 | 读/写 | 获取或设置原始日期时间。 |
| device_setting_description | byte | 读/写 | 获取或设置设备设置描述 |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置数字变焦比例。 |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置仅属于 EXIF 部分的标签。 |
| exif_version | byte | 读/写 | 获取或设置 EXIF 版本。 |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 获取或设置曝光偏差值。 |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置曝光指数。 |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | 获取或设置曝光模式。 |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | 获取或设置曝光程序。 |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置曝光时间。 |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置光圈值。 |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | 获取或设置文件来源类型。 |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | 获取或设置闪光灯。 |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置闪光能量。 |
| flashpix_version | byte | 读/写 | 获取或设置闪光像素版本。 |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置焦距。 |
| focal_length_in_35_mm_film | ushort | 读/写 | 获取或设置 35 毫米胶片中的焦距。 |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | 获取或设置焦平面分辨率单位。 |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置焦平面 X 分辨率。 |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置焦平面 Y 分辨率。 |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | 获取或设置整体图像增益调整的程度。 |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置伽马。 |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 海拔。 |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | 获取或设置用作参考海拔的 GPS 海拔。 |
| gps_area_information | byte | 读/写 | 获取或设置 GPS 区域信息。 |
| gps_date_stamp | 字符串 | 读/写 | 获取或设置相对于 UTC（协调世界时）的 GPS 字符串记录的日期和时间信息。 |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置指向目的地点的 GPS 方位角。 |
| gps_dest_bearing_ref | 字符串 | 读/写 | 获取或设置用于给出指向目的地点方位角的 GPS 参考。 |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置到目的地点的 GPS 距离。 |
| gps_dest_distance_ref | 字符串 | 读/写 | 获取或设置用于表示到目的地点距离的 GPS 单位。 |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置目的地点的 GPS 纬度。 |
| gps_dest_latitude_ref | 字符串 | 读/写 | 获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。 |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置目的地点的 GPS 经度。 |
| gps_dest_longitude_ref | 字符串 | 读/写 | 获取或设置指示目的地点经度是东经还是西经的 GPS 值。 |
| gps_differential | ushort | 读/写 | 获取或设置一个 GPS 值，用于指示是否对 GPS 接收器应用差分校正。 |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置图像拍摄时的 GPS 方向。 |
| gps_img_direction_ref | 字符串 | 读/写 | 获取或设置用于指示图像拍摄时方向的 GPS 参考。 |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 纬度。 |
| gps_latitude_ref | 字符串 | 读/写 | 获取或设置 GPS 纬度是北纬还是南纬。 |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 经度。 |
| gps_longitude_ref | 字符串 | 读/写 | 获取或设置 GPS 经度是东经还是西经。 |
| gps_map_datum | 字符串 | 读/写 | 获取或设置 GPS 接收器使用的 GPS 大地测量数据。 |
| gps_measure_mode | 字符串 | 读/写 | 获取或设置 GPS 测量模式。 |
| gps_processing_method | byte | 读/写 | 获取或设置记录用于定位的方法名称的 GPS 字符串。 |
| gps_satellites | 字符串 | 读/写 | 获取或设置用于测量的 GPS 卫星。 |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 接收器移动的速度。 |
| gps_speed_ref | 字符串 | 读/写 | 获取或设置用于表示 GPS 接收器移动速度的单位。 |
| gps_status | 字符串 | 读/写 | 获取或设置图像记录时 GPS 接收器的状态。 |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置仅属于 GPS 部分的标签。 |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 时间为 UTC（协调世界时）。 |
| gps_track | 字符串 | 读/写 | 获取或设置 GPS 接收器移动方向。 |
| gps_track_ref | 字符串 | 读/写 | 获取或设置用于指示 GPS 接收器移动方向的参考。 |
| gps_version_id | byte | 读/写 | 获取或设置 GPS 版本标识符。 |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS DOP（数据精度等级）。 |
| image_description | 字符串 | 读/写 | 获取或设置图像描述。 |
| image_length | uint | 读/写 | 获取或设置图像长度。 |
| image_unique_id | 字符串 | 读/写 | 获取或设置图像唯一标识符。 |
| image_width | uint | 读/写 | 获取或设置图像宽度。 |
| is_big_endian | bool | 读/写 | 获取或设置一个值，指示用于创建流 EXIF 数据的字节序是否为大端序。 |
| iso_speed | uint | 读/写 | 获取或设置 ISO 速度 |
| iso_speed_latitude_yyy | uint | 读/写 | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。 |
| iso_speed_latitude_zzz | uint | 读/写 | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。 |
| lens_make | 字符串 | 读/写 | 获取或设置镜头制造商。 |
| lens_model | 字符串 | 读/写 | 获取或设置镜头型号。 |
| lens_serial_number | 字符串 | 读/写 | 获取或设置镜头序列号。 |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置镜头规格 |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | 获取或设置光源。 |
| make | 字符串 | 读/写 | 获取或设置录音设备的制造商。 |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | 获取制造商备注数据。 |
| maker_note_raw_data | byte | 读/写 | 获取或设置制造商备注原始数据。 |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置最大光圈值。 |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | 获取或设置测光模式。 |
| model | 字符串 | 读/写 | 获取或设置型号。 |
| oecf | byte | 读/写 | 获取或设置 ISO 14524 中指定的光电转换函数（OECF）。 |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | 获取或设置方向。 |
| photographic_sensitivity | uint | 读/写 | 获取或设置感光度。 |
| photometric_interpretation | ushort | 读/写 | 获取或设置光度解释。 |
| pixel_x_dimension | uint | 读/写 | 获取或设置像素 X 维度。 |
| pixel_y_dimension | uint | 读/写 | 获取或设置像素 Y 维度。 |
| planar_configuration | ushort | 读/写 | 获取或设置平面配置。 |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置图像三原色的色度。 |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置所有 EXIF 标签（包括通用标签和 GPS 标签）。 |
| recommended_exposure_index | uint | 读/写 | 获取或设置推荐曝光指数。 |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置参考的黑白。 |
| related_sound_file | 字符串 | 读/写 | 获取或设置相关的声音文件。 |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | 获取或设置分辨率单位。 |
| samples_per_pixel | ushort | 读/写 | 获取或设置每像素的采样数。 |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | 获取或设置饱和度。 |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | 获取或设置场景捕获类型。 |
| scene_type | byte | 读/写 | 获取或设置场景类型。 |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | 获取或设置感测方法。 |
| sensitivity_type | ushort | 读/写 | 获取或设置感光类型。 |
| 锐度 | ushort | 读/写 | 获取或设置锐度。 |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 获取或设置快门速度值。 |
| 软件 | 字符串 | 读/写 | 获取或设置软件。 |
| spatial_frequency_response | byte | 读/写 | 获取或设置空间频率响应。 |
| spectral_sensitivity | 字符串 | 读/写 | 获取或设置光谱灵敏度。 |
| standard_output_sensitivity | uint | 读/写 | 获取或设置标准输出灵敏度 |
| subject_area | ushort | 读/写 | 获取或设置主体区域。 |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置主体距离。 |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | 获取或设置主体距离范围。 |
| subject_location | ushort | 读/写 | 获取或设置主体位置。 |
| subsec_time | 字符串 | 读/写 | 获取或设置 DateTime 标记的秒分数。 |
| subsec_time_digitized | 字符串 | 读/写 | 获取或设置 DateTimeDigitized 标记的秒分数。 |
| subsec_time_original | 字符串 | 读/写 | 获取或设置 DateTimeOriginal 标记的秒分数。 |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | 获取或设置缩略图。 |
| transfer_function | ushort | 读/写 | 获取或设置传输函数。 |
| user_comment | 字符串 | 读/写 | 获取或设置用户评论。 |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | 获取或设置白平衡。 |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置图像白点的色度。 |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 X 分辨率。 |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | 获取或设置色度分量相对于亮度分量的位置。 |
| y_cb_cr_sub_sampling | ushort | 读/写 | 获取或设置色度分量相对于亮度分量的采样比例。 |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 Y 分辨率。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | 从容器中移除标签 |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | 从容器中移除标签 |
| [serialize_exif_data()](#serialize_exif_data__3) | 序列化 EXIF 数据。写入标签值和内容。最影响大小的标签是缩略图标签内容。 |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

初始化 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 类的新实例。

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

使用数组中的数据初始化 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 常用标签。 |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | EXIF 标签。 |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | GPS 标签。 |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

使用数组中的数据初始化 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 包含常用标签和 GPS 标签的 EXIF 标签数组。 |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

从容器中移除标签

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | 要移除的标签 |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

从容器中移除标签

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tag_id | ushort | 要移除的标签标识符。 |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

序列化 EXIF 数据。写入标签值和内容。最影响大小的标签是缩略图标签内容。

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 序列化的 EXIF 数据。 |


