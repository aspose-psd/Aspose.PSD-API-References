---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerMaskData Properti. Mendapat atau menyetel topengRectangledari layer mask di file PSD. Dibutuhkan properti kiri kanan atas dan bawah dan membuatRectangle
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Mendapat atau menyetel topeng[`Rectangle`](../../../aspose.psd/rectangle/)dari layer mask di file PSD. Dibutuhkan properti kiri, kanan, atas dan bawah dan membuat[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Nilai properti

Kotak topeng.

### Contoh

Contoh ini menunjukkan cara mendapatkan, memperbarui, menghapus, dan menambahkan layer mask raster di file Adobe® Photoshop® secara terprogram.

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

// Mendapatkan topeng raster dari lapisan gambar PSD dan menyimpannya ke file
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

// Menambahkan topeng raster dari file ke lapisan dan menyimpannya dalam format gambar PSD
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

    // Menambahkan LayerMaskData saja tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui;
    // lapisan.LayerMaskData = topeng; // Ini tidak menambahkan saluran topeng

    // Tambahkan (atau perbarui) topeng
    layer.AddLayerMask(maskData); // Tapi ini menambah / memperbarui topeng dan saluran!
}

// Contoh ini menunjukkan cara mendapatkan, memperbarui, menghapus, dan menambahkan layer mask raster di file Adobe® Photoshop® secara terprogram.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Dapatkan topeng raster dari lapisan dan simpan ke file
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Ubah layer mask (balikkan) dan simpan gambar
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Hanya mengubah LayerMaskData sudah cukup untuk mempengaruhi rendering
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Tapi mengubah LayerMaskData saja tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui;
    layer.LayerMaskData = mask; // Ini juga tidak berhasil
    layer.AddLayerMask(mask); // Tapi ini memperbarui topeng dan saluran!
    image.Save("FourWithMasksUpdated2.psd");

    // Hapus topeng raster dari lapisan dan simpan gambar
    layer.LayerMaskData = null; // Menghapus LayerMaskData saja sudah cukup untuk mempengaruhi rendering tetapi tidak untuk menyimpan ke format PSD
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Tapi ini menghilangkan topeng dan saluran topeng!
    image.Save("FourWithMasksRemoved2.psd");

    // Tambahkan topeng raster dari file ke lapisan dan simpan gambar
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Lihat juga

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* perakitan [Aspose.PSD](../../../)


