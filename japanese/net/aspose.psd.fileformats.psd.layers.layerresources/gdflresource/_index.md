---
title: "クラス GdFlResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GdFlResource クラス。クラス GdFlResource。このリソースはクリップされた要素のブレンドに関する情報を含みます。"
type: docs
weight: 2760
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
{{< psd/tize >}}
## GdFlResource class

クラス GdFlResource。このリソースは、クリップされた要素のブレンド情報を含みます。

```csharp
public class GdFlResource : FillLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GdFlResource](gdflresource/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer/) { get; set; } | [align with layer] かどうかを示す値を取得または設定します。 |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle/) { get; set; } | 取得または設定します。角度。 |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color/) { get; set; } | RGB の色を取得します。 |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colormodel/) { get; set; } | カラーモデル - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints/) { get; set; } | カラーポイントを取得します。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither/) { get; set; } | この `GdFlResource` がディザリングかどうかを示す値を取得または設定します。 |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval/) { get; set; } | グラデーション間隔を取得または設定します。 |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientmode/) { get; set; } | このグラデーションのモード。'Gradient Type' を 'Solid/Noise' (= \"CstS\"/\"ClNs\") に決定します。 |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname/) { get; set; } | グラデーションの名前を取得または設定します。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype/) { get; set; } | グラデーションのタイプを取得または設定します。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset/) { get; set; } | 取得または設定します。水平オフセット。 |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/interpolationmethod/) { get; set; } | グラデーションの補間方法を取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/maximumcolor/) { get; set; } | PixelDataFormat の最大色。 |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/minimumcolor/) { get; set; } | PixelDataFormat の最小色。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse/) { get; set; } | `GdFlResource` が逆かどうかを示す値を取得または設定します。 |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/rndnumberseed/) { get; set; } | ノイズグラデーションの色を生成するために使用される乱数シード。 |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/roughness/) { get; set; } | 粗さ係数。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale/) { get; set; } | スケールを取得または設定します。 |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/showtransparency/) { get; set; } | 透過表示のフラグ。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints/) { get; set; } | 透過ポイントを取得します。 |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/usevectorcolor/) { get; set; } | ベクトルカラー使用のフラグ。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset/) { get; set; } | 取得または設定します。垂直オフセット。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey/) | タイプツール情報キーです。 |

## 例

次の例は GdFlResource のリソース読み込みのサポートを示しています。

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string exportPath = "ComplexGradientFillLayer_after.psd";
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
                if (res is GdFlResource)
                {
                    // 読み取り
                    var resource = (GdFlResource)res;
                    if (resource.AlignWithLayer != false ||
                     (Math.Abs(resource.Angle - 45.0) > 0.001) ||
                     resource.Dither != true ||
                     resource.Reverse != false ||
                     resource.Color != Color.Empty ||
                     Math.Abs(resource.HorizontalOffset - (-39)) > 0.001 ||
                     Math.Abs(resource.VerticalOffset - (-5)) > 0.001 ||
                     resource.TransparencyPoints.Length != 3 ||
                     resource.ColorPoints.Length != 2)
                    {
                        throw new Exception("Resource Parameters were read wrong");
                    }
                    var transparencyPoints = resource.TransparencyPoints;
                    if (Math.Abs(100.0 - transparencyPoints[0].Opacity) > 0.25 ||
                     transparencyPoints[0].Location != 0 ||
                     transparencyPoints[0].MedianPointLocation != 50 ||
                     Math.Abs(50.0 - transparencyPoints[1].Opacity) > 0.25 ||
                     transparencyPoints[1].Location != 2048 ||
                     transparencyPoints[1].MedianPointLocation != 50 ||
                     Math.Abs(100.0 - transparencyPoints[2].Opacity) > 0.25 ||
                     transparencyPoints[2].Location != 4096 ||
                     transparencyPoints[2].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Transparency Points were read Wrong");
                    }
                    var colorPoints = resource.ColorPoints;
                    if (colorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
                     colorPoints[0].Location != 0 ||
                     colorPoints[0].MedianPointLocation != 50 ||
                     colorPoints[1].Color != Color.FromArgb(203, 0, 0) ||
                     colorPoints[1].Location != 4096 ||
                     colorPoints[1].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Color Points were read Wrong");
                    }
                    // 編集
                    resource.Angle = 30.0;
                    resource.Dither = false;
                    resource.AlignWithLayer = true;
                    resource.Reverse = true;
                    resource.HorizontalOffset = 25;
                    resource.VerticalOffset = -15;
                    var newColorPoints = new List<IGradientColorPoint>(resource.ColorPoints);
                    var
                     newTransparencyPoints = new
                    List<IGradientTransparencyPoint>(resource.TransparencyPoints);
                    newColorPoints.Add(new GradientColorPoint()
                    {
                        Color = Color.Violet,
                        Location = 4096,
                        MedianPointLocation = 75
                    });
                    colorPoints[1].Location = 3000;
                    newTransparencyPoints.Add(new GradientTransparencyPoint()
                    {
                        Opacity = 80.0,
                        Location = 4096,
                        MedianPointLocation = 25
                    });
                    transparencyPoints[2].Location = 3000;
                    resource.ColorPoints = newColorPoints.ToArray();
                    resource.TransparencyPoints = newTransparencyPoints.ToArray();
                    im.Save(exportPath);
                }
                break;
            }
            break;
        }
    }
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


