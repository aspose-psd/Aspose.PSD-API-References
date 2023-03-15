---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD for .NET API リファレンス
description: LayerMaskData 財産. マスクを取得または設定しますRectanglePSDファイルのレイヤーマスクの. 左右上下のプロパティを取り作成しますRectangle
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

マスクを取得または設定します[`Rectangle`](../../../aspose.psd/rectangle/)PSDファイルのレイヤーマスクの. 左、右、上、下のプロパティを取り、作成します[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### プロパティ値

マスクの四角形。

### 例

この例では、Adobe® Photoshop® ファイルのラスター レイヤー マスクをプログラムで取得、更新、削除、および追加する方法を示します。

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

// ビッグエンディアンのバイト順に変換された int 値を取得します。
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// ビッグエンディアンから Int32 に変換された値を取得します。
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

// PSD 画像のレイヤーからラスター マスクを取得し、ファイルに保存します
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

// ラスター マスクをファイルからレイヤーに追加し、PSD 形式の画像として保存します
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

    // チャンネルが更新されないため、LayerMasData を追加するだけでは正しく保存できません。
    // layer.LayerMaskData = mask; // これはマスク チャネルを追加しません

    // マスクを追加 (または更新)
    layer.AddLayerMask(maskData); // しかし、これはマスクとチャンネルの両方を追加/更新します!
}

// この例では、Adobe® Photoshop® ファイルのラスター レイヤー マスクをプログラムで取得、更新、削除、および追加する方法を示します。
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // レイヤーからラスター マスクを取得し、ファイルに保存します
    SaveRasterMask("FourWithMasks2.msk", layer);

    // レイヤーマスクを変更（反転）して画像を保存
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // LayerMaskData を変更するだけでレンダリングに影響します
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // ただし、チャネルが更新されないため、LayerMasData を変更するだけでは正しく保存するには不十分です。
    layer.LayerMaskData = mask; // これも動かない
    layer.AddLayerMask(mask); // しかし、これはマスクとチャンネルの両方を更新します!
    image.Save("FourWithMasksUpdated2.psd");

    // レイヤーからラスター マスクを削除し、画像を保存します
    layer.LayerMaskData = null; // LayerMaskData を削除するだけでレンダリングに影響しますが、PSD 形式に保存するには十分ではありません
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // しかし、これはマスクとマスク チャネルの両方を削除します!
    image.Save("FourWithMasksRemoved2.psd");

    // ファイルからレイヤーにラスター マスクを追加し、画像を保存します
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* 組み立て [Aspose.PSD](../../../)


