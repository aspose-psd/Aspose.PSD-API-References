---
title: "クラス LmskResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource クラス。LMsk リソース"
type: docs
weight: 3020
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

LMsk リソース。

```csharp
public class LmskResource : LayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LmskResource](lmskresource/)() | `LmskResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | カラーコンポーネント 1 を取得します。 |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | カラーコンポーネント 2 を取得します。 |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | カラーコンポーネント 3 を取得します。 |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | カラーコンポーネント 4 を取得します。 |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | カラースペースを取得します。 |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | フラグを取得します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | 不透明度を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | タイプツール情報キーです。 |

## 備考

このリソースはカラースペース ID を含み、特定のカラースペースタイプを参照し、4 つのカラーコンポーネントがあります。ID に応じて、カラーコンポーネントの意味は異なります。カラースペースタイプが 4 つの値を必要としない場合、余分なコンポーネントは未定義となり、常にゼロで書き込まれます。カラースペースタイプ別のコンポーネント: RGB - 最初の 3 つのコンポーネントは赤、緑、青です。HSB - 最初の 3 つのコンポーネントは色相、彩度、明度です。CMYK - 4 つのコンポーネントはシアン、マゼンタ、イエロー、ブラックです。Lab - 最初の 3 つのコンポーネントは明度、a クロマ、b クロマです。Grayscale - 最初のコンポーネントはグレイ値で、0〜10000 の範囲です。

## 例

以下のコードは、LmskResource プロパティを変更して 16 ビット画像のレイヤーマスク表示オプションを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 16ビット画像をロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource を検索します。
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource のプロパティを確認します。
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource のプロパティを変更します。
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // 画像を保存します。
    image.Save(outputPsd);
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


