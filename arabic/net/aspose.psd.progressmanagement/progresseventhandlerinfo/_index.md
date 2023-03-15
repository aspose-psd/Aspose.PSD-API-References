---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo فصل. تمثل هذه الفئة معلومات حول تقدم عمليات تحميل / حفظ / تصدير الصور  التي يمكن استخدامها في تطبيق خارجي لإظهار تقدم التحويل إلى user
type: docs
weight: 5300
url: /ar/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

تمثل هذه الفئة معلومات حول تقدم عمليات تحميل / حفظ / تصدير الصور ، التي يمكن استخدامها في تطبيق خارجي لإظهار تقدم التحويل إلى user

```csharp
public class ProgressEventHandlerInfo
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | يحصل على وصف الحدث |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | يحصل على نوع الحدث. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | يحصل على الحد الأعلى لقيمة التقدم . |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | يحصل على قيمة التقدم الحالية . |

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

* مساحة الاسم [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* المجسم [Aspose.PSD](../../)


