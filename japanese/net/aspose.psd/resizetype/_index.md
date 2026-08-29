---
title: "列挙体 ResizeType"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ResizeType 列挙体。リサイズタイプを指定します。"
type: docs
weight: 5870
url: /ja/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

リサイズの種類を指定します。

```csharp
public enum ResizeType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | リサイズ操作中にピクセルは保持されません。 |
| LeftTopToLeftTop | `1` | 新しい画像の左上点は元画像の左上点と一致します。必要に応じてクロップが行われます。 |
| RightTopToRightTop | `2` | 新しい画像の右上点は元画像の右上点と一致します。必要に応じてクロップが行われます。 |
| RightBottomToRightBottom | `3` | 新しい画像の右下点は元画像の右下点と一致します。必要に応じてクロップが行われます。 |
| LeftBottomToLeftBottom | `4` | 新しい画像の左下点は元画像の左下点と一致します。必要に応じてクロップが行われます。 |
| CenterToCenter | `5` | 新しい画像の中心は元画像の中心と一致します。必要に応じてクロップが行われます。 |
| LanczosResample | `6` | a=3 の Lanczos アルゴリズムを使用してリサンプリングします。 |
| NearestNeighbourResample | `7` | 最近傍アルゴリズムを使用してリサンプリングします。 |
| AdaptiveResample | `8` | 重み付けおよびブレンドされた有理関数と Lanczos3 補間アルゴリズムに基づく適応アルゴリズムを使用してリサンプリングします。 |
| BilinearResample | `9` | バイリニア補間を使用してリサンプリングします。必要に応じて、リサンプリング前にノイズを除去するための画像事前フィルタリングが許可されます。 |
| HighQualityResample | `10` | 高品質のリサンプリング |
| CatmullRom | `11` | Catmull-Rom キュービック補間法。 |
| CubicConvolution | `12` | この Cubic Convolution 補間法 |
| CubicBSpline | `13` | この CubicBSpline キュービック補間法 |
| Mitchell | `14` | この Mitchell キュービック補間法 |
| SinC | `15` | この Sinc (Lanczos3) キュービック補間法 |
| Bell | `16` | この Bell 補間法 |

## 例

以下のコードは、新しい SinC リサイズタイプで画像をリサイズする方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

以下のコードは、新しい Bell リサイズタイプで画像をリサイズする方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

以下のコードは、新しい Mitchell リサイズタイプで画像をリサイズする方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

以下のコードは、新しい CatmullRom リサイズタイプで画像をリサイズする方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

以下のコードは、新しい CubicBSpline リサイズタイプで画像をリサイズする方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

以下のコードは、新しい CubicConvolution リサイズタイプで画像をリサイズする方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


