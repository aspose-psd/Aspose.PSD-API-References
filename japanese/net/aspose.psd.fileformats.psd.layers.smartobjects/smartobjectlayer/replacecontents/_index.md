---
title: "SmartObjectLayer.ReplaceContents"
second_title: "Aspose.PSD for .NET API Reference"
description: "SmartObjectLayer メソッド。スマート オブジェクト レイヤーに埋め込まれたスマート オブジェクト コンテンツを置き換えます。"
type: docs
weight: 160
url: /ja/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/
---
{{< psd/tize >}}
## ReplaceContents(Image) {#replacecontents}

スマートオブジェクトレイヤーに埋め込まれたスマートオブジェクトのコンテンツを置き換えます。

```csharp
public void ReplaceContents(Image image)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 画像です。 |

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

* class [Image](../../../aspose.psd/image/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(Image, ResolutionSetting) {#replacecontents_1}

スマートオブジェクトレイヤーに埋め込まれたスマートオブジェクトのコンテンツを置き換えます。

```csharp
public void ReplaceContents(Image image, ResolutionSetting resolution)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 画像です。 |
| 解像度 | ResolutionSetting | 解像度設定です。null の場合は画像の解像度が使用されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 埋め込みスマート オブジェクトのみ置き換えることができます。 |

## 例

この例は、新しいコンテンツ ファイルの解像度が異なる場合でも ReplaceContents メソッドが正しく機能することを示しています。

```csharp
[C#]

// この例は、新しいコンテンツ ファイルの解像度が異なる場合でも ReplaceContents メソッドが正しく機能することを示しています。
string fileName = "CommonPsb.psd";
string filePath = baseFolder + fileName; // original PSD image
string newContentPath = baseFolder + "image.jpg"; // the new content file for the smart object
string outputFilePath = outputFolder + "ChangedPsd";
string pngOutputPath = outputFilePath + ".png"; // the output PNG file
string psdOutputPath = outputFilePath + ".psd"; // the output PSD file
using (PsdImage psd = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < psd.Layers.Length; i++)
    {
        var layer = psd.Layers[i];
        SmartObjectLayer smartObjectLayer = layer as SmartObjectLayer;
        if (smartObjectLayer != null)
        {
            smartObjectLayer.ReplaceContents(newContentPath);

            psd.Save(psdOutputPath);
            psd.Save(pngOutputPath, new PngOptions() { ColorType = Aspose.PSD.FileFormats.Png.PngColorType.TruecolorWithAlpha });
        }
    }
}
```

### 関連項目

* class [Image](../../../aspose.psd/image/)
* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting) {#replacecontents_3}

コンテンツをファイルで置き換えます。その後 UpdateModifiedContent メソッドを呼び出す必要はありません。

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| linkedPath | 文字列 | リンクされたパスです。 |
| 解像度 | ResolutionSetting | 解像度設定です。null の場合は画像の解像度が使用されます。 |

### 関連項目

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting, bool) {#replacecontents_4}

コンテンツをファイルで置き換えます。その後 UpdateModifiedContent メソッドを呼び出す必要はありません。

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution, bool isReplaceOnlyThis)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| linkedPath | 文字列 | リンクされたパスです。 |
| 解像度 | ResolutionSetting | 解像度設定です。null の場合は画像の解像度が使用されます。 |
| isReplaceOnlyThis | Boolean | このフラグは、このスマートレイヤーからコンテンツを置換するか、またはこのコンテンツを持つすべてのスマートレイヤーに置換することを示します。 |

## 例

この例は、新しいコンテンツ ファイルの解像度が異なる場合でも ReplaceContents メソッドが正しく機能することを示しています。

```csharp
[C#]

// この例は、新しいコンテンツ ファイルの解像度が異なる場合でも ReplaceContents メソッドが正しく機能することを示しています。
string fileName = "CommonPsb.psd";
string filePath = baseFolder + fileName; // original PSD image
string newContentPath = baseFolder + "image.jpg"; // the new content file for the smart object
string outputFilePath = outputFolder + "ChangedPsd";
string pngOutputPath = outputFilePath + ".png"; // the output PNG file
string psdOutputPath = outputFilePath + ".psd"; // the output PSD file
using (PsdImage psd = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < psd.Layers.Length; i++)
    {
        var layer = psd.Layers[i];
        SmartObjectLayer smartObjectLayer = layer as SmartObjectLayer;
        if (smartObjectLayer != null)
        {
            smartObjectLayer.ReplaceContents(newContentPath);

            psd.Save(psdOutputPath);
            psd.Save(pngOutputPath, new PngOptions() { ColorType = Aspose.PSD.FileFormats.Png.PngColorType.TruecolorWithAlpha });
        }
    }
}
```

以下のコードは、同じソース参照を持つ多数のスマートオブジェクトでコンテンツを置換するサポートを示しています。

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// これにより、同じリンクを持つすべてのスマートレイヤーの同じコンテキストが置換されます。
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // これにより、同じコンテンツを使用するすべての SmartLayers のコンテンツが置換されます。
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//これにより、選択されたレイヤーのみのコンテキストが置換され、他のすべてのレイヤーは同じコンテキストのまま残ります。
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // それは選択された SmartLayer のコンテンツのみを置換します。
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

### 関連項目

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string) {#replacecontents_2}

コンテンツをファイルで置き換えます。その後 UpdateModifiedContent メソッドを呼び出す必要はありません。

```csharp
public void ReplaceContents(string linkedPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| linkedPath | 文字列 | リンクされたパスです。 |

### 関連項目

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, bool) {#replacecontents_5}

コンテンツをファイルで置き換えます。その後 UpdateModifiedContent メソッドを呼び出す必要はありません。

```csharp
public void ReplaceContents(string linkedPath, bool isReplaceOnlyThis)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| linkedPath | 文字列 | リンクされたパスです。 |
| isReplaceOnlyThis | Boolean | このフラグは、このスマートレイヤーからコンテンツを置換するか、またはこのコンテンツを持つすべてのスマートレイヤーに置換することを示します。 |

## 例

以下のコードは、同じソース参照を持つ多数のスマートオブジェクトでコンテンツを置換するサポートを示しています。

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// これにより、同じリンクを持つすべてのスマートレイヤーの同じコンテキストが置換されます。
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // これにより、同じコンテンツを使用するすべての SmartLayers のコンテンツが置換されます。
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//これにより、選択されたレイヤーのみのコンテキストが置換され、他のすべてのレイヤーは同じコンテキストのまま残ります。
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // それは選択された SmartLayer のコンテンツのみを置換します。
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

以下のコードは、リンクされたスマートオブジェクトの更新サポートを示しています。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// この例では、これらのメソッドを使用して外部または埋め込みのスマートオブジェクトレイヤーを更新する方法を示します。
// RelinkToFile, UpdateModifiedContent, ExportContents
ExampleOfUpdatingSmartObjectLayer("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfUpdatingSmartObjectLayer("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfUpdatingSmartObjectLayer(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // この例では、PSD ファイル内のスマートオブジェクトレイヤーを変更し、そのコンテンツをエクスポート/更新する方法を示します。
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "updating_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_modified.png";
    string png2OutputPath = dataDir + fileName + "_updated_modified.png";
    string psd2OutputPath = dataDir + fileName + "_updated_modified.psd";
    string exportPath = dataDir + fileName + "_exported." + GetFormatExt(format);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        var contentType = smartObjectLayer.ContentType;
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        if (contentType == SmartObjectType.AvailableLinked)
        {
            Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
            // PSD のスマートオブジェクトレイヤーから外部スマートオブジェクト画像を新しい場所へエクスポートしましょう
            // それを変更する予定だからです。
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // スマートオブジェクトのコンテンツを反転させましょう：内部（キャッシュされていない）画像
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // 変更されたコンテンツがまだレンダリングに影響しないか確認しましょう。
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // 更新されたコンテンツがレンダリングに影響し、psd 画像が正しく保存されているか確認しましょう
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// この例では、ConvertToLinked メソッドを使用して埋め込みスマートオブジェクトを外部リンクコンテンツに変換する方法を示します。
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("new_panama-papers-4.psd", 0x10caa, 0, 0, 0x280, 0x169, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r3-embedded.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-tiff.psd", 0xca94, 0, 0, 0xb, 0x10, FileFormat.Tiff);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-bmp.psd", 0x278, 0, 0, 0xb, 0x10, FileFormat.Bmp);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-gif.psd", 0x3ec, 0, 0, 0xb, 0x10, FileFormat.Gif);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg.psd", 0x327, 0, 0, 0xb, 0x10, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg2000.psd", 0x519f, 0, 0, 0xb, 0x10, FileFormat.Jpeg2000);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-psd.psd", 0xc074, 0, 0, 0xb, 0x10, FileFormat.Psd);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfEmbeddedSmartObjectLayerToLinkedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // これは、PSD ファイル内の埋め込みスマートオブジェクトレイヤーを外部のものに変換する方法を示しています。
    var formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_linked_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_external.png";
    string psdOutputPath = dataDir + fileName + "_to_external.psd";
    string externalPath = dataDir + fileName + "_external." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        Directory.CreateDirectory(Path.GetDirectoryName(externalPath));
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer.ConvertToLinked(externalPath);

        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        // 変換された画像が正しく保存されているか確認しましょう
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);
    }
}

// この例では、EmbedLinked メソッドを使用して外部スマートオブジェクトレイヤーを1つ、またはすべてのリンクレイヤーを PSD ファイルに埋め込む方法を示します。
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
void ExampleOfLinkedSmartObjectLayerToEmbeddedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_embedded_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_embedded.png";
    string psdOutputPath = dataDir + fileName + "_to_embedded.psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer0 = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer0.EmbedLinked();
        AssertAreEqual(contentsLength, smartObjectLayer0.Contents.Length);
        AssertAreEqual(left, smartObjectLayer0.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer0.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer0.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer0.ContentsBounds.Bottom);
        if (image.Layers.Length >= 2)
        {
            var smartObjectLayer1 = (SmartObjectLayer)image.Layers[1];
            AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer0.ContentType);
            AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer1.ContentType);

            image.SmartObjectProvider.EmbedAllLinked();
            foreach (Layer layer in image.Layers)
            {
                var smartLayer = layer as SmartObjectLayer;
                if (smartLayer != null)
                {
                    AssertAreEqual(SmartObjectType.Embedded, smartLayer.ContentType);
                }
            }
        }

        Directory.CreateDirectory(Path.GetDirectoryName(psdOutputPath));
        // 変換された画像が正しく保存されているか確認しましょう
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer.ContentType);
    }
}

// この例では、Adobe® Photoshop® の外部スマートオブジェクトレイヤーを変更し、そのコンテンツをエクスポート/更新する方法を示します。
// ExportContents と ReplaceContents メソッドを使用して。
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked2.psd", 0x4aea, 0, 0, 10, 10, FileFormat.Psd);
void ExampleOfExternalSmartObjectLayerSupport(string filePath, int contentsLength, int left, int top, int right, int bottom, FileFormat format)
{
    string formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "external_support_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + ".png";
    string psdOutputPath = dataDir + fileName + ".psd";
    string linkOutputPath = dataDir + fileName + "_inverted." + formatExt;
    string png2OutputPath = dataDir + fileName + "_updated.png";
    string psd2OutputPath = dataDir + fileName + "_updated.psd";
    string exportPath = dataDir + fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[image.Layers.Length - 1];
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
        // PSD のスマートオブジェクトレイヤーからリンクされたスマートオブジェクト画像をエクスポートしましょう
        smartObjectLayer.ExportContents(exportPath);

        // 元の画像が正しく保存されているか確認しましょう
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // リンクされたスマートオブジェクト画像を反転させましょう
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // PSD レイヤー内のリンクされたスマートオブジェクト画像を置き換えましょう
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // 更新された画像が正しく保存されているか確認しましょう
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// 画像を反転させます。
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// ラスタ画像を反転します。
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

// フォーマット拡張子を取得します。
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### 関連項目

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


