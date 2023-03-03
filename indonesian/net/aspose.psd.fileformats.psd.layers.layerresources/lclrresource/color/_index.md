---
title: LclrResource.Color
second_title: Aspose.PSD untuk Referensi .NET API
description: LclrResource Properti. Mendapat atau mengatur warna layer.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

Mendapat atau mengatur warna layer.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Nilai properti

Warna.

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* perakitan [Aspose.PSD](../../../)


