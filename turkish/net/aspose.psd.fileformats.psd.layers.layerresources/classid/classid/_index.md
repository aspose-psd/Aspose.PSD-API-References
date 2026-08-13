---
title: "ClassID.ClassID"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ClassID yapıcı. ClassID sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

[`ClassID`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public ClassID(byte[] classID)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| classID | Byte[] | Sınıf kimliği bayt serisi olarak. |

### Ayrıca Bakınız

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

[`ClassID`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| classID | Byte[] | Sınıf kimliği bayt serisi olarak. |
| isZeroLength | Boolean | eğer `true` olarak ayarlanırsa [sıfır uzunluk]. Kaydedilen dize uzunluğu sıfırdır ancak gerçek uzunluk dörttür. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | classID null. |

### Ayrıca Bakınız

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

[`ClassID`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public ClassID(int classID)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| classID | Int32 | Sınıf kimliği. |

### Ayrıca Bakınız

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

[`ClassID`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public ClassID(uint classID)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| classID | UInt32 | Sınıf kimliği. |

### Ayrıca Bakınız

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

[`ClassID`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| classID | String | ASCII kodlamasında sınıf kimliği. |
| isZeroLength | Boolean | eğer `true` olarak ayarlanırsa [sıfır uzunluk]. |

## Örnekler

Bu örnek, bir görüntüden içe aktarılan katmanın akıllı nesne katmanına dönüştürüldüğünü ve kaydedilen PSD dosyasının doğru olduğunu gösterir.

```csharp
[C#]

// Katmanın bir görüntüden içe aktarıldıktan sonra akıllı nesne katmanına dönüştürüldüğünü ve kaydedilen PSD dosyasının doğru olduğunu test eder.

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

### Ayrıca Bakınız

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

[`ClassID`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public ClassID(string classID)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| classID | String | ASCII kodlamasında sınıf kimliği. |

### Ayrıca Bakınız

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


