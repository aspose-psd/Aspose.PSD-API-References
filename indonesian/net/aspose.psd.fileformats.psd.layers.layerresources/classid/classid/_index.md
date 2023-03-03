---
title: ClassID.ClassID
second_title: Aspose.PSD untuk Referensi .NET API
description: ClassID konstruktor. Menginisialisasi instance baru dariClassID kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Menginisialisasi instance baru dari[`ClassID`](../) kelas.

```csharp
public ClassID(byte[] classID)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| classID | Byte[] | ID kelas sebagai rangkaian byte. |

### Lihat juga

* class [ClassID](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* perakitan [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Menginisialisasi instance baru dari[`ClassID`](../) kelas.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| classID | Byte[] | ID kelas sebagai rangkaian byte. |
| isZeroLength | Boolean | jika diatur ke`BENAR` [adalah panjang nol]. Panjang string yang direkam adalah nol tetapi sebenarnya adalah empat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | classID adalah nol. |

### Lihat juga

* class [ClassID](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* perakitan [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Menginisialisasi instance baru dari[`ClassID`](../) kelas.

```csharp
public ClassID(int classID)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| classID | Int32 | ID kelas. |

### Lihat juga

* class [ClassID](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* perakitan [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Menginisialisasi instance baru dari[`ClassID`](../) kelas.

```csharp
public ClassID(uint classID)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| classID | UInt32 | ID kelas. |

### Lihat juga

* class [ClassID](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* perakitan [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Menginisialisasi instance baru dari[`ClassID`](../) kelas.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| classID | String | ID kelas dalam pengkodean ASCII. |
| isZeroLength | Boolean | jika diatur ke`BENAR` [panjang nol]. |

### Contoh

Contoh ini menunjukkan bahwa lapisan, yang diimpor dari gambar, diubah menjadi lapisan objek pintar dan file PSD yang disimpan sudah benar.

```csharp
[C#]

// Menguji apakah lapisan, yang diimpor dari gambar, diubah menjadi lapisan objek pintar dan file PSD yang disimpan sudah benar.

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

### Lihat juga

* class [ClassID](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* perakitan [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Menginisialisasi instance baru dari[`ClassID`](../) kelas.

```csharp
public ClassID(string classID)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| classID | String | ID kelas dalam pengkodean ASCII. |

### Lihat juga

* class [ClassID](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* perakitan [Aspose.PSD](../../../)


