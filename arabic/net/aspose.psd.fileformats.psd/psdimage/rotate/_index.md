---
title: PsdImage.Rotate
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage طريقة. تدوير الصورة حول المركز .
type: docs
weight: 610
url: /ar/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

تدوير الصورة حول المركز .

```csharp
public override void Rotate(float angle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| angle | Single | زاوية الدوران بالدرجات. ستدور القيم الموجبة في اتجاه عقارب الساعة. |

### أمثلة

يوضح الكود التالي القدرة على تدوير الصورة بقيمة زاوية محددة.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// الصورة الكاملة بالتناوب
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

// طبقة الدورية
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

### أنظر أيضا

* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

تدوير الصورة حول المركز .

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| angle | Single | زاوية الدوران بالدرجات. ستدور القيم الموجبة في اتجاه عقارب الساعة. |
| resizeProportionally | Boolean | إذا تم التعيين على`حقيقي` سيتم تغيير حجم صورتك وفقًا لإسقاطات المستطيل المستدير (نقاط الزاوية) في حالة أخرى والتي تترك الأبعاد دون تغيير ويتم تدوير محتويات الصورة الداخلية فقط. |
| backgroundColor | Color | لون الخلفية. |

### أنظر أيضا

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


