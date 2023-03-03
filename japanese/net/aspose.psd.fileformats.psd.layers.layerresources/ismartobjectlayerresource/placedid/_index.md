---
title: ISmartObjectLayerResource.PlacedId
second_title: Aspose.PSD for .NET API リファレンス
description: ISmartObjectLayerResource 財産. PSD 画像内のこのスマート オブジェクト レイヤー データの一意の識別子を取得または設定します
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/
---
## ISmartObjectLayerResource.PlacedId property

PSD 画像内のこのスマート オブジェクト レイヤー データの一意の識別子を取得または設定します。

```csharp
public Guid PlacedId { get; set; }
```

### プロパティ値

このスマート オブジェクト レイヤー リソースの一意の識別子。

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

* interface [ISmartObjectLayerResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ismartobjectlayerresource/)
* 組み立て [Aspose.PSD](../../../)


