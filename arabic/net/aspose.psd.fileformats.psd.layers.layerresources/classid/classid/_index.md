---
title: ClassID.ClassID
second_title: Aspose.PSD لمرجع .NET API
description: ClassID البناء. يقوم بتهيئة مثيل جديد لملفClassID فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`ClassID`](../) فئة .

```csharp
public ClassID(byte[] classID)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| classID | Byte[] | معرف الفئة كسلسلة من البايت. |

### أنظر أيضا

* class [ClassID](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* المجسم [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`ClassID`](../) فئة .

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| classID | Byte[] | معرف الفئة كسلسلة من البايت. |
| isZeroLength | Boolean | إذا تم التعيين على`حقيقي` [طول صفري] . طول السلسلة المسجلة صفر ولكن الفعلي أربعة . |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | classID خالية. |

### أنظر أيضا

* class [ClassID](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* المجسم [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`ClassID`](../) فئة .

```csharp
public ClassID(int classID)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| classID | Int32 | معرف الفصل. |

### أنظر أيضا

* class [ClassID](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* المجسم [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`ClassID`](../) فئة .

```csharp
public ClassID(uint classID)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| classID | UInt32 | معرف الفصل. |

### أنظر أيضا

* class [ClassID](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* المجسم [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`ClassID`](../) فئة .

```csharp
public ClassID(string classID, bool isZeroLength)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| classID | String | معرف الفئة في ترميز ASCII. |
| isZeroLength | Boolean | إذا تم التعيين على`حقيقي` [طوله صفر]. |

### أمثلة

يوضح هذا المثال أن الطبقة ، المستوردة من صورة ، يتم تحويلها إلى طبقة كائن ذكي وأن ملف PSD المحفوظ صحيح.

```csharp
[C#]

// تختبر أن الطبقة ، المستوردة من صورة ، يتم تحويلها إلى طبقة كائن ذكي وأن ملف PSD المحفوظ صحيح.

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### أنظر أيضا

* class [ClassID](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* المجسم [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`ClassID`](../) فئة .

```csharp
public ClassID(string classID)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| classID | String | معرف الفئة في ترميز ASCII. |

### أنظر أيضا

* class [ClassID](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* المجسم [Aspose.PSD](../../../)


