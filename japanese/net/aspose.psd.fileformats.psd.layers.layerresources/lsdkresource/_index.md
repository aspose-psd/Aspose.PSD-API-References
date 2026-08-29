---
title: "クラス LsdkResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LsdkResource クラス。lsdk レイヤーリソースのネストされたレイヤーセクションリソース"
type: docs
weight: 3110
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lsdkresource/
---
{{< psd/tize >}}
## LsdkResource class

lsdk レイヤーリソース（ネストされたレイヤーセクションリソース）。

```csharp
public class LsdkResource : BaseLayerSectionResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LsdkResource](lsdkresource/)() | `LsdkResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendModeKey](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/) { get; set; } | ブレンドモードキーを取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| [SectionType](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/sectiontype/) { get; set; } | セクションタイプを取得または設定します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [Subtype](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/subtype/) { get; set; } | サブタイプを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lsdkresource/typetoolkey/) | タイプツール情報キーです。 |

## 例

以下のコードは LsdkResource のサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string srcFile = "123 1.psd";
string outFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
    psdImage.Save(outFile);
}

// 保存後に確認してください
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
}
```

### 関連項目

* class [BaseLayerSectionResource](../baselayersectionresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


