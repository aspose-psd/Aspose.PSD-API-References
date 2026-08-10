---
title: "LmskResource.ColorComponent3"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "LmskResource property. Mendapatkan komponen warna 3"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/
---
{{< psd/tize >}}
## LmskResource.ColorComponent3 property

Mendapatkan komponen warna 3.

```csharp
public ushort ColorComponent3 { get; set; }
```

### Property Value

Komponen warna 3.

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

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


