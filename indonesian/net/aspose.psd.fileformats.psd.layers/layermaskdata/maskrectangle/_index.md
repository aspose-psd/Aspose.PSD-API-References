---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti LayerMaskData. Mendapatkan atau mengatur Rectangle masker dari masker lapisan dalam file PSD. Ia mengambil properti left, right, top, dan bottom dan membuat Rectangle"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Mendapatkan atau mengatur mask [`Rectangle`](../../../aspose.psd/rectangle/) dari masker lapisan dalam file PSD. Ia mengambil properti left, right, top, dan bottom dan membuat [`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

Rectangle masker.

## Contoh

Contoh ini menunjukkan cara mendapatkan, memperbarui, menghapus, dan menambahkan masker lapisan raster dalam file Adobe® Photoshop® secara programatis.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Mendapatkan nilai int yang dikonversi ke urutan byte big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Mendapatkan nilai yang dikonversi dari big endian ke Int32.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// Mendapatkan masker raster dari lapisan gambar PSD dan menyimpannya ke file
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// Menambahkan masker raster dari file ke lapisan dan menyimpannya sebagai gambar format PSD
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // Hanya menambahkan LayerMaskData tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui;
    // layer.LayerMaskData = mask; // Ini tidak menambahkan saluran masker

    // Tambah (atau perbarui) masker
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Contoh ini menunjukkan cara mendapatkan, memperbarui, menghapus, dan menambahkan masker lapisan raster dalam file Adobe® Photoshop® secara programatis.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Dapatkan masker raster dari lapisan dan simpan ke file
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Ubah masker lapisan (invert) dan simpan gambar
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Hanya mengubah LayerMaskData sudah cukup untuk memengaruhi rendering
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Namun hanya mengubah LayerMaskData tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Hapus masker raster dari lapisan dan simpan gambar
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Tambahkan masker raster dari file ke lapisan dan simpan gambar
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Lihat Juga

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


