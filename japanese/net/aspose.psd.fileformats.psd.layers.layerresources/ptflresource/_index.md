---
title: Class PtFlResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource クラス. クラス PtFlResourceパターン塗りつぶしレイヤー データが含まれています
type: docs
weight: 2960
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
## PtFlResource class

クラス PtFlResource。パターン塗りつぶしレイヤー データが含まれています。

```csharp
public class PtFlResource : FillLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PtFlResource](ptflresource/)(string, string) | の新しいインスタンスを初期化します`PtFlResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | [レイヤーに合わせる]かどうかを示す値を取得または設定します。 |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | このインスタンスがレイヤーとリンクされているかどうかを示す値を取得または設定します. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | オフセットを取得または設定します。 |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | パターン識別子を取得または設定します。 |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | パターンの名前を取得または設定します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion/) { get; } | レイヤー リソースに必要な最小限の psd バージョンを取得します。 0 は制限なしを示します。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | スケールを取得または設定します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature/) { get; } | 層リソース署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | タイプ ツール情報キー。 |

### 例

次の例は、PtFlResource リソースの読み込みと編集のサポートを示しています。

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // 読む
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // 編集中
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // PattResource にはデータをパターン化していないので、追加できます。
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


