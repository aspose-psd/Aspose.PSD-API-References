---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD for .NET API Reference"
description: "AiLayerSection プロパティ。カラーのインデックスを取得または設定します。この引数は 1 から 26 の値を取ります。各整数はユーザー識別目的でレイヤーに割り当てられるカラーを表します"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

色のインデックスを取得または設定します。この引数は –1 から 26 の間の値を取ります。各整数は、ユーザー識別用にレイヤーに割り当てられる色を表します。

```csharp
public int ColorIndex { get; set; }
```

### Property Value

カラーのインデックスです。

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


