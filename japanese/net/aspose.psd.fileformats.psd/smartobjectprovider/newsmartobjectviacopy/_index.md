---
title: "SmartObjectProvider.NewSmartObjectViaCopy"
second_title: "Aspose.PSD for .NET API Reference"
description: "SmartObjectProvider メソッド。ソースレイヤーをコピーして新しいスマートオブジェクトレイヤーを作成します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectProvider.NewSmartObjectViaCopy method

元のレイヤーをコピーして新しいスマートオブジェクトレイヤーを作成します。

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | ソースレイヤーです。 |

### 戻り値

クローンされた [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) インスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 埋め込みスマートオブジェクトのみ置き換えることができます。 |

## 例

これらの例は、PSD 画像内でスマートオブジェクトレイヤーをコピーする方法を示しています。

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// これらの例は、PSD 画像内でスマートオブジェクトレイヤーをコピーする方法を示しています。
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // 埋め込みスマートオブジェクト画像を反転させましょう（内部 PSD 画像の場合は最初のレイヤーのみを反転します）
            InvertImage(innerImage);

            // PSD レイヤー内の埋め込みスマートオブジェクト画像を置き換えましょう
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 複製されたレイヤーは、元のスマートオブジェクトと埋め込まれた画像を共有します。
        // そして、明示的に更新しなければ、レンダリングキャッシュは変更されません。
        // NewSmartObjectViaCopy によって作成された新しいレイヤーを確実にするため、すべてのスマートオブジェクトを更新します。
        // 他のものと埋め込まれた画像を共有しません。
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// PSD 画像を含むラスタ画像を反転させます。
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

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### 関連項目

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


