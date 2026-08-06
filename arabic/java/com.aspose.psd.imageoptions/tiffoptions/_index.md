---
title: "TiffOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات صيغة ملف tiff."
type: docs
weight: 25
url: /ar/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

خيارات تنسيق ملف TIFF. لاحظ أن وسوم العرض والارتفاع سيتم استبدالها عند إنشاء الصورة بواسطة معلمات العرض والارتفاع، لذا لا حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات تُعيد قيمة افتراضية، لكن هذا لا يعني أن هذا الخيار تم تعيينه صراحةً كقيمة للوسم. للتحقق من وجود الوسم، استخدم خاصية Tags أو الطريقة المقابلة IsTagPresent.

تحذير! لا تقم بتعديل خيارات TIFF أثناء الحفظ لأن ذلك قد يسبب آثارًا جانبية وأخطاء يصعب اكتشافها. تم ترك السطر التالي معلقًا خصيصًا لأنه تسبب في تحديد غير صحيح لبداية البيانات. الخيارات الممررة لم تحتوي على spp (على الرغم من أن الخيارات غير صحيحة في مثل هذه الحالة لكن هذا السيناريو لا يزال يسبب أخطاء) والسطر التالي تسبب في إضافة وسم +spp ووسم +bpp وعند كتابة الخيارات بعد كتابة البيانات بالكامل تم استبدال بداية البيانات للترميز غير المضغوط!!! راجع TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | ينشئ مثيلًا جديدًا من الفئة TiffOptions. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | ينشئ مثيلًا جديدًا من الفئة TiffOptions. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | ينشئ مثيلًا جديدًا من الفئة TiffOptions. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | ينشئ مثيلًا جديدًا من الفئة TiffOptions. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | يضيف وسمًا جديدًا. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | يضيف الوسوم. |
| [clone()](#clone--) |  |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينسخ هذه النسخة. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | يحصل أو يضبط خيار تخزين ألفا. |
| [getArtist()](#getArtist--) | الحصول أو تعيين الفنان. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | يحصل أو يضبط لون الخلفية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل. |
| [getBitsPerSample()](#getBitsPerSample--) | يحصل على عدد البتات لكل عينة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [getByteOrder()](#getByteOrder--) | يحصل أو يضبط قيمة تشير إلى ترتيب بايتات TIFF. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | يحصل على الذاكرة المؤقتة. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | يحصل أو يضبط خريطة الألوان. |
| [getCompressedQuality()](#getCompressedQuality--) | يحصل على جودة الصورة المضغوطة. |
| [getCompression()](#getCompression--) | يحصل على الضغط. |
| [getCopyright()](#getCopyright--) | يحصل على حقوق النشر. |
| [getDateTime()](#getDateTime--) | الحصول أو تعيين التاريخ والوقت. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | الحصول أو تعيين حد تخصيص الذاكرة الافتراضي. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getDocumentName()](#getDocumentName--) | الحصول أو تعيين اسم المستند. |
| [getExifIfd()](#getExifIfd--) | الحصول أو تعيين المؤشر إلى EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | الحصول على عدد العينات الإضافية. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | الحصول على قيم العينات الإضافية. |
| [getFaxT4Options()](#getFaxT4Options--) | الحصول أو تعيين خيارات الفاكس t4. |
| [getFileStandard()](#getFileStandard--) | الحصول أو تعيين معيار ملف TIFF. |
| [getFillOrder()](#getFillOrder--) | الحصول أو تعيين ترتيب تعبئة بتات البايت. |
| [getFullFrame()](#getFullFrame--) | يحصل على قيمة تشير إلى ما إذا كان [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | الحصول أو تعيين تلميحات نصف الظل. |
| [getIccProfile()](#getIccProfile--) | الحصول على تدفق ملف تعريف ICC. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [getImageDescription()](#getImageDescription--) | الحصول أو تعيين وصف الصورة. |
| [getImageLength()](#getImageLength--) | الحصول أو تعيين طول الصورة. |
| [getImageWidth()](#getImageWidth--) | الحصول أو تعيين عرض الصورة. |
| [getInkNames()](#getInkNames--) | الحصول أو تعيين أسماء الحبر. |
| [getMaxSampleValue()](#getMaxSampleValue--) | الحصول أو تعيين قيمة العينة القصوى. |
| [getMinSampleValue()](#getMinSampleValue--) | الحصول أو تعيين قيمة العينة الدنيا. |
| [getMultiPageOptions()](#getMultiPageOptions--) | خيارات الصفحات المتعددة |
| [getOrientation()](#getOrientation--) | الحصول أو تعيين الاتجاه. |
| [getPageName()](#getPageName--) | الحصول أو تعيين اسم الصفحة. |
| [getPageNumber()](#getPageNumber--) | الحصول أو تعيين علامة رقم الصفحة. |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان. |
| [getPhotometric()](#getPhotometric--) | الحصول أو تعيين الخصائص الضوئية. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | الحصول أو تعيين تكوين المستوى. |
| [getPredictor()](#getPredictor--) | الحصول أو تعيين المتنبئ لضغط LZW. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | الحصول أو تعيين قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل أو يضبط معالج حدث التقدم. |
| [getResolutionSettings()](#getResolutionSettings--) | يحصل أو يضبط إعدادات الدقة. |
| [getResolutionUnit()](#getResolutionUnit--) | الحصول أو تعيين وحدة الدقة. |
| [getRowsPerStrip()](#getRowsPerStrip--) | الحصول أو تعيين عدد الصفوف لكل شريط. |
| [getSampleFormat()](#getSampleFormat--) | الحصول أو تعيين تنسيق العينة. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | الحصول على العينات لكل بكسل. |
| [getScannerManufacturer()](#getScannerManufacturer--) | الحصول أو تعيين شركة تصنيع الماسح. |
| [getScannerModel()](#getScannerModel--) | الحصول أو تعيين طراز الماسح. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | الحصول أو تعيين قيمة العينة القصوى. |
| [getSminSampleValue()](#getSminSampleValue--) | الحصول أو تعيين قيمة العينة الدنيا. |
| [getSoftwareType()](#getSoftwareType--) | الحصول أو تعيين نوع البرنامج. |
| [getSource()](#getSource--) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [getStripByteCounts()](#getStripByteCounts--) | يحصل أو يضبط عدد بايتات الشريط. |
| [getStripOffsets()](#getStripOffsets--) | يحصل أو يضبط إزاحات الشريط. |
| [getSubFileType()](#getSubFileType--) | يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [getTagByType(int tagKey)](#getTagByType-int-) | يحصل على نسخة العلامة حسب النوع. |
| [getTags()](#getTags--) | يحصل أو يضبط العلامات. |
| [getTargetPrinter()](#getTargetPrinter--) | يحصل أو يضبط الطابعة المستهدفة. |
| [getThreshholding()](#getThreshholding--) | يحصل أو يضبط عملية العتبة. |
| [getTileByteCounts()](#getTileByteCounts--) | يحصل أو يضبط عدد بايتات البلاطة. |
| [getTileLength()](#getTileLength--) | يحصل أو يضبط طول البلاطة. |
| [getTileOffsets()](#getTileOffsets--) | يحصل أو يضبط إزاحات البلاطة. |
| [getTileWidth()](#getTileWidth--) | يحصل أو يضبط عرض البلاطة. |
| [getTotalPages()](#getTotalPages--) | يحصل على إجمالي الصفحات. |
| [getValidTagCount()](#getValidTagCount--) | يحصل على عدد العلامات الصالحة. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | يحصل على عدد العلامات الصالحة. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [getXPAuthor()](#getXPAuthor--) | يحصل على مؤلف الصورة، الذي يستخدمه مستكشف Windows. |
| [getXPComment()](#getXPComment--) | يحصل على تعليق على الصورة، الذي يستخدمه مستكشف Windows. |
| [getXPKeywords()](#getXPKeywords--) | يحصل على صورة الموضوع، التي يستخدمها مستكشف Windows. |
| [getXPSubject()](#getXPSubject--) | يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [getXPTitle()](#getXPTitle--) | يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [getXmpData()](#getXmpData--) | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [getXposition()](#getXposition--) | يحصل أو يضبط موضع x. |
| [getXresolution()](#getXresolution--) | الحصول أو تعيين دقة x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | يحصل أو يضبط YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | يحصل أو يضبط عوامل أخذ العينات الفرعية للقياس الضوئي YCbCr. |
| [getYposition()](#getYposition--) | يحصل أو يضبط موضع y. |
| [getYresolution()](#getYresolution--) | الحصول أو تعيين دقة y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة. |
| [isTagPresent(int tag)](#isTagPresent-int-) | يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [isTiled()](#isTiled--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى بلاطات. |
| [isValid()](#isValid--) | يحصل على قيمة تشير إلى ما إذا تم تكوين  TiffOptions  بشكل صحيح. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | يزيل العلامة. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | يحصل أو يضبط خيار تخزين ألفا. |
| [setArtist(String value)](#setArtist-java.lang.String-) | الحصول أو تعيين الفنان. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | يحصل أو يضبط لون الخلفية. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | يضبط عدد البتات لكل عينة. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [setByteOrder(int value)](#setByteOrder-int-) | يحصل أو يضبط قيمة تشير إلى ترتيب بايتات TIFF. |
| [setColorMap(int[] value)](#setColorMap-int---) | يحصل أو يضبط خريطة الألوان. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | يضبط جودة الصورة المضغوطة. |
| [setCompression(int value)](#setCompression-int-) | يضبط الضغط. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | يضبط حقوق النشر. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | الحصول أو تعيين التاريخ والوقت. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | الحصول أو تعيين حد تخصيص الذاكرة الافتراضي. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | الحصول أو تعيين اسم المستند. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | يضبط قيم العينات الإضافية. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | الحصول أو تعيين خيارات الفاكس t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | الحصول أو تعيين معيار ملف TIFF. |
| [setFillOrder(int value)](#setFillOrder-int-) | الحصول أو تعيين ترتيب تعبئة بتات البايت. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | الحصول أو تعيين تلميحات نصف الظل. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | يضبط تدفق ملف تعريف ICC. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | الحصول أو تعيين وصف الصورة. |
| [setImageLength(long value)](#setImageLength-long-) | الحصول أو تعيين طول الصورة. |
| [setImageWidth(long value)](#setImageWidth-long-) | الحصول أو تعيين عرض الصورة. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | الحصول أو تعيين أسماء الحبر. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | الحصول أو تعيين قيمة العينة القصوى. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | الحصول أو تعيين قيمة العينة الدنيا. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | خيارات الصفحات المتعددة |
| [setOrientation(int value)](#setOrientation-int-) | الحصول أو تعيين الاتجاه. |
| [setPageName(String value)](#setPageName-java.lang.String-) | الحصول أو تعيين اسم الصفحة. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | الحصول أو تعيين علامة رقم الصفحة. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يحصل أو يضبط لوحة الألوان. |
| [setPhotometric(int value)](#setPhotometric-int-) | الحصول أو تعيين الخصائص الضوئية. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | الحصول أو تعيين تكوين المستوى. |
| [setPredictor(int value)](#setPredictor-int-) | الحصول أو تعيين المتنبئ لضغط LZW. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | الحصول أو تعيين قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يحصل أو يضبط معالج حدث التقدم. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | يحصل أو يضبط إعدادات الدقة. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | الحصول أو تعيين وحدة الدقة. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | الحصول أو تعيين عدد الصفوف لكل شريط. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | الحصول أو تعيين تنسيق العينة. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | الحصول أو تعيين شركة تصنيع الماسح. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | الحصول أو تعيين طراز الماسح. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | الحصول أو تعيين قيمة العينة القصوى. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | الحصول أو تعيين قيمة العينة الدنيا. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | الحصول أو تعيين نوع البرنامج. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | يحصل أو يضبط عدد بايتات الشريط. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | يحصل أو يضبط إزاحات الشريط. |
| [setSubFileType(long value)](#setSubFileType-long-) | يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | يحصل أو يضبط العلامات. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | يحصل أو يضبط الطابعة المستهدفة. |
| [setThreshholding(int value)](#setThreshholding-int-) | يحصل أو يضبط عملية العتبة. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | يحصل أو يضبط عدد بايتات البلاطة. |
| [setTileLength(long value)](#setTileLength-long-) | يحصل أو يضبط طول البلاطة. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | يحصل أو يضبط إزاحات البلاطة. |
| [setTileWidth(long value)](#setTileWidth-long-) | يحصل أو يضبط عرض البلاطة. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | يضبط مؤلف الصورة، والذي يستخدمه مستكشف Windows. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | يضبط التعليق على الصورة، والذي يستخدمه مستكشف Windows. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | يضبط موضوع الصورة، والذي يستخدمه مستكشف Windows. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | يضبط معلومات حول الصورة، والذي يستخدمه مستكشف Windows. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | يضبط معلومات حول الصورة، والذي يستخدمه مستكشف Windows. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط موضع x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | الحصول أو تعيين دقة x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | يحصل أو يضبط YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | يحصل أو يضبط عوامل أخذ العينات الفرعية للقياس الضوئي YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | يحصل أو يضبط موضع y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | الحصول أو تعيين دقة y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | يتحقق من صحة ما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


ينشئ مثيلًا جديدًا من الفئة TiffOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | int | تنسيق ملف tiff المتوقع. |
| byteOrder | int | ترتيب البايت لتنسيق ملف TIFF الذي سيُستخدم. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


ينشئ مثيلاً جديداً من الفئة TiffOptions. بشكل افتراضي يتم استخدام نظام little endian.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | int | تنسيق ملف tiff المتوقع. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


ينشئ مثيلًا جديدًا من الفئة TiffOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | الخيارات التي سيتم النسخ منها. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


ينشئ مثيلًا جديدًا من الفئة TiffOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | العلامات التي سيتم تهيئة الخيارات بها. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


يضيف وسمًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | العلامة التي سيتم إضافتها. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


يضيف الوسوم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | العلامات التي سيتم إضافتها. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


ينسخ هذه النسخة.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


يحصل أو يضبط خيار تخزين ألفا. تُستخدم الخيارات غير TiffAlphaStorage.Unspecified عندما يكون هناك أكثر من 3 SamplesPerPixel معرفة.

**Returns:**
int - خيار تخزين ألفا.
### getArtist() {#getArtist--}
```
public String getArtist()
```


الحصول أو تعيين الفنان.

**Returns:**
java.lang.String - الفنان.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


يحصل أو يضبط لون الخلفية. يُستخدم لأغراض داخلية لتخزين لون خلفية الصورة.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل.

**Returns:**
int - عدد البت لكل بكسل.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


يحصل على عدد البتات لكل عينة.

**Returns:**
int[] - قيمة عدد البتات لكل عينة.

عند ضبط هذه القيمة، ضع في اعتبارك أنها ستضبط أيضًا قيمة SamplesPerPixel إلى طول المصفوفة. هاتان الخاصيتان مرتبطتان ارتباطًا وثيقًا جدًا لذا قد يتم ضبطهما معًا فقط.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


يحصل أو يضبط قيمة تشير إلى ترتيب بايتات TIFF.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


يحصل على الذاكرة المؤقتة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العلامة | int | الـ tag (وهو نوع مصفوفة). |

**Returns:**
long[] - قيمة الـ tag.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


يحصل أو يضبط خريطة الألوان.

**Returns:**
int[] - خريطة الألوان.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


يحصل على جودة الصورة المضغوطة. يُستخدم مع ضغط Jpeg.

**Returns:**
int - جودة الصورة المضغوطة.
### getCompression() {#getCompression--}
```
public int getCompression()
```


يحصل على الضغط.

**Returns:**
int - الضغط.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


يحصل على حقوق النشر.

**Returns:**
java.lang.String - حقوق النشر.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


الحصول أو تعيين التاريخ والوقت.

**Returns:**
java.lang.String - التاريخ والوقت.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


الحصول أو تعيين حد تخصيص الذاكرة الافتراضي.

**Returns:**
int - حد تخصيص الذاكرة الافتراضي.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


يحصل أو يضبط الخط الافتراضي للاستبدال (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

القيمة: الخط الافتراضي للاستبدال.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


الحصول أو تعيين اسم المستند.

**Returns:**
java.lang.String - اسم المستند.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


الحصول أو تعيين المؤشر إلى EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


الحصول على عدد العينات الإضافية.

القيمة: عدد العينات الإضافية.

**Returns:**
long - عدد العينات الإضافية.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


الحصول على قيم العينات الإضافية.

القيمة: قيمة العينات الإضافية.

**Returns:**
int[] - قيم العينات الإضافية.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


الحصول أو تعيين خيارات الفاكس t4.

**Returns:**
long - خيارات الفاكس t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


الحصول أو تعيين معيار ملف TIFF.

**Returns:**
int - معيار ملف TIFF.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


الحصول أو تعيين ترتيب تعبئة بتات البايت.

**Returns:**
int - ترتيب تعبئة بتات البايت.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


يحصل على قيمة تشير إلى ما إذا كان [full frame].

القيمة:  true  إذا كان [full frame]؛ وإلا،  false .

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


الحصول أو تعيين تلميحات نصف الظل.

**Returns:**
int[] - تلميحات نصف الظل.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


الحصول على تدفق ملف تعريف ICC.

**Returns:**
byte[] - ملف تعريف icc.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء.

القيمة:  true  إذا تم التجاهل بعد حدث الإنشاء؛ وإلا،  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


الحصول أو تعيين وصف الصورة.

**Returns:**
java.lang.String - وصف الصورة.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


الحصول أو تعيين طول الصورة.

**Returns:**
long - طول الصورة.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


الحصول أو تعيين عرض الصورة.

**Returns:**
long - عرض الصورة.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


الحصول أو تعيين أسماء الحبر.

**Returns:**
java.lang.String - أسماء الحبر.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


الحصول أو تعيين قيمة العينة القصوى.

**Returns:**
int[] - القيمة القصوى للعينات.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


الحصول أو تعيين قيمة العينة الدنيا.

**Returns:**
int[] - قيمة العينة الدنيا.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


خيارات الصفحات المتعددة

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


الحصول أو تعيين الاتجاه.

**Returns:**
int - الاتجاه.
### getPageName() {#getPageName--}
```
public String getPageName()
```


الحصول أو تعيين اسم الصفحة.

**Returns:**
java.lang.String - اسم الصفحة.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


الحصول أو تعيين علامة رقم الصفحة.

**Returns:**
int[] - وسم رقم الصفحة.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل أو يضبط لوحة الألوان.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


الحصول أو تعيين الخصائص الضوئية.

**Returns:**
int - الفوتومتري.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


الحصول أو تعيين تكوين المستوى.

**Returns:**
int - تكوين المستوى.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


الحصول أو تعيين المتنبئ لضغط LZW.

**Returns:**
int - نوع المتنبئ.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


الحصول أو تعيين قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا.

**Returns:**
boolean -  true  إذا كان يجب ضرب المكونات مسبقًا؛ وإلا،  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


يحصل أو يضبط معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


يحصل أو يضبط إعدادات الدقة.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


الحصول أو تعيين وحدة الدقة.

**Returns:**
int - وحدة الدقة.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


الحصول أو تعيين عدد الصفوف لكل شريط.

**Returns:**
long - عدد الصفوف لكل شريط.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


الحصول أو تعيين تنسيق العينة.

**Returns:**
int[] - تنسيق العينة.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


يحصل على العينات لكل بكسل. لتغيير قيمة هذه الخاصية استخدم مُعيّن خاصية  BitsPerSample .

**Returns:**
int - العينات لكل بكسل.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


الحصول أو تعيين شركة تصنيع الماسح.

**Returns:**
java.lang.String - الشركة المصنعة للماسح.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


الحصول أو تعيين طراز الماسح.

**Returns:**
java.lang.String - طراز الماسح.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


يحصل أو يضبط قيمة العينة القصوى. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte, Short أو Long type).

**Returns:**
long[] - قيمة العينة القصوى.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


يحصل أو يضبط قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte, Short أو Long type).

**Returns:**
long[] - قيمة العينة الدنيا.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


الحصول أو تعيين نوع البرنامج.

**Returns:**
java.lang.String - نوع البرنامج.
### getSource() {#getSource--}
```
public final Source getSource()
```


يحصل أو يضبط المصدر لإنشاء الصورة فيه.

القيمة: المصدر لإنشاء الصورة فيه.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


يحصل أو يضبط عدد بايتات الشريط.

**Returns:**
long[] - عدد بايتات الشريط.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


يحصل أو يضبط إزاحات الشريط.

**Returns:**
long[] - إزاحات الشريط.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي.

**Returns:**
long - الإشارة العامة إلى نوع البيانات الموجودة في هذا الملف الفرعي.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


يحصل على نسخة العلامة حسب النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagKey | int | مفتاح الوسم. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


يحصل أو يضبط العلامات.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - العلامات.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


يحصل أو يضبط الطابعة المستهدفة.

**Returns:**
java.lang.String - الطابعة المستهدفة.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


يحصل أو يضبط عملية العتبة.

**Returns:**
int - الحد.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


يحصل أو يضبط عدد بايتات البلاطة.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


يحصل أو يضبط طول البلاطة.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


يحصل أو يضبط إزاحات البلاطة.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


يحصل أو يضبط عرض البلاطة.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


يحصل على إجمالي الصفحات.

**Returns:**
int - إجمالي الصفحات.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


يحصل على عدد العلامات الصالحة. هذا ليس عدد العلامات الإجمالي بل عدد العلامات التي يمكن حفظها.

**Returns:**
int - عدد العلامات الصالحة.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


يحصل على عدد العلامات الصالحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | العلامات المراد التحقق منها. |

**Returns:**
int - عدد العلامات الصالحة.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


يحصل أو يضبط خيارات تمثيل المتجهات.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


يحصل على مؤلف الصورة، الذي يستخدمه مستكشف Windows.

القيمة: مؤلف الصورة، يُستخدم بواسطة مستكشف Windows. الـ  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) يتم تجاهله بواسطة مستكشف Windows إذا كان وسم الـ  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) موجودًا.

**Returns:**
java.lang.String - مؤلف الصورة، الذي يُستخدم بواسطة مستكشف Windows.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


يحصل على تعليق على الصورة، الذي يستخدمه مستكشف Windows.

القيمة: تعليق على الصورة، يُستخدم بواسطة مستكشف Windows.

**Returns:**
java.lang.String - تعليق على الصورة، الذي يُستخدم بواسطة مستكشف Windows.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


يحصل على صورة الموضوع، التي يستخدمها مستكشف Windows.

القيمة: موضوع الصورة، يُستخدم بواسطة مستكشف Windows.

**Returns:**
java.lang.String - موضوع الصورة، الذي يُستخدم بواسطة مستكشف Windows.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows.

القيمة: معلومات عن الصورة، يُستخدم بواسطة مستكشف Windows.

**Returns:**
java.lang.String - معلومات عن الصورة، التي تُستخدم بواسطة مستكشف Windows.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows.

القيمة: معلومات عن الصورة، يُستخدم بواسطة مستكشف Windows. الـ  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) يتم تجاهله بواسطة مستكشف Windows إذا كان وسم الـ  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) موجودًا.

**Returns:**
java.lang.String - معلومات عن الصورة، التي تُستخدم بواسطة مستكشف Windows.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


يحصل أو يضبط حاوية بيانات التعريف XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


يحصل أو يضبط موضع x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


الحصول أو تعيين دقة x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


يحصل أو يضبط YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - معاملات YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


يحصل أو يضبط عوامل أخذ العينات الفرعية للقياس الضوئي YCbCr.

**Returns:**
int[] - عوامل التقسيم الفرعي لـ YCbCr الفوتومتري.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


يحصل أو يضبط موضع y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


الحصول أو تعيين دقة y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة.

**Returns:**
boolean -  true  إذا كان هناك عينات إضافية؛ وإلا،  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العلامة | int | معرف الوسم للتحقق منه. |

**Returns:**
boolean -  true  إذا كان الوسم موجودًا؛ وإلا،  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى بلاطات.

**Returns:**
boolean -  true  إذا كانت الصورة مقسمة إلى بلاطات؛ وإلا،  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


يحصل على قيمة تشير إلى ما إذا كان  TiffOptions  قد تم تكوينه بشكل صحيح. استخدم طريقة Validate للعثور على سبب الفشل.

**Returns:**
boolean -  true  إذا تم تكوين TiffOptions بشكل صحيح؛ وإلا،  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


يزيل العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العلامة | int | الوسم المراد إزالته. |

**Returns:**
boolean - true إذا تم الإزالة بنجاح
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


يحصل أو يضبط خيار تخزين ألفا. تُستخدم الخيارات غير TiffAlphaStorage.Unspecified عندما يكون هناك أكثر من 3 SamplesPerPixel معرفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | خيار تخزين ألفا. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


الحصول أو تعيين الفنان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الفنان. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


يحصل أو يضبط لون الخلفية. يُستخدم لأغراض داخلية لتخزين لون خلفية الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون الخلفية. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


يضبط عدد البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int[] | قيمة البتات لكل عينة. |

عند ضبط هذه القيمة، ضع في اعتبارك أنها ستضبط أيضًا قيمة SamplesPerPixel إلى طول المصفوفة. هاتان الخاصيتان مرتبطتان ارتباطًا وثيقًا جدًا لذا قد يتم ضبطهما معًا فقط. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


يحصل أو يضبط قيمة تشير إلى ترتيب بايتات TIFF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


يحصل أو يضبط خريطة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | خريطة الألوان. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


يضبط جودة الصورة المضغوطة. يُستخدم مع ضغط JPEG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | جودة الصورة المضغوطة. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


يضبط الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الضغط. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


يضبط حقوق النشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | حقوق النشر. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


الحصول أو تعيين التاريخ والوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | التاريخ والوقت. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


الحصول أو تعيين حد تخصيص الذاكرة الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | حد تخصيص الذاكرة الافتراضي. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


يحصل أو يضبط الخط الافتراضي للاستبدال (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

القيمة: الخط الافتراضي للاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


الحصول أو تعيين اسم المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | اسم المستند. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


يضبط قيم العينات الإضافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | قيمة العينات الإضافية. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


الحصول أو تعيين خيارات الفاكس t4.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | خيارات الفاكس T4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


الحصول أو تعيين معيار ملف TIFF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | معيار ملف TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


الحصول أو تعيين ترتيب تعبئة بتات البايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | ترتيب تعبئة بتات البايت. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [full frame].

القيمة:  true  إذا كان [full frame]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


الحصول أو تعيين تلميحات نصف الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | تلميحات نصف النغمة. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


يضبط تدفق ملف تعريف ICC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] | ملف icc. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء.

القيمة:  true  إذا تم التجاهل بعد حدث الإنشاء؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


الحصول أو تعيين وصف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | وصف الصورة. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


الحصول أو تعيين طول الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | طول الصورة. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


الحصول أو تعيين عرض الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | عرض الصورة. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


الحصول أو تعيين أسماء الحبر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | أسماء الحبر. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


الحصول أو تعيين قيمة العينة القصوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | القيمة القصوى للعينات. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


الحصول أو تعيين قيمة العينة الدنيا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | القيمة الدنيا للعينات. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


خيارات الصفحات المتعددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


الحصول أو تعيين الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الاتجاه. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


الحصول أو تعيين اسم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | اسم الصفحة. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


الحصول أو تعيين علامة رقم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | علامة رقم الصفحة. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يحصل أو يضبط لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


الحصول أو تعيين الخصائص الضوئية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الضوئي. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


الحصول أو تعيين تكوين المستوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تكوين المستوى. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


الحصول أو تعيين المتنبئ لضغط LZW.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نوع المتنبئ. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


الحصول أو تعيين قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح إذا كان يجب ضرب المكونات مسبقًا؛ وإلا، خطأ. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


يحصل أو يضبط معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


يحصل أو يضبط إعدادات الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


الحصول أو تعيين وحدة الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وحدة الدقة. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


الحصول أو تعيين عدد الصفوف لكل شريط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | عدد الصفوف لكل شريط. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


الحصول أو تعيين تنسيق العينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | تنسيق العينة. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


الحصول أو تعيين شركة تصنيع الماسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | شركة صانع الماسح. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


الحصول أو تعيين طراز الماسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | طراز الماسح. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


يحصل أو يضبط قيمة العينة القصوى. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte, Short أو Long type).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] | القيمة القصوى للعينات. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


يحصل أو يضبط قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte, Short أو Long type).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] | القيمة الدنيا للعينات. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


الحصول أو تعيين نوع البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | نوع البرنامج. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


يحصل أو يضبط المصدر لإنشاء الصورة فيه.

القيمة: المصدر لإنشاء الصورة فيه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


يحصل أو يضبط عدد بايتات الشريط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] | عدد البايتات في الشريط. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


يحصل أو يضبط إزاحات الشريط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] | إزاحات الشريط. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | الإشارة العامة إلى نوع البيانات الموجودة في هذا الملف الفرعي. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


يحصل أو يضبط العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | العلامات. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


يحصل أو يضبط الطابعة المستهدفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الطابعة المستهدفة. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


يحصل أو يضبط عملية العتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تحديد العتبة. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


يحصل أو يضبط عدد بايتات البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


يحصل أو يضبط طول البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


يحصل أو يضبط إزاحات البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


يحصل أو يضبط عرض البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


يحصل أو يضبط خيارات تمثيل المتجهات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


يضبط مؤلف الصورة، والذي يستخدمه مستكشف Windows.

القيمة: مؤلف الصورة، يُستخدم بواسطة Windows Explorer. يتم تجاهل XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) من قبل Windows Explorer إذا كان وسم Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) موجودًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | مؤلف الصورة، الذي يُستخدم بواسطة Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


يضبط التعليق على الصورة، والذي يستخدمه مستكشف Windows.

القيمة: تعليق على الصورة، يُستخدم بواسطة مستكشف Windows.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | تعليق على الصورة، الذي يُستخدم بواسطة Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


يضبط موضوع الصورة، والذي يستخدمه مستكشف Windows.

القيمة: موضوع الصورة، يُستخدم بواسطة مستكشف Windows.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | صورة الموضوع، التي تُستخدم بواسطة Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


يضبط معلومات حول الصورة، والذي يستخدمه مستكشف Windows.

القيمة: معلومات عن الصورة، يُستخدم بواسطة مستكشف Windows.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | معلومات عن الصورة، التي تُستخدم بواسطة Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


يضبط معلومات حول الصورة، والذي يستخدمه مستكشف Windows.

القيمة: معلومات عن الصورة، تُستخدم بواسطة Windows Explorer. يتم تجاهل XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) من قبل Windows Explorer إذا كان وسم ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) موجودًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | معلومات عن الصورة، التي تُستخدم بواسطة Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يحصل أو يضبط حاوية بيانات التعريف XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | حاوية بيانات XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


يحصل أو يضبط موضع x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | موضع x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


الحصول أو تعيين دقة x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | دقة x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


يحصل أو يضبط YCbCrCoefficients.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | معاملات YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


يحصل أو يضبط عوامل أخذ العينات الفرعية للقياس الضوئي YCbCr.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | عوامل أخذ العينات الفرعية للصور الفوتومترية YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


يحصل أو يضبط موضع y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | موضع y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


الحصول أو تعيين دقة y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | دقة y. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


يتحقق من صحة ما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات

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

