---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdLoadOptions プロパティ。ワープ変換の有無にかかわらず、レンダリングされた画像を保存するかどうかを取得または設定します。"
type: docs
weight: 30
url: /ja/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

取得または設定するのは、ワープ変換の有無にかかわらず、レンダリングされた画像とともに保存するかどうかです。

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` はワープ変換で画像をレンダリングし、`false` はレンダリングしません。

## 例

以下のコードは、Warp エフェクトのレンダリングを示しています。

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### 関連項目

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


