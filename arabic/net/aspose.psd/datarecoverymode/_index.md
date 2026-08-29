---
title: "التعداد DataRecoveryMode"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.DataRecoveryMode. وضع استعادة البيانات"
type: docs
weight: 740
url: /ar/net/aspose.psd/datarecoverymode/
---
{{< psd/tize >}}
## DataRecoveryMode enumeration

وضع استعادة البيانات.

```csharp
public enum DataRecoveryMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لا يُفترض استعادة البيانات. كلما كان تنسيق الملف يحتوي على بعض البيانات التالفة يتم رمي الاستثناء المناسب. |
| ConsistentRecover | `1` | وضع الاستعادة المتسق يحاول استعادة جميع البيانات طالما أن الفساد لا يكسر تنسيق الملف ويسمح بالمعالجة اللاحقة الصحيحة. |
| MaximalRecover | `2` | وضع الاستعادة القصوى يستعيد جميع البيانات حتى إذا كان تنسيق الملف يحتوي على بنية تالفة وقد تؤدي المعالجة اللاحقة إلى تأثيرات غير مقصودة. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


