---
title: "فئة PdfOptions"
type: docs
weight: 80
url: /ar/python-net/aspose.psd.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PdfOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | يُنشئ مثيلًا جديدًا من فئة PdfOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| default_replacement_font | string | r/w | يحصل أو يعيّن خط الاستبدال الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى رستر، إذا لم يكن خط الطبقة الموجود في ملف PSD متوفرًا في النظام).<br/>            للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | خيارات الصفحات المتعددة |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | يحصل أو يعيّن حجم الصفحة. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. |
| pdf_core_options | [PdfCoreOptions](/psd/python-net/aspose.psd.fileformats.pdf/pdfcoreoptions/) | r/w | خيارات النواة PDF |
| pdf_document_info | [PdfDocumentInfo](/psd/python-net/aspose.psd.fileformats.pdf/pdfdocumentinfo/) | r/w | يحصل أو يعيّن البيانات الوصفية للمستند. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | يحصل أو يعيّن إعدادات الدقة. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه الحالة. |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

يُنشئ مثيلًا جديدًا من فئة PdfOptions

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذه الحالة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | يعيد نسخة سطحية من هذه الحالة |


