---
title: "TextLayer.Resize"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode TextLayer. Mengubah ukuran gambar. Nilai default LeftTopToLeftTop digunakan"
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Mengubah ukuran gambar. Default LeftTopToLeftTop digunakan.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| resizeType | ResizeType | Tipe transformasi ubah ukuran [`ResizeType`](../../../aspose.psd/resizetype/) |

## Contoh

Kode berikut menunjukkan fungsi TextLayer.Resize dengan parameter untuk memilih mekanisme pengubahan ukuran.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Ini mengatur ukuran baru lapisan teks
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Ini mengatur mekanisme bagaimana fungsi ubah ukuran akan mengubah ukuran lapisan (nilai default)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Mekanisme baru pengubahan ukuran untuk lapisan teks yang digunakan di sini
    // Tidak hanya lapisan tetapi juga matriks transformasi dari lapisan teks akan diubah
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
        // Semua baik
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Lihat Juga

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


