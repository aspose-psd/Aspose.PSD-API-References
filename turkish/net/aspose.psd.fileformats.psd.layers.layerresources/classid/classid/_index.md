---
title: ClassID.ClassID
second_title: Aspose.PSD for .NET API Referansı
description: ClassID inşaatçı. Yeni bir örneğini başlatır.ClassID sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Yeni bir örneğini başlatır.[`ClassID`](../) sınıf.

```csharp
public ClassID(byte[] classID)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| classID | Byte[] | Bayt dizisi olarak sınıf kimliği. |

### Ayrıca bakınız

* class [ClassID](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* toplantı [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Yeni bir örneğini başlatır.[`ClassID`](../) sınıf.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| classID | Byte[] | Bayt dizisi olarak sınıf kimliği. |
| isZeroLength | Boolean | olarak ayarlanmışsa`doğru` [sıfır uzunluk]. Kaydedilen dizi uzunluğu sıfır ama gerçek dört. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | sınıf kimliği boş. |

### Ayrıca bakınız

* class [ClassID](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* toplantı [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Yeni bir örneğini başlatır.[`ClassID`](../) sınıf.

```csharp
public ClassID(int classID)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| classID | Int32 | Sınıf kimliği. |

### Ayrıca bakınız

* class [ClassID](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* toplantı [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Yeni bir örneğini başlatır.[`ClassID`](../) sınıf.

```csharp
public ClassID(uint classID)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| classID | UInt32 | Sınıf kimliği. |

### Ayrıca bakınız

* class [ClassID](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* toplantı [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Yeni bir örneğini başlatır.[`ClassID`](../) sınıf.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| classID | String | ASCII kodlamasındaki sınıf kimliği. |
| isZeroLength | Boolean | olarak ayarlanmışsa`doğru` [sıfır uzunluktur]. |

### Örnekler

Bu örnek, bir görüntüden içe aktarılan katmanın akıllı nesne katmanına dönüştürüldüğünü ve kaydedilen PSD dosyasının doğru olduğunu göstermektedir.

```csharp
[C#]

// Bir görüntüden içe aktarılan katmanın akıllı nesne katmanına dönüştürüldüğünü ve kaydedilen PSD dosyasının doğru olduğunu test eder.

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

### Ayrıca bakınız

* class [ClassID](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* toplantı [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Yeni bir örneğini başlatır.[`ClassID`](../) sınıf.

```csharp
public ClassID(string classID)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| classID | String | ASCII kodlamasındaki sınıf kimliği. |

### Ayrıca bakınız

* class [ClassID](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* toplantı [Aspose.PSD](../../../)


