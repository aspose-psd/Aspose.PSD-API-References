---
title: RasterCachedImage.Resize
second_title: Aspose.PSD for .NET API リファレンス
description: RasterCachedImage 方法. 画像のサイズを変更します
type: docs
weight: 120
url: /ja/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

画像のサイズを変更します。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅。 |
| newHeight | Int32 | 新しい高さ。 |
| resizeType | ResizeType | リサイズタイプ。 |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* 名前空間 [Aspose.PSD](../../rastercachedimage/)
* 組み立て [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

画像のサイズを変更します。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅。 |
| newHeight | Int32 | 新しい高さ。 |
| settings | ImageResizeSettings | リサイズの設定。 |

### 関連項目

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* 名前空間 [Aspose.PSD](../../rastercachedimage/)
* 組み立て [Aspose.PSD](../../../)


