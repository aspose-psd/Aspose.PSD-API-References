---
title: TextLayer.Resize
second_title: Aspose.PSD untuk Referensi .NET API
description: TextLayer metode. Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan.
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| resizeType | ResizeType | Jenis transformasi pengubahan ukuran[`ResizeType`](../../../aspose.psd/resizetype/) |

### Contoh

Kode berikut menunjukkan fungsi TextLayer.Resize dengan parameter untuk memilih mekanisme pengubahan ukuran.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Ini menetapkan ukuran baru dari layer teks
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Ini mengatur mekanisme bagaimana fungsi resize akan mengubah ukuran layer (nilai default)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Mekanisme baru pengubahan ukuran untuk lapisan teks menggunakan di sini
    // Tidak hanya layer tetapi juga matriks transformasi dari layer teks akan berubah
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Alasan delta adalah font default yang berbeda
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Semua baik - baik saja
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Lihat juga

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* perakitan [Aspose.PSD](../../../)


