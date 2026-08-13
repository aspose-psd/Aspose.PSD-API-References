---
title: "فئة JpegExifData"
type: docs
weight: 20
url: /ar/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | ينشئ مثيلًا جديدًا من الفئة [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | ينشئ مثيلًا جديدًا من الفئة [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) باستخدام البيانات من المصفوفة. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | ينشئ مثيلًا جديدًا من الفئة [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) باستخدام البيانات من المصفوفة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | الحد الأقصى لحجم قطاع EXIF بالبايت المسموح به. |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط قيمة الفتحة. |
| الفنان | string | r/w | يحصل أو يعيّن الفنان. |
| bits_per_sample | ushort | r/w | يحصل أو يعيّن عدد البتات لكل عينة. |
| body_serial_number | string | r/w | يحصل أو يضبط الرقم التسلسلي لجسم الكاميرا. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | يحصل أو يضبط قيمة السطوع. |
| camera_owner_name | string | r/w | يحصل أو يضبط اسم مالك الكاميرا |
| cfa_pattern | byte | r/w | يحصل أو يضبط نمط CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | يحصل أو يضبط مساحة اللون. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يضبط العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي صيغة tiff يتم استخدام tiffOptions بدلاً من ذلك |
| components_configuration | byte | r/w | يحصل أو يضبط تكوين المكونات. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط عدد البتات المضغوطة لكل بكسل. |
| compression | ushort | r/w | يحصل أو يضبط الضغط. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | الحصول على أو تعيين التباين. |
| copyright | string | r/w | يحصل أو يعيّن حقوق النشر. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | يحصل أو يضبط العرض المخصص. |
| date_time | string | r/w | يحصل أو يعيّن التاريخ والوقت. |
| date_time_digitized | string | r/w | يحصل أو يضبط تاريخ ووقت الرقمنة. |
| date_time_original | string | r/w | يحصل أو يضبط تاريخ ووقت الأصل. |
| device_setting_description | byte | r/w | يحصل أو يضبط وصف إعدادات الجهاز |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط نسبة التكبير الرقمي. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يضبط العلامات التي تنتمي إلى قسم EXIF فقط. |
| exif_version | byte | r/w | يحصل أو يضبط نسخة EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | يحصل أو يضبط قيمة انحياز التعرض. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط مؤشر التعرض. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | يحصل أو يضبط وضع التعرض. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | يحصل أو يضبط برنامج التعرض. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين وقت التعرض. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين رقم F. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | الحصول أو تعيين نوع مصدر الملف. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | الحصول أو تعيين الفلاش. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين طاقة الفلاش. |
| flashpix_version | byte | r/w | الحصول أو تعيين إصدار flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين البعد البؤري. |
| focal_length_in_35_mm_film | ushort | r/w | الحصول أو تعيين البعد البؤري في فيلم 35 مم. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | الحصول أو تعيين وحدة دقة المستوى البؤري. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين دقة المستوى البؤري X. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين دقة المستوى البؤري Y. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | الحصول أو تعيين درجة تعديل الكسب الكلي للصورة. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط غاما. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين ارتفاع GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | الحصول أو تعيين ارتفاع GPS المستخدم كارتفاع مرجعي. |
| gps_area_information | byte | r/w | الحصول أو تعيين معلومات منطقة GPS. |
| gps_date_stamp | string | r/w | الحصول أو تعيين سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (التوقيت العالمي المنسق). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين اتجاه GPS إلى نقطة الوجهة. |
| gps_dest_bearing_ref | string | r/w | الحصول أو تعيين مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين مسافة GPS إلى نقطة الوجهة. |
| gps_dest_distance_ref | string | r/w | يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط خط عرض GPS لنقطة الوجهة. |
| gps_dest_latitude_ref | string | r/w | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط خط طول GPS لنقطة الوجهة. |
| gps_dest_longitude_ref | string | r/w | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| gps_differential | ushort | r/w | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان تصحيح الفرق مطبقًا على مستقبل GPS. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط اتجاه GPS للصورة عند التقاطها. |
| gps_img_direction_ref | string | r/w | يحصل أو يضبط مرجع GPS لتحديد اتجاه الصورة عند التقاطها. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط خط عرض GPS. |
| gps_latitude_ref | string | r/w | يحصل أو يضبط ما إذا كان خط عرض GPS شماليًا أم جنوبيًا. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط خط طول GPS. |
| gps_longitude_ref | string | r/w | يحصل أو يضبط ما إذا كان خط طول GPS شرقًا أم غربًا. |
| gps_map_datum | string | r/w | يحصل أو يضبط بيانات المسح الجيوديسي GPS المستخدمة من قبل مستقبل GPS. |
| gps_measure_mode | string | r/w | يحصل أو يضبط وضع قياس GPS. |
| gps_processing_method | byte | r/w | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| gps_satellites | string | r/w | يحصل أو يضبط أقمار GPS المستخدمة للقياسات. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط سرعة حركة مستقبل GPS. |
| gps_speed_ref | string | r/w | يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. |
| gps_status | string | r/w | يحصل أو يضبط حالة مستقبل GPS عندما يتم تسجيل الصورة. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يضبط العلامات التي تنتمي إلى قسم GPS فقط. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| gps_track | string | r/w | يحصل أو يضبط اتجاه حركة مستقبل GPS. |
| gps_track_ref | string | r/w | يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS. |
| gps_version_id | byte | r/w | يحصل أو يضبط معرف إصدار GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط قيمة DOP الخاصة بـ GPS (درجة دقة البيانات). |
| image_description | string | r/w | يحصل أو يعيّن وصف الصورة. |
| image_length | uint | r/w | يحصل أو يعيّن طول الصورة. |
| image_unique_id | string | r/w | يحصل أو يضبط المعرف الفريد للصورة. |
| image_width | uint | r/w | يحصل أو يعيّن عرض الصورة. |
| is_big_endian | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان تدفق بيانات EXIF المُنشأ من نظام big endian. |
| iso_speed | uint | r/w | يحصل أو يضبط سرعة ISO |
| iso_speed_latitude_yyy | uint | r/w | يحصل أو يضبط قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | يحصل أو يضبط قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| lens_make | string | r/w | يسترجع أو يعيّن صانع العدسة. |
| lens_model | string | r/w | يسترجع أو يعيّن نموذج العدسة. |
| lens_serial_number | string | r/w | يسترجع أو يعيّن الرقم التسلسلي للعدسة. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يسترجع أو يعيّن مواصفات العدسة |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | يسترجع أو يعيّن مصدر الضوء. |
| make | string | r/w | يحصل أو يعيّن الشركة المصنعة لمعدات التسجيل. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | يسترجع بيانات ملاحظة الصانع. |
| maker_note_raw_data | byte | r/w | يسترجع أو يعيّن البيانات الخام لملاحظة الصانع. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يسترجع أو يعيّن قيمة الفتحة القصوى. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | يسترجع أو يعيّن وضع القياس. |
| model | string | r/w | الحصول أو تعيين النموذج. |
| oecf | byte | r/w | يسترجع أو يعيّن وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | يحصل أو يضبط الاتجاه. |
| photographic_sensitivity | uint | r/w | يسترجع أو يعيّن الحساسية الفوتوغرافية. |
| photometric_interpretation | ushort | r/w | الحصول أو تعيين التفسير الضوئي. |
| pixel_x_dimension | uint | r/w | يسترجع أو يعيّن بُعد البكسل X. |
| pixel_y_dimension | uint | r/w | يسترجع أو يعيّن بُعد البكسل Y. |
| planar_configuration | ushort | r/w | يحصل أو يضبط تكوين المستوى. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين التشبع اللوني للثلاث ألوان الأساسية في الصورة. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | يسترجع أو يعيّن جميع وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS). |
| recommended_exposure_index | uint | r/w | يسترجع أو يعيّن مؤشر التعرض الموصى به. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين اللونين الأسود والابيض المرجعي. |
| related_sound_file | string | r/w | الحصول أو تعيين ملف الصوت المرتبط. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | يحصل أو يعيّن وحدة الدقة. |
| samples_per_pixel | ushort | r/w | الحصول أو تعيين العينات لكل بكسل. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | يحصل أو يضبط التشبع. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | الحصول أو تعيين نوع التقاط المشهد. |
| scene_type | byte | r/w | الحصول أو تعيين نوع المشهد. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | الحصول أو تعيين طريقة الاستشعار. |
| sensitivity_type | ushort | r/w | الحصول أو تعيين نوع الحساسية. |
| sharpness | ushort | r/w | الحصول أو تعيين الحدة. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | الحصول أو تعيين قيمة سرعة الغالق. |
| البرمجيات | string | r/w | الحصول أو تعيين البرمجيات. |
| spatial_frequency_response | byte | r/w | الحصول أو تعيين استجابة التردد المكاني. |
| spectral_sensitivity | string | r/w | الحصول أو تعيين الحساسية الطيفية. |
| standard_output_sensitivity | uint | r/w | الحصول أو تعيين حساسية الإخراج القياسية |
| subject_area | ushort | r/w | الحصول أو تعيين منطقة الموضوع. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين مسافة الموضوع. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | الحصول أو تعيين نطاق مسافة الموضوع. |
| subject_location | ushort | r/w | الحصول أو تعيين موقع الموضوع. |
| subsec_time | string | r/w | الحصول أو تعيين أجزاء الثواني لعلامة DateTime. |
| subsec_time_digitized | string | r/w | يحصل أو يعيّن أجزاء الثواني لعلامة DateTimeDigitized. |
| subsec_time_original | string | r/w | يحصل أو يعيّن أجزاء الثواني لعلامة DateTimeOriginal. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | الحصول أو تعيين صورة المصغرة. |
| transfer_function | ushort | r/w | الحصول أو تعيين دالة النقل. |
| user_comment | string | r/w | يحصل أو يعيّن تعليق المستخدم. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | يحصل أو يعيّن توازن اللون الأبيض. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن تشبع اللون للنقطة البيضاء في الصورة. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن دقة x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | الحصول أو تعيين موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| y_cb_cr_sub_sampling | ushort | r/w | الحصول أو تعيين نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن دقة y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | إزالة العلامة من الحاوية |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | إزالة العلامة من الحاوية |
| [serialize_exif_data()](#serialize_exif_data__3) | يسلسل بيانات EXIF. يكتب قيم الوسوم ومحتوياتها. أكثر وسوم الحجم تأثيرًا هو محتويات وسمة الصورة المصغرة. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

ينشئ مثيلًا جديدًا من الفئة [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

ينشئ مثيلًا جديدًا من الفئة [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) باستخدام البيانات من المصفوفة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | العلامات الشائعة. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | علامات EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | علامات GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

ينشئ مثيلًا جديدًا من الفئة [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) باستخدام البيانات من المصفوفة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | مصفوفة من علامات EXIF مع العلامات الشائعة وعلامات GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

إزالة العلامة من الحاوية

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | العلامة المراد إزالتها |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

إزالة العلامة من الحاوية

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tag_id | ushort | معرّف العلامة المراد إزالتها. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

يسلسل بيانات EXIF. يكتب قيم الوسوم ومحتوياتها. أكثر وسوم الحجم تأثيرًا هو محتويات وسمة الصورة المصغرة.

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | بيانات EXIF المتسلسلة. |


