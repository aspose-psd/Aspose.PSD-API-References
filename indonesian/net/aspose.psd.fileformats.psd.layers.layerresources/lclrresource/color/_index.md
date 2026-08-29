---
title: "LclrResource.Color"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti LclrResource. Mendapatkan atau mengatur warna lapisan"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
{{< psd/tize >}}
## LclrResource.Color property

Mendapatkan atau mengatur warna lapisan.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Property Value

Warna.

## Contoh

Contoh berikut menunjukkan cara Anda dapat mengubah Sorotan Warna Sheet di Aspose.PSD (pengaturan warna Sheet)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Dalam file, warna sorotan lapisan berada dalam urutan ini
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

// Warna Sheet Lapisan digunakan untuk menyorot lapisan secara visual.
// Misalnya Anda dapat memperbarui beberapa lapisan di PSD dan kemudian menyorot dengan warna lapisan yang ingin Anda tarik perhatiannya.
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
            // Sumber lcrl selalu hadir dalam daftar sumber file PSD.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Balikkan warna lembar gaya. Pengaturan sorotan warna Lapisan.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Lihat Juga

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


