---
title: Enum ResizeType
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ResizeType 列挙. リサイズタイプを指定します
type: docs
weight: 5370
url: /ja/net/aspose.psd/resizetype/
---
## ResizeType enumeration

リサイズタイプを指定します。

```csharp
public enum ResizeType
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | サイズ変更操作中、ピクセルは保持されません。 |
| LeftTopToLeftTop | `1` | 新しい画像の左上の点は、元の画像の左上の点と一致します。必要に応じてトリミングが行われます. |
| RightTopToRightTop | `2` | 新しい画像の右上の点は、元の画像の右上の点と一致します。必要に応じてトリミングが行われます. |
| RightBottomToRightBottom | `3` | 新しい画像の右下の点は、元の画像の右下の点と一致します。必要に応じてトリミングが行われます. |
| LeftBottomToLeftBottom | `4` | 新しい画像の左下の点は、元の画像の左下の点と一致します。必要に応じてトリミングが行われます. |
| CenterToCenter | `5` | 新しい画像の中心は元の画像の中心と一致します。必要に応じてトリミングが行われます. |
| LanczosResample | `6` | a=3. で lanczos アルゴリズムを使用してリサンプリングします。 |
| NearestNeighbourResample | `7` | 最近隣アルゴリズムを使用してリサンプルします。 |
| AdaptiveResample | `8` | 加重およびブレンドされた有理関数と lanczos3 補間アルゴリズムに基づく適応アルゴリズムを使用してリサンプリングします。 |
| BilinearResample | `9` | バイリニア補間を使用してリサンプルします。必要に応じて、画像の事前フィルタリングにより、再サンプルの前にノイズを除去できます |
| HighQualityResample | `10` | 高品質なリサンプル |
| CatmullRom | `11` | Catmull-Rom 3 次補間法。 |
| CubicConvolution | `12` | Cubic Convolution 補間法 |
| CubicBSpline | `13` | CubicBSpline 3 次補間メソッド |
| Mitchell | `14` | ミッチェル三次補間法 |
| SinC | `15` | Sinc (Lanczos3) 三次補間法 |
| Bell | `16` | ベル補間法 |

### 例

次のコードは、新しい SinC サイズ変更タイプを使用して画像のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

次のコードは、新しい Bell サイズ変更タイプを使用して画像のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

次のコードは、新しい Mitchell サイズ変更タイプを使用して画像のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

次のコードは、新しい CatmullRom サイズ変更タイプを使用して画像のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

次のコードは、新しい CubicBSpline サイズ変更タイプを使用して画像のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

次のコードは、新しい CubicConvolution サイズ変更タイプを使用して画像のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


