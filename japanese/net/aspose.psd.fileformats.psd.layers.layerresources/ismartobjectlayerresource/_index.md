---
title: "インターフェイス ISmartObjectLayerResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ISmartObjectLayerResource インターフェイス。PSD ファイル内のスマートオブジェクトレイヤーリソースに関する情報を含む ISmartObjectLayerResource インターフェイスを定義します。また、Adobe Photoshop 画像内の Sold および Sole リソースの両方を指定するために使用されるマークアップインターフェイスでもあります。"
type: docs
weight: 2830
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/
---
{{< psd/tize >}}
## ISmartObjectLayerResource interface

ISmartObjectLayerResource インターフェイスを定義し、PSD ファイル内のスマートオブジェクトレイヤーリソースに関する情報を含みます。Adobe® Photoshop® 画像で Sold と Sole の両方のリソースを指定するために使用されるマークアップインターフェイスでもあります。

```csharp
public interface ISmartObjectLayerResource : IPlacedLayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/) { get; set; } | PSD 画像内のこのスマートオブジェクトレイヤーデータの一意識別子を取得または設定します。 |

## 例

以下のコードは埋め込みスマートオブジェクトのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// この例は、PSD ファイル内のスマートオブジェクトレイヤーを変更し、スマートオブジェクトの元の埋め込みコンテンツをエクスポート/更新する方法を示します。
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

        // PSD のスマートオブジェクトレイヤーから埋め込みスマートオブジェクト画像をエクスポートしましょう
        smartObjectLayer.ExportContents(exportPath);

        // 元の画像が正しく保存されているか確認しましょう
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 元のスマートオブジェクト画像を反転させましょう
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // PSD レイヤー内の埋め込みスマートオブジェクト画像を置き換えましょう
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 更新された画像が正しく保存されているか確認しましょう
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 関連項目

* interface [IPlacedLayerResource](../iplacedlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


