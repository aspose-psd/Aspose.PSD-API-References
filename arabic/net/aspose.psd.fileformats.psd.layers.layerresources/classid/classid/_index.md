---
title: "ClassID.ClassID"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ ClassID. يُنشئ مثلاً جديدًا من فئة ClassID"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

يُنشئ مثلاً جديدًا من الفئة [`ClassID`](../).

```csharp
public ClassID(byte[] classID)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classID | Byte[] | معرف الفئة كسلسلة من البايتات. |

### انظر أيضًا

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

يُنشئ مثلاً جديدًا من الفئة [`ClassID`](../).

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classID | Byte[] | معرف الفئة كسلسلة من البايتات. |
| isZeroLength | Boolean | إذا تم تعيينه إلى `true` [is zero length]. طول السلسلة المسجلة هو صفر لكن الفعلي هو أربعة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | classID فارغ. |

### انظر أيضًا

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

يُنشئ مثلاً جديدًا من الفئة [`ClassID`](../).

```csharp
public ClassID(int classID)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classID | Int32 | معرّف الفئة. |

### انظر أيضًا

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

يُنشئ مثلاً جديدًا من الفئة [`ClassID`](../).

```csharp
public ClassID(uint classID)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classID | UInt32 | معرّف الفئة. |

### انظر أيضًا

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

يُنشئ مثلاً جديدًا من الفئة [`ClassID`](../).

```csharp
public ClassID(string classID, bool isZeroLength)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classID | String | معرف الفئة بتشفير ASCII. |
| isZeroLength | Boolean | إذا تم تعيينه إلى `true` [is zero length]. |

## أمثلة

هذا المثال يوضح أن الطبقة المستوردة من صورة يتم تحويلها إلى طبقة كائن ذكي وأن ملف PSD المحفوظ صحيح.

```csharp
[C#]

// يختبر أن الطبقة المستوردة من صورة يتم تحويلها إلى طبقة كائن ذكي وأن ملف PSD المحفوظ صحيح.

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

### انظر أيضًا

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

يُنشئ مثلاً جديدًا من الفئة [`ClassID`](../).

```csharp
public ClassID(string classID)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classID | String | معرف الفئة بتشفير ASCII. |

### انظر أيضًا

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


