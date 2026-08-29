---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD for .NET API Reference"
description: "Layer プロパティ。クリップされた要素のブレンドを取得または設定します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

クリップされた要素のブレンドを取得または設定します。

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

クリップされた要素のブレンドです。

## 例

以下のコードは BlendClippedElements プロパティのサポートを示しています。

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 関連項目

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


