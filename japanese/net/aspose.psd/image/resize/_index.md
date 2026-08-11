---
title: "Image.Resize"
second_title: "Aspose.PSD for .NET API Reference"
description: "Image メソッド。画像をリサイズします。"
type: docs
weight: 200
url: /ja/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

画像のサイズを変更します。

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅です。 |
| newHeight | Int32 | 新しい高さです。 |
| resizeType | ResizeType | リサイズタイプです。 |

### 関連項目

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

画像のサイズを変更します。デフォルトの NearestNeighbourResample が使用されます。

```csharp
public void Resize(int newWidth, int newHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅です。 |
| newHeight | Int32 | 新しい高さです。 |

## 例

以下の例は、PSD 画像をリサイズする方法と Aspose.PSD によって得られる結果を示します。

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

画像のサイズを変更します。

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅です。 |
| newHeight | Int32 | 新しい高さです。 |
| 設定 | ImageResizeSettings | リサイズ設定です。 |

### 関連項目

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


