---
title: Class LclrResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource kelas. Class LclrResource. Resource ini berisi informasi tentang warna layer pada daftar layer PS. Hanya
type: docs
weight: 2620
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Class LclrResource. Resource ini berisi informasi tentang warna layer pada daftar layer PS. Hanya

```csharp
public class LclrResource : LayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Menginisialisasi instance baru dari`LclrResource` kelas. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Menginisialisasi instance baru dari`LclrResource` kelas. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Menginisialisasi instance baru dari`LclrResource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Mendapat atau mengatur warna layer. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Mendapatkan versi psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Mendapat tanda tangan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Kunci info alat ketik. |

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat mengubah Sorotan Warna Lembar Di Aspose.PSD (Pengaturan warna lembar)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Dalam warna file penyorotan lapisan ada dalam urutan ini
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// Layer Sheet Color digunakan untuk menyorot layer secara visual. 
// Misalnya Anda dapat memperbarui beberapa lapisan di PSD dan kemudian menyorot dengan warna lapisan yang ingin Anda perhatikan.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Warna harus dibalik
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // Sumber daya lcrl selalu ditampilkan dalam daftar sumber daya file psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Kebalikan dari warna style sheet. Pengaturan sorotan warna Lapisan.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Lihat juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


