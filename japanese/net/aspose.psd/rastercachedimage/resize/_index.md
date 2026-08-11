---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD for .NET API Reference"
description: "RasterCachedImage メソッド。画像のサイズを変更します"
type: docs
weight: 120
url: /ja/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

画像のサイズを変更します。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅です。 |
| newHeight | Int32 | 新しい高さです。 |
| resizeType | ResizeType | リサイズタイプです。 |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

画像のサイズを変更します。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅です。 |
| newHeight | Int32 | 新しい高さです。 |
| 設定 | ImageResizeSettings | リサイズ設定です。 |

### 関連項目

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


