---
title: "JpegExifData"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "حاوية بيانات EXIF لملفات JPEG."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller), [com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

حاوية بيانات EXIF لملفات JPEG.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | ينشئ مثيلاً جديداً من الفئة JpegExifData. |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | ينشئ مثيلاً جديداً من الفئة JpegExifData ببيانات من مصفوفة. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | ينشئ مثيلاً جديداً من الفئة JpegExifData ببيانات من مصفوفة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | الحد الأقصى لحجم مقطع EXIF بالبايت المسموح به. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | يحصل أو يعيّن قيمة الفتحة. |
| [getArtist()](#getArtist--) | الحصول أو تعيين الفنان. |
| [getBitsPerSample()](#getBitsPerSample--) | الحصول أو تعيين عدد البتات لكل عينة. |
| [getBodySerialNumber()](#getBodySerialNumber--) | يحصل أو يعيّن الرقم التسلسلي لجسم الكاميرا. |
| [getBrightnessValue()](#getBrightnessValue--) | يحصل أو يعيّن قيمة السطوع. |
| [getCFAPattern()](#getCFAPattern--) | يحصل أو يعيّن نمط CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | يحصل أو يعيّن اسم مالك الكاميرا |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | يحصل أو يعيّن مساحة اللون. |
| [getCommonTags()](#getCommonTags--) | يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | يحصل أو يعيّن تكوين المكونات. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل. |
| [getCompression()](#getCompression--) | الحصول أو تعيين الضغط. |
| [getContrast()](#getContrast--) | يحصل أو يعيّن التباين. |
| [getCopyright()](#getCopyright--) | الحصول أو تعيين حقوق النشر. |
| [getCustomRendered()](#getCustomRendered--) | يحصل أو يعيّن الإخراج المخصص. |
| [getDateTime()](#getDateTime--) | الحصول أو تعيين تاريخ ووقت. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | يحصل أو يعيّن تاريخ ووقت الرقمنة. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | يحصل أو يعيّن تاريخ ووقت الأصل. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | يحصل أو يعيّن وصف إعدادات الجهاز |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | يحصل أو يعيّن نسبة التكبير الرقمي. |
| [getExifTags()](#getExifTags--) | يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط. |
| [getExifVersion()](#getExifVersion--) | يحصل أو يعيّن نسخة EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | يحصل أو يعيّن قيمة انحياز التعرض. |
| [getExposureIndex()](#getExposureIndex--) | يحصل أو يعيّن مؤشر التعرض. |
| [getExposureMode()](#getExposureMode--) | يحصل أو يضبط وضع التعريض. |
| [getExposureProgram()](#getExposureProgram--) | يحصل أو يضبط برنامج التعريض. |
| [getExposureTime()](#getExposureTime--) | يحصل أو يضبط زمن التعريض. |
| [getFNumber()](#getFNumber--) | يحصل أو يضبط رقم F. |
| [getFileSource()](#getFileSource--) | يحصل أو يضبط نوع مصدر الملف. |
| [getFlash()](#getFlash--) | يحصل أو يضبط الفلاش. |
| [getFlashEnergy()](#getFlashEnergy--) | يحصل أو يضبط طاقة الفلاش. |
| [getFlashpixVersion()](#getFlashpixVersion--) | يحصل أو يضبط نسخة فلاش pix. |
| [getFocalLength()](#getFocalLength--) | يحصل أو يضبط البعد البؤري. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | يحصل أو يضبط البعد البؤري في فيلم 35 مم. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | يحصل أو يضبط وحدة دقة المستوى البؤري. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | يحصل أو يضبط دقة المستوى البؤري X. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | يحصل أو يضبط دقة المستوى البؤري Y. |
| [getGPSAltitude()](#getGPSAltitude--) | يحصل أو يضبط ارتفاع GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | يحصل أو يضبط معلومات منطقة GPS. |
| [getGPSDOP()](#getGPSDOP--) | يحصل أو يضبط DOP GPS (درجة دقة البيانات). |
| [getGPSDateStamp()](#getGPSDateStamp--) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل تاريخ ووقت المعلومات بالنسبة إلى UTC (الوقت العالمي المنسق). |
| [getGPSDestBearing()](#getGPSDestBearing--) | يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [getGPSDestDistance()](#getGPSDestDistance--) | يحصل أو يضبط مسافة GPS إلى نقطة الوجهة. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | يحصل أو يضبط خط عرض GPS لنقطة الوجهة. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | يحصل أو يضبط خط طول GPS لنقطة الوجهة. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| [getGPSDifferential()](#getGPSDifferential--) | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | يحصل أو يعيّن اتجاه GPS للصورة عند التقاطها. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | يحصل أو يعيّن مرجع GPS لتحديد اتجاه الصورة عند التقاطها. |
| [getGPSLatitude()](#getGPSLatitude--) | يحصل أو يعيّن خط عرض GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | يحصل أو يعيّن ما إذا كان خط عرض GPS شماليًا أم جنوبيًا. |
| [getGPSLongitude()](#getGPSLongitude--) | يحصل أو يعيّن خط طول GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | يحصل أو يعيّن ما إذا كان خط طول GPS شرقًا أم غربًا. |
| [getGPSMapDatum()](#getGPSMapDatum--) | يحصل أو يعيّن بيانات المسح الجيوديسي GPS المستخدمة من قبل جهاز استقبال GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | يحصل أو يعيّن وضع قياس GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | يحصل أو يعيّن سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [getGPSSatellites()](#getGPSSatellites--) | يحصل أو يعيّن أقمار GPS المستخدمة للقياسات. |
| [getGPSSpeed()](#getGPSSpeed--) | يحصل أو يعيّن سرعة حركة جهاز استقبال GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | يحصل أو يعيّن الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS. |
| [getGPSStatus()](#getGPSStatus--) | يحصل أو يعيّن حالة جهاز استقبال GPS عند تسجيل الصورة. |
| [getGPSTags()](#getGPSTags--) | يحصل أو يعيّن العلامات التي تخص قسم GPS فقط. |
| [getGPSTimestamp()](#getGPSTimestamp--) | يحصل أو يعيّن وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| [getGPSTrack()](#getGPSTrack--) | يحصل أو يعيّن اتجاه حركة جهاز استقبال GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | يحصل أو يعيّن المرجع لتحديد اتجاه حركة جهاز استقبال GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | يحصل أو يعيّن معرف إصدار GPS. |
| [getGainControl()](#getGainControl--) | يحصل أو يعيّن درجة تعديل الكسب الكلي للصورة. |
| [getGamma()](#getGamma--) | يحصل أو يعيّن قيمة الجاما. |
| [getISOSpeed()](#getISOSpeed--) | يحصل أو يعيّن سرعة ISO |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | يحصل أو يعيّن قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | يحصل أو يعيّن قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [getImageDescription()](#getImageDescription--) | الحصول أو تعيين وصف الصورة. |
| [getImageLength()](#getImageLength--) | الحصول أو تعيين طول الصورة. |
| [getImageUniqueID()](#getImageUniqueID--) | يحصل أو يضبط المعرف الفريد للصورة. |
| [getImageWidth()](#getImageWidth--) | الحصول أو تعيين عرض الصورة. |
| [getLensMake()](#getLensMake--) | يحصل أو يضبط صانع العدسة. |
| [getLensModel()](#getLensModel--) | يحصل أو يضبط طراز العدسة. |
| [getLensSerialNumber()](#getLensSerialNumber--) | يحصل أو يضبط الرقم التسلسلي للعدسة. |
| [getLensSpecification()](#getLensSpecification--) | يحصل أو يضبط مواصفات العدسة |
| [getLightSource()](#getLightSource--) | يحصل أو يضبط مصدر الضوء. |
| [getMake()](#getMake--) | يحصل على الشركة المصنعة لمعدات التسجيل. |
| [getMakerNoteData()](#getMakerNoteData--) | يحصل على بيانات ملاحظة الصانع. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | يحصل أو يضبط البيانات الخام لملاحظة الصانع. |
| [getMakerNotes()](#getMakerNotes--) | يحصل على ملاحظات الصانع. |
| [getMaxApertureValue()](#getMaxApertureValue--) | يحصل أو يضبط قيمة الفتحة القصوى. |
| [getMeteringMode()](#getMeteringMode--) | يحصل أو يضبط وضع القياس. |
| [getModel()](#getModel--) | الحصول أو تعيين النموذج. |
| [getOECF()](#getOECF--) | يحصل أو يضبط وظيفة التحويل الضوئي-الكهربي (OECF) المحددة في ISO 14524. |
| [getOrientation()](#getOrientation--) | الحصول أو تعيين الاتجاه. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | يحصل أو يضبط الحساسية الفوتوغرافية. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | الحصول أو تعيين التفسير الضوئي. |
| [getPixelXDimension()](#getPixelXDimension--) | يحصل أو يضبط البُعد X للبكسل. |
| [getPixelYDimension()](#getPixelYDimension--) | يحصل أو يضبط البُعد Y للبكسل. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | الحصول أو تعيين تكوين المستوى. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | الحصول أو تعيين اللونية للثلاث ألوان الأساسية في الصورة. |
| [getProperties()](#getProperties--) | يحصل أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | يحصل أو يضبط مؤشر التعرض الموصى به. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | الحصول أو تعيين المرجع الأسود والأبيض. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | يحصل أو يضبط ملف الصوت المرتبط. |
| [getResolutionUnit()](#getResolutionUnit--) | الحصول أو تعيين وحدة الدقة. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | الحصول أو تعيين العينات لكل بكسل. |
| [getSaturation()](#getSaturation--) | يحصل أو يضبط التشبع. |
| [getSceneCaptureType()](#getSceneCaptureType--) | يحصل أو يضبط نوع التقاط المشهد. |
| [getSceneType()](#getSceneType--) | يحصل أو يضبط نوع المشهد. |
| [getSensingMethod()](#getSensingMethod--) | يحصل أو يضبط طريقة الاستشعار. |
| [getSensitivityType()](#getSensitivityType--) | يحصل أو يضبط نوع الحساسية. |
| [getSharpness()](#getSharpness--) | يحصل أو يضبط الحدة. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | يحصل أو يضبط قيمة سرعة الغالق. |
| [getSoftware()](#getSoftware--) | الحصول أو تعيين البرنامج. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | يحصل أو يضبط استجابة التردد المكاني. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | يحصل أو يضبط الحساسية الطيفية. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | يحصل على الحساسية القياسية للإخراج |
| [getSubjectArea()](#getSubjectArea--) | يحصل أو يضبط منطقة الموضوع. |
| [getSubjectDistance()](#getSubjectDistance--) | يحصل أو يضبط مسافة الموضوع. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | يحصل أو يضبط نطاق مسافة الموضوع. |
| [getSubjectLocation()](#getSubjectLocation--) | يحصل أو يضبط موقع الموضوع. |
| [getSubsecTime()](#getSubsecTime--) | يحصل أو يضبط أجزاء الثواني للوسم DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | يحصل أو يضبط أجزاء الثواني للوسم DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | يحصل أو يضبط أجزاء الثواني للوسم DateTimeOriginal. |
| [getThumbnail()](#getThumbnail--) | الحصول أو تعيين صورة المصغرة. |
| [getTransferFunction()](#getTransferFunction--) | الحصول أو تعيين دالة النقل. |
| [getUserComment()](#getUserComment--) | يحصل أو يضبط تعليق المستخدم. |
| [getWhiteBalance()](#getWhiteBalance--) | يحصل أو يضبط توازن الأبيض. |
| [getWhitePoint()](#getWhitePoint--) | يحصل أو يضبط اللونية لنقطة الأبيض في الصورة. |
| [getXResolution()](#getXResolution--) | الحصول أو تعيين دقة x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | الحصول أو تعيين معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | الحصول أو تعيين موضع مكونات التشبع اللوني بالنسبة للمكون الإضاءة. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | الحصول أو تعيين نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة للمكون الإضاءة. |
| [getYResolution()](#getYResolution--) | الحصول أو تعيين دقة y. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF المتدفقة التي تم إنشاؤها من هي ذات ترتيب big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | إزالة الوسم من الحاوية |
| [serializeExifData()](#serializeExifData--) | تسلسل بيانات EXIF. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن قيمة الفتحة. |
| [setArtist(String value)](#setArtist-java.lang.String-) | الحصول أو تعيين الفنان. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF المتدفقة التي تم إنشاؤها من هي ذات ترتيب big endian. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | الحصول أو تعيين عدد البتات لكل عينة. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | يحصل أو يعيّن الرقم التسلسلي لجسم الكاميرا. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | يحصل أو يعيّن قيمة السطوع. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | يحصل أو يعيّن نمط CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | يحصل أو يعيّن اسم مالك الكاميرا |
| [setColorSpace(int value)](#setColorSpace-int-) | يحصل أو يعيّن مساحة اللون. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | يحصل أو يعيّن تكوين المكونات. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل. |
| [setCompression(int value)](#setCompression-int-) | الحصول أو تعيين الضغط. |
| [setContrast(int value)](#setContrast-int-) | يحصل أو يعيّن التباين. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | الحصول أو تعيين حقوق النشر. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | يحصل أو يعيّن الإخراج المخصص. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | الحصول أو تعيين تاريخ ووقت. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | يحصل أو يعيّن تاريخ ووقت الرقمنة. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | يحصل أو يعيّن تاريخ ووقت الأصل. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | يحصل أو يعيّن وصف إعدادات الجهاز |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن نسبة التكبير الرقمي. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | يحصل أو يعيّن نسخة EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | يحصل أو يعيّن قيمة انحياز التعرض. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن مؤشر التعرض. |
| [setExposureMode(int value)](#setExposureMode-int-) | يحصل أو يضبط وضع التعريض. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | يحصل أو يضبط برنامج التعريض. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط زمن التعريض. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط رقم F. |
| [setFileSource(byte value)](#setFileSource-byte-) | يحصل أو يضبط نوع مصدر الملف. |
| [setFlash(int value)](#setFlash-int-) | يحصل أو يضبط الفلاش. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط طاقة الفلاش. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | يحصل أو يضبط نسخة فلاش pix. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط البعد البؤري. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | يحصل أو يضبط البعد البؤري في فيلم 35 مم. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | يحصل أو يضبط وحدة دقة المستوى البؤري. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة المستوى البؤري X. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة المستوى البؤري Y. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط ارتفاع GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | يحصل أو يضبط معلومات منطقة GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط DOP GPS (درجة دقة البيانات). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل تاريخ ووقت المعلومات بالنسبة إلى UTC (الوقت العالمي المنسق). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط مسافة GPS إلى نقطة الوجهة. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يضبط خط عرض GPS لنقطة الوجهة. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يضبط خط طول GPS لنقطة الوجهة. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن اتجاه GPS للصورة عند التقاطها. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | يحصل أو يعيّن مرجع GPS لتحديد اتجاه الصورة عند التقاطها. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يعيّن خط عرض GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | يحصل أو يعيّن ما إذا كان خط عرض GPS شماليًا أم جنوبيًا. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يعيّن خط طول GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | يحصل أو يعيّن ما إذا كان خط طول GPS شرقًا أم غربًا. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | يحصل أو يعيّن بيانات المسح الجيوديسي GPS المستخدمة من قبل جهاز استقبال GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | يحصل أو يعيّن وضع قياس GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | يحصل أو يعيّن سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | يحصل أو يعيّن أقمار GPS المستخدمة للقياسات. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن سرعة حركة جهاز استقبال GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | يحصل أو يعيّن الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | يحصل أو يعيّن حالة جهاز استقبال GPS عند تسجيل الصورة. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | يحصل أو يعيّن العلامات التي تخص قسم GPS فقط. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يعيّن وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | يحصل أو يعيّن اتجاه حركة جهاز استقبال GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | يحصل أو يعيّن المرجع لتحديد اتجاه حركة جهاز استقبال GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | يحصل أو يعيّن معرف إصدار GPS. |
| [setGainControl(int value)](#setGainControl-int-) | يحصل أو يعيّن درجة تعديل الكسب الكلي للصورة. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يعيّن قيمة الجاما. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | يحصل أو يعيّن سرعة ISO |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | يحصل أو يعيّن قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | يحصل أو يعيّن قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | الحصول أو تعيين وصف الصورة. |
| [setImageLength(long value)](#setImageLength-long-) | الحصول أو تعيين طول الصورة. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | يحصل أو يضبط المعرف الفريد للصورة. |
| [setImageWidth(long value)](#setImageWidth-long-) | الحصول أو تعيين عرض الصورة. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | يحصل أو يضبط صانع العدسة. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | يحصل أو يضبط طراز العدسة. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | يحصل أو يضبط الرقم التسلسلي للعدسة. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يضبط مواصفات العدسة |
| [setLightSource(int value)](#setLightSource-int-) | يحصل أو يضبط مصدر الضوء. |
| [setMake(String value)](#setMake-java.lang.String-) | يضبط الشركة المصنعة لمعدات التسجيل. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | يحصل أو يضبط البيانات الخام لملاحظة الصانع. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط قيمة الفتحة القصوى. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | يحصل أو يضبط وضع القياس. |
| [setModel(String value)](#setModel-java.lang.String-) | الحصول أو تعيين النموذج. |
| [setOECF(byte[] value)](#setOECF-byte---) | يحصل أو يضبط وظيفة التحويل الضوئي-الكهربي (OECF) المحددة في ISO 14524. |
| [setOrientation(int value)](#setOrientation-int-) | الحصول أو تعيين الاتجاه. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | يحصل أو يضبط الحساسية الفوتوغرافية. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | الحصول أو تعيين التفسير الضوئي. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | يحصل أو يضبط البُعد X للبكسل. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | يحصل أو يضبط البُعد Y للبكسل. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | الحصول أو تعيين تكوين المستوى. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | الحصول أو تعيين اللونية للثلاث ألوان الأساسية في الصورة. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | يحصل أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | يحصل أو يضبط مؤشر التعرض الموصى به. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | الحصول أو تعيين المرجع الأسود والأبيض. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | يحصل أو يضبط ملف الصوت المرتبط. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | الحصول أو تعيين وحدة الدقة. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | الحصول أو تعيين العينات لكل بكسل. |
| [setSaturation(int value)](#setSaturation-int-) | يحصل أو يضبط التشبع. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | يحصل أو يضبط نوع التقاط المشهد. |
| [setSceneType(byte value)](#setSceneType-byte-) | يحصل أو يضبط نوع المشهد. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | يحصل أو يضبط طريقة الاستشعار. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | يحصل أو يضبط نوع الحساسية. |
| [setSharpness(int value)](#setSharpness-int-) | يحصل أو يضبط الحدة. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | يحصل أو يضبط قيمة سرعة الغالق. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | الحصول أو تعيين البرنامج. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | يحصل أو يضبط استجابة التردد المكاني. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | يحصل أو يضبط الحساسية الطيفية. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | يضبط الحساسية القياسية للإخراج |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | يحصل أو يضبط منطقة الموضوع. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط مسافة الموضوع. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | يحصل أو يضبط نطاق مسافة الموضوع. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | يحصل أو يضبط موقع الموضوع. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | يحصل أو يضبط أجزاء الثواني للوسم DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | يحصل أو يضبط أجزاء الثواني للوسم DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | يحصل أو يضبط أجزاء الثواني للوسم DateTimeOriginal. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | الحصول أو تعيين صورة المصغرة. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | الحصول أو تعيين دالة النقل. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | يحصل أو يضبط تعليق المستخدم. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | يحصل أو يضبط توازن الأبيض. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يضبط اللونية لنقطة الأبيض في الصورة. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | الحصول أو تعيين دقة x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | الحصول أو تعيين معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | الحصول أو تعيين موضع مكونات التشبع اللوني بالنسبة للمكون الإضاءة. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | الحصول أو تعيين نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة للمكون الإضاءة. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | الحصول أو تعيين دقة y. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


ينشئ مثيلاً جديداً من الفئة JpegExifData.

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


ينشئ مثيلاً جديداً من الفئة JpegExifData ببيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | مصفوفة من وسوم EXIF مع الوسوم العامة ووسوم GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


ينشئ مثيلاً جديداً من الفئة JpegExifData ببيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | الوسوم العامة. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | وسوم EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | وسوم GPS. |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


الحد الأقصى لحجم مقطع EXIF بالبايت المسموح به.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


يحصل أو يعيّن قيمة الفتحة.

القيمة: قيمة الفتحة.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


الحصول أو تعيين الفنان.

القيمة: الفنان.

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


الحصول أو تعيين عدد البتات لكل عينة.

القيمة: عدد البتات لكل عينة.

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


يحصل أو يعيّن الرقم التسلسلي لجسم الكاميرا.

القيمة: الرقم التسلسلي للجسم.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


يحصل أو يعيّن قيمة السطوع.

القيمة: قيمة السطوع.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


يحصل أو يعيّن نمط CFA.

القيمة: نمط CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


يحصل أو يعيّن اسم مالك الكاميرا

القيمة: اسم مالك الكاميرا.

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


يحصل أو يعيّن مساحة اللون.

القيمة: مساحة اللون.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي تنسيق tiff يتم استخدام tiffOptions بدلاً من ذلك

القيمة: علامات القسم المشترك.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


يحصل أو يعيّن تكوين المكونات.

القيمة: تكوين المكونات.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل.

القيمة: عدد البتات المضغوطة لكل بكسل.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


الحصول أو تعيين الضغط.

القيمة: الضغط.

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


يحصل أو يعيّن التباين.

القيمة: التباين.

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


الحصول أو تعيين حقوق النشر.

القيمة: حقوق النشر.

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


يحصل أو يعيّن الإخراج المخصص.

القيمة: تم العرض المخصص.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


الحصول أو تعيين تاريخ ووقت.

القيمة: تاريخ ووقت.

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


يحصل أو يعيّن تاريخ ووقت الرقمنة.

القيمة: تاريخ ووقت الرقمنة.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


يحصل أو يعيّن تاريخ ووقت الأصل.

القيمة: تاريخ ووقت الأصل.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


يحصل أو يعيّن وصف إعدادات الجهاز

القيمة: وصف إعداد الجهاز.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


يحصل أو يعيّن نسبة التكبير الرقمي.

القيمة: نسبة التكبير الرقمي.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط.

القيمة: علامات قسم EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


يحصل أو يعيّن نسخة EXIF.

القيمة: نسخة EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


يحصل أو يعيّن قيمة انحياز التعرض.

القيمة: قيمة إزاحة التعرض.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


يحصل أو يعيّن مؤشر التعرض.

القيمة: فهرس التعرض.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


يحصل أو يضبط وضع التعريض.

القيمة: وضع التعرض.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


يحصل أو يضبط برنامج التعريض.

القيمة: برنامج التعرض.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


يحصل أو يضبط زمن التعريض.

القيمة: زمن التعرض.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


يحصل أو يضبط رقم F.

القيمة: رقم F.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


يحصل أو يضبط نوع مصدر الملف.

القيمة: نوع مصدر الملف.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


يحصل أو يضبط الفلاش.

القيمة: الفلاش.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


يحصل أو يضبط طاقة الفلاش.

القيمة: طاقة الفلاش.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


يحصل أو يضبط نسخة فلاش pix.

القيمة: إصدار FlashPix.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


يحصل أو يضبط البعد البؤري.

القيمة: طول البؤري.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


يحصل أو يضبط البعد البؤري في فيلم 35 مم.

القيمة: طول البؤرة في فيلم 35 مم.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


يحصل أو يضبط وحدة دقة المستوى البؤري.

القيمة: وحدة دقة سطح البؤرة.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


يحصل أو يضبط دقة المستوى البؤري X.

القيمة: دقة سطح البؤرة X.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


يحصل أو يضبط دقة المستوى البؤري Y.

القيمة: دقة سطح البؤرة Y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


يحصل أو يضبط ارتفاع GPS.

القيمة: ارتفاع نظام تحديد المواقع (GPS).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي.

القيمة: ارتفاع GPS المستخدم كارتفاع مرجعي.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


يحصل أو يضبط معلومات منطقة GPS.

القيمة: معلومات منطقة GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


يحصل أو يضبط DOP GPS (درجة دقة البيانات).

القيمة: DOP GPS (درجة دقة البيانات).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل تاريخ ووقت المعلومات بالنسبة إلى UTC (الوقت العالمي المنسق).

القيمة: سلسلة الأحرف GPS التي تسجل تاريخ ووقت المعلومات بالنسبة إلى توقيت UTC (التوقيت العالمي المنسق).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة.

القيمة: اتجاه GPS إلى نقطة الوجهة.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

القيمة: مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


يحصل أو يضبط مسافة GPS إلى نقطة الوجهة.

القيمة: مسافة GPS إلى نقطة الوجهة.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

القيمة: وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


يحصل أو يضبط خط عرض GPS لنقطة الوجهة.

القيمة: خط عرض GPS لنقطة الوجهة.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


يحصل أو يضبط خط طول GPS لنقطة الوجهة.

القيمة: خط طول GPS لنقطة الوجهة.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS.

القيمة: قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


يحصل أو يعيّن اتجاه GPS للصورة عند التقاطها.

القيمة: اتجاه GPS للصورة عند التقاطها.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


يحصل أو يعيّن مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

القيمة: مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


يحصل أو يعيّن خط عرض GPS.

القيمة: خط عرض GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


يحصل أو يعيّن ما إذا كان خط عرض GPS شماليًا أم جنوبيًا.

القيمة: خط عرض GPS هو شمالي أو جنوبي.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


يحصل أو يعيّن خط طول GPS.

القيمة: خط الطول GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


يحصل أو يعيّن ما إذا كان خط طول GPS شرقًا أم غربًا.

القيمة: خط الطول GPS هو خط الطول الشرقي أو الغربي.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


يحصل أو يعيّن بيانات المسح الجيوديسي GPS المستخدمة من قبل جهاز استقبال GPS.

القيمة: بيانات المسح الجيوديسي GPS المستخدمة بواسطة مستقبل GPS.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


يحصل أو يعيّن وضع قياس GPS.

القيمة: وضع قياس GPS.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


يحصل أو يعيّن سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

القيمة: سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


يحصل أو يعيّن أقمار GPS المستخدمة للقياسات.

القيمة: أقمار GPS المستخدمة للقياسات.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


يحصل أو يعيّن سرعة حركة جهاز استقبال GPS.

القيمة: سرعة حركة مستقبل GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


يحصل أو يعيّن الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS.

القيمة: الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


يحصل أو يعيّن حالة جهاز استقبال GPS عند تسجيل الصورة.

القيمة: حالة مستقبل GPS عند تسجيل الصورة.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


يحصل أو يعيّن العلامات التي تخص قسم GPS فقط.

القيمة: وسوم GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


يحصل أو يعيّن وقت GPS كـ UTC (التوقيت العالمي المنسق).

القيمة: وقت GPS كـ UTC (التوقيت العالمي المنسق).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


يحصل أو يعيّن اتجاه حركة جهاز استقبال GPS.

القيمة: اتجاه حركة مستقبل GPS.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


يحصل أو يعيّن المرجع لتحديد اتجاه حركة جهاز استقبال GPS.

القيمة: المرجع لتحديد اتجاه حركة مستقبل GPS.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


يحصل أو يعيّن معرف إصدار GPS.

القيمة: معرف إصدار GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


يحصل أو يعيّن درجة تعديل الكسب الكلي للصورة.

القيمة: درجة تعديل الكسب الكلي للصورة.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


يحصل أو يعيّن قيمة الجاما.

القيمة: قيمة غاما.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


يحصل أو يعيّن سرعة ISO

القيمة: سرعة ISO.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


يحصل أو يعيّن قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه الوسم بدون ISOSpeed و ISOSpeedLatitudezzz.

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


يحصل أو يعيّن قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه الوسم بدون ISOSpeed و ISOSpeedLatitudeyyy.

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


الحصول أو تعيين وصف الصورة.

القيمة: وصف الصورة.

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


الحصول أو تعيين طول الصورة.

القيمة: طول الصورة.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


يحصل أو يضبط المعرف الفريد للصورة.

القيمة: المعرف الفريد للصورة.

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


الحصول أو تعيين عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


يحصل أو يضبط صانع العدسة.

القيمة: صانع العدسة.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


يحصل أو يضبط طراز العدسة.

القيمة: طراز العدسة.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


يحصل أو يضبط الرقم التسلسلي للعدسة.

القيمة: الرقم التسلسلي للعدسة.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


يحصل أو يضبط مواصفات العدسة

القيمة: مواصفة العدسة.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


يحصل أو يضبط مصدر الضوء.

القيمة: مصدر الضوء.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


يحصل على الشركة المصنعة لمعدات التسجيل.

القيمة: الشركة المصنعة لمعدات التسجيل.

**Returns:**
java.lang.String - الشركة المصنعة لمعدات التسجيل.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


يحصل على بيانات ملاحظة الصانع.

القيمة: بيانات ملاحظة الصانع.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


يحصل أو يضبط البيانات الخام لملاحظة الصانع.

القيمة: البيانات الخام لملاحظة الصانع.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


يحصل على ملاحظات الصانع.

القيمة: ملاحظات الصانع.

**Returns:**
com.aspose.psd.exif.MakerNote[] - ملاحظات الصانع.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


يحصل أو يضبط قيمة الفتحة القصوى.

القيمة: قيمة الفتحة القصوى.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


يحصل أو يضبط وضع القياس.

القيمة: وضع القياس.

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


الحصول أو تعيين النموذج.

القيمة: النموذج.

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


يحصل أو يضبط وظيفة التحويل الضوئي-الكهربي (OECF) المحددة في ISO 14524.

القيمة: دالة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


الحصول أو تعيين الاتجاه.

القيمة: الاتجاه.

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


يحصل أو يضبط الحساسية الفوتوغرافية.

القيمة: الحساسية الفوتوغرافية.

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


الحصول أو تعيين التفسير الضوئي.

القيمة: التفسير الضوئي.

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


يحصل أو يضبط البُعد X للبكسل.

القيمة: البُعد السيني للبكسل.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


يحصل أو يضبط البُعد Y للبكسل.

القيمة: البُعد الصادي للبكسل.

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


الحصول أو تعيين تكوين المستوى.

القيمة: تكوين المستوي.

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


الحصول أو تعيين اللونية للثلاث ألوان الأساسية في الصورة.

القيمة: اللونية للثلاث ألوان أساسية في الصورة.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


يحصل أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS).

القيمة: وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


يحصل أو يضبط مؤشر التعرض الموصى به.

القيمة: مؤشر التعرض الموصى به.

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


الحصول أو تعيين المرجع الأسود والأبيض.

القيمة: المرجع الأسود والأبيض.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


يحصل أو يضبط ملف الصوت المرتبط.

القيمة: ملف الصوت المرتبط.

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


الحصول أو تعيين وحدة الدقة.

القيمة: وحدة الدقة.

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


الحصول أو تعيين العينات لكل بكسل.

القيمة: العينات لكل بكسل.

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


يحصل أو يضبط التشبع.

القيمة: التشبع.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


يحصل أو يضبط نوع التقاط المشهد.

القيمة: نوع التقاط المشهد.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


يحصل أو يضبط نوع المشهد.

القيمة: نوع المشهد.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


يحصل أو يضبط طريقة الاستشعار.

القيمة: طريقة الاستشعار.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


يحصل أو يضبط نوع الحساسية.

القيمة: نوع الحساسية.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


يحصل أو يضبط الحدة.

القيمة: الحدة.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


يحصل أو يضبط قيمة سرعة الغالق.

القيمة: قيمة سرعة الغالق.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


الحصول أو تعيين البرنامج.

القيمة: البرنامج.

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


يحصل أو يضبط استجابة التردد المكاني.

القيمة: استجابة التردد المكاني.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


يحصل أو يضبط الحساسية الطيفية.

القيمة: الحساسية الطيفية.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


يحصل على الحساسية القياسية للإخراج

القيمة: حساسية الإخراج القياسية.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


يحصل أو يضبط منطقة الموضوع.

القيمة: منطقة العنصر.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


يحصل أو يضبط مسافة الموضوع.

القيمة: مسافة العنصر.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


يحصل أو يضبط نطاق مسافة الموضوع.

القيمة: نطاق مسافة العنصر.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


يحصل أو يضبط موقع الموضوع.

القيمة: موقع العنصر.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


يحصل أو يضبط أجزاء الثواني للوسم DateTime.

القيمة: أجزاء الثواني للعلامة DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


يحصل أو يضبط أجزاء الثواني للوسم DateTimeDigitized.

القيمة: أجزاء الثواني للعلامة DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


يحصل أو يضبط أجزاء الثواني للوسم DateTimeOriginal.

القيمة: أجزاء الثواني للعلامة DateTimeOriginal.

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


الحصول أو تعيين صورة المصغرة.

القيمة: الصورة المصغرة.

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


الحصول أو تعيين دالة النقل.

القيمة: دالة النقل.

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


يحصل أو يضبط تعليق المستخدم.

القيمة: تعليق المستخدم.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


يحصل أو يضبط توازن الأبيض.

القيمة: توازن اللون الأبيض.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


يحصل أو يضبط اللونية لنقطة الأبيض في الصورة.

القيمة: اللونية لنقطة اللون الأبيض في الصورة.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


الحصول أو تعيين دقة x.

القيمة: دقة x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


الحصول أو تعيين معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

القيمة: معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


الحصول أو تعيين موضع مكونات التشبع اللوني بالنسبة للمكون الإضاءة.

القيمة: موضع مكونات التشبع اللوني بالنسبة للمكون الإضاءة.

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


الحصول أو تعيين نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة للمكون الإضاءة.

القيمة: نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة للمكون الإضاءة.

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


الحصول أو تعيين دقة y.

القيمة: دقة y.

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


يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF المتدفقة التي تم إنشاؤها من هي ذات ترتيب big endian.

القيمة:  true  إذا كانت بيانات EXIF التي تم إنشاؤها من الدفق ذات ترتيب بايت كبير؛ وإلا،  false .

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


إزالة الوسم من الحاوية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة لإزالتها. |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


يقوم بتسلسل بيانات EXIF. يكتب قيم العلامات ومحتوياتها. العلامة الأكثر تأثيرًا على الحجم هي محتويات علامة Thumbnail.

**Returns:**
byte[] - البيانات المتسلسلة EXIF.

يجب أن يكون حجم الجزء الكلي أقل من أو يساوي MaxExifSegmentSize بايت لإنتاج صورة jpeg صحيحة. تلميح: حاول تقليل حجم الصورة المصغرة أو تغيير ضغطها في حال كان حجم قسم EXIF كبيرًا جدًا.
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


يحصل أو يعيّن قيمة الفتحة.

القيمة: قيمة الفتحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


الحصول أو تعيين الفنان.

القيمة: الفنان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF المتدفقة التي تم إنشاؤها من هي ذات ترتيب big endian.

القيمة:  true  إذا كانت بيانات EXIF التي تم إنشاؤها من الدفق ذات ترتيب بايت كبير؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


الحصول أو تعيين عدد البتات لكل عينة.

القيمة: عدد البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


يحصل أو يعيّن الرقم التسلسلي لجسم الكاميرا.

القيمة: الرقم التسلسلي للجسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


يحصل أو يعيّن قيمة السطوع.

القيمة: قيمة السطوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


يحصل أو يعيّن نمط CFA.

القيمة: نمط CFA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


يحصل أو يعيّن اسم مالك الكاميرا

القيمة: اسم مالك الكاميرا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


يحصل أو يعيّن مساحة اللون.

القيمة: مساحة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي تنسيق tiff يتم استخدام tiffOptions بدلاً من ذلك

القيمة: علامات القسم المشترك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


يحصل أو يعيّن تكوين المكونات.

القيمة: تكوين المكونات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل.

القيمة: عدد البتات المضغوطة لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


الحصول أو تعيين الضغط.

القيمة: الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


يحصل أو يعيّن التباين.

القيمة: التباين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


الحصول أو تعيين حقوق النشر.

القيمة: حقوق النشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


يحصل أو يعيّن الإخراج المخصص.

القيمة: تم العرض المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


الحصول أو تعيين تاريخ ووقت.

القيمة: تاريخ ووقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


يحصل أو يعيّن تاريخ ووقت الرقمنة.

القيمة: تاريخ ووقت الرقمنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


يحصل أو يعيّن تاريخ ووقت الأصل.

القيمة: تاريخ ووقت الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


يحصل أو يعيّن وصف إعدادات الجهاز

القيمة: وصف إعداد الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


يحصل أو يعيّن نسبة التكبير الرقمي.

القيمة: نسبة التكبير الرقمي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط.

القيمة: علامات قسم EXIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


يحصل أو يعيّن نسخة EXIF.

القيمة: نسخة EXIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


يحصل أو يعيّن قيمة انحياز التعرض.

القيمة: قيمة إزاحة التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


يحصل أو يعيّن مؤشر التعرض.

القيمة: فهرس التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


يحصل أو يضبط وضع التعريض.

القيمة: وضع التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


يحصل أو يضبط برنامج التعريض.

القيمة: برنامج التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


يحصل أو يضبط زمن التعريض.

القيمة: زمن التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


يحصل أو يضبط رقم F.

القيمة: رقم F.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


يحصل أو يضبط نوع مصدر الملف.

القيمة: نوع مصدر الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


يحصل أو يضبط الفلاش.

القيمة: الفلاش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


يحصل أو يضبط طاقة الفلاش.

القيمة: طاقة الفلاش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


يحصل أو يضبط نسخة فلاش pix.

القيمة: إصدار FlashPix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


يحصل أو يضبط البعد البؤري.

القيمة: طول البؤري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


يحصل أو يضبط البعد البؤري في فيلم 35 مم.

القيمة: طول البؤرة في فيلم 35 مم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


يحصل أو يضبط وحدة دقة المستوى البؤري.

القيمة: وحدة دقة سطح البؤرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


يحصل أو يضبط دقة المستوى البؤري X.

القيمة: دقة سطح البؤرة X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


يحصل أو يضبط دقة المستوى البؤري Y.

القيمة: دقة سطح البؤرة Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


يحصل أو يضبط ارتفاع GPS.

القيمة: ارتفاع نظام تحديد المواقع (GPS).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي.

القيمة: ارتفاع GPS المستخدم كارتفاع مرجعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


يحصل أو يضبط معلومات منطقة GPS.

القيمة: معلومات منطقة GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


يحصل أو يضبط DOP GPS (درجة دقة البيانات).

القيمة: DOP GPS (درجة دقة البيانات).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل تاريخ ووقت المعلومات بالنسبة إلى UTC (الوقت العالمي المنسق).

القيمة: سلسلة الأحرف GPS التي تسجل تاريخ ووقت المعلومات بالنسبة إلى توقيت UTC (التوقيت العالمي المنسق).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة.

القيمة: اتجاه GPS إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

القيمة: مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


يحصل أو يضبط مسافة GPS إلى نقطة الوجهة.

القيمة: مسافة GPS إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

القيمة: وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


يحصل أو يضبط خط عرض GPS لنقطة الوجهة.

القيمة: خط عرض GPS لنقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


يحصل أو يضبط خط طول GPS لنقطة الوجهة.

القيمة: خط طول GPS لنقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS.

القيمة: قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


يحصل أو يعيّن اتجاه GPS للصورة عند التقاطها.

القيمة: اتجاه GPS للصورة عند التقاطها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


يحصل أو يعيّن مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

القيمة: مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


يحصل أو يعيّن خط عرض GPS.

القيمة: خط عرض GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


يحصل أو يعيّن ما إذا كان خط عرض GPS شماليًا أم جنوبيًا.

القيمة: خط عرض GPS هو شمالي أو جنوبي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


يحصل أو يعيّن خط طول GPS.

القيمة: خط الطول GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


يحصل أو يعيّن ما إذا كان خط طول GPS شرقًا أم غربًا.

القيمة: خط الطول GPS هو خط الطول الشرقي أو الغربي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


يحصل أو يعيّن بيانات المسح الجيوديسي GPS المستخدمة من قبل جهاز استقبال GPS.

القيمة: بيانات المسح الجيوديسي GPS المستخدمة بواسطة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


يحصل أو يعيّن وضع قياس GPS.

القيمة: وضع قياس GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


يحصل أو يعيّن سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

القيمة: سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


يحصل أو يعيّن أقمار GPS المستخدمة للقياسات.

القيمة: أقمار GPS المستخدمة للقياسات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


يحصل أو يعيّن سرعة حركة جهاز استقبال GPS.

القيمة: سرعة حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


يحصل أو يعيّن الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS.

القيمة: الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


يحصل أو يعيّن حالة جهاز استقبال GPS عند تسجيل الصورة.

القيمة: حالة مستقبل GPS عند تسجيل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تخص قسم GPS فقط.

القيمة: وسوم GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


يحصل أو يعيّن وقت GPS كـ UTC (التوقيت العالمي المنسق).

القيمة: وقت GPS كـ UTC (التوقيت العالمي المنسق).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


يحصل أو يعيّن اتجاه حركة جهاز استقبال GPS.

القيمة: اتجاه حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


يحصل أو يعيّن المرجع لتحديد اتجاه حركة جهاز استقبال GPS.

القيمة: المرجع لتحديد اتجاه حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


يحصل أو يعيّن معرف إصدار GPS.

القيمة: معرف إصدار GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


يحصل أو يعيّن درجة تعديل الكسب الكلي للصورة.

القيمة: درجة تعديل الكسب الكلي للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


يحصل أو يعيّن قيمة الجاما.

القيمة: قيمة غاما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


يحصل أو يعيّن سرعة ISO

القيمة: سرعة ISO.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


يحصل أو يعيّن قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه الوسم بدون ISOSpeed و ISOSpeedLatitudezzz.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


يحصل أو يعيّن قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه الوسم بدون ISOSpeed و ISOSpeedLatitudeyyy.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


الحصول أو تعيين وصف الصورة.

القيمة: وصف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


الحصول أو تعيين طول الصورة.

القيمة: طول الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


يحصل أو يضبط المعرف الفريد للصورة.

القيمة: المعرف الفريد للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


الحصول أو تعيين عرض الصورة.

القيمة: عرض الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


يحصل أو يضبط صانع العدسة.

القيمة: صانع العدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


يحصل أو يضبط طراز العدسة.

القيمة: طراز العدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


يحصل أو يضبط الرقم التسلسلي للعدسة.

القيمة: الرقم التسلسلي للعدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


يحصل أو يضبط مواصفات العدسة

القيمة: مواصفة العدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


يحصل أو يضبط مصدر الضوء.

القيمة: مصدر الضوء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


يضبط الشركة المصنعة لمعدات التسجيل.

القيمة: الشركة المصنعة لمعدات التسجيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | مصنّع معدات التسجيل. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


يحصل أو يضبط البيانات الخام لملاحظة الصانع.

القيمة: البيانات الخام لملاحظة الصانع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


يحصل أو يضبط قيمة الفتحة القصوى.

القيمة: قيمة الفتحة القصوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


يحصل أو يضبط وضع القياس.

القيمة: وضع القياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


الحصول أو تعيين النموذج.

القيمة: النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


يحصل أو يضبط وظيفة التحويل الضوئي-الكهربي (OECF) المحددة في ISO 14524.

القيمة: دالة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


الحصول أو تعيين الاتجاه.

القيمة: الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


يحصل أو يضبط الحساسية الفوتوغرافية.

القيمة: الحساسية الفوتوغرافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


الحصول أو تعيين التفسير الضوئي.

القيمة: التفسير الضوئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


يحصل أو يضبط البُعد X للبكسل.

القيمة: البُعد السيني للبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


يحصل أو يضبط البُعد Y للبكسل.

القيمة: البُعد الصادي للبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


الحصول أو تعيين تكوين المستوى.

القيمة: تكوين المستوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


الحصول أو تعيين اللونية للثلاث ألوان الأساسية في الصورة.

القيمة: اللونية للثلاث ألوان أساسية في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


يحصل أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS).

القيمة: وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


يحصل أو يضبط مؤشر التعرض الموصى به.

القيمة: مؤشر التعرض الموصى به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


الحصول أو تعيين المرجع الأسود والأبيض.

القيمة: المرجع الأسود والأبيض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


يحصل أو يضبط ملف الصوت المرتبط.

القيمة: ملف الصوت المرتبط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


الحصول أو تعيين وحدة الدقة.

القيمة: وحدة الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


الحصول أو تعيين العينات لكل بكسل.

القيمة: العينات لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


يحصل أو يضبط التشبع.

القيمة: التشبع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


يحصل أو يضبط نوع التقاط المشهد.

القيمة: نوع التقاط المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


يحصل أو يضبط نوع المشهد.

القيمة: نوع المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


يحصل أو يضبط طريقة الاستشعار.

القيمة: طريقة الاستشعار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


يحصل أو يضبط نوع الحساسية.

القيمة: نوع الحساسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


يحصل أو يضبط الحدة.

القيمة: الحدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


يحصل أو يضبط قيمة سرعة الغالق.

القيمة: قيمة سرعة الغالق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


الحصول أو تعيين البرنامج.

القيمة: البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


يحصل أو يضبط استجابة التردد المكاني.

القيمة: استجابة التردد المكاني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


يحصل أو يضبط الحساسية الطيفية.

القيمة: الحساسية الطيفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


يضبط الحساسية القياسية للإخراج

القيمة: حساسية الإخراج القياسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


يحصل أو يضبط منطقة الموضوع.

القيمة: منطقة العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


يحصل أو يضبط مسافة الموضوع.

القيمة: مسافة العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


يحصل أو يضبط نطاق مسافة الموضوع.

القيمة: نطاق مسافة العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


يحصل أو يضبط موقع الموضوع.

القيمة: موقع العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


يحصل أو يضبط أجزاء الثواني للوسم DateTime.

القيمة: أجزاء الثواني للعلامة DateTime.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


يحصل أو يضبط أجزاء الثواني للوسم DateTimeDigitized.

القيمة: أجزاء الثواني للعلامة DateTimeDigitized.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


يحصل أو يضبط أجزاء الثواني للوسم DateTimeOriginal.

القيمة: أجزاء الثواني للعلامة DateTimeOriginal.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


الحصول أو تعيين صورة المصغرة.

القيمة: الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


الحصول أو تعيين دالة النقل.

القيمة: دالة النقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


يحصل أو يضبط تعليق المستخدم.

القيمة: تعليق المستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


يحصل أو يضبط توازن الأبيض.

القيمة: توازن اللون الأبيض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


يحصل أو يضبط اللونية لنقطة الأبيض في الصورة.

القيمة: اللونية لنقطة اللون الأبيض في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


الحصول أو تعيين دقة x.

القيمة: دقة x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


الحصول أو تعيين معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

القيمة: معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


الحصول أو تعيين موضع مكونات التشبع اللوني بالنسبة للمكون الإضاءة.

القيمة: موضع مكونات التشبع اللوني بالنسبة للمكون الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


الحصول أو تعيين نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة للمكون الإضاءة.

القيمة: نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة للمكون الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


الحصول أو تعيين دقة y.

القيمة: دقة y.

**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

