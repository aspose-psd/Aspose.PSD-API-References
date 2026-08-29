---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD for .NET API Reference"
description: "AiLayerSection プロパティ。このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します"
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` このインスタンスがマルチレイヤーマスクを持つ場合; それ以外は `false`。

## 例

次のコードは AiLayerSection における HasMultiLayerMasks と ColorIndex プロパティのサポートを示しています。

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### 関連項目

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


