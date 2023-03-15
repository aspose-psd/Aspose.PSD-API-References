---
title: SmartObjectProvider.NewSmartObjectViaCopy
second_title: Aspose.PSD for .NET API リファレンス
description: SmartObjectProvider 方法. ソース レイヤーをコピーして新しいスマート オブジェクト レイヤーを作成します
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
## SmartObjectProvider.NewSmartObjectViaCopy method

ソース レイヤーをコピーして、新しいスマート オブジェクト レイヤーを作成します。

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | ソース層。 |

### 戻り値

クローン[`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)インスタンス.

### 例外

| 例外 | 調子 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 埋め込まれたスマート オブジェクトのみを置き換えることができます。 |

### 例

これらの例は、PSD 画像でスマート オブジェクト レイヤーをコピーする方法を示しています。

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// これらの例は、PSD 画像でスマート オブジェクト レイヤーをコピーする方法を示しています。
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // コピーするレイヤー番号
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
            // 埋め込まれたスマートオブジェクト画像を反転させましょう (内側の PSD 画像の場合、最初のレイヤーのみを反転させます)
            InvertImage(innerImage);

            // PSD レイヤーに埋め込まれたスマート オブジェクト画像を置き換えましょう
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 複製されたレイヤーは、埋め込まれた画像を元のスマート オブジェクトと共有します
        // 明示的に更新する必要があります。そうしないと、レンダリング キャッシュは変更されません。
        // すべてのスマート オブジェクトを更新して、NewSmartObjectViaCopy によって作成された新しいレイヤーが
        // 埋め込まれた画像を他のユーザーと共有しません。
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// PSD 画像を含むラスター画像を反転します。
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

// ラスター画像を反転します。
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
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../smartobjectprovider/)
* 組み立て [Aspose.PSD](../../../)


