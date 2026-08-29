---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti TextLayer. Mengambil atau mengatur matriks transformasi"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Mendapatkan atau mengatur matriks transformasi

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

Matriks transformasi

## Contoh

Kode berikut menunjukkan cara mendapatkan ukuran font untuk setiap bagian teks dalam lapisan teks.

```csharp
[C#]

// Ukuran Font yang diekstrak salah 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // API lama (Menggunakan font paragraf pertama)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Memeriksa ukuran font dasar
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Memeriksa ukuran font sebenarnya
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // API Baru (Satu lapisan teks dapat berisi jumlah ukuran font apa pun)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Memeriksa ukuran font bagian dasar
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Memeriksa ukuran font bagian nyata
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Lihat Juga

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


