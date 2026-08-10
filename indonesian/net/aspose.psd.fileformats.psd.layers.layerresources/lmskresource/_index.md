---
title: "Kelas LmskResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource. Sumber daya LMsk"
type: docs
weight: 3020
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

Sumber daya LMsk.

```csharp
public class LmskResource : LayerResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LmskResource](lmskresource/)() | Menginisialisasi sebuah instance baru dari kelas `LmskResource`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Mendapatkan komponen warna 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Mendapatkan komponen warna 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Mendapatkan komponen warna 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Mendapatkan komponen warna 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Mendapatkan ruang warna. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Mendapatkan bendera. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Mendapatkan opasitas. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | Kunci info alat tipe. |

## Catatan

Sumber daya ini berisi ID ruang warna, yang mengacu pada tipe ruang warna tertentu, dan 4 komponen warna. Bergantung pada ID, komponen warna memiliki makna yang berbeda. Jika tipe ruang warna tidak memerlukan empat nilai, komponen tambahan tidak terdefinisi dan selalu ditulis sebagai nol. Komponen warna berdasarkan tipe ruang warna: RGB - tiga komponen pertama adalah merah, hijau, dan biru. HSB - tiga komponen pertama adalah hue, saturasi, dan kecerahan. CMYK - empat komponen adalah cyan, magenta, kuning, dan hitam. Lab - tiga komponen pertama adalah kecerahan, a krominansi, dan b krominansi. Grayscale - komponen pertama adalah nilai abu-abu, dari 0...10000.

## Contoh

Kode berikut menunjukkan cara mengubah Opsi Tampilan Masker Lapisan pada gambar 16-bit melalui mengubah properti LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Muat gambar 16-bit.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Temukan LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Periksa properti LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Ubah properti LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Simpan gambar.
    image.Save(outputPsd);
}
```

### Lihat Juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


