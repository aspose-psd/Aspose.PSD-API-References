---
title: "ClassID.ClassID"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor ClassID. Menginisialisasi instance baru dari kelas ClassID"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

Menginisialisasi instance baru dari kelas [`ClassID`](../).

```csharp
public ClassID(byte[] classID)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classID | Byte[] | ID kelas sebagai rangkaian byte. |

### Lihat Juga

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Menginisialisasi instance baru dari kelas [`ClassID`](../).

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classID | Byte[] | ID kelas sebagai rangkaian byte. |
| isZeroLength | Boolean | Jika disetel ke `true` [is zero length]. Panjang string yang tercatat adalah nol tetapi sebenarnya empat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | classID bernilai null. |

### Lihat Juga

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Menginisialisasi instance baru dari kelas [`ClassID`](../).

```csharp
public ClassID(int classID)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classID | Int32 | ID kelas. |

### Lihat Juga

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Menginisialisasi instance baru dari kelas [`ClassID`](../).

```csharp
public ClassID(uint classID)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classID | UInt32 | ID kelas. |

### Lihat Juga

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Menginisialisasi instance baru dari kelas [`ClassID`](../).

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classID | String | ID kelas dalam enkoding ASCII. |
| isZeroLength | Boolean | Jika disetel ke `true` [is zero length]. |

## Contoh

Contoh ini menunjukkan bahwa lapisan, yang diimpor dari gambar, diubah menjadi lapisan objek pintar dan file PSD yang disimpan sudah benar.

```csharp
[C#]

// Menguji bahwa lapisan, yang diimpor dari gambar, diubah menjadi lapisan objek pintar dan file PSD yang disimpan sudah benar.

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

### Lihat Juga

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Menginisialisasi instance baru dari kelas [`ClassID`](../).

```csharp
public ClassID(string classID)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classID | String | ID kelas dalam enkoding ASCII. |

### Lihat Juga

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


