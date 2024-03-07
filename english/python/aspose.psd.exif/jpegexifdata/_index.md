---
title: JpegExifData Class
type: docs
weight: 20
url: /python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Initializes a new instance of the [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) class. |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Initializes a new instance of the [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) class with data from array. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Initializes a new instance of the [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) class with data from array. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | The maximum EXIF segment size in bytes allowed. |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the aperture value. |
| artist | string | r/w | Gets or sets the artist. |
| bits_per_sample | ushort | r/w | Gets or sets the bits per sample. |
| body_serial_number | string | r/w | Gets or sets camera body serial number. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Gets or sets the brightness value. |
| camera_owner_name | string | r/w | Gets or sets camera owner name |
| cfa_pattern | byte | r/w | Gets or sets the CFA pattern. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Gets or sets the color space. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Gets or sets tags, which belong to common section. This applies only to jpeg images, in tiff format tiffOptions are being used instead |
| components_configuration | byte | r/w | Gets or sets the components configuration. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the compressed bits per pixel. |
| compression | ushort | r/w | Gets or sets the compression. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Gets or sets the contrast. |
| copyright | string | r/w | Gets or sets the copyright. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Gets or sets the custom rendered. |
| date_time | string | r/w | Gets or sets the date time. |
| date_time_digitized | string | r/w | Gets or sets the date time digitized. |
| date_time_original | string | r/w | Gets or sets the date time original. |
| device_setting_description | byte | r/w | Gets or sets device settings description |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the digital zoom ratio. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Gets or sets tags which belong to EXIF section only. |
| exif_version | byte | r/w | Gets or sets the EXIF version. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Gets or sets the exposure bias value. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the exposure index. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Gets or sets the exposure mode. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Gets or sets the exposure program. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the exposure time. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the F-number. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Gets or sets the file source type. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Gets or sets the flash. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the flash energy. |
| flashpix_version | byte | r/w | Gets or sets the flash pix version. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the focal length. |
| focal_length_in_35_mm_film | ushort | r/w | Gets or sets the focal length in 35 mm film. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Gets or sets the focal plane resolution unit. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the focal plane x resolution. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the focal plane y resolution. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Gets or sets the degree of overall image gain adjustment. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS altitude. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Gets or sets the GPS altitude used as the reference altitude. |
| gps_area_information | byte | r/w | Gets or sets the GPS area information. |
| gps_date_stamp | string | r/w | Gets or sets the GPS character string recording date and time information relative to UTC (Coordinated Universal Time). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS bearing to the destination point. |
| gps_dest_bearing_ref | string | r/w | Gets or sets the GPS reference used for giving the bearing to the destination point. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS distance to the destination point. |
| gps_dest_distance_ref | string | r/w | Gets or sets the GPS unit used to express the distance to the destination point. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS latitude of the destination point. |
| gps_dest_latitude_ref | string | r/w | Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS longitude of the destination point. |
| gps_dest_longitude_ref | string | r/w | Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude. |
| gps_differential | ushort | r/w | Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS direction of the image when it was captured. |
| gps_img_direction_ref | string | r/w | Gets or sets the GPS reference for giving the direction of the image when it is captured. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS latitude. |
| gps_latitude_ref | string | r/w | Gets or sets the GPS latitude is north or south latitude. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS longitude. |
| gps_longitude_ref | string | r/w | Gets or sets the GPS longitude is east or west longitude. |
| gps_map_datum | string | r/w | Gets or sets the GPS geodetic survey data used by the GPS receiver. |
| gps_measure_mode | string | r/w | Gets or sets the GPS measurement mode. |
| gps_processing_method | byte | r/w | Gets or sets the GPS character string recording the name of the method used for location finding. |
| gps_satellites | string | r/w | Gets or sets the GPS satellites used for measurements. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the speed of GPS receiver movement. |
| gps_speed_ref | string | r/w | Gets or sets the unit used to express the GPS receiver speed of movement. |
| gps_status | string | r/w | Gets or sets the status of the GPS receiver when the image is recorded. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Gets or sets tags, which belong to GPS section only. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS time as UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Gets or sets direction of GPS receiver movement. |
| gps_track_ref | string | r/w | Gets or sets the reference for giving the direction of GPS receiver movement. |
| gps_version_id | byte | r/w | Gets or sets the GPS version identifier. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the GPS DOP (data degree of precision). |
| image_description | string | r/w | Gets or sets the image description. |
| image_length | uint | r/w | Gets or sets the image length. |
| image_unique_id | string | r/w | Gets or sets the image unique identifier. |
| image_width | uint | r/w | Gets or sets the image width. |
| is_big_endian | bool | r/w | Gets or sets a value indicating whether the stream EXIF data created from is big endian. |
| iso_speed | uint | r/w | Gets or sets ISO speed |
| iso_speed_latitude_yyy | uint | r/w | Gets or sets the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Gets or sets the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232. |
| lens_make | string | r/w | Gets or sets the maker of lens. |
| lens_model | string | r/w | Gets or sets the lens model. |
| lens_serial_number | string | r/w | Gets or sets the lens serial number. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the lens specification |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Gets or sets the light source. |
| make | string | r/w | Gets or sets the manufacturer of the recording equipment. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Gets the maker note data. |
| maker_note_raw_data | byte | r/w | Gets or sets the maker note raw data. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the maximum aperture value. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Gets or sets the metering mode. |
| model | string | r/w | Gets or sets the model. |
| oecf | byte | r/w | Gets or sets the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | Gets or sets the orientation. |
| photographic_sensitivity | uint | r/w | Gets or sets the photographic sensitivity. |
| photometric_interpretation | ushort | r/w | Gets or sets the photometric interpretation. |
| pixel_x_dimension | uint | r/w | Gets or sets the pixel x dimension. |
| pixel_y_dimension | uint | r/w | Gets or sets the pixel y dimension. |
| planar_configuration | ushort | r/w | Gets or sets the planar configuration. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the chromaticity of the three primary colors of the image. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Gets or sets all the EXIF tags (including common and GPS tags). |
| recommended_exposure_index | uint | r/w | Gets or sets the recommended exposure index. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the reference black white. |
| related_sound_file | string | r/w | Gets or sets the related sound file. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Gets or sets the resolution unit. |
| samples_per_pixel | ushort | r/w | Gets or sets the samples per pixel. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Gets or sets the saturation. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Gets or sets the scene capture type. |
| scene_type | byte | r/w | Gets or sets the scene type. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Gets or sets the sensing method. |
| sensitivity_type | ushort | r/w | Gets or sets the sensitivity type. |
| sharpness | ushort | r/w | Gets or sets the sharpness. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Gets or sets the shutter speed value. |
| software | string | r/w | Gets or sets the software. |
| spatial_frequency_response | byte | r/w | Gets or sets the spatial frequency response. |
| spectral_sensitivity | string | r/w | Gets or sets the spectral sensitivity. |
| standard_output_sensitivity | uint | r/w | Gets or sets standard output sensitivity |
| subject_area | ushort | r/w | Gets or sets the subject area. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the subject distance. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Gets or sets the subject distance range. |
| subject_location | ushort | r/w | Gets or sets the subject location. |
| subsec_time | string | r/w | Gets or sets the fractions of seconds for the DateTime tag. |
| subsec_time_digitized | string | r/w | Gets or sets the fractions of seconds for the DateTimeDigitized tag. |
| subsec_time_original | string | r/w | Gets or sets the fractions of seconds for the DateTimeOriginal tag. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | Gets or sets the thumbnail image. |
| transfer_function | ushort | r/w | Gets or sets the transfer function. |
| user_comment | string | r/w | Gets or sets the user comment. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Gets or sets the white balance. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the chromaticity of the white point of the image. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the x resolution. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the matrix coefficients for transformation from RGB to YCbCr image data. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | Gets or sets the position of chrominance components in relation to the luminance component. |
| y_cb_cr_sub_sampling | ushort | r/w | Gets or sets the sampling ratio of chrominance components in relation to the luminance component. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the y resolution. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Remove tag from container |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Remove tag from container |
| [serialize_exif_data()](#serialize_exif_data__3) | Serializes the EXIF data. Writes the tags values and contents. The most influencing size tag is Thumbnail tag contents. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Initializes a new instance of the [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) class.

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Initializes a new instance of the [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) class with data from array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The common tags. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The EXIF tags. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The GPS tags. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Initializes a new instance of the [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) class with data from array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Array of EXIF tags together with common and GPS tags. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Remove tag from container

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | The tag to remove |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Remove tag from container

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | ushort | The tag identifier to remove. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

Serializes the EXIF data. Writes the tags values and contents. The most influencing size tag is Thumbnail tag contents.

**Returns**

| Type | Description |
| :- | :- |
| byte | The serialized EXIF data. |


