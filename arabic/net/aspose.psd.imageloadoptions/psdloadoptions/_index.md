---
title: "فئة PsdLoadOptions"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageLoadOptions.PsdLoadOptions. خيارات تحميل Psd."
type: docs
weight: 5250
url: /ar/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

خيارات تحميل PSD

```csharp
public class PsdLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | يحصل أو يعيّن ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء العرض إذا لم يتم تعديل الطبقة. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | يحصل أو يعيّن ما إذا كان يجب الحفظ مع الصورة المرسومة، مع أو بدون تحويل التشويه. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | يحصل أو يعيّن خلفية [`Image`](../../aspose.psd/image/) [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | يحصل أو يعيّن وضع استعادة البيانات. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [تجاهل قناة ألفا]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان سيتم تجاهل عرض النص الثابت لطبقة النص PSD عند تنفيذ عملية UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [تحميل موارد التأثيرات] (بشكل افتراضي لا يتم تحميل المورد). عند تعيين هذا الخيار سيتم عرض التأثيرات المدعومة فقط في الصورة المدمجة النهائية. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [استخدام وضع القراءة فقط]. هذا هو وضع القراءة فقط، مدعوم لتوافق تام مع Adobe Photoshop. عندما يتم تعيين هذا الخيار، لن يتم حفظ جميع التغييرات التي تم تطبيقها على الطبقات في الصورة النهائية. يتم استخدام جميع البيانات من قسم ImageData، لذا فهو مطابق لـ Photoshop. بشكل افتراضي، جميع الصور المحملة ليست متوافقة تماماً مع Adobe Photoshop. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | يحصل أو يعيّن وضع القراءة فقط المستخدم عند تحميل صورة PSD. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [استخدام القرص لتحميل موارد التأثيرات] (بشكل افتراضي يُستخدم القرص لتحميل موارد التأثيرات، ولكن يمكن استخدام الذاكرة إذا كان ذلك كافياً بتعيين هذه القيمة إلى false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |

## أمثلة

المثال التالي يوضح أن تقدم تحويل المستند يعمل بشكل صحيح وبدون استثناء.

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

### انظر أيضًا

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


