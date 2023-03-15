---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD لمرجع .NET API
description: مرجع دالة معالج حدث التقدم
type: docs
weight: 5280
url: /ar/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

مرجع دالة معالج حدث التقدم

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | بيانات معالج حدث التقدم. |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


