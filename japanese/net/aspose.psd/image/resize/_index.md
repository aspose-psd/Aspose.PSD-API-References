---
title: Image.Resize
second_title: Aspose.PSD for .NET API リファレンス
description: Image 方法. 画像のサイズを変更します
type: docs
weight: 190
url: /ja/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

画像のサイズを変更します。

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅. |
| newHeight | Int32 | 新しい高さ. |
| resizeType | ResizeType | リサイズタイプ. |

### 関連項目

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています.

```csharp
public void Resize(int newWidth, int newHeight)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅. |
| newHeight | Int32 | 新しい高さ. |

### 例

次の例は、Aspose.PSD で取得した PSD イメージと結果のサイズを変更する方法を示しています。

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

画像のサイズを変更します。

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅。 |
| newHeight | Int32 | 新しい高さ。 |
| settings | ImageResizeSettings | リサイズの設定。 |

### 関連項目

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)


