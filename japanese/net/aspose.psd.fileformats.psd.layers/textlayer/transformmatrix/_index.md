---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD for .NET API Reference"
description: "TextLayer プロパティ。変換行列を取得または設定します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

変換行列を取得または設定します

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

変換行列です

## 例

次のコードは、テキストレイヤー内の任意のテキスト部分のフォントサイズを取得する方法を示しています。

```csharp
[C#]

// 誤ったフォントサイズが抽出されました
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 旧 API（最初の段落フォントを使用）
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // 基本フォントサイズを確認しています
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実際のフォントサイズを確認しています
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 新 API（1 つのテキストレイヤーは任意の数のフォントサイズを含むことができます）
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // 基本部分のフォントサイズを確認しています
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実際の部分のフォントサイズを確認しています
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### 関連項目

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


