---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD for .NET API リファレンス
description: SmartObjectLayer 財産. スマート オブジェクト レイヤーのコンテンツを取得または設定します 埋め込まれたスマート オブジェクトのコンテンツは埋め込まれた生の画像ファイルですDataおよびそのプロパティ. リンクされたスマート オブジェクトのコンテンツはリンクされた画像ファイルが利用可能な場合そのファイルの生のコンテンツでありそのプロパティは次のとおりですLiFeDataSource . Adobe Photoshop  Graphics Library からの読み込みはサポートしていませんIsLibraryLink true. 通常のリンク ファイルの場合最初はRelativePathソースイメージパスに対して相対的に ファイルを探すSourceImagePath 利用できない場合は確認しますFullPath そうでない場合は画像と同じディレクトリでリンク ファイルを探しますSourceImagePath .
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

スマート オブジェクト レイヤーのコンテンツを取得または設定します。 埋め込まれたスマート オブジェクトのコンテンツは、埋め込まれた生の画像ファイルです。[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/)およびそのプロパティ. リンクされたスマート オブジェクトのコンテンツは、リンクされた画像ファイルが利用可能な場合、そのファイルの生のコンテンツであり、そのプロパティは次のとおりです。[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Adobe� Photoshop� � Graphics Library からの読み込みはサポートしていません。[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) true. 通常のリンク ファイルの場合、最初は[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/)ソースイメージパスに対して相対的に ファイルを探すSourceImagePath, 利用できない場合は確認します[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), そうでない場合は、画像と同じディレクトリでリンク ファイルを探します。SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### プロパティ値

byte[]スマート オブジェクト レイヤーの内容.

### 例外

| 例外 | 調子 |
| --- | --- |
| NotSupportedException | Adobe� Photoshop� �� ライブラリからコンテンツを取得できません。 |

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

* class [SmartObjectLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* 組み立て [Aspose.PSD](../../../)


