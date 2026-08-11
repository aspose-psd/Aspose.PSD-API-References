---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerMaskData プロパティ。PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。left、right、top、bottom プロパティを受け取り、Rectangle を作成します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

レイヤーマスクのマスク [`Rectangle`](../../../aspose.psd/rectangle/) を取得または設定します。left、right、top、bottom プロパティを受け取り、[`Rectangle`](../../../aspose.psd/rectangle/) を作成します。

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

マスク矩形です。

## 例

この例では、Adobe® Photoshop® ファイルでラスターレイヤーマスクを取得、更新、削除、追加する方法をプログラムで示します。

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

// int 値をビッグエンディアンのバイト順に変換して取得します。
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

// PSD 画像のレイヤーからラスターマスクを取得し、ファイルに保存します
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

// ファイルからラスターマスクをレイヤーに追加し、PSD 形式の画像として保存します
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

    // LayerMaskData を追加するだけでは、チャンネルが更新されないため正しく保存できません；
    // layer.LayerMaskData = mask; // これはマスクチャンネルを追加しません

    // マスクを追加（または更新）
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// この例では、Adobe® Photoshop® ファイルでラスターレイヤーマスクを取得、更新、削除、追加する方法をプログラムで示します。
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // レイヤーからラスターマスクを取得し、ファイルに保存します
    SaveRasterMask("FourWithMasks2.msk", layer);

    // レイヤーマスクを変更（反転）し、画像を保存します
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // LayerMaskData を変更するだけでレンダリングに影響を与えるのに十分です。
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // しかし、LayerMaskData を変更するだけでは、チャンネルが更新されないため、正しく保存するには不十分です；
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // レイヤーからラスターマスクを削除し、画像を保存する
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // ファイルからラスターマスクをレイヤーに追加し、画像を保存する
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


