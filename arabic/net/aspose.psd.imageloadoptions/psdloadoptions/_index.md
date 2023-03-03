---
title: Class PsdLoadOptions
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions فصل. خيارات تحميل Psd
type: docs
weight: 4770
url: /ar/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

خيارات تحميل Psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | الحصول على أو تعيين ما إذا كان سيتم الحفظ مع الصورة المقدمة ، مع أو بدون تحويل الالتواء. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | يحصل أو يحدد ملف[`Image`](../../aspose.psd/image/) خلفية[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | الحصول على أو تعيين وضع استعادة البيانات. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى [تجاهل قناة ألفا] . |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم تجاهل العرض الثابت لطبقة نص PSD عند تنفيذ عملية UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [تحميل مورد التأثيرات] (افتراضيًا لم يتم تحميل المورد). عند تعيين هذا الخيار ، سيتم عرض التأثيرات المدعومة فقط على الصورة المدمجة النهائية. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | الحصول على أو تحديد قيمة تشير إلى [استخدام وضع القراءة فقط]. هذا وضع للقراءة فقط ، مدعوم للتوافق المماثل مع Adobe Photoshop . عند تعيين هذا الخيار ، لن يتم حفظ جميع التغييرات المطبقة على الطبقات في الصورة النهائية. يتم استخدام جميع البيانات من قسم ImageData ، لذا فهي مطابقة لبرنامج Photoshop. افتراضيًا ، لا تكون جميع الصور المحملة متطابقة مع Adobe Photoshop المتوافقة. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى [استخدام القرص لمورد تأثيرات التحميل] (القرص المستخدم افتراضيًا لتحميل مورد التأثيرات ، ولكن يمكن استخدام الذاكرة إذا كانت كافية عن طريق تعيين هذه القيمة على خطأ) . |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC . |

### أمثلة

يوضح المثال التالي أن تقدم تحويل المستند يعمل بشكل صحيح وبدون استثناء.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### أنظر أيضا

* class [LoadOptions](../../aspose.psd/loadoptions/)
* مساحة الاسم [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* المجسم [Aspose.PSD](../../)


