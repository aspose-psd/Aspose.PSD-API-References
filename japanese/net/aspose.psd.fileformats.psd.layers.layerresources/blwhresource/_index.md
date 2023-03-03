---
title: Class BlwhResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BlwhResource クラス. BlwhResource クラスは白黒調整レイヤーのリソースです
type: docs
weight: 2320
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---
## BlwhResource class

BlwhResource クラスは白黒調整レイヤーのリソースです。

```csharp
public class BlwhResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BlwhResource](blwhresource/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlackAndWhitePresetFileName](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blackandwhitepresetfilename/) { get; set; } | 白黒プリセット ファイル名を取得または設定します。 |
| [Blues](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blues/) { get; set; } | ブルース値を取得または設定します。 |
| [BwPresetKind](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/bwpresetkind/) { get; set; } | 白黒プリセット種別値を取得または設定します。 |
| [Cyans](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/cyans/) { get; set; } | シアン値を取得または設定します。 |
| [Greens](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/greens/) { get; set; } | 緑の値を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| [Magentas](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/magentas/) { get; set; } | マゼンタ値を取得または設定します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/psdversion/) { get; } | psd バージョンを取得します。 |
| [Reds](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/reds/) { get; set; } | 赤の値を取得または設定します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |
| [TintColor](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/tintcolor/) { get; set; } | Tint Color ARGB 値を取得または設定します。 |
| [UseTint](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/usetint/) { get; set; } | [色合い] を使用するかどうかを示す値を取得または設定します。 |
| [Yellows](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/yellows/) { get; set; } | 黄色の値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/typetoolkey/) | タイプツール情報キー。 |

### 例

次の例は、BlwhResource を編集する方法を示しています。

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

const string ActualPropertyValueIsWrongMessage = "Expected property value is not equal to actual value";

string destinationFileName = "Output" + sourceFileName;
bool isRequiredResourceFound = false;
using (PsdImage im = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == tintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == bwPresetKind, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == bwPresetFileName, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue) < 1e-6, ActualPropertyValueIsWrongMessage);

                // 編集と保存のテスト
                blwhResource.Reds = reds - 15;
                blwhResource.Yellows = yellows - 15;
                blwhResource.Greens = greens + 15;
                blwhResource.Cyans = cyans + 15;
                blwhResource.Blues = blues - 15;
                blwhResource.Magentas = magentas - 15;
                blwhResource.UseTint = !useTint;
                blwhResource.BwPresetKind = 4;
                blwhResource.BlackAndWhitePresetFileName = "bwPresetFileName";
                blwhLayer.TintColorRed = tintColorRed - 60;
                blwhLayer.TintColorGreen = tintColorGreen - 60;
                blwhLayer.TintColorBlue = tintColorBlue - 60;

                im.Save(destinationFileName);
                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");

isRequiredResourceFound = false;

using (PsdImage im = (PsdImage)Image.Load(destinationFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == !useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == newTintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == 4, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == "bwPresetFileName", ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue + 60) < 1e-6, ActualPropertyValueIsWrongMessage);

                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");
```

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


