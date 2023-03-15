---
title: Interface ISmartObjectLayerResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ISmartObjectLayerResource インターフェース. PSD ファイル内のスマート オブジェクト レイヤー リソースに関する情報を含む ISmartObjectLayerResource インターフェイスを定義します はAdobe Photoshop 画像内の Sold リソースと Sole リソースの両方を指定するために使用されるマークアップ インターフェイスでもあります
type: docs
weight: 2540
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/
---
## ISmartObjectLayerResource interface

PSD ファイル内のスマート オブジェクト レイヤー リソースに関する情報を含む ISmartObjectLayerResource インターフェイスを定義します。 は、Adobe® Photoshop® 画像内の Sold リソースと Sole リソースの両方を指定するために使用されるマークアップ インターフェイスでもあります。

```csharp
public interface ISmartObjectLayerResource : IPlacedLayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/) { get; set; } | PSD 画像内のこのスマート オブジェクト レイヤー データの一意の識別子を取得または設定します。 |

### 例

次のコードは、埋め込みスマート オブジェクトのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// この例では、PSD ファイルのスマート オブジェクト レイヤーを変更し、スマート オブジェクトの元の埋め込みコンテンツをエクスポート/更新する方法を示します。
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // 埋め込まれたスマート オブジェクト イメージを PSD スマート オブジェクト レイヤーからエクスポートしましょう
        smartObjectLayer.ExportContents(exportPath);

        // 元の画像が正しく保存されているか確認してみましょう
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 元のスマートオブジェクトの画像を反転させましょう
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // PSD レイヤーに埋め込まれたスマート オブジェクト画像を置き換えましょう
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 更新された画像が正しく保存されているか確認してみましょう
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 関連項目

* interface [IPlacedLayerResource](../iplacedlayerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


