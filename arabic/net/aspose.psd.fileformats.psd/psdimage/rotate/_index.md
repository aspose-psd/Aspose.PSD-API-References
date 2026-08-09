---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. تدوير الصورة حول المركز"
type: docs
weight: 670
url: /ar/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

يدور الصورة حول المركز.

```csharp
public override void Rotate(float angle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الزاوية | Single | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

## أمثلة

الكود التالي يوضح القدرة على تدوير الصورة بزاوية محددة.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// تدوير الصورة بالكامل
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// تدوير الطبقة
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### انظر أيضًا

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

يدور الصورة حول المركز.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الزاوية | Single | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | Boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور محتويات الصورة الداخلية فقط. |
| backgroundColor | لون | لون الخلفية. |

### انظر أيضًا

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


