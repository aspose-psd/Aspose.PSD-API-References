---
title: "クラス ImfxResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ImfxResource クラス。Imfx リソース、マルチエフェクトリソースです。"
type: docs
weight: 2850
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/imfxresource/
---
{{< psd/tize >}}
## ImfxResource class

Imfx リソース（マルチエフェクトリソース）

```csharp
public sealed class ImfxResource : BaseFxResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImfxResource](imfxresource/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | ディスクリプタのバージョンを取得します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/imfxresource/typetoolkey/) | タイプツール情報キーです。 |

## 例

以下のコードはマルチエフェクトリソースのサポートを示しています。

```csharp
[C#]

// PSD 画像には 2 つのドロップシャドウ効果が含まれています。
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // それは 2 つのドロップシャドウ効果で PSD 画像をレンダリングします。
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // 3 番目のドロップシャドウ効果を追加します。
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // それは 3 つのドロップシャドウ効果で PSD 画像をレンダリングします。
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // レイヤーに同じタイプの複数のエフェクトが含まれる場合、imfx リソースが使用されます。
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // すべてのエフェクトをクリアします。
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // PSD画像を1つのドロップシャドウ効果でレンダリングします（他は削除されました）
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // レイヤーに同じタイプの複数のエフェクトが含まれていない場合、lfx2リソースが使用されます。
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### 関連項目

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


